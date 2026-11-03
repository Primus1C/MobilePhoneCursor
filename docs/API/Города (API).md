---
dg-publish: true
---
# GET `/api/v1/cities`

**Описание:** получение городов. 
> [!tip] 
> Метод, записывающий города в 1С отсутствует 

**Запрос**
    GET /trade/hs/stock/cities
    
**Параметры:** нет

**Ответ 200**
```json
{
    "page": 1,
    "pageSize": 500,
    "totalItems": 75,
    "totalPages": 1,
    "items": [
        {
            "city": "Tashkent",
            "cityCode": "62",
            "country": "Узбекистан",
            "countryCode": "016"
        },
        {
            "city": "Tallin",
            "cityCode": "59",
            "country": "Эстония",
            "countryCode": "015"
        }
	]
}   
```