# Math

## Содержание

1. [О проекте](#о-проекте)
2. [Особенности проекта](#особенности-проекта)
3. [Makefile](#makefile)
4. [Участники проекта](#участники-проекта)

## О проекте

В данном учебном проекте "Школы 21" была реализована собственная библиотека s21_math.h, аналог базовой библиотеки math.h языка C. В ней содержатся определения и объявления основных математичеких операций.

### Список возможностей программы:

Библиотека s21_math.h состоит из следующих функций:
* abs;
* acos;
* asin;
* atan;
* ceil;
* cos;
* exp;
* fabs;
* floor;
* fmod;
* log;
* pow;
* sin;
* sqrt;
* tan.

## Особенности проекта

В рамках учебного проекта неоходимо было соответствовать следующим требованиям:
* Программа разработана в соответствии с принципами объектно-ориентированного программирования и использованием компилятора gcc;
* При написании кода необходимо придерживаться Google Style;
* Использования префикса "s21_" в названии каждой функции; 
* Функции библиотеки покрываются unit-тестами не менее 80%(используется библиотека Check);
* Запрещено копирование и использование оригинальной библиотеки math.h (кроме тестов);
* Нужно придерживаться логики поведения оригинальной библиотеки (работа с памятью, нештатные ситуации, проверки);
* Проверяемая точность - 16 значащих цифр;
* Проверяемая точность дробной части - максимум 6 знаков после запятой.


## Makefile

Makefile проекта содержит следующие цели:

&nbsp;&nbsp;&nbsp;&nbsp;``all`` - включает в себя цели clean, s21_math.a, test, gcov_report;

&nbsp;&nbsp;&nbsp;&nbsp;``test`` - Запускает unit-тесты на проверку функций библиотеки s21_math.h с помощью библиотеки Check;

&nbsp;&nbsp;&nbsp;&nbsp;``s21_math.a`` - создание статической библиотеки на основе объектного файла s21_math.o;

&nbsp;&nbsp;&nbsp;&nbsp;``gcov_report`` - генерация html-отчета с помощью lcov для измерения покрытия кода тестами;

&nbsp;&nbsp;&nbsp;&nbsp;``check`` - анализирует код на стилистические нормы;

&nbsp;&nbsp;&nbsp;&nbsp;``clean`` - удаляет файлы, созданные во время прохождения тестов, отчеты о покрытии, объектные файлы.

## Участники проекта

| Участник      |            |
| ------------- | ------------------ |
| [lenwooda](https://github.com/llllenivka), [kristofs](https://github.com/BalagurovaA), latricin, [lesleyle](https://github.com/IvanVito) | Функции abs, acos, asin, atan, ceil, exp, fabs, floor, fmod, log, pow, sin, sqrt, соответствующие unit-тесты |
| [lemongrb](https://github.com/Shyrasya) | Функции cos, tan, соответствующие unit-тесты |
