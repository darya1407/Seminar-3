# Туториал по языку разметки markdown

## Работа с заголовками

## Работа со списками

Новый текст 

## Работа с изображениями

Воздушный шарик
Чтобы добавить изображение в MarkDown, используйте следующую конструкцию:
!
["Альтернативныйтекст"] (https://s1.1zoom.ru/big7/76/Scenery_Sky_Mountains_356720.jpg)

## Работа с таблицами 

Для того, чтобы добавить таблицу в MarkDown, нужно пойти на некоторые ухищрения. Воспользуемся разметкой GFM, пример:

First Header | Second Header
------------- | -------------
Content Cell | Content Cell
Content Cell | Content Cell
Для красоты можно и по бокам линии нарисовать.

| First Header | Second Header |
| ------------- | ------------- |
| Content Cell | Content Cell |
| Content Cell | Content Cell |
Можно управлять выравниванием столбцов при помощи
двоеточия.
| Left-Aligned | Center Aligned | Right Aligned |
|:------------- |:---------------:| -------------:|
| col 3 is | some wordy text | **$1600** |
| col 2 is | centered | $12 |
| zebra stripes | are neat | ~~$1~~ |
Внутри таблиц можно использовать ссылки, наклонный,
жирный или зачеркнутый текст.

Для всего остального есть обычный HTML. Воспользуйтесь тегом table: 

```
<table><td><tr></tr></td></table>
```
