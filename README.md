# Введение
Всем привет! 
Здесь я делюсь своими наработками по тематике умного дома.
Выбранная система - Home Assistant. Советы приветствуются.
# Описание
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
### Полное управление всеми устройствами и контроль состояний через [месенджер Telegram](https://www.home-assistant.io/integrations/telegram/).
### Рулонные шторы.
  1. Проект [LazzyRolls](https://github.com/ACE1046/LazyRolls). 
### ТВ.
  1. Samsung UEJ5530, интеграция [Smart TV](https://www.home-assistant.io/integrations/samsungtv).
  2. Supra без Lan/WiFi с помощью [Яндекс Пульта](https://yandex.ru/support/smart-home/control-center/about.html) и пробросом в Home Assistant интеграцией [Yandex Station от AlexIT](https://github.com/AlexxIT/YandexStation).
### Бытовые приборы.
  1. Посудомоечная машина Bosch. Интеграция [Home Connect Alt](https://github.com/ekutner/home-connect-hass).
  2. Увлажнитель, интеграция [Xiaomi Miot Auto](https://github.com/al-one/hass-xiaomi-miot).
  3. Вентилятор
  4. Робот-пылесос, интеграция [Xiaomi Miot Auto](https://github.com/al-one/hass-xiaomi-miot).
### DIY устройства.
  1. Координаторный домофон на базе ESP, [Чат автора](https://t.me/domofon_esp).
## В планах на будущее
1. Энерномониторинг.
2. Резервирование.
3. [Espresense](https://espresense.com/).
# Интересные автоматизации
В процессе наполнения
# Как связаться
[Telegram](https://t.me/alex_zob)