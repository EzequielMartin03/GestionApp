Requisitos - GestionApp
Introducción
El cliente necesita un sistema para gestionar las ventas de productos, que permita registrar, visualizar y mantener un control de dichas ventas. Además, se debe generar recibos automáticamente al cargar una venta.

Requisitos funcionales
Gestión de Ventas
Visualización de Ventas
Sistema de Login
Gestión de Usuarios
Gestión de Categorías
Generación de Recibos de Ventas
Detalle requisitos funcionales
REQ 1: Gestión de Ventas
El sistema debe permitir guardar, editar y eliminar ventas.
Los datos requeridos para cada venta son:
Marca
Tipo (e.g., celular, computadora, etc.)
Modelo
Color
Precio
IMEI/Número de serie
Cliente (nombre)
Fecha de venta

REQ 2: Visualización de Ventas
El cliente necesita visualizar las ventas en una tabla con las siguientes características:
Paginador: para manejar grandes cantidades de registros.
Filtro por nombre de cliente: debe permitir buscar ventas por cliente.
Las ventas filtradas deben mostrarse en la misma tabla principal.







REQ 3: Sistema de Login
El sistema debe contar con una pantalla de inicio de sesión.
Los campos requeridos para el login son:
Email
Clave (contraseña)
La autenticación debe validar los datos ingresados para permitir el acceso al sistema.

REQ 4: Gestión de Usuarios
El sistema debe incluir un módulo de gestión de usuarios con las siguientes funcionalidades:
Crear usuarios.
Eliminar usuarios.
Blanquear contraseñas (restablecer al estado inicial o generar una nueva contraseña).

REQ 5: Gestión de Categorías
El sistema debe incluir un módulo para gestionar categorías de productos.
Crear categorías.
Modificar categorías.
Eliminar categorías.

REQ 6: Generación de Recibos de Ventas
El sistema debe generar un recibo automático cada vez que se registre una venta.
El recibo debe incluir los siguientes datos:
Número de recibo único.
Información de la venta (Marca, Tipo, Modelo, Precio, etc.).
Datos del cliente (nombre o identificación si aplica).
Fecha de emisión del recibo.
El recibo debe ser exportable en formato PDF y estar disponible para impresión.


