# Bot TARS - Simples

Este é um bot do Telegram básico usando `python-telegram-bot`.

## Como rodar no Render

1. Faça o upload deste projeto para o seu GitHub.
2. Vá até [Render.com](https://render.com), crie um novo Web Service e conecte ao seu GitHub.
3. Configure:
   - **Build Command:** `pip install -r requirements.txt`
   - **Start Command:** `python main.py`
4. Vá em Environment > Add Environment Variable e adicione:
   - `BOT_TOKEN` = (coloque seu token do bot)

Depois de publicado, envie `/start` no Telegram e o bot vai responder.
