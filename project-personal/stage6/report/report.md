---
## Front matter
title: "Отчет по персональному проекту 6"
subtitle: "Дисциплина:Операционные системы"
author: "Алехин Давид Андреевич"

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
mainfont: IBM Plex Serif
romanfont: IBM Plex Serif
sansfont: IBM Plex Sans
monofont: IBM Plex Mono
mathfont: STIX Two Math
mainfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
romanfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
sansfontoptions: Ligatures=Common,Ligatures=TeX,Scale=MatchLowercase,Scale=0.94
monofontoptions: Scale=MatchLowercase,Scale=0.94,FakeStretch=0.9
mathfontoptions:
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

Создать свой сайт.

# Задание

    Сделать поддержку английского и русского языков.
    Разместить элементы сайта на обоих языках.
    Разместить контент на обоих языках.
    Сделать пост по прошедшей неделе.
    Добавить пост на тему по выбору (на двух языках).


# Теоретическое введение



# Выполнение лабораторной работы

Добавьте в config/_default/config.yaml настройки для двух языков: (рис. [-@fig:001]).

![1](/home/david_aliokhin/work/study/2025-2026/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2025-05-22 15-39-48.png){#fig:001 width=70%}

Проверяю отоброжение языков (рис. [-@fig:002]).

![2](/home/david_aliokhin/work/study/2025-2026/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2025-05-22 15-42-28.png){#fig:002 width=70%}

Создаю файлы about.md для структуры файловой системы, а также разделяю структуру на английские файлы и русские (переношу поссты проекты и тд в эти папки, в папку с английским языком встявляю их перевод).  (рис. [-@fig:003], [-@fig:004] ).

![3](/home/david_aliokhin/work/study/2025-2026/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2025-05-22 15-46-47.png){#fig:003 width=70%}

![4](/home/david_aliokhin/work/study/2025-2026/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2025-05-22 15-47-04.png){#fig:004 width=70%}

Настраиваю переключение языков (рис. [-@fig:005]).

![5](/home/david_aliokhin/work/study/2025-2026/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2025-05-29 15-26-34.png){#fig:005 width=70%}

Проверяю переключение на сайте, вижу что появилась кноака для смены языков (рис. [-@fig:006]).

![6](/home/david_aliokhin/work/study/2025-2026/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2025-05-27 16-21-47.png){#fig:006 width=70%}

Пишу пост по прошедшей неделе (2 файла на русском и английском) (рис. [-@fig:007], [-@fig:008]).

![7](/home/david_aliokhin/work/study/2025-2026/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2025-05-27 16-45-46.png){#fig:007 width=70%}

![8](/home/david_aliokhin/work/study/2025-2026/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2025-05-27 16-47-00.png){#fig:008 width=70%}

Создаю пост на тему по выбору на 2х языках (рис. [-@fig:009], [-@fig:010]).

![9](/home/david_aliokhin/work/study/2025-2026/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2025-05-27 16-49-28.png){#fig:009 width=70%}

![10](/home/david_aliokhin/work/study/2025-2026/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2025-05-27 16-50-47.png){#fig:010 width=70%}

Смотрю результат на разных языках (рис. [-@fig:011], [-@fig:012]).

![11](/home/david_aliokhin/work/study/2025-2026/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2025-05-27 16-52-05.png){#fig:011 width=70%}

![12](/home/david_aliokhin/work/study/2025-2026/Операционные системы/os-intro/project-personal/stage6/report/image/Снимок экрана от 2025-05-27 16-52-16.png){#fig:012 width=70%}

# Выводы

Я выполнил все задания по проекту:
Сделать поддержку английского и русского языков.
    Разместить элементы сайта на обоих языках.
    Разместить контент на обоих языках.
    Сделать пост по прошедшей неделе.
    Добавить пост на тему по выбору (на двух языках).




# Список литературы{.unnumbered}

https://esystem.rudn.ru/mod/page/view.php?id=1224217
    
