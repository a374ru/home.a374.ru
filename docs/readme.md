<div class="navi"><nav id="navi"><!-- js --></nav></div>

# Документация `Ольховка-90/91/92`

<span id="az1-img" class="img" onclick="imgResize()">![img](assets/svg/000-start.svg)</span>

### Что нужно уметь?

1. Уметь пользоваться сервисом `GitHub` (обязательно)
2. Знать разметку `markdown` (необязательно)

Разместите папку `docs` в корне вашего проета в `github` и просто добавляйте страницы в папку `/docs`.

Скопируйте содержимое `000.md` в свою страницу с расширением `.md` и добавьте в файл `navi.js` в объект `pageDict{}` запись, — где ключ это имя страницы, и значение, которое будет отображено в меню.

**ПРИМЕР  кода  НИЖЕ** для двух страниц: `az.md` и `contacts.md`

```js
// это файл navi.js
pageDict = {
	az: "Азъ",
	contacts: "Контакты",
};
```

Загрузите или толкните проект в Гитхаб и включите `pages` в настройках `Github`.

Если вам нужно добавить поиск по материалам большой документации, лучше воспользуйтесь `Google-search` инструментами. Пример [здесь…](navi-page.md)

<span style="color: #e34234;">Обязательно замените скрипт примера на свой собственный.

## Рекомендации по использованию

<span style="color: #8F7161;">Для прописанных ниже разметок в стиле `markdown` применяются стили данного проекта.

## Заголовки

	1. <H1> # - один для названия страницы
	2. <H2> ## - много, разделяйте подтемы страницы
	3. <H3> ### - много, небольшое одноцветное выделение
   
## Цитаты

	> Текст цитаты (выделение для привлечения внимания)


## Код

	```js
	let az = "-i- или -я- с маленькой буквы";
	```

## Таблицы

	| title | title | title |
	| :---: | :---: | :---: |
	| text  | text  | text  |
	| text  | text  | text  |

## Картинки

	Можно использовать: JPG, PNG, SVG и т.д..

<br>

<span id="az2-img-2" class="img" onclick="imgResize()">![img](assets/svg/000-end.svg)</span>

||||
|:---|:---:|---:|
[🔙](contacts.md)|[ 🔝 ](#)|[🔜](water.md)

<script src="assets/js/navi.js"></script>