---
## Front matter
lang: ru-RU
title: Научная презентация (индивидуальный проект часть 1)
subtitle: Дисциплина:Операционные системы
author:
  - Алехин Давид Андреевич
institute:
  - Российский университет дружбы народов, Москва, Россия
  - Математический институт имени Никольского, Москва, Россия
date: 06.03.25

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Алехин Давид Андреевич 
  * Студент 
  * Студент НММбд-01-24
  * Российский университет дружбы народов
  * [1132246830@pfur.ru](mailto:trustdef@gamil.com)
  * <https://github.com/trustdef>

:::
::: {.column width="30%"}

![]()

:::
::::::::::::::

# Вводная часть

## Актуальность

- В современном мире многие занимаются предпринимательством, поэтому важно уметь самому делать сайты.

## Объект и предмет исследования

- Конструктор сайтов hugo 

## Цели и задачи


- Установить hugo  
- Добавить репозиторий с сайтом 
- Запустить свой первый сайт 


## Материалы и методы

- https://github.com/wowchemy/starter-hugo-academic (репозиторий странички)
- hugo-extended 

# Создание презентации

## Процессор `pandoc`

- Pandoc: преобразователь текстовых файлов
- Сайт: <https://pandoc.org/>
- Репозиторий: <https://github.com/jgm/pandoc>

## Формат `pdf`

- Использование LaTeX
- Пакет для презентации: [beamer](https://ctan.org/pkg/beamer)
- Тема оформления: `metropolis`

## Код для формата `pdf`

```yaml
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
```

## Формат `html`

- Используется фреймворк [reveal.js](https://revealjs.com/)
- Используется [тема](https://revealjs.com/themes/) `beige`

## Код для формата `html`

- Тема задаётся в файле `Makefile`

```make
REVEALJS_THEME = beige 
```
# Результаты

## Получающиеся форматы

- Полученный `pdf`-файл можно демонстрировать в любой программе просмотра `pdf`
- Полученный `html`-файл содержит в себе все ресурсы: изображения, css, скрипты

# Элементы презентации

## Актуальность

- В современном мире многие занимаются предпринимательством, поэтому важно уметь самому делать сайты.


## Цели и задачи

- Установить hugo  
- Добавить репозиторий с сайтом 
- Запустить свой первый сайт 

## Материалы и методы

- https://github.com/wowchemy/starter-hugo-academic (репозиторий странички)
- hugo-extended 

## Содержание исследования
Для начала устанавливаю hugo_extended из официального репозитория с помощью команды wget, после распаковываю и переножу в файл /usr/local/bin (забыл сделать скрин).
 
Добавляю себе в git репозиторий с будующей страничкой сайта и синхронизирую (рис. [-@fig:001]).

![Репозиторий](/home/david_aliokhin/work/study/2025-2026/Операционные системы/os-intro/project-personal/stage1/report/image/Снимок экрана от 2025-03-03 20-08-40.png){#fig:001 width=70%}

## Содержание исследования

Далее перехожу в репозиторий и запускаю сервер (рис. [-@fig:002]).

![Сервер](/home/david_aliokhin/work/study/2025-2026/Операционные системы/os-intro/project-personal/stage1/report/image/Снимок экрана от 2025-03-03 21-14-40.png){#fig:002 width=70%}

## Содержание исследования

Перехожу на сайт (рис. [-@fig:003]).

![Сайт](/home/david_aliokhin/work/study/2025-2026/Операционные системы/os-intro/project-personal/stage1/report/image/Снимок экрана от 2025-03-03 21-15-24.png){#fig:003 width=70%}

## Содержание исследования

Создаю подрепозиторий для сайта (рис. [-@fig:004]).

![Создаю подрепозиторий](/home/david_aliokhin/work/study/2025-2026/Операционные системы/os-intro/project-personal/stage1/report/image/Снимок экрана от 2025-03-04 18-58-44.png){#fig:004 width=70%}

## Содержание исследования

Клонирую подрепозиторий для сайта (рис. [-@fig:005]).

![Клонирую подрепозиторий](/home/david_aliokhin/work/study/2025-2026/Операционные системы/os-intro/project-personal/stage1/report/image/Снимок экрана от 2025-03-04 18-25-17.png){#fig:005 width=70%}

## Содержание исследования

Меняю URL (рис. [-@fig:006]).

![URL](/home/david_aliokhin/work/study/2025-2026/Операционные системы/os-intro/project-personal/stage1/report/image/Снимок экрана от 2025-03-04 18-22-43.png){#fig:006 width=70%}

## Содержание исследования

Запускаю сайт (рис. [-@fig:007]).

![Запуск сайта](/home/david_aliokhin/work/study/2025-2026/Операционные системы/os-intro/project-personal/stage1/report/image/Снимок экрана от 2025-03-04 18-29-23.png){#fig:007 width=70%}

## Содержание исследования

Отправляю изменения на git (рис. [-@fig:008]).

![Отправляю изменения](/home/david_aliokhin/work/study/2025-2026/Операционные системы/os-intro/project-personal/stage1/report/image/Снимок экрана от 2025-03-04 18-33-35.png){#fig:008 width=70%}





## Результаты

Я выполнил основную цель работы а именно:
Размещение на Github pages заготовки для персонального сайта.

## Итоговый слайд

В теории, теория и практика неразделимы. На практике это не так.
Yoggi Berra

:::

