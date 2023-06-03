# **Reconocimiento facial mediante emociones para registrar el horario de entrada y salida del personal.**

<img src="https://setronics.net/wp-content/uploads/2020/04/biface.gif">

## Grupo 2
- Ricardo Amiel Acuña Villogas
- Enzo Sebastián Gómez Villegas
- Matías Castillo Quincho
- Renzo Alfonso Acervo Correa
- Mateo Espinoza Monti
- Dickson Marcelo Azalde Lazo

## Descripción del proyecto
<p align="justify">
Esta aplicación web se basará en una interfaz pragmática, sencilla de comprender y utilizar. Contaremos con un sistema de reconocimiento facial y asismismo funcionará tanto para imágenes como videos. El uso de deep learning nos ayudará a predecir e identificar los rostros.
</p>


## **Objetivos y características principales**
### Objetivos
<p align="justify">
    Un mejor registro en el horario de nuestro personal será un punto benificioso en la comodidad de ellos. La empresa que evaluaremmos tiene un registro de horario de ingreso y salida a papel, usted firma y registra su horario de entrada y salida en la hoja de trabajo de cada día, con nuestro algoritmo implementado se reducirá eso tiempo con tan solo mostrar tu imagen facial. Además de ello, la interacción entre cliente - aplicación web se plantea ser amigable y productiva para el trabajador.
</p>

### Características
<p align="justify">
    La interfaz de nuestra aplicación web contará con la carga de imágenes faciales, tal cual fuera mostrar un carné de identificación por el cual registrarás el horario de estadía del personal. SQLAlchemy registrará todos las imágenes cargadas en nuestra base de datos con la cual se podrá identificar y darle uso al algoritmo. Todo esto sucederá a tiempo real, las predicciones serán precisas y rápidas para ahorrar el mayor tiempo posible.
</p>


### Visión del proyecto
<p align="justify">
    Buscamos aprovechar a lo máximo el uso de las redes neuronales y así innovar con el algoritmo implementado. De esta manera, poder ofrecer una tecnología muy eficaz a aquellos que la adquieran. El uso de nuestro proyecto será ventajoso en el manejo de registros tanto en asistencia como la fecha de horario y salida.
</p>

### Planificación del proyecto
<p align="justify">
    Este estará divido en 7 puntos distintos, en los cuales se realizará este proyecto:
        1. [Completar]
        2. [Completar]
        3. [Completar]
        4. [Completar]
        5. [Completar]
        6. [Completar]
        7. [Completar]
</p>

## Librerías a aplicar

1. Flask

2. SQLAlchemy

3. UUID

4. TensorFlow

## Despegar Web (Temporal)
<p align="justify">
    
    1. Debemos crear nuestro ambiente virtual para correr en nuestra máquina, instalamos el módulo 'pip install virtualenv'. Luego creamos el entorno desde nuestra terminal 'python3 -m denv env', el nombre de nuestro entorno virtual será env. Finalmente la activamos con el siguiente comando en nuestro terminal 'env\Scripts\Activate'.
    
    2. A continuación por ahora instalamos los módulos correspondientes con el siguiente comando en la terminal 'pip install -r requirements.txt'.
    
    3. Ingresamos a nuestro postgresql por terminal en nuestro VSCODE mediante el comando: 'psql -U postgres'.
    
    4. Creamos nuestra base de datos llamada 'database_db', utilizando el comando 'CREATE DATABASE database_db;', luego conectamos nuestra tabla.
    
    5. Finalmente corremos el programa principal 'flask -app proyecto.py run'
