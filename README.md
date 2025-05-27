# Documentación Técnica del Sistema - Hotel CAVA
Producto 2: Desarrollo de Software, Conexión con Base de Datos y Documentación de Código

**Integrantes del equipo (en orden alfabético):**
1. Hernández Santiesteban Luis Eduardo
2. Lizárraga Meza Julia Isabel
3. Lorena Ríos Méndez
4. Rivera Alvarado Jesús Ernesto
5. Víctor Ramírez Méndez 

# Introducción
Este documento describe el desarrollo técnico del sistema de gestión hotelera Hotel CAVA. Incluye el diseño de la interfaz, conexión con base de datos, autenticación de usuarios y funcionalidad CRUD para clientes. El objetivo es proporcionar un sistema funcional que facilite la administración de clientes y reservas en un entorno hotelero.

## Resumen del sistema 
El sistema está compuesto por una interfaz web, un backend desarrollado con Node.js y Express, y una base de datos MongoDB. Se incluye autenticación de usuarios, registro, login y un CRUD completo de clientes. La interfaz está basada en un diseño de Figma y es responsiva
Para ello se generara una base de datos que almacenara toda la información necesaria y los programas correspondientes para el registro y procesamiento de los datos, así como la obtención de los reportes correspondientes. 	
Contará con un formulario de inicio de sesión y el menú con las opciones requeridas por el sistema y usuario.										
Este sistema incluirá la disponibilidad de habitaciones, pecios así como la gestión de cancelación y modificación de la reserva.									
Se registrara la entrada y salida de los clientes, acelerando el proceso y reducir la carga administrativa y mejorando la experiencia del cliente.								
El cliente podrá facturar los servicios prestados en el hotel 														
Contará con la gestión de inventarios de productos y servicios dentro del hotel 												
El sistema proporcionara informes y análisis detallados sobre el rendimiento del hotel, incluyendo ocupación, ingresos, tendencias de reserva, entre otros indicadores clave					
.

### Descripcion del Proyecto
El proyecto a realizar consitira en desarrollar una aplicacion de escritorio para llevar el registro y control eficiente de reservas, Check-in/Check-out. Gestion de habitaciones , facturacion y pagos. 
Control de inventarion con el proposito de obtener informacion precisa y oportuna y asi poder brindar un mejor servicio a sus clientes.
#### Requisitos  Funcionales 

  ![image](https://github.com/user-attachments/assets/de4cf5ad-52b6-4355-90b5-8dc38b7e31df)



  No Funcionales 
  Escalabilidad: El sistema debe ser capaz de manejar un aumento en el volumen de reservas y operaciones, especialmente en temporada alta.
  Seguridad:     Debe asegurar la protección de la información sensible de los clientes 
  Usabilidad:    La interfaz debe ser intuitiva t fácil de usar para los empleados del hotel, sin importar nivel técnico 
  Fiabilidad:    Debe ser confiable y estar disponible en todo momento, sin caídas frecuentes que afecten la operación del hotel
  Rendimiento:   Debe ser rápido, tiempos de respuesta cortos incluso durante picos de alta demanda
  Mantenimiento y soporte: Debe ser fácil de mantener y actualizar, con un equipo de soporte disponible para resolver problemas técnicos 



  Tecnicos: Node.js v18+
            Express.js
            MongoDB
            HTML5,CSS3 y JavaScript.
            

  De arquitectura del sistema 
            El sistema se estructura en dos partes principales: 
  1.- Frontend: Interfaz grafica contrusida conHTML, CSS y JS.
  2.- Backend:  Servidor con Express.js que expone una API REST conectada a Mongodb.

  

  ![image](https://github.com/user-attachments/assets/175c4349-fc4f-423b-98de-566f0c216de3)

  
##### Instalacion 
1. Clona el repositorio o extrae el archivo ZIP.
2. Abre una terminal en la carpeta /backend.
3. Ejecuta `npm install` para instalar dependencias.
4. Crea un archivo `.env` con la variable MONGO_URI.
5. Ejecuta `npm start` para iniciar el servidor.
   
###### Uso del Sistema
- Visita `http://localhost:3000/login.html` para iniciar sesión.
- Usa `register.html` para crear una cuenta.
- Accede a `clientes.html` para gestionar registros de clientes.


Base de datos
Se utiliza MongoDB. El esquema principal es `Cliente`, con campos como:
- nombre (String)
- correo (String)
- teléfono (String)
- dirección (String





 


**Texto en negrilla**
_Texto_
