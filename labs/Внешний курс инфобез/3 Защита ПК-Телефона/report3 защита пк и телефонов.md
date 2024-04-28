---
## Front matter
title: "Отчет о втором модуле внешнего курса"
subtitle: "Защита ПК/телефона"
author: "Ганина Таисия Сергеевна"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---


# Выполнение заданий модуля

Выполнение заданий. (рис. @fig:001, @fig:002, @fig:003, @fig:004, @fig:005, @fig:006, @fig:007, @fig:008, @fig:009, @fig:010, @fig:011, @fig:012, @fig:013, @fig:014, @fig:015).

![Шифрование диска 1](image/1.png){#fig:001 width=70%}

![Шифрование диска 2](image/2.png){#fig:002 width=70%}

![Шифрование диска 3](image/3.png){#fig:003 width=70%}

![Пароли 1](image/4.png){#fig:004 width=70%}

![Пароли 2](image/5.png){#fig:005 width=70%}

![Пароли 3](image/6.png){#fig:006 width=70%}

![Пароли 4](image/7.png){#fig:007 width=70%}

![Пароли 5](image/8.png){#fig:008 width=70%}

![Пароли 6](image/9.png){#fig:009 width=70%}

![Фишинг 1](image/10.png){#fig:010 width=70%}

![Фишинг 2](image/11.png){#fig:011 width=70%}

![Вирусы 1](image/12.png){#fig:012 width=70%}

![Вирусы 2](image/13.png){#fig:013 width=70%}

![Безопасность мессенджеров 1](image/14.png){#fig:014 width=70%}

![Безопасность мессенджеров 2](image/15.png){#fig:015 width=70%}

::: {#refs}
:::
