# Отчёт о тестировании приложения "KeyValidator"

## Проверка валидности ключей
* Установка OpenJDK11;
* [Ключи для проверки](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md#%D0%BA%D0%BB%D1%8E%D1%87%D0%B8-%D0%B4%D0%BB%D1%8F-%D0%BF%D1%80%D0%BE%D0%B2%D0%B5%D1%80%D0%BA%D0%B8).

## В результате тестирования выявлены следующие дефекты: 
* [Нераспознанный компонент валидный ключ #387eedc6-12e9-3b32-9881-63b6b5e85317](https://github.com/BulygaDenis/javaHW1.1/issues/1);
* [FAIL для валидного ключа #80b427f8-92cd-3aae-ba04-3927fbe17c6](https://github.com/BulygaDenis/javaHW1.1/issues/2).
* [OK для невалидного ключа #2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1](https://github.com/BulygaDenis/javaHW1.1/issues/3)

## Документация:
[Инструкция по установке OpenJDK 11](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md);
[Руководство использования](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md).

## Результаты

Валидные ключи:

```
8f05e6a7-70e9-33d7-bfe7-b19eae0d8998 OK
80b427f8-92cd-3aae-ba04-3927fbe17c6 FAIL
b295bc63-9f03-3b4b-af80-969b39f8c262 OK
387eedc6-12e9-3b32-9881-63b6b5e85317 FAIL
c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180 OK
```
Невалидные ключи:
```
18252235-78e0-44a5-8720-556f0c7da17a FAIL
e66075b6-ddad-445e-baf6-161b3289522b FAIL
b6d53250-f07e-4352-a293-6102ddf7f1ca FAIL
c2bc778a-1cb9-46c6-b435-0489649d2a42 FAIL
2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1 OK
```


1. 10\3
2. Issues:
[#1](https://github.com/BulygaDenis/javaHW1.1/issues/1)
[#2](https://github.com/BulygaDenis/javaHW1.1/issues/2)
[#3](https://github.com/BulygaDenis/javaHW1.1/issues/3)


## Окружение:

Win 10 x 64
openjdk version "11.0.8" 2020-07-14
OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.8+10)
OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.8+10, mixed mode)




