# Usa la imagen oficial de OpenJDK como base
FROM openjdk:11-jdk-slim

# Configura el directorio de trabajo en el contenedor
WORKDIR /app

# Copia el archivo Java al contenedor
COPY prueba.java .

# Compila el archivo Java
RUN javac prueba.java

# Define el comando por defecto para ejecutar el programa
CMD ["java", "prueba"]