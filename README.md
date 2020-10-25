

## About 
    This application is a simple chat room application created using Laravel 8 and Vue.js.
    Using pusher as real-time data for chat and laravel echo for listening from pusher





## Requirements

    PHP 7.4 or newer.
    Laravel 8 
    MySQL Server 5.x or newer for main database.
    pusher account you can make it here https://pusher.com/



## Config .env File
    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=your database
    DB_USERNAME=your username
    DB_PASSWORD=your pass

    BROADCAST_DRIVER=pusher

    PUSHER_APP_ID= your App ID
    PUSHER_APP_KEY= your App Key
    PUSHER_APP_SECRET= your App 
    PUSHER_APP_CLUSTER= your App Cluster

## Before You Running The App
    php artisan key:generate
    php artisan migrate

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
