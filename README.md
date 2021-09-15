# Reto de kruger:
## El reto consiste en crear un inventario de vacunación para empleados utilizando JAVA y Spring Boot como BACK-END

## En primer lugar se necesita tener un editor de código, en este caso usaremos Apache NetBeans:
### https://netbeans.apache.org
## También se necesitará tener instalado java, el jdk:
## https://www.java.com/es/download/help/develop.html
### Para iniciar el proyecto desde Apache NetBeans, bastara con ejecutarlo desde el botón RUN
### El programa se ejecutará en 
## http://localhost:8080
### Se utilizan las siguientes rutas para la API:
#### Get (todos los usuarios)
#### http://localhost:8080/api/test/usuarios 
#### ------------------------------------------------------------------------
#### Get (búsqueda por id)
#### http://localhost:8080/api/test/usuarios/+{id}
#### ------------------------------------------------------------------------
#### Delete
#### http://localhost:8080/api/test/usuarios/+{id}
#### ------------------------------------------------------------------------
#### Post
#### http://localhost:8080/api/test/usuarios/+{id}
#### ------------------------------------------------------------------------
#### Put
#### http://localhost:8080/api/test/usuarios/+{id}
#### ------------------------------------------------------------------------
#### Datos de ejemplo en Json:
[
  {
    "id": 1,
    "cedula": "130000000",
    "nombres": "Rey Cruz",
    "apellidos": "Mera Macias",
    "email": "rey@gmail.com",
    "fechanacimiento": "12/10/1995",
    "direcciondomicilio": "Portoviejo",
    "telefonomovil": "0998888444",
    "estadovacuna": false,
    "tipovacuna": "Pfizer",
    "fechavacuna": "07/08/2021",
    "numerodosis": 2
  }
]
