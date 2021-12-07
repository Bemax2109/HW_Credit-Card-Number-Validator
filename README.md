# Отчёт о тестировании "Credit Card Number Validator"
## Краткое описание
24.10.2020 - 29.10.2020 было проведено модульное тестирование приложения "Credit Card Number Validator".

На тестирование затрачено: 6 часов

### В результате тестирования выявлены следующие дефекты:

Валидными являются только номера карт с количеством чисел равное 16 (см. скриншот)

![1](https://user-images.githubusercontent.com/71455523/97514959-8a535900-19c2-11eb-8800-9ff9dfd47e2f.png)

![2](https://user-images.githubusercontent.com/71455523/97514963-8cb5b300-19c2-11eb-8868-1f1f0a9619cc.png)

![3](https://user-images.githubusercontent.com/71455523/97514965-8cb5b300-19c2-11eb-98da-cfcc6ede072b.png)

## Описание процесса тестирования
### В процессе тестирования использовались следующие артефакты:
- Руководство по установке IntelliJ IDEA
- Сервис freeformatter.com

### В качестве тестовых данных использовались cгенерированные валидные номера карт сервиса freeformatter.com:
При использовании заведомо валидных номеров программа выдаст сообщение "Result is ОК", в противном случае "Result is FAIL"

### Тестирование производилось в следующем окружении:

Устройство: Windows 10 Pro x64
openjdk version "11.0.9" 2020-10-20
OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.9+11)
OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.9+11, mixed mode)
IntelliJ IDEA 2021.3 (Community Edition)
Build #IC-213.5744.223, built on November 27, 2021
