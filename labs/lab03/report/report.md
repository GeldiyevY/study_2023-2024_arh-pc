---
## Front matter
title: "Лабараторная работа №03. НПИбд-03-24"
subtitle: "Подготовил:"
author: "Гелдиев Ыхлас. Студенческий номер: 1032249184"

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

Целью работы является оформление отчетов с использованием Markdown

# Выполнение лабораторной работы

1 Открыл терминал (рис. [-@fig:001])

![Открытие терминал](image/open_terminal.jpg){#fig:001 width=100%}

2 Перешел в каталог курса и обновил локальный репозиторий (рис. [-@fig:002]) (рис. [-@fig:003])

![Переход в arch-pc](image/goto_arch-pc.jpg){#fig:002 width=100%}

![git pull](image/git_pull.jpg){#fig:003 width=100%}

3 Перешел в каталог отчета по лабораторной работе № 3 (рис. [-@fig:004])

![Перешел в отчет](image/goto_report.jpg){#fig:004 width=100%}


![make](image/make_1.jpg){#fig:005 width=100%}

4 Провел компиляцию шаблона с использованием Makefile (рис. [-@fig:005])

![make clean](image/make_clean.jpg){#fig:006 width=100%}

5 Удалил файлы созданные make и убедился в этом используя ls (рис. [-@fig:006])

![открыте файла report.md](image/report_md.jpg){#fig:007 width=100%}

6 Открыл файл report.md и внимательно изучил его (рис. [-@fig:007])

# Выводы

Я научился формировать отчеты и компилировать их с использвованием Makefile

