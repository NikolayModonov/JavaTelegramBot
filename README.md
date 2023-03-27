# Телеграм-бот

Это пример проекта телеграм-бота на Java, который использует библиотеку [TelegramBots](https://github.com/rubenlagus/TelegramBots). Бот отвечает на сообщения, отправленные пользователем, и может выполнять определенные команды.

## Настройка проекта

1. Установите [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/javase-downloads.html) и [Maven](https://maven.apache.org/).

2. Скачайте проект с помощью Git:
```console
git clone https://github.com/NikolayModonov/JavaTelegramBot
```
Или загрузите архив проекта и распакуйте его.

3. Создайте бота в Telegram и получите токен. Для этого необходимо написать боту @BotFather в Telegram и выполнить несколько команд.

4. Замените значение переменной `botToken` в классе `Bot.java` на ваш токен:

```java
String botToken = "your_bot_token";
```
## Запуск проекта
1. Соберите проект с помощью Maven.
2. Запустите бота.

## Использование бота
Чтобы взаимодействовать с ботом, найдите его в Telegram и напишите ему сообщение. Бот ответит на ваше сообщение и может выполнить некоторые команды. Например, вы можете отправить ему сообщение "/help", чтобы получить список доступных команд.

## Лицензия
Этот проект в текущей версии может использоваться при упоминании автора и ссылки на оригинальный источник кода. 