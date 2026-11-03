---
dg-publish: true
---
# GET `/api/v1/warehouses`

**Описание:** метод возвращает массив всех складов, доступных текущей [[Учетные записи интеграции|учетной записи]].

**Запрос**

    GET /trade/hs/stock/warehouses

**Ответ**

```json
[
  {
    "warehouse": "Склад1",
    "warehouseCode": "1"
  },
  {
    "warehouse": "Склад2",
    "warehouseCode": "2"
  }
]
```