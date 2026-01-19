# Laravel + Docker (Development Environment)

Este proyecto es un entorno de desarrollo para Laravel usando Docker.
No requiere instalar PHP, Composer ni MySQL en el sistema host.

## Stack
- PHP 8.x (FPM)
- Nginx
- MySQL 8
- Docker Compose

## Requisitos
- Docker
- Docker Compose

## Instalación

1. Crear archivo `.env` en la raíz del proyecto:

2. Levantar contenedores:

3. Ejecutar migraciones:

## Notas
- La base de datos corre dentro de Docker
- Laravel consume variables de entorno inyectadas por Docker
- No se expone MySQL en producción
