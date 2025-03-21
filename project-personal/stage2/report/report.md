---
## Front matter
title: "Отчет по индивидуальному проекту №2"
subtitle: "Дисциплина: Операционные системы"
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

Добавить к сайту данные о себе.

# Задание


    Разместить фотографию владельца сайта.
    Разместить краткое описание владельца сайта (Biography).
    Добавить информацию об интересах (Interests).
    Добавить информацию от образовании (Education).
    Сделать пост по прошедшей неделе.
    Добавить пост на тему по выбору:
    Управление версиями. Git.
    Непрерывная интеграция и непрерывное развертывание (CI/CD).

# Теоретическое введение



# Выполнение лабораторной работы

Добавляю основную информацию для лицевой страници сайта (рис. [-@fig:001]).

![Основная информация](/home/david_aliokhin/work/study/2025-2026/Операционные системы/os-intro/project-personal/stage2/report/image/Снимок экрана от 2025-03-21 12-35-45.png){#fig:001 width=70%}

Добавляю Biography (рис. [-@fig:002]).

![Biography](/home/david_aliokhin/work/study/2025-2026/Операционные системы/os-intro/project-personal/stage2/report/image/Снимок экрана от 2025-03-21 12-38-58.png){#fig:002 width=70%}

Добавляю Interests (рис. [-@fig:003]).

![Interests](/home/david_aliokhin/work/study/2025-2026/Операционные системы/os-intro/project-personal/stage2/report/image/Снимок экрана от 2025-03-21 12-40-45.png){#fig:003 width=70%}

Добавляю Education (рис. [-@fig:004]).

![Education](/home/david_aliokhin/work/study/2025-2026/Операционные системы/os-intro/project-personal/stage2/report/image/Снимок экрана от 2025-03-21 13-39-21.png){#fig:004 width=70%}

Добавляю своё фото (рис. [-@fig:005]).

![Фото](/home/david_aliokhin/work/study/2025-2026/Операционные системы/os-intro/project-personal/stage2/report/image/Снимок экрана от 2025-03-21 12-48-58.png){#fig:005 width=70%}

Добавляю првый пост о прешедшей неделе (рис. [-@fig:006]).

![пост о прешедшей неделе](/home/david_aliokhin/work/study/2025-2026/Операционные системы/os-intro/project-personal/stage2/report/image/Снимок экрана от 2025-03-21 12-59-54.png){#fig:006 width=70%}

Добавляю пост о системах управления гит (рис. [-@fig:007]).

![пост о системах управления гит](/home/david_aliokhin/work/study/2025-2026/Операционные системы/os-intro/project-personal/stage2/report/image/Снимок экрана от 2025-03-21 13-11-32.png){#fig:007 width=70%}

Смотнрю результат (рис. [-@fig:008], [-@fig:009]).

![посты](/home/david_aliokhin/work/study/2025-2026/Операционные системы/os-intro/project-personal/stage2/report/image/Снимок экрана от 2025-03-21 13-28-28.png){#fig:008 width=70%}

![лицевая часть](/home/david_aliokhin/work/study/2025-2026/Операционные системы/os-intro/project-personal/stage2/report/image/Снимок экрана от 2025-03-21 13-29-00.png){#fig:009 width=70%}

# Выводы

Я выполнил основную цель:
Добавить к сайту данные о себе.

# Список литературы{.unnumbered}

https://esystem.rudn.ru/mod/page/view.php?id=1224217
