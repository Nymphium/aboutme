---
layout: plain
title: About
author: Kawahara Satoru s1311350@gmail.com
refer: https://nymphium.github.io/aboutme.html
---

- Website: https://nymphium.github.io
- GitHub: https://github.com/Nymphium

# Summary
I'm a full-time job engineer working at [HERP, Inc.](https://herp.co.jp)
My interests are functional programming language and that mechanisms, especially program conversion, control operators, delimited continuation and algebraic effects.

# Engineering Skills
## Languages
- OCaml
- Lua
- Haskell
- Scala
- JavaScript
- Racket
- Scheme
- Ruby

## Platforms
- Linux

## Other
- Git (locally, GitHub, BitBucket)

    + GitHub activities

        Please log in to see them.

        * [Issues](https://github.com/issues?utf8=%E2%9C%93&q=is%3Aissue+author%3ANymphium+archived%3Afalse+)
        * [Pull Requess](https://github.com/pulls?utf8=%E2%9C%93&q=is%3Apr+author%3ANymphium+archived%3Afalse+)
- Zsh
- Vim/Neovim

# Main works
## llix
{% gh_repo nymphium/llix %}

llix is meta-circular [Lua](https://lua.org) interpreter with exception and delimited continuation mechanism.
The interpreter uses CPS as intermediate representation to manage contexts.
[Here](https://nymphium.github.io/pdf/information_special_seminar.html) is a presentation.

## Opeth
{% gh_repo nymphium/opeth %}

Opeth is Lua VM 5.3 Bytecode optimizer and debug tools.

Lua VM is not documented officially while the source code is [opened](https://github.com/lua/lua).
For implementing Opeth, I read VM's source code.

Opeth has an optimizer, bytecode visualizer, step-by-step instruction interpreter, based on global data/control -flow analysis, and, assembly-like language compiled to the bytecode.

[Here](https://nymphium.github.io/pdf/opeth_report.pdf) is a report.

## Pnyao
{% gh_repo nymphium/pnyao %}

Pnyao is pdf management system.
It adopts server-client method 
The server uses play framework and you can access with web browser as client.

## Eff.lua & Ruff
{% gh_repo nymphium/eff.lua %}
{% gh_repo nymphium/ruff %}

Eff.lua and Ruff are libraries that provide one-shot algebraic effects.
These libraries are based on our research which translates one-shot algebraic effect handlers to (full, or namely stackful) asymmetric coroutines.
Ruff has algebraic effects with *subtyping on effects*.

Detailed:

{% twicard "" https://nymphium.github.io/2019/12/22/effsub.html %}

# Education
## Bachelor: College of Information Science, University of Tsukuba, 04/2013 ~ 03/2018 
I researched about intermediate representation about compiler for functional language.
In this research I designed the intermediate language for impure functional language and optimization for them.

Bachelor thesis: [合流点を追加したコンパイラ中間言語の設計と検証](http://logic.cs.tsukuba.ac.jp/~sat/pdf/bachelor_thesis.pdf)

## Graduate school: same as above, 04/2018 ~ 03/2020
We taclke to the relationship about asymmetric coroutines and algebraic effects.

- Poster: <u>河原 悟</u>, [JSSST2018](https://jssst2018.wordpress.com/), [ワンショットの限定継続に着目した代数的効果から非対称コルーチンへの変換](http://logic.cs.tsukuba.ac.jp/~sat/pdf/jssst2018.pdf).
- Article: <u>Satoru Kawahara</u> and Kameyama Yukiyoshi, [Trends in Functional Programming 2020](http://www.cse.chalmers.se/~rjmh/tfp/), [One-shot Algebraic Effects as Coroutines](http://logic.cs.tsukuba.ac.jp/~sat/pdf/tfp2020.pdf).
- Master thesis: [コルーチンを用いた代数的効果の新しい実装方法の提案](http://logic.cs.tsukuba.ac.jp/~sat/pdf/master_thesis.pdf)

# Work career
- National Institute of Advanced Industrial Science and Technology, Part-time, 09/2014 ~ 02/2015.
- AgilePoint Japan, Part-time, 05/2015 ~ 11/2018.
- HERP, inc. Part-time, 11/2018 ~ 03/2020.
- Linux Development head office, Fujitsu, as an internship, 09/2015 ~ 10/2015

# Publications
## 『つくってかんたんVM-Based Interpreter』 from 『Dragon University 技術書典5』
This column focuses on how to design virtual machine-based interpreter and implement it.
You can learn the formalization of the VM state and the compilation rules from the source to the instruction sequence.

The book gives an implementation of toy language.

{% gh_repo Nymphium/techbookfest5-toylang %}

{% twicard "https://dragonuniversity.booth.pm/items/1055860" https://dragonuniversity.booth.pm/items/1055860 %}

## 『Let's go Algebraic Effects and Handlers: from an introduction to advanced topics』
This column introduces algebraic effects and handlers by examples, containing delimited controls, and talk about the advanced topics.

{% twicard "https://dragonuniversity.booth.pm/items/1317197" https://dragonuniversity.booth.pm/items/1317197 %}
