# Введение
Всем привет. Здесь я делюсь своими наработками по тематике умного дома.
Выбранная система - Home Assistant. Советы приветствуются.
# Описание
В качестве рабочей машины использую raspberry pi 3b+, вариант установки [HAOS](https://www.home-assistant.io/installation/raspberrypi)
## Что реализовано
### Освещение
1. Все выключатели заменены на [Aqara](https://aqara.ru/shop/), интеграция [Xiaomi GW3 от AlexIT](https://github.com/AlexxIT/XiaomiGateway3). 
2. Подсветка по периметру всех комнат [WLED](https://github.com/Aircoookie/WLED). 
3. Светильники [Gyver](https://alexgyver.ru/gyverlamp/)
### Отопление
1. Газовый котел и термостат HeatCold th120w. Интеграция [Xiaomi Miot Auto](https://github.com/al-one/hass-xiaomi-miot).
### Автомобиль
1. Интеграция [Starline](https://www.home-assistant.io/integrations/starline/). Реализован полный контроль за состоянием авто: пробег, охрана, открытие/закрытие, контроль сервисного интервала и ошибки, геолокация.
### Голосовое управление.
1. Используется несколько [станций с Алисой](https://yandex.ru/alice/station/index-mobile) от Яндекс. Интеграция [Yandex Station от AlexIT](https://github.com/AlexxIT/YandexStation).
2. Все устройства проброшены в [Умный Дом Яндекс](https://yandex.ru/alice/smart-home-mobile) интеграцией [YahaCloud](https://github.com/dext0r/yandex_smart_home).
3. Дополнительно большинство устройств проброшено в [HomeKit](https://www.home-assistant.io/integrations/homekit/) для быстрого управления с iPhone.
### Telegram
1. Полное управление всеми устройствами и контроль состояний через [месенджер](https://www.home-assistant.io/integrations/telegram/).
### ТВ
1. Samsung UEJ5530, интеграция [Smart TV](https://www.home-assistant.io/integrations/samsungtv).
2. Supra без Lan/WiFi с помощью [Яндекс Пульта](https://yandex.ru/support/smart-home/control-center/about.html) и пробросом в Home Assistant интеграцией [Yandex Station от AlexIT](https://github.com/AlexxIT/YandexStation).
### Бытовые приборы
1. Посудомоечная машина Bosch. Интеграция [Home Connect Alt](https://github.com/ekutner/home-connect-hass).
2. Увлажнитель, интеграция [Xiaomi Miot Auto](https://github.com/al-one/hass-xiaomi-miot).
3. Вентилятор
4. Робот-пылесос, интеграция [Xiaomi Miot Auto](https://github.com/al-one/hass-xiaomi-miot).
### DIY устройства
1. Координаторный домофон на базе ESP, [Чат автора](https://t.me/domofon_esp).
2. Рулонные шторы, проект [LazzyRolls](https://github.com/ACE1046/LazyRolls).
### Lovelace
1. Настройка с нуля используя карты [Mushroom](https://github.com/piitaya/lovelace-mushroom).
### Видео-наблюдение
1. Камера [Tapo tc70](https://www.tp-link.com/ru/home-networking/cloud-camera/tc70/), интеграция [Tapo cameras](https://github.com/JurajNyiri/HomeAssistant-Tapo-Control)
## В планах на будущее
1. Энерномониторинг.
2. Резервирование.
3. [Espresense](https://espresense.com/).
4. Распознование лиц (нужно новое железо).
# Интересные автоматизации
В процессе наполнения
# Как связаться
[Telegram](https://t.me/alex_zob)
## Если мой конфиг вдохновил на новые идеи

<a href="https://www.buymeacoffee.com/8tyfmdy2bnG" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-blue.png" alt="Buy Me A Coffee"  width="150px" ></a>