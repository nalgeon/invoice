# Генератор счетов

Как использовать:

1. Форкнуть или скачать репозиторий
2. Прописать реквизиты своей компании в `company.json`
3. Скопировать логотип, печать и факсимиле в каталог `img`
4. Выставлять счета!

Чтобы выставить счет, достаточно передать реквизиты счета в `invoice.html` через параметры URL. Например, хотим выставить счет с такими реквизитами:

-   Номер счета: 1234
-   Покупатель: ООО «Магазинчик»
-   Товар или услуга: Подписка на год
-   Стоимость: 5000 ₽

Получится такая строка запроса:

```
invoice.html?number=1234&company=ООО+«Магазинчик»&item=Подписка+на+год&price=5000
```

[Пример счета](https://nalgeon.github.io/invoice/invoice.html?number=1234&company=ООО+«Магазинчик»&item=Подписка+на+год&price=5000)

[Конструктор счета](https://nalgeon.github.io/invoice/)
