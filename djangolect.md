### Для начала создать виртуальное окружение в питоне: 

    python -m venv <название_окружения> 

### Активируем его:

    <название_окружения>\Scripts\activate (deactivate - для деактивации) 

### Создаем стартовые файлы для Django проекта: 

    django-admin startproject <название_проекта> 

### Переходим в папку с проектом и запускаем сервер:

    python manage.py runserver 

### Для запуска миграций запустим команду 
    python manage.py migrate 

### Создаем пользователя админ: 
    python manage.py createsuperuser
