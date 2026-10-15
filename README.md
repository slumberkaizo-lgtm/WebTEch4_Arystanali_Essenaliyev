# Assignment 4 — Forms and Validation

Учебная практика на HTML и CSS без JavaScript.

Студент: укажите ФИО.  
Группа: укажите группу.

## Запуск

Откройте index.html в браузере.

## Файлы

- index.html — Task 0: контактная форма.
- html5.html — Task 1: встроенная HTML5-валидация.
- bootstrap.html — Task 2: форма с классами и сеткой Bootstrap.
- validation.html — Task 3: сообщения проверки и примеры is-valid / is-invalid.
- registration.html — Task 4: регистрационная форма.
- success.html — страница после отправки.
- css/style.css — Bootstrap 5.3.8 в начале файла, затем простые стили практики.
- BOOTSTRAP-LICENSE.txt — лицензия Bootstrap.

required делает поле обязательным, type="email" проверяет email, minlength и maxlength ограничивают длину. label связан с полем через for и id. row и col-md-6 задают адаптивную сетку Bootstrap.

:user-valid и :user-invalid показывают сообщения через CSS после взаимодействия с полем. Классы is-valid и is-invalid отдельно показаны в примерах на Task 3. Reset сбрасывает форму.

HTML и CSS не сравнивают пароли между собой. Проверяются обязательность и длина обоих полей. У паролей нет name, поэтому при GET-отправке они не попадают в адресную строку. Данные не сохраняются, аккаунт не создаётся.

## Сдача

Загрузите файлы в GitHub-репозиторий и включите GitHub Pages в Settings → Pages, выбрав ветку main и / (root). Можно также использовать Netlify без команды сборки.

Ссылка на репозиторий: https://github.com/slumberkaizo-lgtm/WEB_Tech4  
Ссылка на сайт: добавьте после публикации.
