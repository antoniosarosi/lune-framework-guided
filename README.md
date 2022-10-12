# Lune Framework
Refactor of Lune Framework with step by step commits

Migrations (check [`.env`](./.env)):

```
php lune.php migrate
```

App:

```
cd public
php -S localhost:8000
```

Tests (`.env` not implemented, check [`./tests/Database/RefreshDatabase.php`](./tests/Database/RefreshDatabase.php)):

```
composer run tests
```
