# Proyecto de Consultas SQL

## Descripción del Proyecto
Este proyecto consiste en el análisis y manipulación de una base de datos PostgreSQL de un sistema de alquiler de películas. Se han desarrollado múltiples consultas SQL para extraer información relevante y realizar análisis de datos.

## Estructura del Proyecto
Proyecto-Consultas-SQL/
BBDD/BBDD_Proyecto.sql -->    **El script original de la base de datos**
Esquema/Esquema.png -->       **El esquema de la base de datos realizado en pgAdmin4**
Proyecto.sql -->              **Archivo con todas las consultas realizadas**
Readme.md -->                 **Archivo con todos los pasos seguidos durante el proyecto y el informe de mi análisis.**

## Estructura de la Base de Datos
La base de datos está compuesta por las siguientes tablas principales:

- **actor**: Almacena información de actores
- **category**: Categorías de películas
- **film**: Información de películas
- **film_actor**: Relación entre películas y actores
- **film_category**: Relación entre películas y categorías
- **language**: Idiomas disponibles
- **inventory**: Inventario de películas
- **rental**: Registro de alquileres
- **customer**: Información de clientes
- **payment**: Registro de pagos
- **staff**: Información de empleados
- **store**: Información de tiendas
- **address**: Direcciones
- **city**: Ciudades
- **country**: Países

## Análisis de Resultados

### Patrones de Alquiler
- Se identificaron patrones de alquiler por categoría
- Se analizó la duración promedio de alquileres
- Se determinaron las películas más populares

### Comportamiento de Clientes
- Se identificaron clientes frecuentes
- Se analizaron patrones de gasto
- Se estudiaron preferencias por categoría

### Inventario y Gestión
- Se evaluó la distribución del inventario
- Se analizó la rotación de películas
- Se identificaron necesidades de stock

## Conclusiones
1. La base de datos está bien estructurada y permite análisis detallados
2. Las consultas desarrolladas cubren aspectos operativos y analíticos
3. Se pueden obtener insights valiosos sobre el negocio
4. El sistema permite un seguimiento efectivo de inventario y alquileres

## Herramientas Utilizadas
- PostgreSQL como sistema de gestión de base de datos
- SQL para consultas y análisis de datos
- Herramientas de visualización en pgAdmin4 para el esquema de la base de datos
