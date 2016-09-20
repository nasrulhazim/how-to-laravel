# Application Installation

There's two ways to install to install Laravel application

## via Composer Create Project

Run the following command to create Laravel application

```
composer create-project laravel/laravel
```

This will create an application with name `laravel`. 

If you want to create Laravel application with your own name, you may use the following syntax:

```
composer create-project laravel/laravel application-name
```

## via Laravel Installer

Run the following command to have a Laravel Installer globally

```
composer global require "laravel/installer"
```

Then you can create project using following syntax:

```
laravel new application-name
```

## Serve the Application

If you are on Windows with Laragon, you will have to virtual host generated for you. Just right click the Laragon control panel, go to `www` and choose you application name. Laragon will open a browser for you.

If you are on Linux or OSX, you may want to use PHP built-in server by running:

```
php artisan serve --port=9000
```

**p/s: Ignore `--port=9000` if you want the application to run on default port - `8000`.**