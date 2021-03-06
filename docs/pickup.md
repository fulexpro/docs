# Оформление заявки на самовывоз

1. Используется для получение заказа вашими клиентами/партнерами в Пункте выдачи заказов (ПВЗ) FuLEx;
2. Для внутреннего перемещения по складу - [подробности тут](movement.md).

## Создание заявки
Для создания заявки необходимо перейти во вкладку Оформить заказ далее Новый заказ
![new_order](img/new_order.png)

## Оформление заявки

### Номер заказа

![order](img/order_number.png)
- Укажите внутренний номер заказа, если вы ведете внутренний учет в своей системе.
- В случае если учет не ведется, заполните это поле произвольно, либо пропустите.

### Тип отправления
Всегда - FulEx
![delivery_fulex](img/delivery_fulex.png) 
### Город получателя
Город, где располагается Пункт выдачи заказов (самовывоза) FuLEx
![receiver](img/delivery_city_pokrov.png)
### Вид доставки
Выберите из раскрывающегося списка в поле "Вид доставки", а именно ФУЛЕКС САМОВЫВОЗ.
![pick_up_select](img/pick_up_select_pokrov.png)
### Данные о получателе

![pick_up_company](img/pick_up_company2.png)

- **Адрес и индекс получателя** заполняется автоматически после выбора ПВЗ;
- **Компания** - название компании получателя, если заказ заберет частное лицо, напишите просто ЧАСТНОЕ ЛИЦО;
- **ФИО получателя** - ФИО человека, кто будет забирать заказ. Если заказ забирает частное лицо - получение по паспорту, если представитель компании (например, курьер), то при себе ему необходимо иметь оригинал доверенности на указанное лицо. 
- **Телефон получателя** - контактный телефон (при необходимости).

**ВАЖНО:** срок хранения готового заказа в Пункте выдачи FuLEx - 14 календарных дней с планируемой даты доставки. По истечение данного срок заказ автоматически будет расформирован. 

### Дата выдачи заказа на самовывоз

![arrival](img/arrival_date.png)
- Дата, когда получатель планирует забрать заказ.
- Удобный временной интервал для получения заказа. Доступные интервалы: 9:00 - 12:00; 12:00 - 15:00; 15:00 - 18:00; 18:00 - 20:00.

### Товары

![product](img/product.png)

Необходимо открыть развернутое меню и добавить товар в заказ.
![menu_goods](img/menu_goods.png)

- **Артикул товара** - нажмите “Выбрать“. Открывается список вашей номенклатуры, возможность поиска нужного SKU и иные варианты сортировки. 

![select_goods](img/select_goods.png) 

Выберите нужный артикул товара.

**ВАЖНО:**  позиции с остатком 0 добавить в заказ нельзя. 

- **Количество** - впишите количество единиц выбранного артикула;

Оставшиеся поля заполнятся автоматически, либо правятся вручную, кроме ВГХ (весогабаритных характеристик). 
Особое внимание уделите полям, где требуется указание цены. Если при получении заказ не будет предполагать оплату, лучше написать "0". 

Теперь смело нажимайте **"Сохранить".**

**Посмотрите**, в заявке отображается нужное количество единиц выбранной позиции. Теперь  выполните те же действия, только для добавления новых позиций.

### Данные о грузе (общие)

![cargo_ready_mp](img/cargo_ready_mp.png)

* **Вес** - автоматически суммируется, если ранее верно был заполнен раздел "Товары";
* **Сумма наложенного платежа** - если заказ предполагает оплату получателем.
* **Сумма страхования груза** из этой цифры будет рассчитана страховка вашего отправления, если Вы указали сумму и сохранили заявку, то отменить данное действие или изменить указанную сумму нельзя. Данные автоматически отправляются в страховую компанию. Если вам не нужно страховать груз, то напишите 0.

![gruzomesto](img/gruzomesto.png) 

- **Количество грузомест** - заполнится складом по результатам сборки заказа.

### Дополнительная информация

![description](img/description.png)
- **Поручение** - техническое задание, в котором описано что нужно сделать с товаром из заявки, если такие услуги необходимы. Перечень услуг склада представлен в Приложении № 1 к Агентскому договору.

### Тип оплаты

![product](img/payment_pickup.png)
- Выберите “Тип оплаты” - Без оплаты. 

### Необходимость возврата документов
При необходимости: "Да"/"Нет"
![needs_doc_back](img/needs_doc_back.png)

### Прикрепленные файлы

![files](img/attached_files.png)
- Вложите документы, которые необходимо передать получателю, или более развернутое ТЗ.

## Статус выполнения заявки
Отслеживать статус выполнения заявки можно через вкладку "Отслеживание" по ее номеру. 

Вот и все, легко же?! 
Вперед!
