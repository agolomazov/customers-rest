# Customers RESTful API

Простой REST API покупателей


### Установка

Создайте новую базу данных и примените скрипт из sql/slimapp.sql

Отредактируйте файл подключение к БД ```src/config/db.php```

Устанавливаем composer зависимости

```sh
$ composer
```

### API Endpints
```sh
$ GET /api/customers
$ GET /api/customer/{id}
$ POST /api/customer/add
$ PUT /api/customer/update/{id}
$ DELETE /api/customer/delete/{id}
```
