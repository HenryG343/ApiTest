-Comando para iniciar proyecto de laravel
php artisan serve

-Comando para poblar la base
php artisan db:seed

-Comandos para realizar las consultas desde postman
Login
POST http://127.0.0.1:8000/api/auth/login
Se deben llenar los campos email y password

Registro
POST http://127.0.0.1:8000/api/auth/register
Se deben llenar los campos email, password, nombre, telefono, username y nacimiento

Usuarios
Create
POST http://127.0.0.1:8000/api/user
Se deben llenar los campos email, password, nombre, telefono, username y nacimiento
Read
GET http://127.0.0.1:8000/api/user
Update
PUT http://127.0.0.1:8000/api/user/{id}
Se deben llenar los campos email, password, nombre, telefono, username y nacimiento
Delete
DELETE http://127.0.0.1:8000/api/user/{id}

Productos
POST http://127.0.0.1:8000/api/productos
Se deben llenar los campos nombre, cantidad, precio, descripcion e imagen
Read
GET http://127.0.0.1:8000/api/productos
Update
PUT http://127.0.0.1:8000/api/productos/{id}
Se deben llenar los campos nombre, cantidad, precio, descripcion e imagen
Delete
DELETE http://127.0.0.1:8000/api/productos/{id}
Buscar por nombre
GET http://127.0.0.1:8000/api/productos/buscarNombre/{nombre}
Buscar por SKU
GET http://127.0.0.1:8000/api/productos/buscarSKU/{SKU}