# laravel 9 php 8 test app


# quick start
```
composer install
```
```
mv .env.example .env
```

set up database connection in .env
i.e 
```
DB_DATABASE=YourDatabase
DB_USERNAME=YourDatabaseUserName
DB_PASSWORD=YourDatabasePassword
```

```
php artisan key:generate
```

```
php artisan migrate
```

```
php artisan db:seed
```

install node packages/modules ( optional for this app )
```
npm install
npm run build
```
now to start the laravel local developlement server
```
php artisan serve
```


