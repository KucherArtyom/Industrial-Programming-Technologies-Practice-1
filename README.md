# Industrial-Programming-Technologies-Practice-1 (ЭФМО-02-24 Кучер Артем Сергеевич)
## Интернет магазин электронники

**Логическая схема базы данных:**

![Снимок экрана 2024-09-16 165717](https://github.com/user-attachments/assets/c281f2e5-08c7-47a5-bd1e-663dff75bd1d)


**Физическая схема базы данных:**

![Снимок экрана 2024-09-16 165142](https://github.com/user-attachments/assets/1af6e282-9516-4ccc-acff-a1d5d64cd711)


1) Order (Заказ) - (id , дата доставки, время доставки, id покупателя)

2) Customer (Покупатель) - (id, фамилия, имя, отчество, телефон, номер карты, почта, пароль)

3) Product (Продукт) - (id, id производителя, id категории продукта, название, цена, количество, артикул, описание, изображение)

4) Reviews (Отзывы) - (id, id покупателя, id продукта, дата отзыва, текст отзыва, оценка/рейтинг)

5) ProductCategory (Категория продукта) - (id, название категории)

6) Manufacturer (Производитель) - (id, название, страна)

7) Favorites (Избранное) - (id, id продукта, id покупателя)

8) Provider (Поставщик) - (id производителя, id покупателя)

9) Basket (Корзина) - (id, id покупателя)

10) Delivery (Доставка) - (id, id заказа, id адресса, статут заказа, дата отправки, планируемая дата доставки)

11) ProductOrder (Заказ_продукт) - (id продукта, id заказа)

12) ProductBasket (Корзина_продукт) - (id продукта, id корзины)

13) Address (Адресс доставки) - (id, id покупателя, страна, город, улица, дом)
