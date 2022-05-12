#Readme



##1-Descripción
Nidec al ser una empresa grande, cuenta con diferentes departamentos el cual conforman esta, en la cual el área de IT se encuentra caótica, debido a que no se lleva un control del inventario:
- CPU
- Monitores 
- Laptop 
- Teclado 
- Mouse 

------------


Esto ha generado grandes problemas dentro del área de TI como:
- Perdida de equipos dentro de la empresa  
- Robo de material  
- Perdida de dinero en el área debido a que se tienen que sustituir los aparatos utilizando recursos de la empresa y generando un desbalance en los gastos asignados para el área.  


------------


##1.1-Solución
Con el fin de disminuir todas estas problemáticas generadas dentro de esta área, como proyecto nos centraremos en el registro del inventario de TI completo, ingresando todo dispositivo nuevo que entre en el área, registrando a quien le fue asignado y datos clave de este, ya que cada uno cuenta con identificador único.

------------


##1.2-Arquitectura
El sistema esta construido y diseñado en la arquitectura MVC
![](https://github.com/Alane-Tc/Inventario_nidec/blob/main/ss/Arquitectura.png?raw=true)

##2-Requerimientos
- Es indispensable tener una version de java 8
- Tener instalado XAMPP.

##2.1-Instalación
1. Tener una versión del JDK superior a la 11.
2. Debemos descargar XAMPP. 
3. Debemos descargar el archivo JAR. 

##Configuración
1. Una vez descargado XAMPP configuraremos XAMPP seleccionando solo el módulo de Apache y MySQL.
2. Iniciaremos el Módulo de Apache y MySQL dentro de XAMPP. 
3. Abriremos en el navegador localhost:8080 
4. Nos iremos a PHPMyAdmin. 
5. Crearemos una Base de Datos con los campos necesarios. 
6. Copiaremos los datos de referencia de la Base de Datos. 
7. En nuestro editor de código abiremos el archivo dentro de Modelo/Conexión y cambiaremos el nombre se la base de datos por la que se ha creado  en:
`con=DriverManager.getConnection("jdbc:mysql://localhost:3306/bd_ejemplo", "root","");`

##Uso
Si eres el usuario final se te asigno un periodo de capacitación para el uso del sistema.
- Si deseas agregar un cliente nuevo, tendrás que llenar los campos del primer bloque, cuando lo termines de llenar tendrás que dar clic en agregar.
- Si deseas actualizar o editar a un cliente, debes seleccionar primero a quien quieres editar, después darás clic al botón editar, y cambiaras los datos que necesites, cuando termines darás al botón de OK para que se guarden tus cambios.
- Si deseas borrar a algún cliente, deberás seleccionar la fina que quieras borrar, después darás clic en el botón de borrar.

##Contribuciones
Si deseas contribuir al proyecto no hay problema, estamos abiertos a recibir contribuciones. 
1. Puedes clonar el proyecto.
2. Crear una rama que se llame Develop.
3. Y es aquí donde puedes experimentar, crear, borrar, modificar el proyecto.
4. Cuando ya estes listo puedes solicitar realizar un pull request.
5. El equipo de desarrollo lo analizara y tomara la decisión si implementarlo o agregarte comentarios si algo está mal.

##Roadmap
En un futuro cercano se tiene esperado y contemplado la implementación de nuevas funciones y más características como:
- Mejorar la interfaz gráfica.
- Agregar más interfaces para realizar cada acción.
- Mejoras de diseño.
- Correcciones de bugs y errores.
