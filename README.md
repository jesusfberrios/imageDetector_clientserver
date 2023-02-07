# imageDetector_clientserver
## Author: Jesús Berríos

### ***This work's objective is to create a client-server infrastructure for image detection***

To begin with, files must be downloaded to a folder, and it must be reachable from Anaconda terminal

```
.
└── pd-2021-lab (this folder)
    ├── images (includes the images)
    ├── server.ipynb (Server code)
    ├── client_en.ipynb (Client code)
    └── requirements.txt (Python dependencies)
```
 
## Previous steps using Conda
 
### Pre-requisites: Having [conda](https://docs.conda.io/en/latest/) installed in your computer.
 
Conda will be used to build a new virtual environment.

### 1. Creating the Virtual Environment

After having conda installed, the first step will be to create a new environment, this can be done executing the following command:
  
```bash
conda create --name pd-2021-lab python=3.7
```
 
Next, it must be activated by executing:
 
```bash
conda activate pd-2021-lab
```
 
All the work to be done will be in this environment; therefore, when editing these files, the environment pd-2021-lab should be active.


### 2. Installing dependencies 
 
Execite the following command, please ensure that it is executed inside the `pd-2021-lab` folder.

```bash
pip install -r requirements.txt
```

This execution may take some minutes... 
 
### 3. Starting Jupyter Lab

```bash
jupyter lab
```


--
**This work was based on the unit 1 from the course (https://www.coursera.org/learn/introduction-to-machine-learning-in-production/home/welcome), as well as in the class "Desarrollo de Productos de Datos" from Prof. Alonso Astroza from UDD**