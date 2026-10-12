# Контрольная работа №2

Тема: «CSS-фреймворки: разработка интерфейса на Bootstrap или альтернативном CSS-фреймворке».

Студент: Ярлыков Кирилл Николаевич
Группа: ЭФБО-03-25

## Описание

Проект представляет собой учебную версию сайта интернет-магазина, разработанную с использованием Bootstrap.

Предметная область: каталог товаров с карточками, страницей товара, формой заявки и модальным окном быстрой заявки.

GitHub Pages : https://kyarlyokv.github.io/kr2-bootstrap-shop/

## Используемый фреймворк

Bootstrap 5.3.8.

## Способ подключения Bootstrap

Bootstrap подключён локально, без CDN. Файлы фреймворка размещены в папке `vendor/bootstrap/`:

- `vendor/bootstrap/css/bootstrap.min.css`;
- `vendor/bootstrap/js/bootstrap.bundle.min.js`.

Подключение CSS:

```html
<link rel="stylesheet" href="vendor/bootstrap/css/bootstrap.min.css">
<link rel="stylesheet" href="css/custom.css">
```

Подключение JS:

```html
<script src="vendor/bootstrap/js/bootstrap.bundle.min.js"></script>
```

`css/custom.css` подключён после Bootstrap.

## Структура проекта

- `index.html` — главная страница;
- `catalog.html` — каталог товаров;
- `product.html` — страница товара;
- `order.html` — форма заявки;
- `css/custom.css` — дополнительные стили проекта;
- `images/` — изображения проекта;
- `vendor/bootstrap/` — файлы Bootstrap;
- `README.md` — описание проекта.

## Реализованные Bootstrap-компоненты

- `navbar`;
- `card`;
- `btn`;
- `badge`;
- `alert`;
- `modal`;
- `accordion`;
- `breadcrumb`;
- `form-control`;
- `form-select`;
- `input-group`;
- `form-check`.

## Форма заявки

Форма заявки расположена на странице `order.html` и в модальном окне на `catalog.html`. Содержит поля имени, e-mail, телефона, выбора товара, комментария и чекбокс согласия на обработку данных.

## Самостоятельные доработки

- Bootstrap подключён локально из папки `vendor/bootstrap/`;
- настроен `css/custom.css` для дополнительных стилей;
- футер прижат к низу страницы на главной;

## Проверка проекта

1. Открыть `index.html`.
2. Проверить навигацию и активный пункт меню.
3. Открыть `catalog.html`.
4. Проверить карточки товаров, модальное окно и аккордеон.
5. Открыть `product.html`.
6. Проверить карточку товара и таблицу характеристик.
7. Открыть `order.html`.
8. Проверить форму заявки.
9. Проверить адаптивность через DevTools на ширинах 375, 768, 1024, 1440 px.