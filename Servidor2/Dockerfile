# Utilizamos una imgaen de python
FROM python:3.9 

# Establecer el directorio de tranajo dentro del contenedor
WORKDIR /servidor

# Copiar todos los archivos desde el hosta al directorio 
COPY . . 

# Instalar las dependencias requeridas
RUN pip install flask

# Ecponer puerto del contenedor
EXPOSE 5001

# Comando para ejecutar la aplicacion 
CMD ["python","app.py"] 