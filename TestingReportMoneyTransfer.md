# Отчёт о тестировании "Money Transfer"

## Краткое описание

19.09.2021 г. - 19.09.2021 г. было проведено санитарное тестирование приложения "Money Transfer".

На тестирование затрачено: 0,5 часа 

В результате тестирования выявлены следующие дефекты:

* https://github.com/KseniaPavlenko/Money-Transfer/issues/1

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:

* Тест кейс 1 Money Transfer https://docs.google.com/spreadsheets/d/1dmgvLBFl8yGIdznMgVC7H1HY-gQoHU1YgCyskGdfgII/edit?usp=sharing

В качестве тестовых данных использовались данные Задача №1 - Money Transfer:

* currentBalance = 2_000_000_000
* transferAmount = 500_000_000
* ожидаемый результат totalBalance = currentBalance + transferAmount = 2_500_000_000

Тестирование производилось в следующем окружении:

* ОС Windows 10 (Версия 20H2 (сборка ОС 19042.1165); 64-разрядная ОС, процессор x64)
* Версия Java JDK11U-jdk_x64_windows_hotspot_11.0.11.9
* IntelliJ IDEA Community Edition 2021.2.1
