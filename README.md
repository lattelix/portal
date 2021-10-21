# 🌈 Rainbow's Server. Языки программирования. 

Это open-source проект, в котором собраны обучающие материалы для изучения различных языков программирования. Внести свой вклад может каждый. 

# ✏️ Как контрибьютить

Сначала вам необходимо скопировать репозиторий к себе в профиль - кнопка ```Fork``` в правом нижнем углу. Все изменения нужно делать именно в нем.

Страница сайта формируется из `.md` файла. Все файлы с контентом находятся в папке [/src/pages/](https://github.com/rbteam/portal/tree/main/src/pages). Чтобы создать новую страницу, нужно создать новый Markdown файл.

# 🔗 Структура файла

В начале каждого файла находится служебная информация о нем:
```markdown
---
title: Заголовок страницы
url: /pages/название_файла/index.html
langs: Языки программирования
author: Авторы
editors: Редакторы
github: Ссылка на файл
---
```

Затем идет содержание файла - пункты, которые будут отображаться, например, список книг или ссыли на видеоуроки. Каждый пункт оформляется следующим образом:

```html
<div class="col-md-6 mb-5">
    <h6>ЗАГОЛОВОК</h6>
    <p class="text-muted">
    КРАТКОЕ ОПИСАНИЕ
    </p>
    <a href="ССЫЛКА" class="btn btn-primary">КНОПКА</a>
</div>
```

Под __авторами__ подразумеваются пользователи, которые добавили что-то новое в содержание, а __редакторы__ - это те, кто изменил уже существующее содержание.

После того, как вы закончили вносить изменения, нужно отправиль Пулл Реквест, указав название, которое кратко его описывает. Например, **Добавляет страницу C++**.
