# 24/7 AternosBot 4.1


Данный бот сделан для хостинга aternos. Он не позволяет выключится серверу.

## OS

 * Windows 10/11
 * Linux
 * Mac

## NodeJS Версия

Версия: 14^

## Функции

 * Поддержка Minecraft 1.8, 1.9, 1.10, 1.11, 1.12, 1.13, 1.14, 1.15, 1.16, 1.17 и 1.18.
 * Анти афк
 * Управление через чат
 * [Настраиваемый конфиг](config.json)
 * [Настраиваемые файлы перевода](lang)
 * [Мультиаккаунт](accounts.txt) 
 * Авто респавн
 * Авто реконект

## Использование

Для Linux:
Запустить install.sh , потом bot.sh

Для Windows
Запустить start.bat (установка пакетов и запуск bot.bat)

Если не работает через .sh .bat, написать в терминале:
```
npm install mineflayer fs util wait-until
node .
```


### Управление через чат

 * ;start - включить анти афк
 * ;stop - выключить анти афк
 * ;pos - посмотреть координаты
