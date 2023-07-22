### Fernando Iovanni Ochoa Marin

# Primer paso

Para la instalacion es necesario `npm install` y `php artisan migrate:fresh --seed` y crear la base de datos que va en mysql

###  Observaciones Generales
- Creacion de CRUD de un control de usuarios en el cual super usuario 'admin@admin.com' es el unico que puede configurar el crud y el usuario solo puede ver algun post que añada, se agrego JWT para crear tokens de sesion.
- El super usuario  puede crear permisos/roles a los usuarios y ver usuarios
- Se creo una interfaz para tener un control de inserciones de datos a nivel visual

