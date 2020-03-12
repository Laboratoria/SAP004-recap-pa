# Trivia

## Índice

* [1. Preâmbulo](#1-preâmbulo)
* [2. Resumo do projeto](#2-resumo-do-projeto)
* [3. Objetivos de aprendizagem](#3-objetivos-de-aprendizagem)
* [4. Considerações gerais](#4-considerações-gerais)
* [5. Critérios de aceitação mínima do
  projeto](#5-critérios-de-aceitação-mínima-do-projeto)
* [6. Hacker edition](#6-hacker-edition)
* [7. Considerações técnicas](#7-considerações-técnicas)
* [8. Guias, dicas e leituras
  complementares](#8-guias-dicas-e-leituras-complementares)

***

## 1. Preâmbulo

A trivia é um tipo de jogo, geralmente presente em game shows, no qual são
apresentadas perguntas cujas respostas devem ser escolhidas entre diferentes
opções.

Atualmente, com o aumento do uso de smartphones, suas aplicações e o acesso à internet, existem muitas possibilidades de participar de um trivia online. Com uma
rápida busca na Internet, você verá que existem trivias de diferentes temas
(ciência, televisão, séries, etc). Existem várias que, inclusive, oferecem
dinheiro como recompensa.

![TRIVIA](https://phandroid.s3.amazonaws.com/wp-content/uploads/2018/01/hq-trivia-android-screenshot.jpg)

## 2. Resumo do projeto

O que tenho que fazer exatamente? Neste projeto você terá que construir um Show do Milhão. Sua aplicação deve permitir que o usuário responda diferentes perguntas e escolha as respostas, a partir de uma lista de alternativas.

O tema é livre. Você deve criar a melhor trivia possível.

## 3. Objetivos de aprendizagem

O objetivo principal deste projeto é ter uma primeira experiência desenvolvendo
aplicações web (WebApp) que interajam com o usuário através do navegador e
desenvolver a lógica, utilizando HTML, CSS e JavaScript como ferramentas.

Pense nos passos que o usuário tem que percorrer, repasse o fluxograma e se organize com sua dupla/trio.

![fluxograma do projeto](https://user-images.githubusercontent.com/32266030/75788882-9f9ab980-5d47-11ea-9512-1ffbbf10da9e.png)

### HTML e CSS

* [ ] Entender e reconhecer a importância do HTML semântico.
* [ ] Identificar e entender tipos de seletores em CSS.

### JavaScript

* [ ] Entender o uso de prompts.
* [ ] Entender o uso de condicionais.
* [ ] Conhecer a diferença entre os distintos tipos de variáveis.

### Boas práticas de desenvolvimento

* [ ] Utilizar identificadores descritivos (Nomenclatura | Semântica).

## 4. Considerações gerais

* Este projeto deve ser resolvido em duplas/trios.
* Tempo para implementá-lo: Tome como referência 4 horas. Trate de estimar um
  tempo para finalizar.

## 5. Critérios mínimos de aceitação do projeto

Os critérios que você deverá considerar para saber se completou o projeto são:

### Implementação da Interface de Usuário (HTML/CSS/JS)

1. Mostrar uma tela de boas-vindas na qual se peça, através de prompt, o nome para começar a jogar.
2. Mostrar uma tela na qual o usuário pode escolher se quer jogar ou não. Caso ele não deseje jogar, o fluxo deve ser encerrado. Caso ele queira jogar, seguirá para a próxima etapa, descrita no item 3.
3. Mostrar, através de prompt,  a pergunta 1 com alternativas. O usuário responde e depois é
   apresentada a pergunta 2 e depois a 3.
4. Mostrar uma tela de resultados (respostas corretas e incorretas).

Seguem exemplos de tela. Você pode usar as cores e fontes que quiser e acrescentar detalhes, porém os seguintes aspectos do leiaute modelo devem ser mantidos:
- O nome da pessoa deve ser impresso na tela;
- As respostas corretas e erradas devem ser impressas na tela em caixas separadas, exibidas lado a lado.

![tela 1](https://user-images.githubusercontent.com/39506102/75469562-fe3ded00-596d-11ea-98e7-17b78d8f45d9.png)

![tela 2](https://user-images.githubusercontent.com/39506102/75469606-101f9000-596e-11ea-838e-9bbdffd5ec8e.png)

![tela 3](https://user-images.githubusercontent.com/39506102/75469610-1281ea00-596e-11ea-8e86-c0eb6e49e699.png)

![tela 4](https://user-images.githubusercontent.com/39506102/75469625-16157100-596e-11ea-95e5-038e068af938.png)

### Entrega

A entrega será feita através do GitHub e sua trivia deve ser publicada no GitHub Pages.

## 6. Hacker edition

Se **terminou** tudo que foi listado anteriormente e ainda te sobrou tempo,
tente explorar e completar o seguinte:

* Adicionar no fluxo, uma condicional que permita ao usuário decidir que tipo de jogo gostará de jogar:
    Exemplo: 
    - Tipo A: perguntas sobre comidas
    - Tipo B: perguntas sobre entretenimento

## 7. Considerações técnicas

A lógica do projeto deve estar implementada completamente em JS, HTML e CSS.
Neste projeto não é permitido usar bibliotecas ou frameworks, somente [vanilla
JavaScript](https://medium.com/laboratoria-how-to/vanillajs-vs-jquery-31e623bbd46e).

Não deve ser usada a _pseudo-variável_ `this`.

### `index.html`

Aqui vai a página que será mostrada para o usuário. Também nos serve para
indicar que script será usado e unir tudo que fizemos.

### `style.css`

Este arquivo deve conter as regras de estilo. Queremos que escreva suas próprias
regras, por isso NÃO está permitido o uso de frameworks de CSS (Bootstrap,
materialize, etc).

### `main.js`

Aqui você escreverá todo o código que tenha a ver com a lógica.

## 8. Guias, dicas e leituras complementares

### Recursos e temas relacionados

* [GitHub](https://github.com/)
* [GitHub Pages](https://pages.github.com/)
* [Tutorial - GitHub e GitHub Pages](https://youtu.be/p36l8QR4-g8)