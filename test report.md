# Отчёт о тестировании KeyValidator

## Краткое описание

03.11.2020 - было проведено:
* UI тесты документации по установке OpenJDK 11;
* UI тесты руководства использования приложения KeyValidator;
* системное функциональное тестирование приложения KeyValidator.


### На тестирование затрачено: 2 часа

### В результате тестирования выявлены следующие дефекты:
1. [KeyValidator неверно обрабатывает тестовый валидный ключ 80b427f8](https://github.com/blackartqa/JavaHW1-1/issues/1)
2. [KeyValidator неверно обрабатывает тестовый валидный ключ 387eedc6](https://github.com/blackartqa/JavaHW1-1/issues/3)
3. [KeyValidator неверно обрабатывает тестовый невалидный ключ ](https://github.com/blackartqa/JavaHW1-1/issues/2)

## Описание процесса тестирования

### В процессе тестирования использовались следующие артефакты:
* [Чеклист](https://github.com/blackartqa/JavaHW1-1/blob/master/checklist.md)
* [Руководство пользователя](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md#%D0%BA%D0%BB%D1%8E%D1%87%D0%B8-%D0%B4%D0%BB%D1%8F-%D0%BF%D1%80%D0%BE%D0%B2%D0%B5%D1%80%D0%BA%D0%B8)

### В качестве тестовых данных использовались данные из [руководсва использования](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md#%D0%BA%D0%BB%D1%8E%D1%87%D0%B8-%D0%B4%D0%BB%D1%8F-%D0%BF%D1%80%D0%BE%D0%B2%D0%B5%D1%80%D0%BA%D0%B8) :

#### Валидные ключи с ожидаемым результатом ОК:
* 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998
* 80b427f8-92cd-3aae-ba04-3927fbe17c6
* b295bc63-9f03-3b4b-af80-969b39f8c262
* 387eedc6-12e9-3b32-9881-63b6b5e85317
* c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180
#### Невалидные ключи с ожидаемым результатом FAIL:
* 18252235-78e0-44a5-8720-556f0c7da17a
* e66075b6-ddad-445e-baf6-161b3289522b
* b6d53250-f07e-4352-a293-6102ddf7f1ca
* c2bc778a-1cb9-46c6-b435-0489649d2a42
* 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1

### Тестирование производилось в следующем окружении:
* Windows 10 Home x64
* Java openjdk version 11.0.9 
