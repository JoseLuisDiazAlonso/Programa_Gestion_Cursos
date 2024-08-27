# Programa de Gestión de Cursos

Bienvenido al proyecto de gestión de Cursos desarrollado en Java utilizando el framework SpringBoot. Esta aplicación permite realizar operaciones CRUD (Crear, Leer, Actualizar y Eliminar) sobre una lista de cursos almacenados en una base de datos
MYSQL.

## Características

- Agregar cursos nuevos
- Ver la lista de cursos disponibles
- Editar la información de cursos existentes.
- Eliminar cursos de la base de datos.
  
## 🛠 Tecnologías y Herramientas

- **Java 11** o superior
- **Spring Boot**
- **MySQL**
- **Maven**

## Prerrequisitos

Antes de empezar, asegurate de tener instalado lo siguiente:

  - **Java 11** o superior
  - **Maven**
  - **MySQL**

## 📦 Instalación
  1. **Clona el repositorio**
     
     git clone https://github.com/tu_usuario/tu_repositorio.git

     cd tu_repositorio

  3. **Configura la base de datos**
     
     Crea una base de datos en MySQL
     CREATE DATABASE gestion_cursos;

     Luego, configura las credenciales de acceso a MySQL en el archivo
     'src/main/resources/application.properties'

    spring.datasource.url=jdbc:mysql://localhost:3306/gestion_cursos
    spring.datasource.username=tu_usuario
    spring.datasource.password=tu_contraseña

    spring.jpa.hibernate.ddl-auto=update
    spring.jpa.show-sql=true


  3. **Construye el Proyecto**
     
     Ejecuta el siguiente comando para compilar el proyecto

      mvn clean install

     
  5. **Ejecuta la aplicación**

     Después de la compilación, ejecuta la aplicación con:

     mvn spring-boot:run

     La aplicación estará disponible en 'http://localhost:8080'

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor, sigue las siguientes pautas para contribuir:

1. **Haz un Fork del repositorio**:
   Haz una copia del repositorio en tu cuenta de GitHub para trabajar en él de manera independiente.

2. **Crea una nueva rama**:
   Cambia a una nueva rama para realizar tus cambios. Puedes hacerlo con el siguiente comando:

   ```bash
   git checkout -b nombre-rama

3. **Realiza tus cambios y haz commit**:

   Realiza las modificaciones necesarias en tu copia del proyecto y luego guarda los cambios con un commit.

   git commit -m 'Añadir nueva característica'

4. **Haz Push a la rama**:

   git push origin nombre-rama
   
4. **Abre el Proyecto en tu navegador**:

   Abre el archivo 'index.html' en tu navegador para ver la página de inicio
