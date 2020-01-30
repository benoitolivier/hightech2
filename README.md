# hightech2

projet fin de formation

installation:
symfony serve,
composer install,
php bin/console doctrine:database:create,
php bin/console make:migration,
php bin/console doctrine:migrations:migrate,
composer require --dev orm-fixtures,
php bin/console doctrine:fixtures:load
