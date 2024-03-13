---
## Front matter
title: "Отчёт по второму этапу проекта"
subtitle: "Дисциплина: Основы информационной безопасности"
author: "Ганина Таисия Сергеевна, НКАбд-01-22"

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

# Цель работы

Установить DVWA и провести первичную настройку.

# Задание

1. Скачать с репозитория DVWA.
2. Провести настройку и запустить.

# Теоретическое введение

Веб-приложение Damn Vulnerable — это программный проект, который намеренно содержит уязвимости в системе безопасности и предназначен для образовательных целей.

# Выполнение лабораторной работы

Смотрю задание (рис. @fig:001).

![Задание](image/1.png){#fig:001 width=70%}

Клонирую репозиторий (рис. @fig:002).

![Клонирование](image/2.png){#fig:002 width=70%}

Произвожу установку и настройку (рис. @fig:003, @fig:004, @fig:005, @fig:006, @fig:007, @fig:008, @fig:009, @fig:010, @fig:011, @fig:012, @fig:013, @fig:014, @fig:015, @fig:016, @fig:017, @fig:018, @fig:019).

![Перемещаю файлы](image/3.png){#fig:003 width=70%}

![Запускаю страничку старта](image/4.png){#fig:004 width=70%}

![Перемещаю файлы](image/5.png){#fig:005 width=70%}

![Запускаю сервер](image/6.png){#fig:006 width=70%}

![Перехожу к корневому пользователю](image/7.png){#fig:007 width=70%}

![Соединение с сервером](image/8.png){#fig:008 width=70%}

![Создаю базу данных](image/9.png){#fig:009 width=70%}

![Создаю базу данных](image/10.png){#fig:010 width=70%}

![Задаю пароль и логин пользователя](image/11.png){#fig:011 width=70%}

![Сохраняю изменения](image/12.png){#fig:012 width=70%}

![Создаю базу данных](image/13.png){#fig:013 width=70%}

![Загрузка утилиты](image/14.png){#fig:014 width=70%}

![Проверка настроек](image/15.png){#fig:015 width=70%}

![Настраиваю](image/16.png){#fig:016 width=70%}

![Меняю id](image/17.png){#fig:017 width=70%}

![Настраиваю](image/18.png){#fig:018 width=70%}

![Результат](image/19.png){#fig:019 width=70%}

# Выводы

Установила DVWA.

# Список литературы{.unnumbered}

1. [Видео](https://www.youtube.com/watch?v=WkyDxNJkgQ4)

::: {#refs}
:::
