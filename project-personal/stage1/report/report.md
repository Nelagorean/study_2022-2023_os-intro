---
## Front matter
title: "Отчёт по выполнению 1го этаа Индивидуального проекта"
subtitle: "Создание сайта на Hugo"
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

Создать сайт на Hugo

# Задание


1. Установить необходимое программное обеспечение.
2. Скачать шаблон темы сайта.
2. Разместить его на хостинге git.
3. Установить параметр для URLs сайта.
4. Разместить заготовку сайта на Github pages.


# Теоретическое введение

Сайт – это совокупность веб-страниц, объединённых под общим доменом и связанных ссылками, тематикой и дизайнерским оформлением. Мы будем создавать статический сайт, для этого нам понадобится Hugo. Hugo — генератор статических страниц для интернета.

# Выполнение 1го этапа инд. проекта

Установим необходимое програмное обеспечение. Скачаем Hugo, распаковываем архим и переносим в новую папку bin в домю каталоге.   
В качестве шаблона индивидуального сайта используется шаблон Hugo Academic Theme. Переходим по ссылке и создаем репозиторий blog, копируем его. Выполняем команду hugo и удаляем "public" из blog.
(рис. [-@fig:001], [-@fig:002])

![команда hugo](image/1.png){#fig:001 width=70%}

![удаление "public"](image/2.png){#fig:002 width=70%}

Выполним команду hugo server (создадутся необходимые файлы). Нам предоставят ссылку. Переходя по ней, открывается наш сайт
(рис. [-@fig:003])

![команда hugo server](image/3.png){#fig:001 width=70%}

Cоздаем еще один репозиторий. Клонируем наш новый репозиторий. Создаем ветку main. Создаем файл README.md. Добавляем в наш репозиторий. 
(рис. [-@fig:004])

![клонирование нового репозитория](image/4.png){#fig:004 width=70%}

Подключаем наш репозиторий к папке public, проверяем всё ли получилось и добавляем файлы в репозиторий.
(рис. [-@fig:005])

![добавление файлов в репозиторий](image/6.png){#fig:005 width=70%}


# Выводы

Научились создавать статические сайты с помощью Hugo.

# Список литературы{.unnumbered}

::: {#refs}
:::
