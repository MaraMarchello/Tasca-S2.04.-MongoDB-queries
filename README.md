# Tasca-S2.04.-MongoDB-queries
# Consultas de Restaurantes en MongoDB

## 📄 Descripción - Ejercicio

Este proyecto contiene una colección de consultas MongoDB para analizar datos de restaurantes. Las consultas demuestran varias operaciones de MongoDB, incluyendo filtrado, proyección, ordenación y el uso de operadores como $and, $or, $in y $elemMatch. Los ejercicios cubren una amplia gama de complejidad de consultas, desde la recuperación básica de documentos hasta el filtrado condicional avanzado.

## 💻 Tecnologías utilizadas

- MongoDB
- JSON

## 📋 REQUISITOS

- MongoDB (versión 4.4 o superior recomendada)
- MongoDB Shell o MongoDB Compass para la ejecución de consultas
- Conocimiento básico del lenguaje de consulta de MongoDB

## 🛠️ Instalación

1. Clonar este repositorio:
   ```
   git clone <url-del-repositorio>
   ```

2. Instalar MongoDB si aún no lo has hecho:
   - [MongoDB Community Edition](https://www.mongodb.com/try/download/community)
   - Sigue las instrucciones de instalación para tu sistema operativo

3. Importar el conjunto de datos de restaurantes:
   ```
   mongoimport --db restaurant --collection restaurants --file restaurants/restaurants.json --jsonArray
   ```

## ▶️ Implementación

1. Iniciar el servicio de MongoDB:
   ```
   mongod
   ```

2. Conectarse al shell de MongoDB:
   ```
   mongo
   ```

3. Seleccionar la base de datos de restaurantes:
   ```
   use restaurant
   ```

4. Ejecutar las consultas del archivo MongoDB_queries.txt en el shell de MongoDB

## 🌐 DESPLIEGUE

Para desplegar este proyecto en un entorno de producción:

1. Configurar un servidor MongoDB con las configuraciones de seguridad adecuadas
2. Configurar autenticación y autorización
3. Configurar copias de seguridad para tus datos
4. Considerar el uso de MongoDB Atlas para el despliegue en la nube

## 🤝 Contribución

Si deseas contribuir a este proyecto:

1. Haz un fork del repositorio
2. Crea una nueva rama para tu funcionalidad
3. Añade tus consultas o mejoras
4. Envía una solicitud de extracción con una descripción detallada de tus cambios
