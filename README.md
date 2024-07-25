# Laboratorio 1
## Enunciado de la Tarea
### **Objetivo**
Desarrollar una API REST utilizando Spring Boot que se conecte a una base de datos MySQL. La API debe permitir la gestión de un inventario de productos con los siguientes campos: id, name, description, price, y quantity. Además, deben realizar pruebas de la API utilizando Postman y entregar la tarea mediante GitHub Classroom con documentación detallada y capturas de pantalla descriptivas.
### **Requisitos**
#### 1. Configuración del Proyecto:
- **Haber realizado la actividad teórica sobre API y Spring Boot**
- **Haber realizado la demo del video o la del .pdf**
- Utiliza Spring Initializr para generar el proyecto Spring Boot con las dependencias necesarias: Spring Web, Spring Data JPA, Lombok, DevTools y MySQL Driver/PostgreSQL Driver.
- Configura el proyecto para conectarse a una base de datos MySQL local o en la nube. En caso de utilizar la nube optar por PostgreSQL Driver y Render.com
#### 2. Modelo de Datos:
- Crea una entidad `Product` con los siguientes campos:
  - `id` (Long, autogenerado)
  - `name` (String)
  - `description` (String)
  - `price` (double)
  - `quantity` (int)
#### 3. Repositorio:
- Crea un repositorio JPA para la entidad `Product`.
#### 4. Controlador:
- Implementa un controlador REST que permita realizar las siguientes operaciones:
  - Crear un nuevo producto (POST `/products`)
  - Obtener todos los productos (GET `/products`)
  - Obtener un producto por su id (GET `/products/{id}`)
  - Actualizar un producto existente (PUT `/products/{id}`)
  - Eliminar un producto por su id (DELETE `/products/{id}`) 
#### 5. Pruebas con Postman:
- Realiza pruebas de todas las operaciones anteriores utilizando Postman.
- Captura de pantalla de las pruebas realizadas en Postman.
#### 6. Documentación:
- Crea un archivo README.md en el repositorio de GitHub con una descripción detallada del proyecto.
- Incluir instrucciones sobre cómo configurar y ejecutar el proyecto.
- Incluir capturas de pantalla de las pruebas realizadas en Postman.
### Entrega
1. Repositorio en GitHub Classroom:
- Subí el código del proyecto a un repositorio en GitHub Classroom.
- Asegurate de incluir el archivo README.md con la documentación detallada.
- Incluir capturas de pantalla de las pruebas realizadas en Postman.
### Evaluación
La tarea será evaluada con base en los siguientes criterios:
- Correcta implementación de la API REST con Spring Boot.
- Correcta configuración y conexión a la base de datos MySQL/PostgreSQL.
- Funcionamiento correcto de las operaciones CRUD.
- Calidad de las pruebas realizadas con Postman.
- Calidad y claridad de la documentación y las capturas de pantalla.

