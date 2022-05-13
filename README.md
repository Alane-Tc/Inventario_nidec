# Readme
![GitHub last commit](https://img.shields.io/github/last-commit/Alane-Tc/Inventario_nidec?style=for-the-badge) ![GitHub forks](https://img.shields.io/github/forks/Alane-Tc/Inventario_nidec?style=for-the-badge) ![GitHub top language](https://img.shields.io/github/languages/top/Alane-Tc/Inventario_nidec?style=for-the-badge) 

![GitHub Release Date](https://img.shields.io/github/release-date/Alane-Tc/Inventario_nidec?style=for-the-badge)

------------
## 1-Descripción
Nidec al ser una empresa grande, cuenta con diferentes departamentos el cual conforman esta, en la cual el área de IT se encuentra caótica, debido a que no se lleva un control del inventario:
- CPU
- Monitores 
- Laptop 
- Teclado 
- Mouse 




Esto ha generado grandes problemas dentro del área de TI como:
- Perdida de equipos dentro de la empresa  
- Robo de material  
- Perdida de dinero en el área debido a que se tienen que sustituir los aparatos utilizando recursos de la empresa y generando un desbalance en los gastos asignados para el área.  


------------


### 1.1-Solución
Con el fin de disminuir todas estas problemáticas generadas dentro de esta área, como proyecto nos centraremos en el registro del inventario de TI completo, ingresando todo dispositivo nuevo que entre en el área, registrando a quien le fue asignado y datos clave de este, ya que cada uno cuenta con identificador único.

------------


### 1.2-Arquitectura
El sistema esta construido y diseñado en la arquitectura MVC
![](https://github.com/Alane-Tc/Inventario_nidec/blob/main/ss/Arquitectura.png?raw=true)

## 2-Requerimientos
- Es indispensable tener una version de java 8
- Tener instalado XAMPP.

### 2.1-Instalación
1. Tener una versión del JDK superior a la 11.
2. Debemos descargar XAMPP. 
3. Debemos descargar el archivo JAR. 

------------


### Configuración
1. En el programa XAMPP elegir el apartado de Apache y MySQL
![](https://raw.githubusercontent.com/Alane-Tc/Inventario_nidec/901a5dbdabf5233e1f4d277b09b133181e82b112/ss/SS2.PNG)
2. Poner en el navegador `localhost:8080 ` esto los dirigira a PHPMyAdmin
3.  Crear la base de datos y poner los campos requeridos del sistema **OJO** llamar a la base de datos en esta linea de código poner el nombre de la base de datos creada `con=DriverManager.getConnection("jdbc:mysql://localhost/nombre_base_datos","root","");`

------------

### Uso
![](https://github.com/Alane-Tc/Inventario_nidec/blob/main/ss/SS3.PNG?raw=true)
Esta es la interfaz de usuario, en donde podras agragar los productos con su respectivo nombre, marca, modelo, num serie y localizacion. 
En el sistema podras agragar, modificar, eliminar y buscar productos del inventario.
Puedes ver el video de la funcionalidad del sistema
[Video Inventario](https://youtu.be/cvXlAoAaxsE "Video Inventario")

------------

### Contribuciones
Puedes usar el proyecto o tambien puedes mencionarnos mejoras del sistema, ya que esto es una primera version. 
Si deseas clonarlo si asi lo deseas 

------------

## Roadmap
- Estamos trabajando en mejorar la interfaz de usuario
- Correciones de bugs
- Agregar nuevas funcionalidades
