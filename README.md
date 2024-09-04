<p align="center"><img src="https://eveys.com/image/icons/brand.svg" width="400" alt="Eveys Logo" /></p>

## Eveys Documentation

This is the source of the official Eveys Docs.


## Local Development

If you want to work on this project on your local machine, you may follow the instructions below. These instructions assume you are serving the site using [Laravel Valet](https://laravel.com/docs/valet) out of your `~/Sites` directory:

1. Fork this repository
2. Open your terminal and cd to your `~/Sites` folder
3. Clone your fork into the `~/Sites/docs` folder, by running the following command with your username placed into the {username} slot:
    git clone git@github.com:{username}/docs statamic-docs
4. CD into the new directory you just created.
5. Run the following commands:
  ```npm
  composer install
  npm install
  npm run dev
  cp .env.example .env
  php artisan key:generate
  ```
