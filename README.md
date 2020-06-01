# Телеграм бот на русском языке
## Ссылка на бота: https://t.me/FunnyZzZBot 
### Используемые библиотеки:
* sklearn
* nltk
* telegram
#### Описание бота
При работе данного бота не используется сторонних серверов, обучение производится посредством машинного обучения. 
Бот написан для общения в диалоге с одним человеком с распознаванием текстовых сообщений. Дата сет содержит более 150 интентов. 
Для генеративного ответа используются диалого из различной художественной литературы. 
#### Принцип работы
После ввода текстового сообщения от пользователя бот, благодаря использованию средств машинного обучения, рассчитывает вероятность принадлжености
ввденого запроса к одному из интентов и при достижении определенного порога выдаёт ответ, соответствующий интенту с максимальной вероятностью, 
если вероятность ниже заданного порога, то используется генеративная модель, которая подбирает ответ из списка диалогов, используемых в различных
литературных произведениях, если и в данном случае ответ не соответствует заданным требованиям, используются фразы-заглушки.
#### Примечания
* Для корректной работы в функции main() необходимо использование выданного  Bot-Father токена, заместо "TOKEN"
* Для поделючения к Telegram при необоходимости стоит заменить proxy-url






