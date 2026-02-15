# Nombre del Proyecto
Proyecto Perfil Personal

## Descripción breve
Este proyecto es una aplicación web desarrollada con el framework **Laravel**.
El proyecto se encuentra alojado en GitHub y puede ser descargado para su ejecución local.
Permite visualizar un perfil personal con las secciones:
- Perfil
- Intereses
- Habilidades
- Metas

Cada vista fue desarrollada usando únicamente **HTML, CSS y PHP (Blade)**.

## Requisitos del sistema
Antes de instalar el proyecto, asegúrese de contar con los siguientes requisitos:

- Laravel >= 8.0
- PHP >= 8.0
- Composer
- Git
- Node.js 
- Servidor local (XAMPP, Laragon o WAMP)

## Instrucciones de instalación
Clonar el repositorio desde GitHub:

- git clone https://github.com/JavierLuna242/mi-perfil-laravel.git
- cd mi-perfil-laravel
- composer install
- cp .env.example .env
- php artisan key:generate
- php artisan migrate (opcional si hay base de datos)

## Cómo ejecutar el proyecto
- Abrir el servidor local para activar Apache y MySQL 
- php artisan serve
- http://127.0.0.1:8000

## Autor y fecha
- Javier Mauricio Luna Díaz
- 15/02/2026




