

**Описание**

Основная задача данного ~~програмного обеспечения~~ собирать информацию из журналов IPMI контроллеров , и оповещать администратора о каждом новом сообщении по Telegram

Веб интерфейс не работает, он создаётся, и возможно его вообще не будет.

#
**Среда выполнения**

Системы которые управляются xcat, утилита reventlog должна работать.
Так же у вас должен быть бот telegram и информация о TOKEN, CHAT_ID

#
**Как пользоваться**

1) Скачать код проекта

2) добавить значения TOKEN, CHAT_ID отредактировав файл ipmi-collector.сonf который находится в каталоге etc проекта (TOKEN=  CHAT_ID= как раз и есть информация о боте Телеграм)

3) запустить скрипт в фоновом режиме командой bash ipmi-collector.sh &

