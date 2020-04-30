# Отчёт о тестировании функциональности валидации номера банковской карты.

## Краткое описание

30.04.2020 - 30.04.2020 было проведено методом серого ящика, модульное и позитивное тестирование функциональности валидации номера банковской карты.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* [Fail при вводе 19 разрядного валидного номера карт](https://github.com/evagud/Gudilkhina1.2/issues/1)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* [Руководство по установке IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)
* [Инструкция по установке OpenJDK11](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md)


В качестве тестовых данных использовались данные из [**сервиса для генерации валидных номеров карт**](https://www.freeformatter.com/credit-card-number-generator-validator.html)

* 6011680936331099328 Result is OK
* 3539893199429907912 Result is OK
* 6396671193837942125 Result is OK
* 4556454348054114 Result is OK
* 4024007166965623 Result is OK
* 5283602588735662 Result is OK
* 5130869713260768 Result is OK
* 2720998159367887 Result is OK

Тестирование производилось в следующем окружении:
*  ОС Windows 10 х64,  версии 1903
 и сборки 18362.720, 
* Ноутбук ASUS LAPTOP-JHKQCJHF
* Терминал Git version 2.26.0.windows.1
* Java version Openjdk "11.0.7" 2020-04-14
