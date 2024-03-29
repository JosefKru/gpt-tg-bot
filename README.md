# Telegram Bot with OpenAI GPT Chat 👾💬🤖

Этот проект представляет собой телеграм бота, разработанного на Node.js, который интегрирует API OpenAI и позволяет использовать функционал GPT-чата внутри телеграм-платформы. Бот обладает способностью обрабатывать текстовые сообщения, а также голосовые сообщения для взаимодействия с пользователем.

## Установка 🚀

1. Склонируйте локально репозиторий:

```bash
git clone https://github.com/JosefKru/gpt-tg-bot.git telegram-bot
```

2. Перейдите в директорию проекта:
```bash
cd telegram-bot
```

3. Установите зависимости, используя npm:
```bash
npm install
```

4. По образу example.json создайте файл default.json в директории config проекта и заполните следующий json объект:
```bash
"TELEGRAM_TOKEN": "",
"OPENAI_KEY": ""
```
В поле TELEGRAM_TOKEN вставьте токен вашего Telegram бота, а в поле OPENAI_KEY ваш API-ключ OpenAI.

5. Запустите приложение:
```bash
npm start
```

## Использование 🎮

1. Добавьте созданного ранее бота в свои контакты в Telegram.
2. Откройте диалог с ботом и отправьте ему текстовое сообщение или голосовое сообщение.
3. Бот обработает ваш запрос, используя OpenAI API, и отправит ответ в виде текстового сообщения.

## Связаться со мной 📧

- Мое портфолио: [https://alyakin.art](https://alyakin.art)
- Мой telegram: [@josefKru](https://t.me/josefKru)
- Мой профиль LinkedIn: [LinkedIn](https://www.linkedin.com/in/ivan-alyakin-976842243/)
- Электронная почта: josefkaru@gmail.com
