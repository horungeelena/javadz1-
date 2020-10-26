# Отчёт о тестировании с разными тестовыми данными Credit Card Number Validator

## Краткое описание

26.10.2020 было проведено тестирование документации, тестирование установки, функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 3 часа.

В результате тестирования выявлены следующие дефекты: 

В процессе тестирования валидных номеров карт данные были failed вместо ok. #1
https://github.com/horungeelena/javadz1-/issues/1#issue-729889067

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* руководство по установке IntelliJ IDEA https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md
* код программы https://github.com/netology-code/javaqa-homeworks/tree/master/intro


В качестве тестовых данных использовались валидные данные https://www.freeformatter.com/credit-card-number-generator-validator.html:
*  VISA 4532629254406403 ok
*  VISA 4024007116200980 ok
*  American Express (AMEX) 349469258853982 failed
*  American Express (AMEX) 347112388846318 failed

Тестирование производилось в следующем окружении:
* Windows 10 64-bit
* Java SE 11.0.8
* IntelliJ IDEA 2020.2.3 (Community Edition)