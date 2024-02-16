---
## Front matter
title: "Отчёт по лабораторной работе №1"
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

Целью данной работы является приобретение практических навыков установки операционной системы Rocky Linux на виртуальную машину, настройки минимально необходимых для дальнейшей работы сервисов.

# Задание

1. Создать новую виртуальную машину. Загрузить образ.
2. Установить операционную систему и произвести первичные настройки.
3. Домашнее задание.
4. Контрольные вопросы.

# Теоретическое введение

## Rocky Linux

Rocky Linux — дистрибутив Linux, разработанный Rocky Enterprise Software Foundation. Предполагается, что это будет полный бинарно-совместимый выпуск, использующий исходный код операционной системы Red Hat Enterprise Linux (RHEL). Цель проекта — предоставить корпоративную операционную систему производственного уровня, поддерживаемую сообществом. Rocky Linux, наряду с Red Hat Enterprise Linux и SUSE Linux Enterprise, стала популярной для использования в корпоративных операционных системах.

Первая версия-кандидат на выпуск Rocky Linux была выпущена 30 апреля 2021 г., а ее первая общедоступная версия была выпущена 21 июня 2021 г. Rocky Linux 8 будет поддерживаться до мая 2029 г. 

## VirtualBox

VirtualBox (Oracle VM VirtualBox) — программный продукт виртуализации для операционных систем Windows, Linux, FreeBSD, macOS, Solaris/OpenSolaris, ReactOS, DOS и других. 

Программа была создана компанией Innotek с использованием исходного кода QEMU. Первая публично доступная версия VirtualBox появилась 15 января 2007 года. В феврале 2008 года Innotek был приобретён компанией Sun Microsystems, модель распространения VirtualBox при этом не изменилась. В январе 2010 года Sun Microsystems была поглощена корпорацией Oracle, модель распространения осталась прежней.

# Выполнение лабораторной работы

1. Я произвела настройку новой виртуальной машины (рис. @fig:001, @fig:002, @fig:003, @fig:004, @fig:005, @fig:006, @fig:007).

![VirtualBox](image/1.png){#fig:001 width=70%}

![Загружаю образ Rocky DVD](image/2.png){#fig:002 width=70%}

![Создание виртуальной машины, имя и операционная система](image/3.png){#fig:003 width=70%}

![Оборудование: 2048МБ памяти и 6 процессоров](image/4.png){#fig:004 width=70%}

![Виртуальный жесткий диск](image/5.png){#fig:005 width=70%}

![Загружаю образ](image/6.png){#fig:006 width=70%}

![Итог](image/7.png){#fig:007 width=70%}

2. Настройка системы (рис. @fig:008, @fig:009, @fig:010, @fig:011, @fig:012, @fig:013, @fig:014, @fig:015, @fig:016, @fig:017).

![Установка языка](image/8.png){#fig:008 width=70%}

![Место установки](image/9.png){#fig:009 width=70%}

![Выбор программ](image/10.png){#fig:010 width=70%}

![Отключение KDUMP](image/11.png){#fig:011 width=70%}

![Сеть и имя узла](image/12.png){#fig:012 width=70%}

![Пароль](image/13.png){#fig:013 width=70%}

![Создание пользователя](image/14.png){#fig:014 width=70%}

![Дата и время](image/15.png){#fig:015 width=70%}

![Установка](image/16.png){#fig:016 width=70%}

![Итог](image/17.png){#fig:017 width=70%}

3. Задания (рис. @fig:018, @fig:019, @fig:020, @fig:021, @fig:022, @fig:023, @fig:024, @fig:025).

![dmesg | less](image/18.png){#fig:018 width=70%}

![Версия Линукс](image/19.png){#fig:019 width=70%}

![Частота процессора](image/20.png){#fig:020 width=70%}

![Модель процессора](image/21.png){#fig:021 width=70%}

![Объем доступной оперативной памяти](image/22.png){#fig:022 width=70%}

![Тип обнаруженного гипервизора](image/23.png){#fig:023 width=70%}

![Тип файловой системы корневого раздела.](image/24.png){#fig:024 width=70%}

![Последовательность монтирования файловых систем](image/25.png){#fig:025 width=70%}


# Выводы

Был установлен дистрибутив Rocky.

# Контрольные вопросы

1. Какую информацию содержит учётная запись пользователя?

Учетная запись пользователя содержит информацию по авторизации - учётные данные. Это идентификатор для подключения к системе. То есть, это:

- Системное имя - должно быть уникальным, содержит только латинские
знаки.
- Уникальных идентификатор пользователя в системе, содержит число.
- Полное имя - ФИО пользователя.


2. Укажите команды терминала и приведите примеры:

- для получения справки по команде = –help;
- для перемещения по файловой системе = cd;
- для просмотра содержимого каталога = ls;
- для определения объёма каталога = du + имя каталога;
- для создания / удаления каталогов = mkdir/rmdir;
- для создания / удаления файлов = touch/rm;
- для задания определённых прав на файл / каталог = chmod;
- для просмотра истории команд = history;
3. Что такое файловая система? Приведите примеры с краткой характеристикой.

Это способ хранения, организации и именования данных на различных носителях. 

Примеры:
- FAT32 - файловая система, в которой пространство разделено на три
части: область служебных структур, указатели в виде таблиц и область
хранения файлов;
- ext4 - система, которая используется в основном в ОС на Linux. Журналируемая файловая система, в послдней версии максимальный размер файла - 16Гб.

4. Как посмотреть, какие файловые системы подмонтированы в ОС?

Для этого нужно ввести в терминал команду df - это покажет список всех файловых систем по номерам устройств, размеры и данные о памяти. Но при этом
можно посмотреть в свойствах папок все эти данные вручную.

5. Как удалить зависший процесс?

- killall - остановит все процессы, которые есть в данный момент.
- kill + id-процесса. Это поможет удалить один конкретный процесс.
(Чтобы узнать id нужно написать в терминале команду ps).

# Список литературы{.unnumbered}

1. [Руководство к лабораторной работе](https://esystem.rudn.ru/pluginfile.php/2293709/mod_folder/content/0/001-lab_virtualbox.pdf)


::: {#refs}
:::
