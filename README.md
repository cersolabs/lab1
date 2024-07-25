# Laboratorio 1
## Enunciado de la Tarea
### **Objetivo**
Desarrollar una API REST utilizando Spring Boot que se conecte a una base de datos MySQL. La API debe permitir la gestión de un inventario de productos con los siguientes campos: id, name, description, price, y quantity. Además, deben realizar pruebas de la API utilizando Postman y entregar la tarea mediante GitHub Classroom con documentación detallada y capturas de pantalla descriptivas.
### **Requisitos**
#### 1. Configuración del Proyecto:
- Utiliza Spring Initializr para generar el proyecto Spring Boot con las dependencias necesarias: Spring Web, Spring Data JPA, Lombok, DevTools y MySQL Driver/PostgreSQL Driver.
- Configura el proyecto para conectarse a una base de datos MySQL local o en la nube. En caso de utilizar la nuve optar por PostgreSQL Driver y Render.com
#### 2. Modelo de Datos:
- Crea una entidad `Product` con los siguientes campos:
  - id (Long, autogenerado)
  - name (String)
  - description (String)
  - price (double)
  - quantity (int)
