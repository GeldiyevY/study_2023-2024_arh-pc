---
## Front matter
title: "Лабараторная работа №06. НПИбд-03-24"
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

Освоить арифметические инструкций языка ассемблера в NASM.

# Выполнение лабораторной работы

1. Создал каталог для програм лабораторной работы № 6 и перешел в него
и создал файл lab6-1.asm (рис. [-@fig:001])

![Подготовка к лабораторной](image/creating_files_for_lab6.jpg){#fig:001 width=100%}

2. Ввел в файл lab6-1.asm текст программы из листинга 6.1 (рис. [-@fig:002])

![Заполнение lab6-1.asm](image/inserted_lab6-1.jpg){#fig:002 width=100%}

3. Создал исполняемый файл и запустил его (рис. [-@fig:003]).

![Запуск lab6-1](image/run_lab6-1.jpg){#fig:003 width=100%}

4. Изменил текст программы и вместо символов, записал в регистры числа (рис. [-@fig:004]).

![Исправление lab6-1](image/changed_char_to_int_lab6-1.jpg){#fig:004 width=100%}

5. Создал исполняемый файл и запустил его (рис. [-@fig:005]).

![Запуск исправленного lab6-1](image/run_lab6-1_2.jpg){#fig:005 width=100%}

6. Создал файл lab6-2.asm в каталоге ~/work/arch-pc/lab06 и ввел в него текст программы (рис. [-@fig:006]) (рис. [-@fig:007]).

![Создание lab6-2](image/creating_lab6-2.jpg){#fig:006 width=100%}

![Заполнение lab6-2](image/inserted_lab6-2.jpg){#fig:007 width=100%}

7. Создал исполняемый файл и запустил его (рис. [-@fig:008]).

![Запуск lab6-2](image/run_lab6-2.jpg){#fig:008 width=100%}

8. Изменил файл lab6-2.asm (рис. [-@fig:009]).

![Изменение в lab6-2](image/changed_char_to_int_lab6-2.jpg){#fig:009 width=100%}

9. Создал исполняемый файл и запустил его (рис. [-@fig:010]).

![Запуск исправленной lab6-2](image/run_lab6-2_2.jpg){#fig:010 width=100%}

10. Заменил функцию iprintLF на iprint (рис. [-@fig:011]).

![Изменение функции iprintLF в lab6-2](image/changed_iprintlf_to_iprint.jpg){#fig:011 width=100%}

11. Создал исполняемый файл и запустил его (рис. [-@fig:012]). iprintLF после вывода так-же переносит строку, в отличие от iprint.

![Запуск измененной lab6-2](image/run_lab6-2_3.jpg){#fig:012 width=100%}

12. Cоздал файл lab6-3.asm в каталоге ~/work/arch-pc/lab06 (рис. [-@fig:013])

![Создание lab6-3](image/creating_lab6-3.jpg){#fig:013 width=100%}

13. Заполнил lab6-3.asm (рис. [-@fig:014]).

![Заполнил lab6-3](image/inserted_lab6-3.jpg){#fig:014 width=100%}

14. Создал исполняемый файл и запустил его (рис. [-@fig:015]).

![Запуск lab6-3](image/run_lab6-3.jpg){#fig:015 width=100%}

15. Изменил текст программы для вычисления выражения f(x) = (4 * 6 + 2)/5 (рис. [-@fig:016]).

![Изменение lab6-3](image/changed_numbers_lab6-3.jpg){#fig:016 width=100%}

16. Cоздал исполняемый файл и запустил его (рис. [-@fig:017]).

![Запуск изменненой lab6-3](image/run_lab6-3_2.jpg){#fig:017}

17. Создал файл variant.asm в каталоге ~/work/arch-pc/lab06 (рис. [-@fig:018]).

![Создал variant](image/creating_variant.jpg){#fig:018}

18. Заполнил variant.asm (рис. [-@fig:019]).

![Заполнил variant](image/inserted_variant.jpg){#fig:019}

19. Cоздал исполняемый файл и запустил его (рис. [-@fig:020]).

![Запуск variant](image/run_variant.jpg){#fig:020 width=100%}

Ответы на вопросы:
	1. Какие строки листинга 6.4 отвечают за вывод на экран сообщения ‘Ваш вариант:’?
		mov eax,rem
		call sprint
	2. Для чего используется следующие инструкции?
		mov ecx, x
		mov edx, 80
		call sread
	Для полученния данных с клавиатуры.
	
	3. Для чего используется инструкция “call atoi”?
	Для преобразования ASCII кода в число
	
	4. Какие строки листинга 6.4 отвечают за вычисления варианта?
		xor edx,edx
		mov ebx,20
		div ebx
		inc edx
		
	5. В какой регистр записывается остаток от деления при выполнении инструкции “div ebx”?
	В edx
	
	6. Для чего используется инструкция “inc edx”?
	Увелечение edx на 1
	
	7. Какие строки листинга 6.4 отвечают за вывод на экран результата вычислений?
		mov eax,edx
		call iprintLF

# Задание для самостоятельной работы

1. Создал файл hw1.asm и заполнил его для вычесления (9x − 8)/8 (вариант №5) (рис. [-@fig:021]).

![Заполнил hw1](image/inserted_hw1.jpg){#fig:021 width=100%}

2. Cоздал исполняемый файл и проверил его работу на 8 и 64 (рис. [-@fig:022]).

![Проверка hw1](image/run_hw_var_5.jpg){#fig:022 width=100%}

# Выводы

Я освоил арифметические инструкции языка ассемблера в NASM.

