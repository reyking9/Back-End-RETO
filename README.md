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
    "cedula": "1350352777",
    "nombres": "Rey Cruz",
    "apellidos": "Mera Macias",
    "email": "reycruzmeramacias@gmail.com",
    "fechanacimiento": "03/09/1995",
    "direcciondomicilio": "Portoviejo",
    "telefonomovil": "0991768974",
    "estadovacuna": false,
    "tipovacuna": "Pfizer",
    "fechavacuna": "07/08/2021",
    "numerodosis": 2
  }
]
