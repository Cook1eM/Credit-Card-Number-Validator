# Отчёт о тестировании IntelliJ IDEA

## Краткое описание
06.11.2020 - 06.11.2020 было проведено *установочное тестрование*  и *функциональное* тестирование приложения IntelliJ IDEA.

На тестирование затрачено: 3 часа

В результате тестирования выявлены следующие дефекты: 

* Программа не считывает карты : American Express (AMEX); Diners Club - International; 19-ти значные номера карт.


## Описание процесса тестирования

### Предисловие : 

* [Руководство по установке IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)
* [Домашнее задание к занятию 1.1](https://github.com/netology-code/javaqa-homeworks/tree/master/intro)


### Шаги : 
1. Проходим по всем этапам установки IntelliJ IDEA Community (ссылка на инструкцию в предисловии)
1. После установки. Замением код "Hello programming!" на тот что приведен в домашнем задании (ссылка на инструкцию в предисловии)
1. Проверяем валидность карт с помощью ресурса [freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html)


### Ожидаемый результат:

* Инструкция по установке IntelliJ IDEA работает под текущий ОС
* Приложение запускается и совместимо с Java 11
* Приложение работает согласно руководству использования
* Программа проверяет валидные данные коректно

### Фактический результат: 

* Инструкция по установке IntelliJ IDEA работает под текущий ОС
* Приложение запускается и совместимо с Java 11
* Приложение работает согласно руководству использования
* [Программа не считывает карты : American Express (AMEX); Diners Club - International; 19-ти значные номера карт.](https://github.com/Cook1eM/Credit-Card-Number-Validator/issues/1)

## Тестирование производилось в следующем окружении:
Windows 10 64-bit

openjdk version "11.0.9.1" 2020-11-04

OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.9.1+1)

OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.9.1+1, mixed mode)

IDEA Version 2020.2.3
