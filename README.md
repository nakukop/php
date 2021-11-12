## Тестовое задание для кандидата на позицию PHP-разработчика
**Дано:**

Есть 3 разных микро-сервиса, каждый из них имеет свой интерфейс настроек. Где могут быть абсолютно разные поля, разные валидации и т.д. В том числе могут быть разные протоколы общения с этими микросервисами.

**Если нужно больше специфики:**

- 1-й микросервис имеет REST API, и настройками для него являются поля ```[field1: string, field2: bool, field3: array<string>]```
- 2-й микросервис работает только через gRPC, и настройками для него являются поля ```[field1: string, field2: bool, field3: int]```
- 3-й микросервис умеет только http, и настройками для него являются поля ```[field1: bool, field2: int, field3: array<string, int>]```

**Нужно:**

- Написать сервис который будет получать доступные настройки из этих микросервисов и выводить на страницу на чтение и запись. Достаточно реализовать логику работы с самими сервисами.
- Задание необходимо выполнить с использованием фреймворка Symfony. Можно использовать и другие современные фреймворки(Laravel, Slim и т.д)
- Код не обязательно должен быть запускаемым и 100% рабочим.
- Тесты не обязательны, но приветствуются.
- Будет оцениваться в первую очередь понимание ООП, также умение работы с фреймворком
