# Отчёт о тестировании СardValidation

## Краткое описание

25.11.21 17:00 - 25.11.21 17:15 было проведено функциональное тестирование приложения **СardValidation**.

На тестирование затрачено: 15 минут

В результате тестирования выявлены следующие дефекты:
* [Программа валидирует только карты с 16 цифрами](https://github.com/Stanislav-Litvinov/Card-Validation/issues/1) 

## Описание процесса тестирования


В качестве тестовых данных использовались данные    [генератора](https://www.getcreditcardnumbers.com/) :
* карта с 13 символами 4532696923224
* карта с 15 символами 210098719212136
* карта с 16 символами 5438344892169601
* карта с 18 символами 417500755029627746
* карта с 19 символами 6011870051440126630 


Тестирование производилось в следующем окружении:
* Windows 10 Домашняя, 20H2, 64-разрядная операционная система, процессор x64
* Runtime version: 11.0.12+7-b1504.40 amd64
