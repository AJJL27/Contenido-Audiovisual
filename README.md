# Contenido-Audiovisual
Este proyecto es un sistema de gestión de contenido audiovisual que permite registrar, listar y guardar información sobre películas, series, documentales, actores y más, utilizando principios de Código Limpio, SOLID y el patrón MVC.

Características
Manejo de Archivos
Lee y guarda datos en un archivo CSV para mantener persistencia de la información.
Código Limpio
Métodos claros y pequeños, sin duplicación de código.
Principios SOLID
Clases y métodos diseñados para ser extensibles, reutilizables y de fácil mantenimiento.
Patrón MVC
Separación de responsabilidades entre el modelo, la vista y el controlador.
Pruebas Unitarias
Implementadas con JUnit para garantizar la calidad del código.
Requisitos del Sistema
Java 11 o superior.
Herramienta de compilación (como IntelliJ IDEA, Eclipse, o cualquier IDE compatible con Java).
JUnit 5 (para las pruebas).
Instalación y Ejecución
Clonar el repositorio:

bash
Copiar código
git clone https://github.com/tuUsuario/tuRepositorio.git
cd tuRepositorio
Compilar el proyecto: Si usas un IDE, simplemente abre el proyecto y compílalo.
Desde la terminal:

bash
Copiar código
javac -d bin -sourcepath src src/VistaContenido.java
Ejecutar el programa:

bash
Copiar código
java -cp bin VistaContenido
Correr pruebas unitarias (opcional): Si tienes configurado JUnit:

bash
Copiar código
java -cp .:junit-platform-console-standalone-1.9.3.jar org.junit.platform.console.ConsoleLauncher --scan-classpath
Uso del Programa
Menú Principal
Al ejecutar el programa, aparecerán las siguientes opciones:

Mostrar Películas: Lista las películas registradas en el sistema.
Agregar Película: Permite registrar una nueva película.
Guardar y Salir: Guarda los datos en el archivo CSV y cierra el programa.
Archivo CSV
El archivo contenido.csv es donde se guarda toda la información. Puedes editarlo manualmente si necesitas agregar o modificar datos de forma rápida.

Estructura del Proyecto
src/

ArchivoContenido.java - Manejo de archivos CSV.
Pelicula.java - Clase representativa de una película.
ControladorContenido.java - Lógica del sistema.
VistaContenido.java - Interfaz de usuario basada en consola.
test/

PeliculaTest.java - Pruebas unitarias para la clase Película.
Principios Aplicados
SRP (Single Responsibility): Cada clase tiene una única responsabilidad.
OCP (Open/Closed): El sistema está diseñado para ser extensible sin modificar las clases existentes.
DIP (Dependency Inversion): Las dependencias están abstraídas y se inyectan donde es necesario.

Contribuciones
Si deseas contribuir, sigue estos pasos:

Haz un fork del repositorio.
Crea una rama con tu característica (git checkout -b feature/nueva-funcionalidad).
Haz commit de tus cambios (git commit -m 'Agrego nueva funcionalidad').
Haz push a la rama (git push origin feature/nueva-funcionalidad).
Crea un Pull Request.
