 1. Создайте таблицу с мобильными телефонами, используя графический интерфейс. Заполните БД данными.

Скриншот в приложенном файле

2. Выведите название, производителя и цену для товаров, количество которых превышает 2.

 SELECT manufacturer, price
 FROM mobile_phones
 WHERE product_count > 2;

 3. Выведите весь ассортимент товаров марки “Samsung”

  SELECT product_name, product_count, price
  FROM mobile_phones
  WHERE manufacturer = "Samsung";

