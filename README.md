
----

<div align="center">
  <h1>t.me/JexSatan Tarafından yapılmış Türkçe - Oyun Botu:)</h1>
</div>
<p align="center">
        <a href="https://telegram.dog/JexOyun_Bot">~Bot~</a>
</p>

----

# Bot Hakkında
**Pyrogram Bot Api Kullanılarak yazılmış basit -oyun botu!**

# Heroku'da Clonlamak

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/JexSatan/JexGameBot)

## Alanları Doldurma
* ``BOT_TOKEN``: Botunuzun tokeni t.me/botfather alınız!
* ``OWNER_API_ID``: Sizin api id'niz http://my.telegram.org/ alınız!
* ``OWNER_API_HASH``: Sizin api hash'ınız http://my.telegram.org/ alınız!


# Örnek Start Komutu
```python
from pyrogram import Client, filters

K_G = Client(
    "Pyrogram Bot",
    bot_token=YOUR_BOT_TOKEN,
    api_id=YOUR_API_ID,
    api_hash=YOUR_API_HASH
    )

@K_G.on_message(filters.command("start"))
async def _(client, message):
    await message.reply_text(text="Merhaba")
```

# İletişim
Şikayet, bağış v.b. için benim ile telegram'dan iletişime geç [@JexSatan](https://t.me/JexSatan)


# Credit
Thanks for;

[MortSolaire](https://github.com/JexSatan)

[Pyrogram Library](https://github.com/pyrogram/pyrogram) Kütüphanesi için
