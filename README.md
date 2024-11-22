# Aplicación Web Serverless con AWS

Este proyecto es el resultado de seguir el tutorial oficial de AWS sobre cómo construir una aplicación web serverless usando los servicios de AWS. En este proyecto se integran diferentes servicios de AWS para crear una solución funcional basada en la nube.

## Descripción del Proyecto

El objetivo fue construir una aplicación web completamente serverless utilizando los siguientes servicios de AWS:

- AWS Lambda: Para manejar la lógica del backend mediante funciones sin servidor.
- Amazon API Gateway: Para exponer las funciones Lambda a través de una API REST.
- Amazon S3: Para alojar los archivos estáticos de la aplicación web.
- Amazon DynamoDB: Para manejar el almacenamiento de datos.
- Amazon Cognito: Para gestionar la autenticación de usuarios.

## Pasos Realizados

A continuación, se detallan los módulos completados del tutorial:

1. Configuración Inicial:
   - Clonar repositorio: git clone https://git-codecommit.us-east-1.amazonaws.com/v1/repos/wildrydes-site
   - Creación un bucket en Amazon S3 para almacenar los archivos estáticos de la aplicación web.
   - Subir los archivos HTML, CSS y JavaScript al bucket de S3.
![image](https://github.com/user-attachments/assets/1f77a37b-ff24-490b-be3e-834829bbc314)

3. Backend con AWS Lambda y API Gateway:
   - Implementar funciones Lambda para manejar las solicitudes del usuario y procesar los datos.
   - Configurar Amazon API Gateway para exponer las funciones Lambda mediante endpoints HTTP.
![image](https://github.com/user-attachments/assets/362f4bd7-91d0-46c5-9d2f-82a278cdddbc)
![image](https://github.com/user-attachments/assets/41b496ce-cd23-4944-8826-2ffeafb9dd6f)

4. Base de Datos con DynamoDB:
   - Configurar una tabla en DynamoDB para almacenar la información de la aplicación.
   - Implementar las operaciones de lectura y escritura desde Lambda hacia DynamoDB.
![image](https://github.com/user-attachments/assets/1ce40a70-0c7b-45a5-96d9-6dc06293daab)
![image](https://github.com/user-attachments/assets/6f30e442-0312-4639-827a-6ced9d14d927)

5. Autenticación con Amazon Cognito:
   - Configurar un grupo de usuarios en Cognito para manejar la autenticación.
   - Agregar funcionalidades de inicio de sesión y registro en la aplicación web.
![image](https://github.com/user-attachments/assets/6af6b612-35f5-4867-b112-a38f30cb302d)

6. Integración de Todo el Sistema:
   - Probar la aplicación para asegurarme de que todos los servicios estaban correctamente integrados.
   - Realizar ajustes finales para optimizar la funcionalidad de la aplicación.
![image](https://github.com/user-attachments/assets/fd5aa206-61eb-4eba-b730-5aad47f9f0a2)
![image](https://github.com/user-attachments/assets/908d6f9a-fe82-457f-accd-19b526b7151f)

## Cómo Ejecutar Este Proyecto

1. Clona este repositorio:
   ```bash
   git clone https://github.com/viviana222601/WebAppAwsCli.git
   cd WebAppAwsCli
