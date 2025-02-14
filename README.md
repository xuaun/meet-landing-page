# Frontend Mentor - Meet landing page solution

## Languages
This first section is in English. 

[Versão em português logo abaixo.](#portuguese)

## Context

This is a solution to the [Meet landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/meet-landing-page-rbTDS6OUR). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

> Your challenge is to build out this landing page and get it looking as close to the design as possible.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

#### Desktop

<p align="center">
  <img src="./src/design/desktop-screenshot.png" alt="Desktop Screenshot of live page" title="Desktop Screenshot of live page" width="600px" />
</p>

#### Tablet

<p align="center">
  <img src="./src/design/tablet-screenshot.png" alt="Tablet proportions Screenshot of live page" title="Tablet proportions Screenshot of live page" width="450px" />
</p>

#### Mobile

<p align="center">
  <img src="./src/design/mobile-screenshot.jpg" alt="Mobile Screenshot of live page" title="Mobile Screenshot of live page" width="300px" />
</p>

### Links

- Solution URL: [GitHub Repository](https://github.com/xuaun/meet-landing-page)
- Live Site URL: [Live Page](https://xuaun.github.io/meet-landing-page/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Media Query + clamp()

### What I learned

In this project I was able to use flexbox, grid, variable, and media query concepts in CSS, as well as using a ready-made Figma design to create this component. I also used `rem` for measurements, `clamp()` to help with responsiveness, and BEM methodology for naming classes.

```css
.mid {
  display: grid;
  grid-template:
    "number number number number" auto
    "photo-1 photo-2 photo-3 photo-4" auto
    "body body body body" auto / clamp(15.2rem, 2.2rem + 16.25vw, 25.6rem)
    clamp(15.2rem, 2.2rem + 16.25vw, 25.6rem) clamp(
      15.2rem,
      2.2rem + 16.25vw,
      25.6rem
    )
    clamp(15.2rem, 2.2rem + 16.25vw, 25.6rem);
}
```

## Author

- Website - [João Víctor de Araujo Lima's Portfolio](https://xuaun.github.io/)
- Frontend Mentor - [@xuaun](https://www.frontendmentor.io/profile/xuaun)


____
<br>

# <p id="portuguese">Frontend Mentor - Solução do projeto de landing page</p>

## Contexto

Esta é uma solução para o [desafio de landing page no Frontend Mentor](https://www.frontendmentor.io/challenges/meet-landing-page-rbTDS6OUR). Os desafios do Frontend Mentor ajudam você a melhorar suas habilidades de codificação construindo projetos realistas.

> Seu desafio é criar esta landing page e fazer com que ela tenha a aparência mais próxima possível do design.

## Lista de conteúdos

- [Visão Geral](#visão-geral)
  - [Desafio](#desafio)
  - [Prints](#prints)
  - [Links](#links-pt)
- [Meu processo](#meu-processo)
  - [Tecnologias utilizadas](#tecnologias-utilizadas)
  - [O que eu aprendi](#o-que-eu-aprendi)
- [Autor](#autor)

## Visão Geral

### Desafio

Os usuários devem ser capazes de:

- Visualizar o layout ideal dependendo do tamanho da tela do dispositivo
- Veja os estados de foco para elementos interativos

### Prints

#### Computador

<p align="center">
  <img src="./src/design/desktop-screenshot.png" alt="Print da tela no Desktop" title="Print da tela no Desktop" width="600px" />
</p>

#### Tablet

<p align="center">
  <img src="./src/design/tablet-screenshot.png" alt="Print da tela nas proporções de um Tablet" title="Print da tela nas proporções de um Tablet" width="450px" />
</p>

#### Celular

<p align="center">
  <img src="./src/design/mobile-screenshot.jpg" alt="Print da tela no Celular" title="Print da tela no Celular" width="300px" />
</p>

### <p id="links-pt">Links</p>

- Link da solução: [Repositório no GitHub](https://github.com/xuaun/meet-landing-page)
- Site com a solução: [Página no ar](https://xuaun.github.io/meet-landing-page/)

## Meu processo

### Tecnologias utilizadas

- HTML5
- CSS
- Flexbox
- CSS Grid
- Media Query + calmp()

### O que eu aprendi

Neste projeto eu pude utilizar conceitos de flexbox e grid, de variáveis e de media query no CSS, além de usar um design pronto do Figma para a elaboração deste componente. Eu também usei `rem` para medidas, `clamp()` para ajudar na responsividade e metodologia BEM para nomear classes.

```css
.mid {
  display: grid;
  grid-template:
    "number number number number" auto
    "photo-1 photo-2 photo-3 photo-4" auto
    "body body body body" auto / clamp(15.2rem, 2.2rem + 16.25vw, 25.6rem)
    clamp(15.2rem, 2.2rem + 16.25vw, 25.6rem) clamp(
      15.2rem,
      2.2rem + 16.25vw,
      25.6rem
    )
    clamp(15.2rem, 2.2rem + 16.25vw, 25.6rem);
}
```

## Autor

- Website - [Portfólio - João Víctor de Araujo Lima](https://xuaun.github.io/)
- Frontend Mentor - [@xuaun](https://www.frontendmentor.io/profile/xuaun)

