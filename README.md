# quarto-rutgers-theme

Minimalist reveal theme for quarto html presentations using RU style/colors. 
This is a port of the [ru_xaringan](https://github.com/jvcasillas/ru_xaringan) theme. 

Example presentation [here](https://www.jvcasillas.com/quarto-rutgers-theme/index.html). 


## Usage

This [Quarto](https://quarto.org) extension can be installed using the following command:

``` bash
quarto install extension jvcasillas/quarto-rutgers-theme
```

If you are unable to install Quarto extensions, you probably should [update Quarto](https://quarto.org/docs/get-started/).

## How to use it

After you install the template, use the following code in the terminal to create a new directory with all files needed:

``` bash
quarto use template jvcasillas/quarto-rutgers-theme
```

```bash
Quarto templates may execute code when documents are rendered. 
If you do not trust the authors of the template, we recommend that you do not install or use the template.
```

```bash
 ? Do you trust the authors of this template (Y/n) › Yes
 ? Directory name: › WRITE/THE/DIRECTORY/HERE/talk/
```

```bash
[✓] Downloading
[✓] Unzipping
    Found 1 extension.
[✓] Copying files...

Files created:
 - quarto-rutgers-theme.Rproj
 - _extensions
 - index.qmd

```

Once you have installed everything, make sure you specify the format in the YAML front matter: 

```
---
title: "Quarto revealjs custom theme"
subtitle: "Subtitle goes here"
author: "Joseph V. Casillas"
institute: "Rutgers University"
date: "Last update: `r Sys.Date()`"
format: rutgers-revealjs
engine: knitr
---
```


## Acknowledgments

I created this extension following the example by [Beatriz Milz](https://github.com/beatrizmilz). 

