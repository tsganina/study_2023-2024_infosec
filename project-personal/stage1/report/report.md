---
## Front matter
title: "Отчёт по первому этапу проекта"
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

Целью данной работы является приобретение практических навыков установки операционной системы Kali Linux на виртуальную машину, настройки минимально необходимых для дальнейшей работы сервисов.

# Задание

1. Создать новую виртуальную машину. Загрузить образ.
2. Установить операционную систему и произвести первичные настройки.

# Теоретическое введение

Kali Linux — GNU/Linux-LiveCD, возникший как результат слияния WHAX и Auditor Security Collection. Проект создали Мати Ахарони (Mati Aharoni) и Макс Мозер (Max Moser). Предназначен прежде всего для проведения тестов на безопасность. Наследник развивавшегося до 2013 года на базе Knoppix дистрибутива BackTrack.

Популярность Kali Linux выросла после показа в нескольких эпизодах сериала Mr. Robot. Инструменты, показанные в фильме, включают Bluesniff, Bluetooth Scanner (btscanner), John the Ripper, Metasploit Framework, nmap, Shellshock и wget. 

# Выполнение лабораторной работы

1. Я произвела настройку новой виртуальной машины (рис. @fig:001, @fig:002, @fig:003, @fig:004, @fig:005, @fig:006).

![Скачала образ](image/1.png){#fig:001 width=70%}

![Скачала образ](image/2.png){#fig:002 width=70%}

![Создаю новую виртуальную машину, настраиваю папку и ее имя](image/3.png){#fig:003 width=70%}

![Настраиваю память и процессоры](image/4.png){#fig:004 width=70%}

![Виртуальный жесткий диск](image/5.png){#fig:005 width=70%}

![Видеопамять](image/6.png){#fig:006 width=70%}

2. Настройка системы (рис. @fig:007, @fig:008, @fig:009, @fig:010, @fig:011, @fig:012, @fig:013, @fig:014, @fig:015, @fig:016, @fig:017, @fig:018, @fig:019, @fig:020, @fig:021, @fig:022, @fig:023, @fig:024, @fig:025).

![Настройка языка](image/7.png){#fig:007 width=70%}

![Местонахождение](image/8.png){#fig:008 width=70%}

![Раскладка клавиатуры](image/9.png){#fig:009 width=70%}

![Переключение раскладки](image/10.png){#fig:010 width=70%}

![Установка](image/11.png){#fig:011 width=70%}

![Настройка сети](image/12.png){#fig:012 width=70%}

![Учетная запись](image/13.png){#fig:013 width=70%}

![Пробую ввести root](image/14.png){#fig:014 width=70%}

![Вышла ошибка, потому что это имя - системное](image/15.png){#fig:015 width=70%}

![Ввожу другое имя учетной записи](image/16.png){#fig:016 width=70%}

![Настраиваю пароль](image/17.png){#fig:017 width=70%}

![Настройка времени](image/18.png){#fig:018 width=70%}

![Разметка дисков](image/19.png){#fig:019 width=70%}

![Выбор диска для разметки](image/20.png){#fig:020 width=70%}

![Способ разметки](image/21.png){#fig:021 width=70%}

![Логические тома](image/22.png){#fig:022 width=70%}

![Разметка дисков](image/23.png){#fig:023 width=70%}

![Вход в систему](image/24.png){#fig:024 width=70%}

![Все настроено!](image/25.png){#fig:025 width=70%}


# Выводы

Был установлен дистрибутив Kali.

# Список литературы{.unnumbered}

1. [Статья об установке Kali](https://help.reg.ru/support/vydelennyye-servery-i-dc/vmware-virtualnyy-data-tsentr/sozdaniye-i-nastroyka-virtualnykh-mashin/kak-ustanovit-kali-linux-na-virtualbox)

2. [Видео по установке Kali Linux](https://www.youtube.com/watch?v=jlaVh22fFS8)

3. [Руководство к первой лабораторной работе](https://esystem.rudn.ru/pluginfile.php/2293709/mod_folder/content/0/001-lab_virtualbox.pdf)

::: {#refs}
:::
