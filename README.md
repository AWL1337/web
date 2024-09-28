# Лабораторные работы

## Лабораторная 1

Данная лабораторная подразумевает создание макета сайта без использования знаний CSS, только HTML. Создаем сайт резюме - портфолио. Главная задача данной лабораторной работы - ознакомиться с наиболее значимыми тегами и правилами их использования.

1. Установить любой текстовый редактор или же специализированное ПО (WebStorm и так далее) - на ваш выбор.
2. Определиться с темой проекта и нарисовать макет вашего сайта (схематично) - расположение картинок, текста, поля контактов.. - картинку также положить в гит репозиторий (Можно фотографию рисунка на листочке)
   > ![Пример](/images/readme/lab1.png)
   >
   > В качестве темы подойдут: портфолио с галереей, интернет-магазин, гостевая книга, блог и т.п.
3. Задать кодировку страницы  UTF-8
4. Описать ключевые слова в метаинформации страницы, а также в описании страницы
5. Для упрощения проектирования подключить файл стилей outlines.css (опционально)
6. Приступить к написанию сайта:
    1. Добавить Doctype
    2. Добавить теги &lt;html&gt;, &lt;head&gt; и &lt;body&gt;,
    3. Установить язык для сайта-русский
    4. Добавить заголовок страницы
    5. Убедиться что в readme.md указана ваше ФИО и номер группы, добавить выбранную тему.
    6. Выделить логические элементы вашего сайта с помощью  тегов:
        - main
        - header
        - footer
    7. Использовать теги section, nav, article, aside, h1-h6, p - согласно их предназначению. (смотреть лекцию)
    8. Использовать теги перечисления (ul, ol) (например, для описание ваших успехов или неуспехов).
    9. Вставить блок с псевдографикой из символов ASCII
    10. Вставить snippet кода, оформив его соответствующими тегами.
    11. Добавить цитату и формулу вашего успеха (желательно использовать тэги sub и sup)
    12. Для выделения наиболее важных моментов использовать strong и b, em и i, del и ins



## Лабораторная 2

Цель лабораторной - научиться создавать и привязывать стили для элементов html. Про размещение элементов пока можно не думать, необходимо достичь эффекта, при котором отдельно взятый элемент смотрится законченным, красивым и приятным глазу. При этом вместе эти элементы не пестрят разными красками. Советую использовать сервисы по сочетаемости цветом - перед началом выполнения лабораторной определиться со стилистикой вашего сайта.
> Например: https://color.adobe.com/ru/

На той же странице, написанной в рамках первой лабораторной работы:
1. Создать и подключить собственный файл стилей
2. Добавить стили всем элементам на странице (границы - отступы и шрифты).
3. Должны быть использованы различные по типу селекторы. (Желательно по какой-либо конкретной методологии, например БЭМ)
4. Добавить картинки.
5. Определить цвета заливки и теней для элементов
   > ![Пример shadow drop](/images/readme/lab2.png)
6. Применить стили для текста, задать свойства:
    - размера шрифта
    - высоты строки
    - семейство используемых шрифтов
    - насыщенность шрифта
    - выравнивание текста (горизонтальное, вертикальное)
    - Фон и цвет текста
    - Отступы
    - пробелы
    - Стилизация  переформатированного текста
    - Подчеркивание, зачеркивание и  другие
    - Регистр символов



## Лабораторная 3

Произвести выравнивание всех ранее описанных элементов вашего сайта используя удобный для вас способ - флексы или флоты либо применить 12-ти столбчатую вёрстку. Обязательное наличие горизонтальных и вертикальных рядов элементов. Если у вас до этого не было - всегда можно добавить – например, галерею с картинками.

Также необходимо проработать то, как ваш макет будет выглядеть на различных мониторах (на маленьком ноутбуке, полноценном Full HD, 2K монитор). Выбрать элементы, которые не будут отображаться на маленьких мониторах, например, рекламный баннер во всю длину footer’a.

1. Использовать css-правила @media screen для скрытия элементов не умещающихся в клиентскую область
2. Закрепить элемент с помощью абсолютного позиционирования - например строку меню либо шапку или подвал сайта.
3. Добавить на страницу таблицу с заголовками и стилями для чётных и нечётных строк. В качестве типа отображения таблицы рекомендуется воспользоваться grid’ом, для достижения лучшей адаптивности. (т.е. необходимо добиться того, чтобы колонки таблицы изменяли свой размер в зависимости от размера окна)
> ![Пример](/images/readme/lab3.png)



## Лабораторная 4

Цель лабораторной работы – научится взаимодействовать со элементами и браузером используя встроенной скриптовой движок JavaScript.

1. Добавить новые страницы для вашего проекта, согласно пунктам меню в шапке сайта.
2. Создать скрипт, который будет выполняться на каждой странице, добавить его в отдельную папку и подключить в разделе <head> ваших страниц.
3. Используя IIFE, подписаться на события загрузки страницы и вывести в подвал статистическую информацию о скорости загрузки:
   > ![Пример](/images/readme/lab4_loadtime.png)
