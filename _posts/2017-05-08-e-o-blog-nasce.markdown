---
layout: post
title:  "E o \"diário\" nasce!"
date:   2017-05-08 11:02:38 -0300
categories:
---

Após dois meses sem nenhuma notícia do projeto, o diário de bordo finalmente nasce. Antes tarde do que nunca, algumas decisões de projeto já foram tomadas, uma quantidade considerável de código já foi escrita e vários imprevistos foram enfrentados. E nada melhor que uma retrospectiva para documentar o que foi feito até o momento.

Tudo começou como PMDSys, e o primeiro desafio foi configurar os testes automatizados utilizando o SonarQube para executarem automaticamente sobre cada commit feito na base de código que viria. Após muito esforço e uma quase desistênica, descobrimos que não informávamos a chave da organização ao Sonar.

