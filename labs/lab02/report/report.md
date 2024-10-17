---
## Front matter
title: "Лабараторная работа №02. НПИбд-03-24"
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

## Базовая настройка git

1. Указал имя и email владельца репозитория (рис. [-@fig:001]).

![имя и email](image/name and email.jpg){#fig:001 width=70%}

2. Настроил utf-8 в выводе сообщений (рис. [-@fig:002])

![utf-8](image/utf-8.jpg){#fig:002}

3. Задал имя начальной ветки (рис. [-@fig:003])

![имя ветки](image/main_branch.jpg){#fig:003}

4. Настроил параметры autocrlf и safecrlf (рис. [-@fig:004])

![autocrlf и safecrlf](image/autocrlf_safecrlf.jpg){#fig:004}

## Создание SSH ключа

5. Сгенерировал пару ключей (приватный и открытый) (рис. [-@fig:005])

![Ключей](image/keys_generation.jpg){#fig:005}

6. Скопировал ключ в буфер обмена (рис. [-@fig:006])

![Скопировал](image/copy.jpg){#fig:006}

7. Добавил ключ на сайт (рис. [-@fig:007])

![Добавил ключ на сайт](image/keys_to_site.jpg){#fig:007}

## Сознание рабочего пространства и репозитория курса на основе шаблона

8. Создал каталог для предмета "Архитектура компьютера" (рис. [-@fig:008])

![arch-pс](image/arch-pc.jpg){#fig:008}

## Создание репозитория курса на основе шаблона

9. Создаю репозиторий на основе шаблона (рис. [-@fig:009])

![template](image/template.jpg){#fig:009}

10. Вписываю название и создаю репозиторий (рис. [-@fig:010])

![repository](image/repository.jpg){#fig:010}

11. Перешел в папку "Архитектура компьютера" (рис. [-@fig:011])

![Перешел в "Архитектура компьютера"](image/went_arch-pc.jpg){#fig:011}

12. Клонировал созданный репозиторий (рис. [-@fig:012])

![Клонировал репозиторий](image/clone_repo.jpg){#fig:012}

## Настройка каталога курса

13. Перешел в каталог курса (рис. [-@fig:013])

![Перешел в каталог курса](image/went_to_catalog.jpg){#fig:013}

14. Удалил лишние файлы (рис. [-@fig:014])

![Удаление](image/delete.jpg){#fig:014}

15. Создал нужные каталоги (рис. [-@fig:015])

![Создание каталогов](image/created_dirs.jpg){#fig:015}

16. Отправляю файлы на сервер (рис. [-@fig:016])

![git push](image/git_push.jpg){#fig:016}


## Самостоятельная работа

17. Создал каталоги для отчета (рис. [-@fig:017])

![mkdir](image/mkdir_report.jpg){#fig:017}

# Выводы

Я научился формировать отчеты и компилировать их с использвованием Makefile

