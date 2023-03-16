---
## Front matter
title: "Отчёт по выполнению 2го этаа Индивидуального проекта"
subtitle: "Добавлениее данных о себе на сайт"
author: "Горяйнова Алёна Андреевна"

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

Постепенно заполнять сайт информацией о себе, новыми постами и тд.

# Задание


- Разместить фотографию владельца сайта.
- Разместить краткое описание владельца сайта (Biography).
- Добавить информацию об интересах (Interests).
- Добавить информацию от образовании (Education).
- Сделать пост по прошедшей неделе.
- Добавить пост на тему "Управление версиями. Git."
  

# Выполнение лабораторной работы

Редактируем сайт через изменение файлов в папке blog и клонируем в соответсвующий репозиторий
Поменяли аватар
(рис. @fig:001)

![Моя новая аватарка](image/1.png){#fig:001 width=70%}

Создали статью про системы контроля версий, поменяли картинку
(рис. @fig:003)

![Пост про Git](image/2.png){#fig:002 width=70%}

Написали статью про прощедшую неделю и тоже добавили картинку
(рис. @fig:003)

![Пост по прошедшей неделе](image/3.png){#fig:003 width=70%}

Всё это загрузилось на сайт и готово)

# Выводы

Я научилась работать с некоторой информацией на сайте, создавать посты и менять аватар

# Список литературы{.unnumbered}

::: {#refs}
:::
