# Leopard Chalenge - задача регрессии

### Введение
Проект из курса Глеба Михайлова "Data Science с Глебом Михайловым" https://stepik.org/course/113596, в котором предлагается решить задачу регрессии - определить цены на различные объекты недвижимости в Мельбурне. В репозитории лежит ноутбук и данные, с которыми производилась работа. В ноутбуке представлена сжатая (хоть там почти и 80 ячеек) информация по работе с проектом, в итоге были оставлено только то, что дало прирост к метрике на Kaggle. 

### Описание кейса
Это данные о ценах на недвижимость в Мельбурне. Каждая строчка – это объект недвижимости, по которому известны некоторые параметры и его цена. Задача заключается в том, чтобы по этим параметрам определить цену объекта.

Описание столбцов (параметров объекта):

Suburb – район
Address – адрес
Rooms – количество комнат
Type – тип объекта
    br - bedroom(s);
    h - house, cottage, villa, semi, terrace;
    u - unit, duplex;
    t - townhouse;
    dev site - development site;
    o res - other residential.
Price – цена объекта
Method – метод продажи объекта:
    S - property sold;
    SP - property sold prior;
    PI - property passed in;
    PN - sold prior not disclosed;
    SN - sold not disclosed;
    NB - no bid;
    VB - vendor bid;
    W - withdrawn prior to auction;
    SA - sold after auction;
    SS - sold after auction price not disclosed.
    N/A - price or highest bid not available.
SellerG – имя риэлтора
Date – дата продажи объекта
Distance – расстояние до центрального района в километрах
Postcode – почтовый индекс
Bedrooms2 – количество спален
Bathroom – количество ванных комнат
Car – количество парковочных мест
Landsize – площадь прилегающей территории
BuildingArea – площадь самого объекта
YearBuilt – год постройки
CouncilArea – округ
Lattitude – широта
Longtitude – долгота
Regionname – еще одно административное деление на подобие округа
Propertycount – количество объектов в округе
id – id объекта
