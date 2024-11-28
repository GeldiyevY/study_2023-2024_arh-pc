---
## Front matter
title: "Лабараторная работа №07. НПИбд-03-24"
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

Изучение команд для условных и безусловных переходов. Освоение навыков программирования с применением переходов. Ознакомление с назначением и структурой файла с листингом.

# Выполнение лабораторной работы

## Реализация переходов в NASM

1. Создал каталог для программ, перешел в него и создал файл lab7-1.asm (рис. [-@fig:001])

![Создал lab7-1.asm](image/create_lab7-1.png){#fig:001}

2. Заполнил lab7-1.asm (рис. [-@fig:002])

![Заполнил lab7-1](image/fill_lab7-1.png){#fig:002}

3. Создал исполняемый файл и запустил его (рис. [-@fig:003])

![Запуск lab7-1](image/run_lab7-1.png){#fig:003}

4. Изменил текст программы (рис. [-@fig:004])

![Изменил текст lab7-1](image/fill_lab7-1_2.png){#fig:004}

5. Создал исполняемый файл и запустил его (рис. [-@fig:005])

![Запуск измененного lab7-1](image/run_lab7-1_2.png){#fig:005}

6. Изменил текст программы так, что бы он соответствовал выводу (рис. [-@fig:006])

![Выполнение мини задания](image/fill_lab7-1_3.png){#fig:006}

7. Проверка выполнения (рис. [-@fig:007])

![Проверка выполнения](image/run_lab7-1_3.png){#fig:007}

8. Созданил файл lab7-2.asm (рис. [-@fig:008])

![Создание lab7-2](image/create_lab7-2.png){#fig:008}

9. Заполнил lab7-2.asm (рис. [-@fig:009])

![Заполнение lab7-2](image/fill_lab7-2.png){#fig:009}

10. Создал исполняемый файл и запустил его (рис. [-@fig:010])

![Запуск lab7-2](image/run_lab7-2.png){#fig:010}

## Изучение структуры файлы листинга

11. Создал файл листинга для программы из файла lab7-2.asm и открыл его (рис. [-@fig:011])

![Компиляция с листингом](image/listing_lab7-2.png){#fig:011}

12. Изменил файл lab7-2 (рис. [-@fig:012])

![Ошибка в lab7-2](image/changed_one_line_lab7-2.png){#fig:012}

13. Создание файла листинга для измененной программы и нахождение изменений (рис. [-@fig:013])

![Измененный листинг](image/added_to_listing.png){#fig:013}

# Задание для самостоятельной работы

1. Программа для нахождения наименьшего из 3 целочисленных переменных (рис. [-@fig:014]) (рис. [-@fig:015])

![Программа hw1](image/fill_hw1.png){#fig:014}

![Запуск hw1](image/run_hw1.png){#fig:015}

2. Программа для вычеслений по формулам 2(x-a) при x>a и 15, при x<=a (Вариант №5) (рис. [-@fig:016]) (рис. [-@fig:017])

![Программма hw2](image/fill_hw2.png){#fig:016}

![Запуск hw2](image/run_hw2.png){#fig:017}

# Выводы

Я изучил команды для условных и безусловных переходов. Я освоил навыки программирования с применением переходов и ознакомился с назначением и структурой файла с листингом.

