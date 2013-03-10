---
layout: post
title: "Finalmente um debug para o Ruby 1.9.3"
date: 2012-04-04 16:30
comments: true
external-url: https://github.com/cldwalker/debugger
categories: ruby
---
O `ruby-debug19` está parado já faz um tempo, o último release foi em **setembro de 2009**! Então [Gabriel Horner](https://github.com/cldwalker) fez um fork do projeto e promete mantê-lo atualizado.

Para instalar é simples:
```
$ gem install debugger
```

Ou adicione em seu projeto Rails:
``` ruby
gem "debugger", "~> 1.0.0"
```