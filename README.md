# Orchid test

El propósito de este test el identificar el conocimiento sobre Laravel & Laravel Orchid

# Concepts

## Screens

- Explicar en pocas palabras como funciona el mecanismo de Screens de Laravel Orchid
- Realizar un ejemplo en codigo con un modulo personalizado para aplicar lo anterior explicado
- Sugerencia para el modulo personalizado: crear un modulo de reservaciones (db: foto de usuario que reserva, fecha de creacion de la reservacion, id de la reservacion, recurrencia de la reservacion, usuario que reservo)

## Form elements

- Documentar mediante comentarios en el codigo cada uno de los *Form elements* usados en el anterior modulo personalizado
- ¿Que *Form element* deberia usar para cargar archivos?
- ¿Que *Form element* deberia usar para crear una tabla con con campos modificables?
- ¿Con cuales *Form elements* puedo crear un selector con relaciones?

## Navigation

- Agregar el modulo personalizado a la barra lateral del administrador de contenido
- Agregar los permisos correspondientes para poder acceder al modulo

## Permissions

- Agregar un ejemplo de como serian las validaciones de permisos desde Screens (Aplicarlo)
- Agregar un ejemplo de como serian las validaciones de permisos desde un Middleware (Solo explicarlo mas no intergrarlo de forma que genere conflictos)
- Agregar un ejemplo de como serian las validaciones de permisos desde un Blade (Solo explicarlo mas no integrarlo de forma que genere conflictos)

## Filtration

- Agregar un filtro por cada uno de los campos anteriormente mensionados fecha de creacion, id de la reservacion, recurrencia de la reservacion y usuario que reservo

## Attachments

- Agregar un campo que permita agregar 1 foto al modulo de reservas
- Agregar un campo que permita agregar multiples fotos al modulo de reservas

## Notifications

- Usar la notificacion tipo Alert para notificar al usuario en sesion que se a creado/editado/eliminado un registro
- User la notificacion tipo Toast para validar los campos del formulario
- Usar la notificacion tipo Dashboard para almacenar las notificaciones en el modulo por defecto que trae Orchid

# Layouts

## Rows

- Agregar los filtros del modulo justo antes de la tabla de lista de registros

## Table

- Listar los datos del modulo en una tabla

## Chart

- Apoyarse de datos fake para construir un grafico de cantidad de reservas diarias
