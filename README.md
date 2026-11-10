# Programacion-de-redes

# Inventario de red

## Datos del alumno
- Nombre: Miguel Angel Garcia
- Matrícula: 125053642

## Descripción
API desarrollada con FastAPI para consultar un inventario de dispositivos de red.

## Instalación

1. Crear el entorno virtual:
   `python -m venv venv`

2. Activar el entorno virtual:
   `venv\Scripts\activate`

3. Instalar dependencias:
   `pip install -r requirements.txt`

## Ejecución

Ejecutar el siguiente comando:

`fastapi dev main.py`

## Rutas disponibles

- GET `/`: Comprueba el estado de la API.
- GET `/dispositivos`: Lista todos los dispositivos.
- GET `/dispositivos/{nombre}`: Busca un dispositivo por nombre.
