# Требования к HTML вёрстке
Основные требования к HTML5 вёрстке для верстальщика

## Соответствие макету
Вёрстка должна максимально соответствовать макету. Допустимо отклонение в 3-5 пикселей.

## HTML код
1. Первой строкой всегда должно быть `<!DOCTYPE html>`
2. Блок `<head>` одинаковый на всех страницах
3. CSS вынесены в файлы и подключаются через `<link>` и только внутри `<head>`
4. Атрибуты `style="..."` и `id="..."` недопустимы, только `class="..."`
5. Весь JavaScript в отдельных файлах и подключается перед `</body>`
6. Перечень подключаемых файлов (стили, скрипты, шрифты) должен быть одинаковым на всех страницах
7. Все файлы лежат в соотвествующей папке js, css, images. Ссылки на внешние ресурсы недопустимы.
8. Шапка и подвал страницы внутри тега `<header>` и `<footer>`
9. Подвал всегда прижат к низу страницы, даже если на ней мало текста
10. Боковые sidebar-ы (колонки) должны быть внутри `<aside>`
11. Список товаров, статей или новостей должен быть внутри тега `<main>` с тегом `<h1>` внутри
12. Содержание новости или статьи должно быть внутри тега `<article>` с тегом `<h1>` внутри
13. В блоках предполагающих редактирование через wisywig редактор не должно быть атрибутов `class="..."`
14. Теги h1-h6 используются только внутри пользовательского контента (основного контента страницы)
15. Валидный код https://validator.w3.org/

##Кроссбраузерность
IE9+ и последние версии Chrome, Firefox, Opera, Safari

##Примеры
* [Страница статьи / новости](https://github.com/RubtsovAV/requirements-for-html-page-proofs/blob/master/examples/article.html)
* [Список статей / новостей](https://github.com/RubtsovAV/requirements-for-html-page-proofs/blob/master/examples/article_list.html)

##Полезные ресурсы
* [Генератор html+css каркаса страницы](http://csstemplater.com/)
