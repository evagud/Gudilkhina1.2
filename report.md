# Отчёт о тестировании функциональности валидации номера банковской карты.

## Краткое описание

30.04.2020 - 30.04.2020 было проведено методом серого ящика, модульное и позитивное тестирование функциональности валидации номера банковской карты.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* [Fail при вводе 19 разрядного валидного номера карт](https://github.com/evagud/Gudilkhina1.2/issues/1)
* [Fail при вводе 13 и 15 разрядного валидного номера карт](https://github.com/evagud/Gudilkhina1.2/issues/2)
* [Fail при вводе 17 и 18 разрядного валидного номера карт](https://github.com/evagud/Gudilkhina1.2/issues/3)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* [Руководство по установке IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)
* [Инструкция по установке OpenJDK11](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md)


В качестве тестовых данных использовались данные из [**сервиса для генерации валидных номеров карт**](https://www.freeformatter.com/credit-card-number-generator-validator.html) и [**еще одного сервиса для генерации номеров карт**](https://cartoved.ru/common/generator-kreditnyh-kart.html)


Тестирование производилось в следующем окружении:
*  ОС Windows 10 х64,  версии 1903
 и сборки 18362.720, 
* Ноутбук ASUS LAPTOP-JHKQCJHF
* Терминал Git version 2.26.0.windows.1
* Java version Openjdk "11.0.7" 2020-04-14
