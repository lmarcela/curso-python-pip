# Game Project

Para correr el juego debes seguir las siguientes instrucciones en la terminal:

```sh
cd game
python3 main.py
```


# App Project

```sh
git clone
cd app
python3 -m venv env
source env/bin/activate
pip3 install -r requirements.txt
python3 main.py
```

# Web server Project

```sh
git clone
cd web-server
python3 -m venv env
source env/bin/activate
pip3 install -r requirements.txt
uvicorn main:app --reload // Para correr como servidor web
python3 main.py // Para ejecutar como script
deactivate // Para salir del entorno virtual
```