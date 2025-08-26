Bienvenido a la sesión de ejercicios de Inteligencia Artificial. En este archivo, te vamos a guiar en la configuración del entorno y la ejecución del primer ejercicio. Puedes ejecutar este ejercicio (y los siguientes) en tu PC o en Google Colab.

## Configuración de Anaconda
El entorno que vamos a utilizar durante este curso es Anaconda.
Descarga e instala conda desde https://www.anaconda.com/.

Abre una terminal (abre el Anaconda Prompt o Anaconda Powershell Prompt en Windows) y crea un entorno utilizando el siguiente comando:

`conda create --name ia python=3.11 -y`

Luego, activa el entorno utilizando el siguiente comando:

`conda activate ia`

Notarás que el nombre del entorno activado actualmente se muestra en la línea de comandos, como:

`(ia) current/working/directory>`

Asegúrate de verificar el nombre del entorno cada vez que ejecutes un comando en la terminal.

Dentro de la terminal, dirígete a la carpeta del ejercicio_01 y continúa con la instalación de los requisitos:

`pip install -r requirements.txt`

¡Ahora estás listo para empezar! Puedes iniciar jupyter notebook directamente, es decir:

`jupyter notebook`

O simplemente utiliza tu IDE preferido para comenzar con el ejercicio.