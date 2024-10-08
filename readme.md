# Task list and ideas

## Tasks

### MPV

- [x] Create a new project in github
- [ ] Crear clase para cada uno de los objetos
  - [ ] Definir la clase `Servicio`
  - [ ] Definir atributos: ID, Descripción, Tiempo aprox, Costo
  - [ ] Agregar métodos para calcular precios adicionales (x50, x100, x500, x1000)
- [ ] Configurar variables de entorno con la api key
  - [ ] Crear archivo `.env`
  - [ ] Configurar la lectura de variables en el script
- [ ] Script para traer los datos de la api en json
  - [ ] Hacer la solicitud HTTP
  - [ ] Manejar errores de conexión
- [ ] Script para volcar los datos en objetos servicio
  - [ ] Parsear el JSON
  - [ ] Crear instancias de la clase `Servicio` para cada dato
- [ ] Determinar servicios para vender
  - [ ] Listar posibles servicios
  - [ ] Filtrar según criterios de venta
- [ ] Script para clasificar precios por servicios
  - [ ] Crear función de clasificación
  - [ ] Implementar lógica para seleccionar 1 o 2 precios por servicio
- [ ] Script para cargar los datos y crear objetos
  - [ ] Leer los datos desde el origen
  - [ ] Crear los objetos correspondientes
- [ ] Parser para llevar a formato csv
  - [ ] Definir el formato del CSV
  - [ ] Implementar la escritura en archivo CSV

### Gestionar pedidos

- [ ] Parser a formato pipe para pedidos
  - [ ] Definir la estructura del parser
  - [ ] Implementar la lógica de conversión
- [ ] Script para cargar pedidos
  - [ ] Leer el archivo en formato pipe
  - [ ] Crear instancias de pedidos según el formato
- [ ] Generar mensaje para el usuario
  - [ ] Definir el contenido del mensaje
  - [ ] Implementar la función de generación de mensajes

### Adicional

- [ ] Calcular los costos desde la tool
  - [ ] Implementar la lógica de cálculo
  - [ ] Adicionar costo de garantía
- [ ] Calcular cantidad de reserva para recargar el servicio
  - [ ] Definir la fórmula de cálculo
  - [ ] Implementar la función de cálculo

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
