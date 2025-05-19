# Imagen base de Python
FROM python:3.11-slim

# Crear directorio de trabajo
WORKDIR /app

# Copiar dependencias
COPY requirements.txt .

# Instalar requerimientos
RUN pip install --no-cache-dir -r requirements.txt

# Copiar el código fuente y recursos
COPY app/ ./app/
COPY images/ ./images/

# Exponer el puerto usado por Streamlit
EXPOSE 8501

# Comando por defecto para iniciar la app
CMD ["streamlit", "run", "app/bg_remove.py", "--server.port=8501", "--server.address=0.0.0.0"]