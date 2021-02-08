<h1>https://github.com/kolei/oap</h1>

Курс лекций для группы И-21

<details>

<summary>Варианты для других групп:</summary>

Лекции написаны в четырех вариантах:
* для группы И-21 на примере языка C# (вариант **master** - основной)
* для группы С-21 на примере языка Питон (вариант **python_c21** - упрощенный)
* для группы И-21 на примере языка Котлин (вариант **kotlin** - устаревший)
* для группы И-21 на примере языка Питон (вариант **python** - устаревший)

Для переключения между вариантами нужно кликнуть по кнопке *Branch* и выбрать нужный:

![](img/readme_c21.png)
  
</details>

# Основы алгоритмизации и программирования

## Тема 1. Основные принципы алгоритмизации и программирования <!-- 6(6) + 6(6) -->

1. [Основные понятия алгоритмизации. Понятие алгоритма. Свойства алгоритма. Формы записи алгоритмов. Общие принципы построения алгоритмов. Определение сложности работы алгоритмов.](articles/t1l1.md) <!-- 2(2) + 0 -->

2. [Основные алгоритмические конструкции: линейные, разветвляющиеся, циклические. Программы для графического отображения алгоритмов](articles/t1l2.md) <!-- 2(4) + 0 -->

3. [Логические основы алгоритмизации. Основы алгебры логики. Логические операции с высказываниями: конъюнкция, дизъюнкция, инверсия. Законы логических операций. Таблицы истинности.](articles/t1l3.md) <!-- 2(6) + 0 -->

>Лабораторные работы
>1. [Разработка алгоритмов для конкретных задач. Определение сложности работы алгоритмов.](articles/t1lab1.md)
>2. Использование программ для графического отображения алгоритмов.
>3. Таблицы истинности

## Тема 2. Языки и методы программирования <!-- 4(10) + 0(6) -->

1. [Языки программирования. Эволюция языков программирования. Классификация языков программирования. Понятие системы программирования. Исходный, объектный и загрузочный модули. Интегрированная среда программирования.](articles/t2l1.md) <!-- 2(8) + 6 -->

2. [Методы программирования: структурный, модульный, объектно-ориентированный. Достоинства и недостатки методов программирования. Общие принципы разработки программного обеспечения. Жизненный цикл программного обеспечения.](articles/t2l2.md) <!-- 2(10) + 6 -->

## Тема 3. Системы контроля версий <!-- 2(12) + 2(8) -->

1. [Системы контроля версий.](articles/skv.md) <!-- 2(12) + 6 -->

**Лабораторные работы**

1. [Создание аккаунта и репозитория в СКВ gihtub](articles/skv_lab.md) <!-- 12 + 2(8) -->

## Тема 4. Программирование на языке C#
[10 + 10 => 24 + 20]: _

1. [Основные элементы языка. Структурная схема программы на алгоритмическом языке. Лексика языка. Переменные и константы. Типы данных. Выражения и операции.](/articles/t3l1.md)<!-- 2(14) + 8 -->

2. [Операторы и операции языка. Синтаксис операторов. Составной оператор. Вложенные условные операторы. Циклические конструкции.](/articles/t3l1_2.md)<!-- 2(16) + 8 -->

3. [Массивы как структурированный тип данных. Объявление массива. Ввод и вывод одномерных и двумерных массивов. Обработка массивов. Стандартные функции для массива целых и вещественных чисел.](/articles/t3l1_3.md)<!-- 2(18) + 8 -->

4. [Строки. Объявление строковых типов данных. Поиск, удаление, замена и добавление символов в строке. Операции со строками. Стандартные функции и процедуры работы со строками.](articles/4_prog_string.md)<!-- 2(20) + 8 -->

5. Объявление множества. Операции над множествами. Коллекции и последовательности

<!-- TODO дописать про Коллекции и последовательности -->


<!-- TODO перетасовать по лекциям -->

+ [Pair, Triple, Map. Методы основных типов данных.](/articles/t3l3.md)
+ [Циклы. Массивы. Коллекции. Множества (Set).](/articles/t3l4.md)
+ [Кодировки символов: ASCII, UNICODE. Консольные программы.](/articles/t3l5.md)


<!--TODO: где-то упомянуть про object -->

>Лабораторные работы
>1. [Работа в среде программирования. Реализация построенных алгоритмов.Составление программ линейной структуры.](/articles/lab1.md)
>2. [Составление программ разветвляющейся структуры.](/articles/lab2.md)
>3. [Составление программ циклической структуры. Обработка одномерных и двумерных массивов.](/articles/lab3.md)
>4. Работа со строковыми переменными. Работа с данными типа множество.
>5. Работа с коллекциями и последовательностями.

[10 + 10 => 24 + 20]: _

## Тема 5. Функции. Лямбды. Исключения. Работа с файлами
[14 + 10 => 38 + 30]: _

1. Понятие подпрограммы. Процедуры и функции, их сущность, назначение и различие. Организация процедур, стандартные процедуры. Процедуры, определенные пользователем: синтаксис, передача аргументов.

