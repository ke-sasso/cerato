<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with Admin LTE and Jetstream


### Requirements

-  PHP ^7.3|^8.0
-  NPM ^7.8.0 
-  Node JS  ^12.16.3
-  Composer


### Install
- Crear archivo .env en la raíz del proyecto y agregar el nombre de la base de datos. Example DB_DATABASE=laravel
- Ejecutar composer install
```bash
$ composer install
```
- Se deben de crear todas las migraciones para eso modificar archivo .env con las credenciales de la BDD y luego ejecutar
```bash
$ php artisan migrate
```

### Inicio rápido
```bash
$ php artisan serve --port=8000
```

### Líneas de comandos para crea proyecto:
#### Via Composer
1. `composer global require laravel/installer` 
2.  `laravel new cerato --jet`  
3.   Ingresar la opción livewire
4.  `npm install && npm run dev`  
5.  `php artisan migrate`  
6.  `php artisan vendor:publish --tag=jetstream-views`  
7.  `composer require jeroennoten/laravel-adminlte`  
8.  `php artisan adminlte:install`  
