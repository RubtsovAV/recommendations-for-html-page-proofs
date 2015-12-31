# Требования к HTML вёрстке
Основные требования к HTML вёрстке для верстальщика

## Соответствие макету
Вёрстка должна максимально соответствовать макету. Допустимы отклонения в 3-5 пикселей.

## HTML код
1. Первой строкой всегда должно быть `<!DOCTYPE html>`
2. Блок `<head>` одинаковый на всех страницах
3. CSS вынесены в файлы и подключаются через `<link>` (и только внутри `<head>`)
4. Атрибуты `style="..."` и `id="..."` недопустимы
5. Весь JavaScript в отдельных файлах и подключается перед `</body>`
6. Перечень подключаемых файлов (стили, скрипты, шрифты) должен быть одинаковым на всех страницах
7. Все файлы должны лежать в соотвествующей папке js, css, images. Ссылки на внешние ресурсы недопустимы.
8. Шапка и подвал страницы внутри тега `<header>` и `<footer>` и недолжны находиться внутри каких-то других тегов, кроме `<body>`
9. Боковые sidebar-ы (колонки) должны быть внутри `<aside>`
10. Заголовки h1-h6 допускаются только там, где без них нельзя обойтись. Например, внутри `<article>`.
11. Список товаров, статей или новостей должен быть внутри тега `<main>` с тегом `<h1>` внутри
12. Содержание новости или статьи должно быть внутри тега `<article>` с тегом `<h1>` внутри
13. Тег `<h1>` всегда без атрибутов (class="..." и др. недопускаются)
14. Валидность кода https://validator.w3.org/

##Кроссбраузерность
IE9+ и последние версии Chrome, Firefox, Opera, Safari
