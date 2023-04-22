# Leopard Chalenge - задача регрессии

### Введение
Проект из курса Глеба Михайлова "Data Science с Глебом Михайловым" https://stepik.org/course/113596, в котором предлагается решить задачу регрессии - определить цены на различные объекты недвижимости в Мельбурне. В репозитории лежит ноутбук и данные, с которыми производилась работа. В ноутбуке представлена сжатая (хоть там почти и 80 ячеек) информация по работе с проектом, в итоге были оставлено только то, что дало прирост к метрике на Kaggle. 

### Описание кейса
Это данные о ценах на недвижимость в Мельбурне. Каждая строчка – это объект недвижимости, по которому известны некоторые параметры и его цена. Задача заключается в том, чтобы по этим параметрам определить цену объекта.

Описание столбцов (параметров объекта):

| Наименование колонки | Описание колонки |
| -------------------- | ---------------- |
| Suburb | Район |
| Address | Адрес |
| Rooms | Количество комнат |
| Type | Тип объекта: |
|    br - bedroom(s); |
|    h - house, cottage, villa, semi, terrace; |
|    u - unit, duplex; |
|    t - townhouse; |
|    dev site - development site; |
|    o res - other residential; |
| Price | Цена объекта |
| Method | Метод продажи объекта: |
|    S - property sold; |
|    SP - property sold prior; |
|    PI - property passed in; |
|    PN - sold prior not disclosed; |
|    SN - sold not disclosed; |
|    NB - no bid; |
|    VB - vendor bid; |
|    W - withdrawn prior to auction; |
|    SA - sold after auction; |
|    SS - sold after auction price not disclosed; |
|    N/A - price or highest bid not available. |
| SellerG | Имя риэлтора |
| Date | Дата продажи объекта |
| Distance | Расстояние до центрального района в километрах |
| Postcode | Почтовый индекс |
| Bedrooms2 | Количество спален |
| Bathroom | Количество ванных комнат |
| Car | Количество парковочных мест |
| Landsize | Площадь прилегающей территории |
| BuildingArea | Площадь самого объекта |
| YearBuilt | Год постройки |
| CouncilArea | Округ |
| Lattitude | Широта |
| Longtitude | Долгота |
| Regionname | Ещё одно административное деление |
| Propertycount | Количество объектов в округе |
| id | id объекта |
