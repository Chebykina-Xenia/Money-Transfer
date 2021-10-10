# Отчёт о тестировании Money Transfer

## Краткое описание

06.10.2021 - 06.10.2021 было проведено модульное тестирование приложения Money Transfer.

На тестирование затрачено: 15 минут

В результате тестирования выявлены следующие дефекты:
* [При сложении current_balance и transfer_amount выводится неверный результат (account_balance)](https://github.com/Chebykina-Xenia/Money-Transfer/issues/1#issue-1018174258)
## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* Домашнее задание 1 в [в домашнем задании](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/MERGED.md)

В качестве тестовых данных использовались данные [из задания 1](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/MERGED.md):
* current_balance = 2_000_000_000;
* transfer_amount = 500_000_000;

Тестирование производилось в следующем окружении:
* ОС Windows 10.Процессор x64. Intel(R) Core(TM) i5-7200U CPU @ 2.50GHz 2.70 GHz. Оперативная память 4,00 ГБ.
* Версия Java 11.0.12
  
  
  