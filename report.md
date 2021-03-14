# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

09.03.2021 - 09.03.2021 было проведено инсталляционное тестирование.
09.03.2021 - 09.03.2021 было проведено функциональное тестирование

На тестирование затрачено: 2  часа

В результате тестирования выявлены следующие дефекты:
* [Задание2. Результат проверки валидных карт American Express (AMEX)](https://github.com/AleksandraRatush/java-homeworks2/issues/1)
* [Задание2. Результат проверки валидных карт Diners Club - Carte Blanche FAIL](https://github.com/AleksandraRatush/java-homeworks2/issues/2)


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* [Руководство по установке IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md)
* Исходный код класса [Main](https://github.com/AleksandraRatush/java-homeworks2/blob/2f39c320feb7200e1aad63c5a3121ca8ea564b9c/src/Main.java)



В качестве тестовых данных использовались карты из [Credit Card Number Generator & Validator](https://www.freeformatter.com/credit-card-number-generator-validator.html)

* "4929184727023857", ожидаемый результат Result OK
* "6011218280513492", ожидаемый результат Result OK
* "30580323206859", ожидаемый результат Result OK
* "4175001316206175", ожидаемый результат Result OK
* "5264932041354527", ожидаемый результат Result OK
* "3540657475576524", ожидаемый результат Result OK
* "36922446490198", ожидаемый результат Result OK
* "6386701062967587", ожидаемый результат Result OK
* "346154684512724", ожидаемый результат Result OK
* "", ожидаемы результат Result OK
* "Пустая строка", ожидаемы результат Result FAIL
* " 30461127825709", ожидаемы результат Result FAIL
* "49291847270238", ожидаемы результат Result FAIL
* 492918472702385a, ожидаемы результат Result FAIL
* null, ожидаемы результат Result FAIL

Тестирование производилось в следующем окружении:

- MacBook Pro (Retina, 13-inch, Mid 2014)
- macOS Big Sur v 11.2.1
- OpenJDK 11.0.2
- IntelliJ IDEA Community Edition v 2020.3
