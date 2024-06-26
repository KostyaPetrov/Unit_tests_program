# Реализация Unit-тестов для различных программ с применением фреймворка JUnit 5

## Разложение в степенной ряд функции sin(x)

[Программа](.src/main/java/ru/konstantinpetrov/SinusFunction.java), реализующая разложение функции sin(x) в степенной ряд. 

Для данной программы написаны [Unit-тесты](.src/test/java/ru/konstantinpetrov/SinusFunctionTest.java), которые проверяют совпадение и не совпадение результатов вычисления данной функции с заранее проверенными значениями.

## Реализация Heap Sorted

Была написана [программа](.src/main/java/ru/konstantinpetrov/HeapSort.java), реализующая пирамидальную сортировку на языке Java. 

Данный алгоритм был [протестирован](.src/test/java/ru/konstantinpetrov/HeapSortTest.java) на корректное выполнение, правильное реагирование на ошибочные значения и верную сортировку заданного массива данных.

## Реализация доменной модели и на её основе простой консольной игры

Была разработана доменная модель, описывающая классы людей и животных. На её основе была разработана простая [консольная игра](.src/main/java/ru/konstantinpetrov/Task3) с противостоянием животных и людей, по итогам которой выявлялся победитель

Для данной игры было написано [Unit-тестирование](.src/test/java/ru/konstantinpetrov/Task3/BattleTest.java), которое включает проверку корректности изменения значений боевых параметров героев, корректное проведение сражения между ними и корректное реагирование на ошибки и исключения
