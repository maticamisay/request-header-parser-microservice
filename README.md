# Microservicio de Análisis de Encabezado de Solicitud

Este proyecto es una implementación del desafío de freeCodeCamp de construir un microservicio de análisis de encabezado de solicitud. Acepta una solicitud y devuelve un objeto JSON que contiene información relevante extraída del encabezado de la solicitud.

## Cómo utilizar el servicio

Para utilizar el servicio, realiza una solicitud GET a la ruta `/api/whoami`. No necesitas proporcionar ningún parámetro.

El servicio te responderá con un objeto JSON que contiene:

- Tu dirección IP en la clave `ipaddress`.
- Tu idioma preferido en la clave `language`.
- Tu software (información del navegador y del sistema operativo) en la clave `software`.

## Cómo instalar y ejecutar el proyecto localmente

1. Clona este repositorio.
2. Navega hasta el directorio del repositorio en tu terminal.
3. Ejecuta `npm install` para instalar las dependencias del proyecto.
4. Ejecuta `npm start` para iniciar el servidor.
5. Abre un navegador web y visita `http://localhost:3000/api/whoami`.

## Tecnologías utilizadas

Este proyecto utiliza Node.js y Express para el servidor y el enrutamiento.

## Licencia

Este proyecto está licenciado bajo los términos de la licencia MIT. Puedes ver el archivo `LICENSE` para más detalles.

## Contacto

Si tienes alguna pregunta sobre este proyecto, no dudes en abrir un issue o enviarme un correo electrónico. Estoy siempre dispuesto a ayudar.

## Reconocimientos

Este proyecto fue creado como parte de las certificaciones de freeCodeCamp. Gracias a freeCodeCamp por proporcionar la plantilla del proyecto y el conjunto de pruebas.