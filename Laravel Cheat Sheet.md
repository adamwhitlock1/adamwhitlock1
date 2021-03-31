## Laravel Cheat Sheet
Thing to help you move faster with Laravel

**Artisan & CLI Commands**
Dump & Regenerate autoload file
From the project root folder path:
```
composer dump
```

Create a model with a migration and controller
```
php artisan make:model --migration --controller test
```

Force a migration
```
php artisan migrate --force
```

Rollback migrations and reseed data
```
php artisan migrate:refresh --seed
```


<!--stackedit_data:
eyJoaXN0b3J5IjpbMjYzODEwNTY1XX0=
-->