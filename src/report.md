# Отчёт о тестировании <Money-Transfer>

## Краткое описание

30.09.2021 - 30.09.2021 было проведено тестирование основного функционала приложения Money-Transfer.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* [неверный расчет итогового баланса счета после перевода 500 млн](https://github.com/KseniyaChepelevich/Money-Transfer/issues/1#issue-1013790918)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* Данные для тестирования: текущий баланс счёта клиента - 2_000_000_000 (два миллиарда рублей)*
  сумма перевода - 500_000_000 (пятьсот миллионов рублей)
* [Программа Money-Transfer](https://github.com/KseniyaChepelevich/Money-Transfer/blob/master/src/Main.java)

В качестве тестовых данных использовались данные [Домашнее задание к Занятию 1](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/MERGED.md):
* balance= 2_000_000_000
* transfer= 500_000_000
* total= balance + transfer = 2_500_000_000

Тестирование производилось в следующем окружении:
* Windows 10 Pro x64
* Openjdk version "11.0.12" 2021-07-20
* IntelliJ IDEA Communiti Edition 2021.2.2