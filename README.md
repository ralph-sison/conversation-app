# conversation-app (context-app)

A simple REST API using laravel 8.83

NOTES:
- I've used a database to store the given contexts so that you can easily add a context (through the seeder).
- I've also added an optional name property in the request data so that it will be included in the response if it is supplied.
- This project already contains the Context model, controller, migration file, api routes file.
- I've added test scripts for automated testing (phpunit) which can easily be ran by the command php artisan test (linux/ubuntu) or php artisan test --without-tty (windows). You can also test this in postman.

# Setup
- download and extract contextapp.zip
- install dependencies (composer install)
- configure env
- migrate and seed

You can now run the application with php artisan serve
