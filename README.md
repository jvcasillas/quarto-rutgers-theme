# ru_reveal

Minimalist reveal theme for quarto html presentations using RU style/colors

Example presentation [here](https://www.jvcasillas.com/ru_reveal/index.html). 

## Usage

```
---
title: "Rutgers reveal.js theme"
subtitle: "Subtitle goes here"
author: "Author name"
institute: "Rutgers University"
date: "`r Sys.Date()`"
format: 
  revealjs:
    theme: [default, rutgers.scss]
    template-partials:
      - title-slide.html
engine: knitr
---
```
