# imageDetector_clientserver

# DESARROLLO DE PROYECTOS Y PRODUCTOS DE DATOS
# Tarea 1
## Autor: Jesús Berríos
## Prof. Alonso Astroza

**Este Trabajo está inspirado en la unidad 1 del curso [Introduction to Machine Learning in Production (DeepLearning.AI)](https://www.coursera.org/learn/introduction-to-machine-learning-in-production/home/welcome) y en la clase de Desarrollo de Productos de Datos del Prof. Alonso Astroza de la UDD**

***El objetivo de este trabajo es expandir lo realizado en el Laboratorio de Implementación de un Modelo de Machine Learning visto en clase (Producto de Datos)***

Para comenzar, se deben descargar los archivos a una carpeta y en el terminal de Anaconda llegar a ese directorio.

```
.
└── pd-2021-lab (este directorio)
    ├── images (incluye las imágenes a utilizar)
    ├── server.ipynb (Código Server)
    ├── client.ipynb (Código Cliente)
    └── requirements.txt (dependencias de Python)
```
 
 
## Pasos previos usando Conda
 
### Prerequisito: Tener [conda](https://docs.conda.io/en/latest/) instalado en tu computador.
 
Vamos a usar Conda para construir un entorno virtual nuevo.
 
### 1. Creando el entorno virtual (Virtual Environment)
 
Asumiremos que tenemos instalado conda. El primer paso es crear un nuevo enviroment para desarrollar. Para crear uno usando Python 3.7 debemos ejecutar el siguiente comando:
 
```bash
conda create --name pd-2021-lab python=3.7
```
 
Luego debemos activarlo usando el comando:
 
```bash
conda activate pd-2021-lab
```
 
Todo el trabajo que realicemos con este código será en este entorno. Así que al trabajarcon estos archivos siempre tiene que estar activo el ambiente pd-2021-lab.
 
### 2. Instalando las dependencias usando PIP 
 
Antes de seguir, verifica que en el terminal de Anaconda estés dentro del directorio `pd-2021-lab`, el cual incluye el archivo `requirements.txt`. Este archivo enlista todas las dependencias necesarias y podemos usarlo para instalarlas todas:
 
```bash
pip install -r requirements.txt
```
 
Este comando puede demorar un rato dependiendo de la velocidad del computador y la de la conexión a Internet. Una vez que termine ya está listo todo para comenzar una sesión de Jupyter Lab o Notebook.
 
### 3. Iniciando Jupyter Lab
 
Jupyter lab debería haber quedado instalado en el paso anterior, así que basta con escribir:

```bash
jupyter lab
```
