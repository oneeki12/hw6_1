# hw6_1
> works only on Linux

Перед запуском локального сервера желательно создать и войти в виртуальное окружение следующей командой: 
`cd hw6_1/hw6_1 && python -m venv venv && source venv/bin/activate`


После чего установить необходимые библиотеки и пакеты:
`pip install -r requirements.txt`

Затем запустить локальный сервер командой:
`python manage.py runserver`

Если все предыдущие этапы выполнены правильно, то в терминале выйдет адрес локального сервера который нужно открыть в браузере, после открытия локальная веб-страница вернёт ошибку 404 (страница не найдена), вам надо вручную после порта через слэш ( / ) дописать вкладку "parser", поле ввода адреса в итоге должен выглядеть так:
`http://127.0.0.1:8000/parser/`

Терминал выдаст статус код - 200 (успешный запрос), вам остается лишь кликнуть на кнопку 'Start-Parsing' 
:)