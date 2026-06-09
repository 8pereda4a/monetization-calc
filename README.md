# 🚛 Монетизация канала — 8 Передача

Калькулятор монетизации для YouTube, TikTok и Instagram.  
Работает как обычный сайт и как **Telegram Mini App**.

## Возможности

- 🎚️ Калькулятор с ползунками (YouTube / TikTok / Instagram / Спонсор)
- 📋 Журнал учёта по месяцам с историей выплат
- 📤 Отправка результата в Telegram
- 📖 Пошаговая инструкция внутри приложения

## Быстрый старт

1. Этот репозиторий уже содержит `index.html`
1. Зайди в **Settings → Pages → Branch: main → Save**
1. Через 2 минуты сайт доступен по адресу:  
   `https://ВАШ_НИК.github.io/monetization-calc`

## Подключение к Telegram

1. Открой @BotFather в Telegram
1. `/newbot` → создай бота
1. `/newapp` → вставь URL сайта
1. `/setmenubutton` → вставь тот же URL

## Стек

- Чистый HTML + CSS + JavaScript (без фреймворков)
- Telegram WebApp SDK
- localStorage для хранения данных