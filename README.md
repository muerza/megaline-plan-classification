## 📱 Proyecto: Clasificación de Planes de Megaline

### 🧩 Descripción del proyecto

La compañía móvil **Megaline** no está satisfecha al ver que muchos de sus clientes utilizan planes heredados.  
Quieren desarrollar un modelo que pueda analizar el comportamiento de los clientes y recomendar uno de los nuevos planes de Megaline: **Smart** o **Ultra**.

Tienes acceso a los datos de comportamiento de los suscriptores que ya se han cambiado a los planes nuevos.  
Tu objetivo es **crear un modelo de clasificación** que escoja el plan correcto.

> 🎯 **Umbral de exactitud mínima:** 0.75  
> Dataset: `/datasets/users_behavior.csv`

### Problema del Negocio:
Clientes utilizan problemas heredados.

### Solucion 
Crear un modelo que recomiende a usuarios nuevos a seleccionar el plan correcto para ellos.

### 📊 Descripción de los datos

Cada observación en el dataset contiene información mensual sobre el comportamiento de un usuario.

| Columna | Descripción |
|----------|--------------|
| `calls` | Número de llamadas |
| `minutes` | Duración total de las llamadas (en minutos) |
| `messages` | Número de mensajes de texto |
| `mb_used` | Tráfico de Internet utilizado (en MB) |
| `is_ultra` | Plan actual del mes: Ultra (1) / Smart (0) |

### 📦 librerías 

sklearn
pathlib
matplotlib
numpy
pandas


### Descubrimientos 

### Conclusiones 

### Recomendaciones 
