---
## Front matter
title: "Лабараторная работа №08. НПИбд-03-24"
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

Освоить написание программ с использованием циклов и обработкой аргументов командной строки.

# Выполнение лабораторной работы

## Реализация циклов в NASM

1. Создал каталог для программ, перешел в него и создал файл lab8-1.asm (рис. [-@fig:001])

![Создал lab8-1.asm](image/create_lab8-1.png){#fig:001}

2. Заполнил lab8-1.asm (рис. [-@fig:002])

![Заполнил lab8-1](image/fill_lab8-1.png){#fig:002}

3. Создал исполняемый файл и запустил его (рис. [-@fig:003])

![Запуск lab8-1](image/run_lab8-1.png){#fig:003}

4. Изменил текст программы (рис. [-@fig:004])

![Изменил текст lab8-1](image/fill_lab8-1_2.png){#fig:004}

5. Создал исполняемый файл и запустил его (рис. [-@fig:005])

![Запуск измененного lab8-1](image/run_lab8-1_2.png){#fig:005}

6. Изменил текст программы, с использованием стека в программу для сохранения корректности работы программы (рис. [-@fig:006])

![Использование стека в программе](image/fill_lab8-1_3.png){#fig:006}

7. Проверка выполнения (рис. [-@fig:007])

![Проверка выполнения](image/run_lab8-1_3.png){#fig:007}

## Обработка аргументов командной строки

8. Создал файл lab8-2.asm (рис. [-@fig:008])

![Создание lab8-2](image/create_lab8-2.png){#fig:008}

9. Заполнил lab8-2.asm (рис. [-@fig:009])

![Заполнение lab8-2](image/fill_lab8-2.png){#fig:009}

10. Создал исполняемый файл и запустил его, указав аргументы. Программа обработала 4 аргумента (рис. [-@fig:010])

![Запуск lab8-2 с аргументами и без](image/run_lab8-2.png){#fig:010}

11. Создал файл lab8-3.asm (рис. [@-fig:011])

![Создание lab8-3.asm](image/create_lab8-3.png){#fig:011}

12. Заполнил lab8-3.asm (рис. [-@fig:012])

![Заполнение lab8-3.asm](image/fill_lab8-3.png){#fig:012}

13. Создал исполняемый файл и запустил его (рис. [-@fig:013])

![Проверка lab8-3.asm](image/run_lab8-3.png){#fig:013}

14. Изменил текст программы для вычисления произведения аргументов командной строки (рис. [-@fig:014])

![Измение программы для вычисления произведения](image/fill_lab8-3_2.png){#fig:014}

15. Проверка программы (рис. [-@fig:015])

![Проверка корректности программы](image/run_lab8-3_2.png){#fig:015}

# Задание для самостоятельной работы

1. Программа для нахождения суммы значений функции f(x) для разных x (рис. [-@fig:016]) (рис. [-@fig:017])

![Программа main.asm](image/fill_main.png){#fig:016}

![Запуск main](image/run_main.png){#fig:017}

# Выводы

Я научился писать программы с использованием циклов и обработкой аргументов командной строки.

