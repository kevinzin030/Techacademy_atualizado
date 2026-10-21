# TechAcademy — arquitetura HTML, CSS e JavaScript

## Organização do código

- `index.html`: estrutura da tela de acesso.
- `dashboard-professor.html`: estrutura do painel do professor e templates HTML reutilizáveis.
- `dashboard-aluno.html`: estrutura do painel do aluno e templates HTML reutilizáveis.
- `css/styles.css`: estilos visuais e responsividade.
- `js/app-professor.js`: estado, navegação, formulários, notas, aulas, quizzes, notificações e persistência do professor.
- `js/app-aluno.js`: aulas, PDFs, quizzes, XP, sequência de atividade e persistência do aluno.
- `js/login.js`: comportamento da tela de acesso.
- `js/mobile-menu.js`: menu lateral em telas pequenas.

## Templates HTML

Cards, formulários e tabelas ficam declarados nos HTMLs dentro de elementos `<template>`. O JavaScript preenche os valores dinâmicos e clona os modelos necessários, evitando esconder a marcação em strings longas de JS.

## Como executar

1. Extraia os arquivos do projeto para uma pasta.
2. Abra a pasta no VS Code e inicie um servidor local, como Live Server.
3. Acesse `index.html` pelo mesmo endereço local usado para testar professor e aluno.

## Limitações

Esta versão é uma simulação local sem API nem banco de dados remoto. Os dados são guardados em `localStorage` e não são compartilhados entre dispositivos ou origens diferentes. O projeto utiliza recursos externos via CDN para parte do visual.
