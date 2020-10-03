# AREP-Taller7

#

# Pre-requisitos
  -Java SE Development Kit 8
  -Java SE Runtime Environment 8
  -Apache Maven.
  -Docker
  -AWS

# Instalación
Copiaremos la aplicación en nuestra maquina local con el siguiente comando
```sh
$ git clone https://github.com/jose-gome/AREP-Funcionalidad-Taller7.git
$ git clone https://github.com/jose-gome/AREP-Login-Taller7.git
 ```
Ahora compilaremos y empaquetaremos con el siguiente comando
```sh
$ mvn package
```
Para ejecuta la aplicación:
```sh
$ mvn exec:java -Dexec.mainClass="edu.escuelaing.arem.ASE.app.AppWeb"
```
# APlicacion
[Aplicación](https://ec2-3-90-218-220.compute-1.amazonaws.com:5000/) en funcionamiento encontraremos un login las credenciales son:
```sh
  prueba@gmail.com
  1234
```
[video](https://youtu.be/hDWAA8E_8Rs) de pruebas echas al login 

# Construido con
  - [Maven](https://maven.apache.org/) - Dependency Management
  - [Heroku](https://cli-auth.heroku.com/) plataforma como servicio de computación en la Nube que soporta distintos lenguajes de programación
  - [Docker](https://www.docker.com/)
  - [AWS](https://www.awseducate.com/) 
# Autores
  - José Luis Gómez Camacho - Estudiante de la Escuela Colombiana De Ingeniería Julio Garavito
# Licencia
Este proyecto está licenciado bajo la GNU v3.0 - ver el archivo LICENSE.md para más detalles
