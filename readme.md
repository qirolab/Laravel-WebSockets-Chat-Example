# Laravel WebSockets 🛰 Chat Example

This is a Chat system example application built with the [Laravel WebSockets](https://github.com/beyondcode/laravel-websockets) package, [VueJs](https://vuejs.org/) and [Laravel-Echo](https://laravel.com/docs/5.7/broadcasting#installing-laravel-echo).

## Tutorial
[![Real-time Chat system]

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

#### Screenshot Of The Login Screen
![Screenshot (13)](https://user-images.githubusercontent.com/43533375/132718982-39f15b53-270e-4b9a-9399-d32bb9430976.png)

#### Screenshot Of Authentication
![Screenshot (14)](https://user-images.githubusercontent.com/43533375/132719013-6da1325f-98db-43cc-bef1-814f7069d889.png)

#### Screenshot Of Landing Screen
![Screenshot (15)](https://user-images.githubusercontent.com/43533375/132719042-5cd3fe7a-dc14-47b1-a779-9e1f65a0aaf4.png)

#### Screenshot of previously sent messages
![Screenshot (16)](https://user-images.githubusercontent.com/43533375/132719047-3a193bfd-5412-45d6-be76-ec7c8561e379.png)

#### Screenshot Of Newly Sent Message From Ritesh To Kunal
![Screenshot (17)](https://user-images.githubusercontent.com/43533375/132719049-fa445895-b17c-4313-a75b-04342d12e386.png)

#### Screenshot Of Newly Sent Message From Kunal To Ritesh
![Screenshot (18)](https://user-images.githubusercontent.com/43533375/132719037-a8e27bca-41cc-476c-81e3-050d59e3d83d.png)

