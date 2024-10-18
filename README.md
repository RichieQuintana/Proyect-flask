# Proyecto Flask

Aplicación web con Flask que incluye registro de usuarios, inicio de sesión y gestión CRUD de datos.

## Características

- **Registro/Iniciar Sesión**: Usuarios pueden registrarse e iniciar sesión.
- **CRUD**: Crear, leer, actualizar y eliminar usuarios.
- **SQLAlchemy**: Manejo de base de datos.
- **Flask-Migrate**: Migraciones de base de datos.

## Instalación

1. Clona el repositorio:
    ```bash
    git clone https://github.com/RichieQuintana/Proyect-flask.git
    cd Proyect-flask
    ```

2. Crea un entorno virtual y actívalo:
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # Linux/Mac
    venv\Scripts\activate     # Windows
    ```

3. Instala dependencias:
    ```bash
    pip install -r requirements.txt
    ```

4. Configura la base de datos:
    ```bash
    flask db init
    flask db migrate
    flask db upgrade
    ```

5. Ejecuta la aplicación:
    ```bash
    flask run
    ```

## Despliegue

La aplicación puede desplegarse en PythonAnywhere, Railway, o Azure.

commit.2 (sin crud): Solo se transfirio lo que la carpeta crud hacia la carpeta principal.
