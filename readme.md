# Вебинар "Подключаем Google-карту на сайт"

## Теоретическая часть

1. Как вообще работают карты.
2. Регистрация API-ключа, кто это должен делать.
3. Как ориентироваться в документации.
4. Обзор сервисов.
5. Почему Google Maps.

## Практическая часть

👨‍💻 Репозиторий содержит исходный код примеров, рассмотренных на вебинаре.

📂 Фалы разделены на папки и пронумерованы.

1. Добавляем карту на веб-страницу.
2. Добавляем несколько объектов (маркеров) на карту.
3. Добавляем показ инфо-окон для объектов на карте.
4. Программное добавление объектов на карту (из массива).
5. Программное центрирование карты (в зависимости от выбранного города).
6. Небольшие улучшения кода.

 👨‍🎓 В конце каждого файла есть комментарии и полезные ссылки для самостоятельного изучения.

## Задание для самостоятельного выполнения

Заменить стандартное изображение маркеров на изображение логотипа "Коксберри".
Задание необходимо выполнить в папке 7, за основу взять код из папки 6.
Изображение логотипа "Коксберри" уже лежит в папке 7.

Всю необходимую информацию нужно самостоятельно найти в документации Google Maps JavaScript API.

Для выполнения задания сделайте форк этого репозитория, после выполнения задания пришлите ментору ссылку на ваш репозиторий.

## Дополнительное задание для самостоятельного выполнения

Добавить в объекты пунктов выдачи свойство `paymentByCard`, у некоторых объектов оно должно быть со значением `false`, у остальных `true`.

Рядом с выпадающим списком городов добавить чекбокс "Оплата картой", при клике по чекбоксу на карте должны остаться только пункты, в объекте которых свойство `paymentByCard` имеет значение `true`.

Задание необходимо выполнить в папке 8, за основу взять код из папки 7.

💡 **Подсказка**: нужно сохранять созданные маркеры в массив, а при клике по чекбоксу все маркеры удалять и снова добвлять на карту (только нужные).

В документации есть описание удаления маркеров.

---
Вебинар организован школой [Skill Factory](https://skillfactory.ru/), запись вебинара можно посмотреть в LMS Skill Factory, в разделе "Вебинары и созвоны" на вкладке "Курс".