---
# Front matter
lang: ru-RU
title: "Лабораторная работа №1"
subtitle: "Математическое моделирование"
author: "Давтян Артур Арменович"

# Formatting
toc-title: "Содержание"
toc: true # Table of contents
toc_depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4paper
documentclass: scrreprt
polyglossia-lang: russian
polyglossia-otherlangs: english
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase
indent: true
pdf-engine: lualatex
header-includes:
  - \linepenalty=10 # the penalty added to the badness of each line within a paragraph (no associated penalty node) Increasing the value makes tex try to have fewer lines in the paragraph.
  - \interlinepenalty=0 # value of the penalty (node) added after each line of a paragraph.
  - \hyphenpenalty=50 # the penalty for line breaking at an automatically inserted hyphen
  - \exhyphenpenalty=50 # the penalty for line breaking at an explicit hyphen
  - \binoppenalty=700 # the penalty for breaking a line at a binary operator
  - \relpenalty=500 # the penalty for breaking a line at a relation
  - \clubpenalty=150 # extra penalty for breaking after first line of a paragraph
  - \widowpenalty=150 # extra penalty for breaking before last line of a paragraph
  - \displaywidowpenalty=50 # extra penalty for breaking before last line before a display math
  - \brokenpenalty=100 # extra penalty for page breaking after a hyphenated line
  - \predisplaypenalty=10000 # penalty for breaking before a display
  - \postdisplaypenalty=0 # penalty for breaking after a display
  - \floatingpenalty = 20000 # penalty for splitting an insertion (can only be split footnote in standard LaTeX)
  - \raggedbottom # or \flushbottom
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Научиться создавать репозитории в github, использовать Git Bash, загружать файлы и папки на GitHub с помощью Git Bash.

# Задание

## Привязать к аккаунту SSH-ключ
## Создать репозиторий
## Первичная настройка Git Bash
## Создать git-репозиторий из каталога на компьютере
## Создать каталог и файл и дать commit
## Загрузить на GitHub


# Выполнение лабораторной работы

## Привязка SSH-ключа к аккаунту 

Создаем SSH-ключ для аккаунта, придумываем пароль, копируем ключ. (рис. -@fig:001)

![Создание SSH-ключа](image/1.png){ #fig:001 width=70% }

Добавляем созданный SSH-ключ в профиль GitHub. (рис. -@fig:002)

![Добавление созданного SSH-ключа в GitHub](image/1b.png){ #fig:002 width=70% }

Проверяем работоспособность SSH-ключа. (рис. -@fig:003)

![Проверка SSH-ключа](image/1a.png){ #fig:003 width=70% }

## Создание репозитория

Заходим на профиль и жмём зеленую кнопку New. (рис. -@fig:004)

![Стрелочка указывает на нужную кнопку](image/2.png){ #fig:004 width=70% }

Даём нашему репозиторию имя (в данном случае — "2020-2021_mathmod"), оставляем его публичным и сохраняем. (рис. -@fig:005)

![Создание репозитория](image/2a.png){ #fig:005 width=70% }


## Первичная настройка Git Bash

Делаем все переводы строк текстовых файлов в главном репозитории одинаковыми и отображение Unicode. (рис. -@fig:006)

![Команды первоначальной настройки](image/3.png){ #fig:006 width=70% }

## Создание git-репозитория из каталога на компьютере.

Вводим git init, создаем файл README с текстом, добавляем в репозиторий созданный файл, добавляем commit, привязываем каталог на компьютере к репозиторию GitHub, добавляем все в репозиторий.(рис. -@fig:007)

![Создание git-репозитория](image/3a.png){ #fig:007 width=70% }

## Создание каталога и файла

Создаем папку lab01 с помощью команды mkdir lab01. Заходим в эту папку (cd lab01), создаём файл hello.html, записываем в нее "Hello, World!", добавляем commit, добавляем в репозиторий на GitHub.(рис. -@fig:008)

![Создание каталога и фпйла](image/3a.png){ #fig:008 width=70% }

## Загрузка на GitHub
В итоге у нас получилось следующее. (рис. -@fig:009)

![Репозиторий на GitHub](image/5.png){ #fig:009 width=70% }

# Выводы

Научился создавать репозитории в github, использовать Git Bash, загружать файлы и папки на GitHub с помощью Git Bash.