2. [Формальные и фактические параметры. Процедуры с параметрами, описание процедур. Консольный ввод/вывод.](/articles/t3l2.md)

3. Функции высшего порядка и лямбды.

4. [Исключения. Рекурсия. Программирование рекурсивных алгоритмов.](/articles/t4l5.md)

[//TODO дописать про рекурсии]: _

5. [Типы файлов. Организация доступа к файлам. Файлы последовательного доступа. Открытие и закрытие файла последовательного доступа.](/articles/t4l1.md)

6. [Файлы произвольного доступа. Порядок работы с файлами произвольного доступа. Открытие и закрытие файла произвольного доступа.](/articles/t4l2.md)

7. [Стандартная библиотека. Подключение не стандартных библиотек.](/articles/t4l3.md)

[Kotlin Standard Library]: https://kotlinlang.org/api/latest/jvm/stdlib/index.html

>Лабораторные работы
>1. [Организация и использование функций. Исключения. (4 часа)](/articles/lab4.md)
>2. Лямбды
>3. Работа с файлами последовательного и произвольного доступа. (4 часа)

[14 + 10 => 38 + 30]: _

## Тема 6. Регулярные выражения
[4 + 4 => 42 + 34]: _

[Регулярные выражения](/articles/t3l6.md) (4 часа)

>Лабораторные работы
>1. [Регулярные выражения.](/articles/lab5.md) (4 часа)

## Тема 7. Параллельные вычисления
[8 + 6 => 50 + 40]: _

1. [Потоки.](/articles/t4l4.md)

2. Корутины. 

3. [Асинхронные вычисления.](/articles/t4l4_2.md) (4 часа)

[_]: _ "//TODO: дописать про синхронный результат асинхронной функции"

>Лабораторные работы
>1. [Потоки.](/articles/lab6-threads.md)
>2. Корутины. 
>3. [Асинхронные вычисления.](/articles/lab6-async.md)

[8 + 6 => 50 + 40]: _

## Тема 8. Основные принципы объектно-ориентированного программирования
[10 + 12 => 60 + 52]: _

1. [История развития ООП. Базовые понятия: объект, его свойства и методы, класс, интерфейс. Основные принципы ООП: инкапсуляция, наследование, полиморфизм.](/articles/t6l1_2.md)

2. Перегрузка операторов

3. [Шаблоны проектирования. Порождающие шаблоны.](/articles/oop_templates_p1.md)

4. [... Структурные шаблоны.](/articles/oop_templates_p2.md)

5. [... Поведенческие шаблоны.](/articles/oop_templates_p3.md)

>Лабораторные работы
>1. [ООП. Основы.](/articles/lab8-oop.md)
>2. [ООП. Классы.](/articles/lab8-oop2.md)
>3. Перегрузка операторов
>4. [ООП. Наследование.](/articles/lab8-oop3.md)
>5. [ООП. Наследование 2.](/articles/lab8-oop4.md)
>6. [ООП. Шаблоны проектирования](/articles/lab-templates.md)

[10 + 12 => 60 + 52]: _

## Тема 9. Знакомство со средой разработчика JetBrains Intelij IDEA
[2 + 10 => 62 + 62]: _

1. [Интерфейс среды разработчика: характеристика, основные окна, инструменты, объекты.](/articles/ide_idea.md) (2 часов)

>Лабораторные работы
>1. Создание простой программы по индивидуальным заданиям (10 часов)

## Тема 10. Этапы разработки приложения
[4 + 8 => 66 + 70]: _

1. Проектирование объектно-ориентированного приложения
2. Программирование, тестирование, отладка приложения. Создание документации.

>Лабораторные работы
>1. Создание объектно-ориентированной програмы по индивидуальным заданиям (8 часов)

[ООП. Шаблоны проектирования]: https://studfile.net/preview/6845209/
[Шаблоны проектирования]: http://it-claim.ru/Education/Course/ISDevelopment/Lab3_tutorial.pdf

[создание проекта с gradle]: https://kotlinlang.org/docs/tutorials/coroutines/coroutines-basic-jvm.html


[_]: https://github.com/latyshevich/education/wiki/%D0%9B%D0%B0%D0%B1%D0%BE%D1%80%D0%B0%D1%82%D0%BE%D1%80%D0%BD%D0%B0%D1%8F-%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0-%E2%84%961-(%D0%9E%D0%9E%D0%9F) "Лабораторные по ООП"

[_]: https://studfile.net/preview/2497114/page:2/ "Лабы ООП"

<!--  

ПООП

Раздел 1. Введение в программирование

Тема 1.1. Языки программирования
1. Развитие языков программирования. 
2. Обзор языков программирования. Области применения языков программирования. Стандарты языков программирования. Среда проектирования. Компиляторы и интерпретаторы. 
3. Жизненный цикл программы. 
Программа. Программный продукт и его характеристики. 
4. Основные этапы решения задач на компьютере.

Тема 1.2. Типы данных
1. Типы данных. Простые типы данных. Производные типы данных. Структурированные типы данных.

Раздел 2.

Тема 2.1. Операторы языка программирования
1. Операции и выражения. Правила формирования и вычисления выражений. Структура программы. Ввод и вывод данных. Оператор присваивания.  Составной оператор.
2. Условный оператор. Оператор выбора.
3. Цикл с постусловием. Цикл с предусловием. Цикл с параметром. Вложенные циклы.
4. Массивы. Двумерные массивы. Строки. Стандартные процедуры и функции для работы со строками.
5. Структурированный тип данных – множество. Операции над множествами. 
6. Комбинированный тип данных – запись. Файлы последовательного доступа. Файлы прямого доступа

Раздел 3.

Тема 3.1. Процедуры и функции
1. Общие сведения о подпрограммах. Определение и вызов подпрограмм. Область видимости и время жизни переменной. Механизм передачи параметров. Организация функций.
2. Рекурсия. Программирование рекурсивных алгоритмов.

Тема 3.2. Структуризация в программировании
1. Основы структурного программирования. Методы структурного программирования.

Тема 3.3. Модульное программирование
1. Модульное программирование. Понятие модуля. Структура модуля. Компиляция и компоновка программы.
2. Стандартные модули.

Раздел 4 Основные конструкции языков программирования

Тема 4.1 Указатели.
1. Указатели. Описание указателей. Основные понятия и применение динамически распределяемой памяти.  Создание и удаление динамических переменных.
2. Структуры данных на основе указателей.
3. Задача о стеке.


Раздел 5

Тема 5.1 Основные принципы объектно-ориентированного 
программирования (ООП)
1. История развития ООП. Базовые понятия ООП: объект, его свойства и методы, класс, интерфейс.
2. Основные принципы ООП: инкапсуляция, наследование, полиморфизм.
3. Классы объектов. Компоненты и их свойства.
4. Событийно-управляемая модель программирования.  Компонентно-ориентированный подход.

Тема 5.2 Интегрированная среда разработчика.
1. Требования к аппаратным и программным средствам интегрированной среды разработчика.
2. Интерфейс среды разработчика: характеристика, основные окна, инструменты, объекты. Форма и размещение на ней управляющих элементов.
3. Панель компонентов и их свойства. Окно кода проекта.
4. Состав и характеристика проекта. Выполнение проекта. Настройка среды и параметров проекта.
5. Панель компонентов и их свойства. Окно кода проекта. Состав и характеристика проекта. Выполнение проекта. Настройка среды и параметров проекта.
6. Настройка среды и параметров проекта.

Тема 5.3. Визуальное событийно-управляемое программирование
1. Основные компоненты (элементы управления) интегрированной среды разработки, их состав и назначение.
2. Дополнительные элементы управления. Свойства компонентов. Виды свойств. Синтаксис определения свойств. Назначения свойств и их влияние на результат. Управление объектом через свойства.
3. События компонентов (элементов управления), их сущность и назначение. Создание процедур на основе событий.

Тема 5.4 Разработка оконного приложения
1. Разработка функционального интерфейса приложения. Создание интерфейса приложения.
2. Разработка функциональной схемы работы приложения.
3. Разработка игрового приложения.

Тема 5.5 Этапы разработки приложений
1.Разработка приложения.
2. Проектирование объектно-ориентированного приложения.
3. Создание интерфейса пользователя.
4. Тестирование, отладка приложения.

Тема 5.6 Иерархия классов.
1. Классы ООП: виды, назначение, свойства, методы, события.
2. Перегрузка методов.
3. Тестирование и отладка приложения.
4. Решение задач

Примерная тематика практических занятий и лабораторных работ:
Знакомство со средой программирования.
Составление программ линейной структуры.
Составление программ разветвляющейся структуры. 
Составление программ циклической структуры
Обработка одномерных массивов.
Обработка двумерных массивов.
Работа со строками.
Работа с данными типа множество.
Файлы последовательного доступа.
Типизированные файлы.
Нетипизированные файлы.
Организация процедур. 
Организация функций. 
Применение рекурсивных функций.
Программирование модуля.
Создание библиотеки подпрограмм.
Использование указателей для организации связанных списков.
Изучение интегрированной среды разработчика.
Создание проекта с использованием компонентов для работы с текстом.
Создание проекта с использованием компонентов ввода и отображения чисел, дат и времени.
События компонентов (элементов управления), их сущность и назначение. 
Создание процедур на основе событий.
Создание проекта с использованием кнопочных компонентов.
Создание проекта с использованием компонентов стандартных диалогов и системы меню.
Разработка функциональной схемы работы приложения.
Разработка оконного приложения с несколькими формами.
Разработка игрового приложения.
Создание процедур обработки событий. Компиляция и запуск приложения.
Разработка интерфейса приложения.
Тестирование, отладка приложения.  
Классы ООП: виды,  назначение, свойства, методы, события.
Объявления класса.
Создание наследованного класса.
Программирование приложений.
Перегрузка методов.

-->