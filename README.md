# streamlit_test
Streamlit test project 

## Crear un repositorio (streamlit_test)
Agregar un README.md y archivo requirements.txt (siguiente)

### Creación de un archivo requirements.txt
*El contenido del archivo debe ser:*
-pandas
-scipy
-streamlit

## Clonar repo en carpeta local
git clone ......

### Instalar librerías si no están instaladas
-pip install streamlit   #instalar streamlit
-pip install pandas   #instalar pandas
-pip install scipy

## Comando para ejecutar app en entorno local
*streamlit run app.py* (Sobre el mismo directorio en dónde esta el proyecto)

### Desplegar app en Render.com
*Para desplegar tu aplicación web en Render, primero crea una cuenta de Render vinculada a tu cuenta de Github. Al crear una cuenta de Render, elige la opción "Github" y sigue los pasos de registro. Luego, crea un nuevo servicio web*

Elige tu poyecto de GitHub

En la sección Build Command, agregamos pip install --upgrade pip && pip install -r requirements.txt.
En la sección Start Command, agregamos streamlit run app.py

*Selecciona la opción gratuita (Free)* y luego, al final de la página, presiona el botón “Deploy Web Service” (Lanzar servicio web): 

Después, tardará unos minutos y debería empezar a desplegarse.

Valida accediendo desde la liga que te proporciona Render.com



