# Symfony testing

## Instruction
- Pull source code from Repository
```sh
git clone https://github.com/quangvietvp/symfony_testing.git
```

- Installation dependencies
```sh
composer install
```

- Update environment inside .env file


- Create database
```sh
php bin/console doctrine:database:create
``` 

- Migrate database
```sh
php bin/console doctrine:migration:migrate
```

- Run server
```sh
symfony server:start
```