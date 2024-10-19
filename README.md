Curso Python backend
"""
from main.py
Instalacion completa de Fastapi: pip install "fastapi[all]"
Manual fastapi: https://fastapi.tiangolo.com/#run-it
RECORDAR ESTAR DENTRO DE LA CARPETA QUE CONTIENE EL ARCHIVO main.py
Para acceder al servidor local ingresar por la terminal: fastapi dev main.py (tambien sirve: uvicorn main:app --reload)
Para detener el servicor local Ctrl + C
url local http://127.0.0.1:8000
Documentacion oficial: https://fastapi.tiangolo.com/es
Documentacion (docs) de las funciones FastApi creadas hasta el momento(Swagger UI) http://127.0.0.1:8000/docs
Documentacion con Redocly: http://127.0.0.1:8000/redoc (cualquiera de las dos funciona y me gusta mas esta)
Extencion de VSCode Thunder Client
"""
imagenes: La siguiente linea de código va en main
app.mount("/static", StaticFiles(directory="static"), name="static") # Forma de exponer Archivos estaticos como imagenes
# ejemplo: http://127.0.0.1:8000/static/images/Leon.jpg
MAIN SOLO NECESITA http://127.0.0.1:8000 PARA PODER VERSE
"""
IMPORTANTE: *** OJO ***
1° En la terminal ubicarnos en la carpeta: cd FastApi (para este ejemplo)
Acceder al servidor local, ingresar por la terminal: fastapi dev users.py (tambien sirve: uvicorn users:app --reload)
En Thunder Client: 
  Para agregar un usuario con post http://127.0.0.1:8000/user/ a traves de un JSON en la pestaña JSON.
    La respuesta (Response) es null, pero se agrega y se puede comprobar así:
  Para ver la lista de usuarios http://127.0.0.1:8000/users/
  
Documentación con Swegger: http://127.0.0.1:8000/docs
Documentación con Redocly: http://127.0.0.1:8000/redoc
"""
"""
Pasos para subir repositorios a github
git init
git remote add origin https://github.com/MarioPerezV/PythonBackend.git
git status
git add . # o enviar la direccion del directorio
git commit -m "configurando repositorio remoto github"
git status
  debido al error
  git config --global user.mail "marioalejandropv"@gmail.com
  git config --global user.name "MarioPerezV"
git add .
git commit -m "configurando repositorio remoto despues del error2"
git push -u origin master

"""