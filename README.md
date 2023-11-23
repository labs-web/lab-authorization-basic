# Lab authorisation basic

## Travail à faire

- Ajouter l'authentification pour [`Lab-Laravel-crud-basic`](https://github.com/Jalil-Betroji/lab-crud.git) .
- Additionner l'autorisation pour [`Lab-Laravel-crud-basic`](https://github.com/Jalil-Betroji/lab-crud.git) en utilisant uniquement `gate` sans recourir aux `policies`.

### Command used in the application

1. Clone the Repository:

```bash
git clone https://github.com/Jalil-Betroji/lab-crud.git
```

2. Update Composer Dependencies:

```bash
composer update 
```

3. Create Environment File:

```bash
cp .env.example .env
```

4. Run Migrations:

```bash
php artisan migrate
```

5. Seed Database:

```bash
php artisan db:seed
```

6. Launch the Application::

```bash 
php artisan serve
```