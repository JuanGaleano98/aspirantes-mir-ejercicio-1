1. Abrir la consola e imprimir la ubicación actual.
$ pwd

2. Crear una carpeta llamada ejercicios en el escritorio desde la consola, si no estas en la ruta del escritorio, muevete a ella.
$ mkdir ejercicios

3. Cambiar la ubicación a la nueva carpeta que crearon.
$ cd ejercicios

4. Abrir la carpeta con VSCode.
$ code

5. En VSCode crear una carpeta ejercicio1.
Opción de crear nueva carpeta en VSCode

6. Crear un archivo llamado README.md (vacío) dentro de la carpeta ejercicio1.
Opción de crear nuevo archivo en VSCode

7. Configurar nombre e email globalmente en git.
$ git config --global user.name "Juan Galeano"
$ git config --globla user.email juanpablog1998@gmail.com
$ git config -l

8. Inicializar el repositorio de git desde la línea de comandos desde la carpeta ejercicios.
$ git init

9. Crear un primer commit con el mensaje “Versión Inicial”.
$ cd ejercicio1
$ git add README.md
$ git commit -m "Versión Inicial"
$ git log

10. Agregar al README.md los comandos que ejecutaron en cada paso.
Se agregan los comandos utilizados en el ejercicio.