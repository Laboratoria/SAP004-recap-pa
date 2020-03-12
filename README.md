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

Atualmente, com o aumento do uso de smartphones, suas aplicações e o acesso a
Internet, existem muitas possibilidades de participar de um trivia online. Com
uma rápida busca na Internet, você verá que existem trivias de diferentes temas
(ciência, televisão, séries, etc..). Existem vários que, inclusive, oferecem
dinheiro como recompensa.

![TRIVIA](https://phandroid.s3.amazonaws.com/wp-content/uploads/2018/01/hq-trivia-android-screenshot.jpg)

## 2. Resumo do projeto

O que tenho que fazer exatamente? Neste projeto você terá que construir uma
aplicação web que permita que o usuário responda diferentes perguntas e escolha
as respostas, a partir de uma lista de alternativas.

O tema é livre. Você deve criar a melhor trivia possível e pensar em como deve
ser a experiência de uso (telas, instruções para o usuário, mensagens, cores, etc).

## 3. Objetivos de aprendizagem

O objetivo principal deste projeto é ter uma primeira experiência desenvolvendo
aplicações web (WebApp) que interajam com o usuário através do navegador e
desenvolver a lógica, utilizando HTML, CSS e JavaScript como ferramentas.

Reflita e depois enumere os objetivos que quer alcançar e aplique no seu
projeto. Pense nisso para decidir sua estratégia de trabalho individual e em
equipe.

### HTML e CSS

* [ ] Entender e reconhecer a importância do HTML semântico.
* [ ] O que são tags de formulário, como `<form>` e `<input>`, e como utilizá-las.
* [ ] Identificar e entender tipos de seletores em CSS.

### DOM

* [ ] Entender e reconhecer os seletores do DOM.
* [ ] Manejar eventos do DOM.
* [ ] Manipular dinamicamente o DOM.

### JavaScript

* [ ] Manipular strings.
* [ ] Entender o uso de condicionais.
* [ ] Utilizar funções.
* [ ] Conhecer a diferença entre os distintos tipos de variáveis.
* [ ] Como vincular funções JS à ações feitas no HTML através do atributo `onclick`. 

### Boas práticas de desenvolvimento

* [ ] Utilizar identificadores descritivos (Nomenclatura | Semântica).

## 4. Considerações gerais

* Este projeto deve ser resolvido em duplas/trios.
* Tempo para implementá-lo: Teremos 1 dia e meio previstos para trabalhar neste projeto; a dupla/trio deve se organizar e priorizar as tarefas para implementar o máximo possível neste tempo.

## 5. Critérios mínimos de aceitação do projeto

Os critérios que você deverá considerar para saber se completou o projeto são:

### Desenho da interface de usuário

Com lápis e papel, façam um rascunho da interface planejada para este projeto: aparência e localização dos inputs e botões, caixas, imagens e etc. Pensem no fluxo que o usuário vai percorrer: onde vai clicar primeiro, o que ele espera que aconteça, etc.

### Implementação da Interface de Usuário (HTML/CSS/JS)

Depois de desenhar sua interface de usuário, você deverá trabalhar em sua
implementação. **Não** é necessário que construa a interface exatamente como a
desenhou. Você não tem um tempo ilimitado para trabalhar, sendo assim, deverá
saber o que priorizar.

O [MVP](https://www.youtube.com/watch?v=0Dn-BHj6l2E) (produto mínimo viável) de
sua aplicação deve:

1. Mostrar uma tela de boas-vindas na qual se peça o nome para começar a jogar.
2. Mostrar uma mensagem de Oi [nome do usuário] e dois botões para começar a
   jogar.
    - Jogar com perguntas do tipo A (Por exemplo: sobre comida)
    - Jogar com perguntas do tipo B (Por exemplo: sobre cervejas)
3. Mostrar as perguntas do tipo selecionado e os inputs para o usuário inserir a resposta.
4. Mostrar uma tela de resultados (respostas corretas) e dois botões de voltar a
   jogar:
    - Jogar com perguntas do tipo A (Por exemplo: sobre comida)
    - Jogar com perguntas do tipo B (Por exemplo: sobre cervejas)

5. A dupla/trio deverá subir o código para o GitHub e implementar a interface usando GitHub pages.

## 6. Hacker edition

Se **terminou** tudo que foi listado anteriormente e ainda te sobrou tempo,
tente explorar e completar o seguinte:

* Adicionar uma contagem regressiva que determine um tempo limite para responder
  cada pergunta.

## 7. Considerações técnicas

A lógica do projeto deve estar implementada completamente em JS, HTML e CSS.
Neste projeto não é permitido usar bibliotecas ou frameworks, somente [vanilla
JavaScript](https://medium.com/laboratoria-how-to/vanillajs-vs-jquery-31e623bbd46e).

Não deve ser usada a _pseudo-variável_ `this`.

### `src/index.html`

Aqui vai a página que será mostrada para o usuário. Também nos serve para
indicar que script será usado e unir tudo que fizemos.

Você encontrará uma tag inicial que pode ser apagada, caso queira, para começar
do zero.

```html
 <div id="root"></div>
```

### `src/style.css`

Este arquivo deve conter as regras de estilo. Queremos que escreva suas próprias
regras, por isso NÃO está permitido o uso de frameworks de CSS (Bootstrap,
Materialize, etc).

### `src/main.js`

Aqui você escreverá todo o código que tenha a ver com a interação com o DOM
(selecionar, atualizar e manipular elementos do DOM e eventos), entre outras
funções que sejam necessárias para atualizar o resultado na tela (UI).

## 8. Guias, dicas e leituras complementares

### Recursos e temas relacionados

#### Desenho de experiência de usuário (User Experience Design)

* Ideação
* Protótipo (sketching)

#### Desenvolvimento Front-end

* Tipos de valores
* Declaração de variáveis
* Controle de fluxo
* Uso de formulários
* Introdução a funções
* Interação com o DOM utilizando JS

#### Organização do trabalho

* [Metodologias Ágeis](https://www.youtube.com/watch?v=v3fLx7VHxGM)
* [Scrum em menos de 2 minutos](https://www.youtube.com/watch?v=TRcReyRYIMg)
* [Scrum em detalhes](https://www.youtube.com/watch?v=XfvQWnRgxG0). Não
  esperamos que faça tudo isso neste projeto.