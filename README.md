# Отчёт о тестировании приложения KeyValidator

## Краткое описание

11.07.2021 было проведено тестирование документации, smoke-тестирование приложения KeyValidator.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* [Действия при некорректной устаноке OpenJDK не описаны в интрукции](https://github.com/senselessmessinspace/task_1-2_KeyValidator/issues/1)
* [Запуск программы KeyValidator в инструкции описан не полностью](https://github.com/senselessmessinspace/task_1-2_KeyValidator/issues/2)
* [Валидные ключи после запуска программы KeyValidator не валидируются](https://github.com/senselessmessinspace/task_1-2_KeyValidator/issues/3)
* [Невалидные ключи после запуска программы KeyValidator валидируются](https://github.com/senselessmessinspace/task_1-2_KeyValidator/issues/4)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [Инструкция по установке OpenJDK11](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md)
* [Руководство использования KeyValidator](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)

В качестве тестовых данных использовались данные, указанные в [документации](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md):
* Валидные ключи
* Невалидные ключи

Тестирование производилось в следующем окружении:
* Windows 8.1 x64
*   Openjdk version "11.0.11" 2021-04-20

    OpenJDK Runtime Environment AdoptOpenJDK-11.0.11+9 (build 11.0.11+9);

    OpenJDK 64-Bit Server VM AdoptOpenJDK-11.0.11+9 (build 11.0.11+9, mixed mode)