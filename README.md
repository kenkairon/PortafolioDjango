# PortafolioDjango
Educativo y de Aprendizaje Personal

---
## Tabla de Contenidos
- [Tecnologías](#Tecnologías)
- [Configuración Inicial](#configuración-Inicial)
- [Creación del Modelo](#creación-del-modelo)
---
# Tecnologías
- Django: Framework web en Python.
- SQLite:
--- 
# Configuración Inicial 
1. Entorno virtual 
    ```bash 
    python -m venv venv

2. Activar el entorno virtual
    ```bash 
    venv\Scripts\activate

3. Instalar Django
    ```bash 
    pip install django 

4. Guardamos dependencias
    ```bash
    pip freeze > requirements.txt 
    
5. Actualizamos el pip 
    ```bash
    python.exe -m pip install --upgrade pip

6. Crear el proyecto de django portafolio
    ```bash 
    django-admin startproject portafolio

7. Ingresamos al proyecto 
    ```bash 
    cd portafolio

8. creao una rama
    ```bash 
    git branch developer/cevasquez

9. Ejecutar el commit
    ```bash 
   git commit -m "Configuración del Proyecto"

10. lo subo a mi rama
    ```bash 
    git push origin developer/cevasquez

11. Creo la app  AuthApp
    ```bash 
    python manage.py startapp AuthApp

12. portafolio/settings.py
    ```bash
   
    INSTALLED_APPS = [
        'django.contrib.admin',
        'django.contrib.auth',
        'django.contrib.contenttypes',
        'django.contrib.sessions',
        'django.contrib.messages',
        'django.contrib.staticfiles',
        'AuthApp',
    ]

12. lo subo a mi rama
    ```bash 
    git add .
    git commit -m "Creación de la App AuthApp"
    git push origin developer/cevasquez

