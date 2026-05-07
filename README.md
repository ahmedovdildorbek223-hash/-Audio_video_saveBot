# -Audio_video_saveBot
Ahmedov dildorbek 
import telebot
TOKEN = "TOKENINGNI_BU_YERGA_QOY"

bot = telebot.TeleBot(TOKEN)

@bot.message_handler(commands=['start'])
def start(message):
    bot.send_message(message.chat.id, "Salom 😄 Bot ishlayapti!")

bot.polling()
