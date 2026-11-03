# MobilePhonesAPI

Репозиторий конфигурации 1С **ИТДБ_Торговля_8_3** (выгрузка в XML: `Configuration.xml`, `ConfigDumpInfo.xml`) и интеграции **StockAPI**.

- GitHub: [primus1c/MobilePhonesAPI](https://github.com/primus1c/MobilePhonesAPI)

## Документация

Материалы в каталоге **[`docs/`](docs/)**. Обзор API: [`docs/Общие сведения.md`](docs/Общие%20сведения.md).

| Файл | Назначение |
|------|------------|
| [`docs/Общие сведения.md`](docs/Общие%20сведения.md) | Авторизация, пагинация, коды ответов, сводная таблица эндпоинтов |
| [`docs/Заказы📌.md`](docs/Заказы📌.md) | Заказы `/orders`, отгрузка, статусы, возвраты, печатные формы |
| [`docs/Документы отгрузки.md`](docs/Документы%20отгрузки.md) | `GET /delivery-notes`, `POST`/`PATCH /delivery` |
| [`docs/Документы возврата.md`](docs/Документы%20возврата.md) | Возврат от покупателя `/return` |
| [`docs/Серии для сборки заказа.md`](docs/Серии%20для%20сборки%20заказа.md) | `GET /series` |
| [`docs/Замена проданного товара (API).md`](docs/Замена%20проданного%20товара%20(API).md) | `GET`/`POST /replace` |
| [`docs/Инвойс (API).md`](docs/Инвойс%20(API).md) | Инвойс закупки `/invoices` |
| [`docs/Приходная накладная (API).md`](docs/Приходная%20накладная%20(API).md) | Приходные `/incomingwaybills` |
| [`docs/Остатки с ценами.md`](docs/Остатки%20с%20ценами.md) | `GET /balances` |
| [`docs/Остатки без цен.md`](docs/Остатки%20без%20цен.md) | `GET /leftover` |
| [`docs/Остатки серий без цен.md`](docs/Остатки%20серий%20без%20цен.md) | `GET /leftoverSeries` |
| [`docs/Ассортимент.md`](docs/Ассортимент.md) | `GET /goods` |
| [`docs/Цены📌.md`](docs/Цены📌.md) | `POST /prices` |
| [`docs/Клиенты.md`](docs/Клиенты.md) | Контрагенты `/counterparties` |
| [`docs/Склады.md`](docs/Склады.md) | `GET /warehouses` |
| [`docs/Валюты.md`](docs/Валюты.md) | `GET /currencies` |
| [`docs/Бренды.md`](docs/Бренды.md) | `GET /brands` |
| [`docs/Города.md`](docs/Города.md) | `GET /cities` |
| [`docs/Операторы склада.md`](docs/Операторы%20склада.md) | `GET /employees` |
| [`docs/Статусы1СИнвойсовПродажи.md`](docs/Статусы1СИнвойсовПродажи.md) | РС `СостоянияИнвойсовПродажи` |
| [`docs/webhook_test_server.txt`](docs/webhook_test_server.txt) | Заметки по тестовому серверу WebHook |

- Правила разработки для Cursor: [.cursor/rules/](.cursor/rules/)

Локальная рабочая копия: `C:\Users\Артур\Documents\ConfigCursorNew`.
