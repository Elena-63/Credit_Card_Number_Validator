# Отчёт о тестировании <Credit Card Number Validator>

## Краткое описание

<01.04.2021> - <02.04.2021> Было проведено функциональное тестирование (валидация номеров банковских карт) приложения Credit Card Number Validator.

На тестирование затрачено: <4 часа>

В результате тестирования выявлены следующие дефекты:

* [Result is FAIL валидной номер карты (VISA)](https://github.com/Elena-63/Credit_Card_Number_Validator/issues/1)
* [Result is FAIL валидной номер карты (Discover)](https://github.com/Elena-63/Credit_Card_Number_Validator/issues/3)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [Домашнее задание к занятию «1.1. Введение в Java: JDK, JRE, JVM, IntelliJ IDEA»](https://github.com/netology-code/javaqa-homeworks/tree/master/intro)
* [Установка IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)

*В качестве тестовых данных использовались валидные и невалидные номера карт, валидные сгенерированы на сайте https://www.freeformatter.com/credit-card-number-generator-validator.html

*Валидные номера карт: VISA:

*4916905842540093 - ожидаемый результат - Result is OK
*4556886165353626 - ожидаемый результат - Result is OK

*MasterCard:

*2221006029356025 - ожидаемый результат - Result is OK
*2720991467197583 - ожидаемый результат - Result is OK

*Maestro:

*6762796859390153 - ожидаемый результат - Result is OK
*6763347368114434 - ожидаемый результат - Result is OK

*Невалидные номера карт:

*4485343747959205932 - ожидаемый результат - Result is FAIL.
*6011573705352231056 - ожидаемый результат - Result is FAIL.

*Тестирование производилось в следующем окружении:      

*Windows 10 Home 64 bit
*версия Java 11.0.10