4. Добавить интерактивности меню, обработать события наведения мыши на конкретные пункты с использованием CSS либо JS.
   > ![Пример](/images/readme/lab4_interactive.png)
5. В зависимости от того, на какой странице находится пользователь (можно понять по document.location) добавить соответствующему пункту меню CSS class, отвечающий за «активное» состояние.



## Лабораторная 5

Целью работы заключается в получении практических навыков по созданию разметки во время выполнения (in runtime).

Необходимо создать отдельную страницу с Web-формой, в которой пользователь с помощью предложенных параметров мог бы создать таблицу по некоему шаблону, например, расписание занятий на 5-ти дневную либо 6-ти дневную неделю, выбрать максимальное количество занятий, язык на котором будет сгенерирована таблица и тому подобное.

Примерный ожидаемый результат лабораторной работы на примере проекта «список дел»:
> ![TodoList](/images/readme/lab5.gif)

1. Создать отдельную страницу и отдельный файл со скриптом, добавить ссылку на «конструктор» в меню.
2. Добавить <form> на новую страницу и <div> контейнер куда будут размещены результаты генерации.
3. Обработать событие отправки формы (перехватить событие onSubmit) и без перезагрузки страницы отобразить результат генерации
4. Предусмотреть возможность сохранения и загрузки введенных пользователем параметров в локальное хранилище браузера пользователя (читай как LocalStorage).

> Для стилизации элементов не используйте атрибуты style, предпочтительно использование атрибутов class из вашего заранее созданного файла со стилями.



## Лабораторная 6

Цель лабораторной работы – познакомится с сущностью Promise и научится создавать http-запросы и корректно обрабатывать ответы.

В качестве практикума студентам предлагается добавить «живых» данных на уже имеющийся прототип. В качестве поставщика данных использовать сервис с Mock данными, например: [JsonPlaceholder](https://jsonplaceholder.typicode.com)

Перед началом работы необходимо выбрать ту часть проекта, в которую в дальнейшем будут загружаться данные. Это может быть профиль пользователя, прошедшего авторизацию, комментарии под той или иной фото в галерее, список пользователей в одной из уже созданных таблиц и т.п.

В качестве данных, которые предоставляет сервис из примера, предлагается 6 видов ресурсов на выбор:
- Сообщения для гостевой книги/форума
  > Поля: body (само сообщение), title (заголовок)
- Комментарии под фото либо любым другим материалом
  > Поля: name (автор комментария), email (email автора комментария), body (комментарий)
- Альбомы и фотографии
  > Поля: title (название), thumbnailUrl (ссылка на маленькое изображение), url (ссылка на изображение)
- Список дел
  > Поля: title (описание), completed (boolean флаг)
- Пользователи
  > Поля: username, name, email, address, phone, website, company

1. Добавить отдельный скрипт и подключить на страницу где подразумевается сетевое взаимодействие.
2. Добавить gif-анимацию либо свою произвольную css-анимацию для элемента типа preloader под элементом где планируется отобразить запрашиваемый контент
3. Дождаться события загрузки страницы и инициализовать обращение к поставщику данных используя [Fetch API](https://developer.mozilla.org/ru/docs/Web/API/Fetch_API)
4. После получения ответа, скрыть preloader, десериализовать данные в JSON объект и отрендерить полученные данные.
5. Добавить псевдо-случайную фильтрацию к запросам (например при первом обращении получать комментарии с id 100 и выше, а при втором c id 200 и меньше).
6. Добавить обработку ошибок (например – сеть перестала быть доступна и запрос не был выполнен), в случае исключительной ситуации добавить под элементом заплатку, например, «⚠ Что-то пошло не так».



## Лабораторная 7

Целью лабораторной работы является изучение продвинутых практик взаимодействия с DOM и CSS с использованием подключаемых JS библиотек.

Студентам предлагается продемонстрировать умения работы со сторонними API популярных библиотек.

1. Выберите одну – две UI библиотеки которые можно интегрировать в ваш проект из предложенного [списка](https://github.com/sorrycc/awesome-javascript)


2. Опишите use-case сценарий с использованием выбранных библиотек и реализуйте его.

3. Добавьте комментарии в JS-коде перед вызовами сторонних библиотек с указанием того какой аргумент функции для чего используется и как именно вы конфигурируете ту или иную часть библиотеки.

4. Добавьте стилизацию подключенных компонентов, чтобы они не выбивались из уже используемой цветовой палитры вашего проекта.

> Лабораторная работа скорее творческая и поможет добрать недостающие баллы если подключенные библиотеки будет использованы качественно в полном объеме предлагаемых возможностей. (т.е. подключение всего Bootstrap фреймворка ради одного элемента внутри таблички не выглядит оправданным)