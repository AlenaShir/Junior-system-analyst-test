Запрос:
GET/api/delivery?sort=name&address=<адрес клиента>&longitude=<долгота>&latitude=<широта>
Host: petrushka_green.com
Accept: application/json

Ответ:
{
"status": 200,
"error_msg": "",
"shops":
[
{
"id": 1,
"name": 'METRO',
"image": "https://petrushka_green.com/image/METRO.png",	
"status": "Ближайшая доставка сегодня 21:00-23:00",
"link": "https://metro.com"
},
{
"id": 2,
"name": "Ашан",
"image": "https://petrushka_green.com/image/Ashan.png",
"status": "Ближайшая доставка сегодня 18:00-20:00",
"link": "https://ashan.com"
},
{
"id": 3,
"name": "ВкусВилл",
"image": "https://petrushka_green.com/image/VV.png",
"status": "Быстрая доставка от 20 до 60 минут",
"link": "https://VV.com"
},
{
"id": 4,
"name": "ВИКТОРИЯ",
"image": "https://petrushka_green.com/image/Viktoria.png",
"status": "Ближайшая доставка сегодня 17:00-19:00",
"link": "https://Viktoria.com"
}
]
}
