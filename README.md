---
layout: plain
title: About me
author: KAWAHARA, Satoru s1311350@gmail.com
refer: https://nymphium.github.io/aboutme.html
---

- Website: <https://nymphium.github.io>
- GitHub: <https://github.com/Nymphium>
- LinkedIn: <https://www.linkedin.com/in/nymphium/>
- Twitter: <https://twitter.com/Nymphium>

# Summary
I'm a full-time software engineer working at [eiicon, Inc.](https://corp.eiicon.net).
My interests lie in functional programming languages and their mechanisms, especially program conversion, control operators, delimited continuation, and algebraic effects.

# Introduction
My core technical strengths are a deep knowledge of programming language theory and practice, and the ability to adapt quickly to new technologies. I specialize in functional languages and those with strong type systems, such as OCaml and Haskell, and I hold a Master's degree where my research focused on language design and the implementation of language processing systems. I am confident that this expertise allows me to not only solve complex technical challenges but also contribute to improving our entire team's technology selection and design capabilities.

Through my experience, I have recently developed a strong interest not just in advancing my individual skills, but in maximizing the productivity of the entire team. I aim to build a technically sound and collaborative team by mentoring members, fostering a strong code review culture, and improving our development processes. I find great fulfillment in overcoming difficult challenges as a united team to contribute to business success—an achievement I value more than individual accomplishments.

I am looking for an environment, regardless of industry, that offers these kinds of technical and organizational challenges. Please feel free to contact me about any technical topics.

# Engineering Skills
## Languages
### Expert
- OCaml <3
- Lua

### Proficient
- TypeScript
- Go

### Familiar
- Haskell
- Scala
- Racket
- Ruby
- JavaScript

## DevOps
### CI/CD
- GitHub Actions
- Circle CI

### Others
- Nix
- Terraform
- k8s
- Git

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

Pnyao is a PDF management system.
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
We investigated the relationship between asymmetric coroutines and algebraic effects.

- Poster: <u>河原 悟</u>, [JSSST2018](https://jssst2018.wordpress.com/), [ワンショットの限定継続に着目した代数的効果から非対称コルーチンへの変換](http://logic.cs.tsukuba.ac.jp/~sat/pdf/jssst2018.pdf).
- Article: <u>Satoru Kawahara</u> and Kameyama Yukiyoshi, [Trends in Functional Programming 2020](http://www.cse.chalmers.se/~rjmh/tfp/), [One-shot Algebraic Effects as Coroutines](http://logic.cs.tsukuba.ac.jp/~sat/pdf/tfp2020.pdf).
- Master thesis: [コルーチンを用いた代数的効果の新しい実装方法の提案](http://logic.cs.tsukuba.ac.jp/~sat/pdf/master_thesis.pdf)

# Work career
- National Institute of Advanced Industrial Science and Technology, Part-time, 09/2014 ~ 02/2015.
- AgilePoint Japan, Part-time, 05/2015 ~ 11/2018.
- HERP, inc. Part-time, 11/2018 ~ 03/2020, and full-time, 04/2020 ~ 03/2023

  As a software engineer w/ TypeScript, Haskell, MySQL, Nix, GitHub Actions and k8s
- Linux Development head office, Fujitsu, as an internship, 09/2015 ~ 10/2015
- Kanmu, inc. Full-time, 04/2023 ~ 08/2024

  As a software engineer w/ Go, Python, PostgreSQL and GitHub Actions
- eiicon, inc. 09/2024 ~ Present

  As a software engineer w/ Go, Ruby, TypeScript, MySQL, AWS, Nix, GitHub Actions, Terraform and k8s

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


## paper
- [<u>Satoru Kawahara</u> and Yukiyoshi Kameyama, "One-shot Algebraic Effects as Coroutines," TFP 2020.](https://link.springer.com/chapter/10.1007/978-3-030-57761-2_8) [[post-symposium version]](http://logic.cs.tsukuba.ac.jp/~sat/pdf/tfp2020-postsymposium.pdf) [[slide]](http://logic.cs.tsukuba.ac.jp/~sat/pdf/tfp2020-slide.pdf) [[video]](https://www.youtube.com/watch?v=JQwc1OBOt5k)
