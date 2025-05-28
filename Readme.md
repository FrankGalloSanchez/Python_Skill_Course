# FastAPI Demo

Este es un proyecto de demostración utilizando FastAPI.

## Requisitos

- Python 3.12.5  
- FastAPI  
- Uvicorn

## Instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu-usuario/tu-repositorio.git
   cd tu-repositorio
2. Crea un entorno virtual:
   ```bash
   python -m venv fastapi-demo

3. Activa el entorno virtual:
- En Windowns
   ```bash
   fastapi-demo\Scripts\activate
- En macOS/Linux:
   ```bash
   source fastapi-demo/bin/activate

4. Instala las dependencias:
   ```bash
   pip install -r requirements.txt

5. Ejecuta la aplicación:
   ```bash
   uvicorn src.main:app --reload

## Uso
Una vez que la aplicación esté en ejecución, puedes acceder a la documentación interactiva de la API en:

- Swagger UI:
   ```bash
  http://localhost:8000/docs
- Redoc :
   ```bash
   http://localhost:8000/redoc
