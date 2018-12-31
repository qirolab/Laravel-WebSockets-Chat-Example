# Laravel WebSockets 🛰 Chat Example

This is a Chat system example application built with the [Laravel WebSockets](https://github.com/beyondcode/laravel-websockets) package, [VueJs](https://vuejs.org/) and [Laravel-Echo](https://laravel.com/docs/5.7/broadcasting#installing-laravel-echo).

## Tutorial
[![Real-time Chat system](http://i3.ytimg.com/vi/H_4UubWE9NQ/hqdefault.jpg)](https://www.youtube.com/watch?v=H_4UubWE9NQ&list=PL1TrjkMQ8UbWfFUCimQ50CdrR_J7QvEFW)

## Usage

1. Clone this repository
`git clone git@github.com:qirolab/Laravel-WebSockets-Chat-Example.git`
2. `composer install`
3. `php artisan key:generate`
4. `cp .env.example .env` and configure your database in .env file.
5. Run migration to create tables in database.
`php artisan migrate`
6. Final step run websockets server.
`php artisan websockets:serve`,

Now test it in your browser.



