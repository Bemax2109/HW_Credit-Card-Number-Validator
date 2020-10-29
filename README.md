# Отчёт о тестировании "Credit Card Number Validator"
## Краткое описание
24.10.2020 - 29.10.2020 было проведено модульное тестирование приложения "Credit Card Number Validator".

На тестирование затрачено: 6 часов

### В результате тестирования выявлены следующие дефекты:

Валидными являются только номера карт с количеством чисел равное 16 (см. скриншот)

https://user-images.githubusercontent.com/71455523/97514959-8a535900-19c2-11eb-8800-9ff9dfd47e2f.png

https://user-images.githubusercontent.com/71455523/97514963-8cb5b300-19c2-11eb-8868-1f1f0a9619cc.png

https://user-images.githubusercontent.com/71455523/97514965-8cb5b300-19c2-11eb-98da-cfcc6ede072b.png

## Описание процесса тестирования
### В процессе тестирования использовались следующие артефакты:
- Руководство по установке IntelliJ IDEA
- Сервис freeformatter.com

### В качестве тестовых данных использовались cгенерированные валидные номера карт сервиса freeformatter.com:
При использовании заведомо валидных номеров программа выдаст сообщение "Result is ОК", в противном случае "Result is FAIL"

### Тестирование производилось в следующем окружении:

- Устройство: Windows 7 SP1 x64
- Браузер: Chrome (86.0.4240.111)
- Git Bash 2.28.0
- openjdk version "11.0.7" 2020-04-14
- OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.8+10)
- OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.8+10, mixed mode)
- Virtual Studio Code Version: 1.50.1
- IntelliJ IDEA 2020.2.3 (Community Edition)
- Build #IC-202.7660.26, built on October 6, 2020