---
layout: post
title:  "E o \"diário\" nasce!"
date:   2017-05-08 11:02:38 -0300
categories:
---

Após dois meses sem nenhuma notícia do projeto, o diário de bordo finalmente nasce. Antes tarde do que nunca, algumas decisões de projeto já foram tomadas, uma quantidade considerável de código já foi escrita e vários imprevistos foram enfrentados. E nada melhor que uma retrospectiva para documentar o que foi feito até o momento.

Tudo começou como PMDSys, e o primeiro desafio foi configurar os testes automatizados utilizando o SonarQube para executarem automaticamente sobre cada commit feito na base de código que viria. Após muito esforço e uma quase desistênica, descobrimos que não informávamos a chave da organização ao Sonar. Então veio a surpresa: não há suporte padrão na ferramenta para a linguagem escolhida (TypeScript).

Enfim, começamos o projeto, já renomeado para EconoCart. Esboçamos o diagrama de classes de modelo, esboçamos algumas poucas telas (5 das 18) e partimos para a codificação ao mesmo tempo que buscávamos modos de testar a aplicação. Os fatores complicadores nesta etapa foi colocar os testes para funcionar - o que consumiu um pouco mais de um mês, ou seja, 2 sprints e meia.

Quando conseguimos fazer alguns poucos testes executarem, o projeto já estava profundamente atrasado, o código escrito já era ilegível (clean code, cadê você?) e as telas que faziam chamadas ao banco de dados não eram testáveis.

E agora, o que fazer neste mês que virá?
