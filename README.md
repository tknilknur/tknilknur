K_G = Client(
    "Pyrogram Bot",
    bot_token=AAHW96z6cR0UbiWSnbQjzC3v0NMASseJB90
    api_id=16280281
    api_hash=AAHW96z6cR0UbiWSnbQjzC3v0NMASseJB90
         0
}
@K_G.on_message(filters.command("start"))
async def _(client, message):
    await message.reply_text(text="Merhaba")
