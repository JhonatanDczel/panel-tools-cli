# Task list and ideas

## Tasks

### MPV

- [x] Create a new project in github
- [ ] Obtener lista de servicios y precios en formato csv
- [ ] Crear clase para cada uno de los objetos
- [ ] Hacer script para traer la lista de servicios
- [ ] Script para clasificar precios por servicios
  - [ ] Seleccionar 1 u 2 precios por servicio
- [ ] Script para cargar los datos y crear objetos
- [ ] Parser para llevar a formato csv

### Gestionar pedidos

- [ ] Parser a formato pipe para pedidos
- [ ] Script para cargar pedidos
- [ ] Generar mensaje para el usuario

### Adicional

- [ ] Calcular los costos desde la tool
  - [ ] Adicionar costo de garantia
- [ ] Calcular cantidad de reserva para recargar el servicio

## Modelos

### Objeto servicio

- ID Servicio
- Descripción
- Tiempo aprox
- Costo

> Adicional:

- Precio x50
- Precio x100
- Precio x500
- Precio x1000
- Ganancia x50, x100, x500, x1000

### Formato pipe para pedido

Pedidos en masa de la forma:

```txt
id_servicio|enlace|cantidad
```
