# SprintBoot - Configuración Inicial

En esta breve guía cubriremos paso a paso el setup inicial de su entorno de desarrollo para el uso del framework SprintBoot. 

En esta guía se estará usando como IDE de desarrollo **Visual Studio Code**  es un editor ligero, fácil y potente, pero usted es libre de usar el editor/IDE de su preferencia. Aquí les deje un enlace en el que podrán ver diferentes opciones para desarrollar con SprintBoot  [https://spring.io/tools](https://spring.io/tools)

**Quick Start** 

También les comparto algunos playlist interesante que servirán para iniciarse o repasar sobre este poderoso framework de desarrollo SprintBoot.

**Español**
[https://www.youtube.com/watch?v=ltA-mIYyxhY&list=PLvimn1Ins-40wR4PC-YtTQ5TKt3vRrVwl](https://www.youtube.com/watch?v=ltA-mIYyxhY&list=PLvimn1Ins-40wR4PC-YtTQ5TKt3vRrVwl)

**Ingles**
[https://www.youtube.com/watch?v=msXL2oDexqw&list=RDQMKl_q0GrCYUI&start_radio=1](https://www.youtube.com/watch?v=msXL2oDexqw&list=RDQMKl_q0GrCYUI&start_radio=1) 

# Instalaciones

El lenguaje de programación utilizado para desarrollar con Sprint Boot es Java por lo que vamos a necesitar el **Java Runtime Enviroment** necesitaremos al menos  la **versión 8 (o 1.8)** del llamado **Java Development Kit** (JDK) está disponible tanto para Linux como para Windows y macOS, por lo que nos permite **elegir libremente** el **sistema operativo** que queramos utilizar.

Como herramienta de compilación, pudes utilizar **Maven** (a partir de 3.3) o **Gradle** (a partir de 4.4).

 Como IDE de desarrollo **Visual Studio Code**  es un editor ligero, fácil y potente.
 
**Links de descargas**
- [OpenJDK/JDK 8 ](https://www.oracle.com/java/technologies/javase-jdk8-downloads.html)
- [Apache Maven](https://maven.apache.org/)
 - [Visual Studio Code](https://code.visualstudio.com/)

## Extensiones para visual studio code

Las extenciones necesarias para poder desarrollar con Sprint Boot usando visual studio code son:

- [Spring Boot Tools](https://marketplace.visualstudio.com/items?itemName=Pivotal.vscode-spring-boot)
- [Spring Initializr Java Support](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-spring-initializr)
- [Sprint Boot Dashboard](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-spring-boot-dashboard)
- [Java Extension pack](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack)

## Generar Aplicación Sprint Boot

Pasos para generar una aplicación en Sprint Boot en visual studio code.

Ya instaladas la extensiones necesarias , abra la **Paleta de comandos** de visual studio code y escriba `Spring Initializr`para comenzar a generar un proyecto Maven o Gradle.

En el asistente seguir los siguientes pasos:

- Seleccionar -> Generate a Maven Project
- Seleccionar -> Java
- Escriba el GroupId que usaras para tu aplicación Ej: **com.example**
- Escriba el ArtifacId que usaras para tu aplicación.
- Selecciona la versión estable de Sprint Boot que usaras (siempre saldra por defecto)
- Selecciona las dependecias necesarias para una configuración inicial (Sprint Boot DevTools, Sprint Web, Sprint Boot Actuator) presiona Enter.
- Selecciona la ubicacion en Disco donde se guardara el projecto que sera generado.
- Luego abre la carpeta donde se encuentra tu projecto.

Para correr nuestra aplicación una de las extenciones que instalamos llamada **Sprint Boot Dashboard** nos habilita en el explorador de objeto una utilidad que reconocera nuestra aplicacion de sprint boot y tiene las opciones para iniciar, detener y abrir en el navegador nuestra aplicación.

Tambien se pueden dirigir a la clase Main de nuestra aplicación Java y la extensión que instalamos nos habilitara encima de la clase Main las opciones **Run | Debug** presionamos **Run** y nuestra aplicación iniciara.

Podemos usar tambien la linea de comando siguiente:
````
mvn spring-boot:run
````

Nuestra aplicación inicia por defecto en el puerto 8080 y podemos ver si esta arriba http://localhost:8080

## Colaboradores

- Junior Sánchez

