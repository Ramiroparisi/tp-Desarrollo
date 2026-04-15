# Propuesta TP Desarrollo de Software

### Integrante
* 51035 - Parisi Ramiro

### Repositorios
* [Repo]

## Tema
### Descripción
Software de gestión de una concesionaria de autos que vende vehículos propios, donde los clientes pueden señarlos.

### Modelo
<img width="806" height="461" alt="Concesionaria (1)" src="https://github.com/user-attachments/assets/13ca7efc-7199-4783-b045-de38d169b522" />


## Alcance Funcional 

### Alcance Mínimo
Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Marca|
|CRUD dependiente|1. CRUD Modelo {depende de} CRUD Marca<br>2. CRUD Vehículo {depende de} CRUD Modelo|
|Listado<br>+<br>detalle| 1. Listado de vehículos filtrado por marca, modelo, año desde, año hasta, precio desde, precio hasta => detalle CRUD Vehículo <br> |
|CUU/Epic|1. Cargar un vehículo|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Usuario|
|Listado | 1. Listado de empleados <br> 2. Listado de reservas
|CUU/Epic|1. Login y registro de usuario <br>2. Realizar reserva de auto|


### Alcance Adicional Voluntario


|Req|Detalle|
|:-|:-|
|Otros|1. Envío de recordatorio de reserva por whatsapp <br> 2. Integración de Mercado Pago para las reservas|
