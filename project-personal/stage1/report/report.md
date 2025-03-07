---
## Front matter
title: "Этап проекта №1"
subtitle: "Дисциплина: архитектура компьютера"
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

Размещение на Github pages заготовки для персонального сайта.

# Задание


    Установить необходимое программное обеспечение.
    Скачать шаблон темы сайта.
    Разместить его на хостинге git.
    Установить параметр для URLs сайта.
    Разместить заготовку сайта на Github pages.


# Теоретическое введение



# Выполнение лабораторной работы

Для начала устанавливаю hugo_extended из официального репозитория с помощью команды wget, после распаковываю и переножу в файл /usr/local/bin (забыл сделать скрин).
 
Добавляю себе в git репозиторий с будующей страничкой сайта и синхронизирую (рис. [-@fig:001]).

![Репозиторий](/home/david_aliokhin/work/study/2025-2026/Операционные системы/os-intro/project-personal/stage1/report/image/Снимок экрана от 2025-03-03 20-08-40.png){#fig:001 width=70%}

Далее перехожу в репозиторий и запускаю сервер (рис. [-@fig:002]).

![Сервер](/home/david_aliokhin/work/study/2025-2026/Операционные системы/os-intro/project-personal/stage1/report/image/Снимок экрана от 2025-03-03 21-14-40.png){#fig:002 width=70%}

Перехожу на сайт (рис. [-@fig:003]).

![Сайт](/home/david_aliokhin/work/study/2025-2026/Операционные системы/os-intro/project-personal/stage1/report/image/Снимок экрана от 2025-03-03 21-15-24.png){#fig:003 width=70%}

Создаю подрепозиторий для сайта (рис. [-@fig:004]).

![Создаю подрепозиторий](/home/david_aliokhin/work/study/2025-2026/Операционные системы/os-intro/project-personal/stage1/report/image/Снимок экрана от 2025-03-04 18-58-44.png){#fig:004 width=70%}

Клонирую подрепозиторий для сайта (рис. [-@fig:005]).

![Клонирую подрепозиторий](/home/david_aliokhin/work/study/2025-2026/Операционные системы/os-intro/project-personal/stage1/report/image/Снимок экрана от 2025-03-04 18-25-17.png){#fig:005 width=70%}

Меняю URL (рис. [-@fig:006]).

![URL](/home/david_aliokhin/work/study/2025-2026/Операционные системы/os-intro/project-personal/stage1/report/image/Снимок экрана от 2025-03-04 18-22-43.png){#fig:006 width=70%}

Запускаю сайт (рис. [-@fig:007]).

![Запуск сайта](/home/david_aliokhin/work/study/2025-2026/Операционные системы/os-intro/project-personal/stage1/report/image/Снимок экрана от 2025-03-04 18-29-23.png){#fig:007 width=70%}

Отправляю изменения на git (рис. [-@fig:008]).

![Отправляю изменения](/home/david_aliokhin/work/study/2025-2026/Операционные системы/os-intro/project-personal/stage1/report/image/Снимок экрана от 2025-03-04 18-33-35.png){#fig:008 width=70%}

# Выводы

Я выполнил основную цель работы а именно:
Размещение на Github pages заготовки для персонального сайта.

# Список литературы{.unnumbered}

https://yamadharma.github.io/ru/post/2022/04/12/creating-hugo-site/
:::
