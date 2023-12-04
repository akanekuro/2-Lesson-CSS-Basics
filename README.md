# Урок 3: Основы CSS
### 1.1 Тема: Введение в CSS
🔗[Документация для работы с СSS ](https://doka.guide/css/)

Обзор
CSS (Cascading Style Sheets) является языком, который используется для описания внешнего вида и форматирования документа, написанного на языке разметки. В этом уроке мы рассмотрим основы CSS, включая синтаксис, как CSS связывается с HTML, и начнем изучать основные стили.

#### Цели Урока:
Понимание Роли CSS в Веб-Разработке:

Объяснение, как CSS улучшает визуальное представление веб-страниц.
Различие между HTML и CSS (структура против стиля).
#### Основы Синтаксиса CSS:

Понимание структуры правил CSS: селекторы, свойства и значения.
Различные типы селекторов: тег, класс, идентификатор.
#### Связывание CSS с HTML:
Внутренний (внутри тега `<style> в <head>`) и внешний (подключение внешних файлов CSS через `<link>`) способы применения стилей.
Примеры использования инлайн стилей (напрямую в HTML элементе).
#### Основные Свойства CSS:
1) Цвет и фон (`color, background-color`). 🔗[Описание тегa для работы с background ](https://doka.guide/css/background-color/) 🔗[Описание тегa для работы с color ](https://doka.guide/css/color/).
2) Шрифты (`font-family, font-size, font-weight`).
3) Текст (`text-align, line-height, text-decoration`).
4) margin: Внешний отступ вокруг элемента(`padding, border, width, height`).
5) Позиционирование и Отображение: (`position, display, z-index`)
6) Флексбокс и Грид: (`display: flex, display: grid`)
7) Анимации и Переходы: (`transition, animation, @keyframes`)

### 🏆 Задание 1:
 1.1 Исследование различных веб-сайтов для анализа их стилей и попытка воссоздания некоторых элементов дизайна.
 
 1.2 Работа с текстом 
 
1) В CSS файле в самом верху создайте селектор для тега body и напишите следующие стили - шрифт Arial, sans-serif, размер шрифта 16px, цвет текста #333, межстрочный отступ 1.5
2) В CSS файле создайте селектор для класса title, и напишите следующие стили - размер шрифта 40px, цвет текста #f03333, межстрочный отступ 1.2, все буквы заглавные
3) После заголовка создайте абзац и напишите там немного текста, можете использовать сайт-генератор случайного текста lipsum.com
4) После абзаца создайте заголовок второго уровня, напишите текст "Заголовок второго уровня" и придайте ему класс subtitle
5) В CSS файле создайте селектор для класса subtitle, и напишите следующие стили - размер шрифта 30px, цвет текста #12ac11, межстрочный отступ 1.2, подчеркивание текста снизу
6) После заголовка создайте абзац и напишите там немного текста, можете использовать lorem или от себя
7) После абзаца создайте ненумерованный список с тремя пунктами
8) В каждом пункте напишите немного текста, на свой выбор
9) Задайте списку класс list
10) В CSS файле создайте селектор для класса list, и напишите следующие стили - размер шрифта 20px, цвет текста #444, все буквы наклонные, стиль маркеров списка - square
    
 1.3 Для блока `<div>` с классом `content-box` добавить следующие стили:

   Border: 2-пиксельная сплошная зеленая граница.
  Background-color: Светло-серый фон.
 Padding и Margin: Внутренние и внешние отступы для создания пространства вокруг содержимого и границ блока.  
  У заголовка `<h1>` внутри .content-box применен зеленый цвет текста #4CAF50;.
У абзаца `<p>` внутри .content-box задан темно-серый цвет текста #333333;.


