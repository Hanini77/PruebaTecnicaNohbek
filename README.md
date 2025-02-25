# PruebaTecnicaNohbek
Prueba técnica para ser becaria arquitecta de software en Nohbek

# El flujo de información es el siguiente:
- El cliente envía una petición HTTP a API Gateway.
- API Gateway redirige la solicitud a una AWS Lambda Function.
- Lambda procesa la solicitud y realiza una operación en DynamoDB.
- Lambda devuelve la respuesta a API Gateway, que la reenvía al cliente.

# Elementos clave de mi diagrama
- Cliente (Navegador o App Móvil)
- API Gateway → Maneja la autenticación y redirige peticiones.
- Lambda Functions → Procesa la lógica del negocio.
- DynamoDB → Base de datos.
- Flechas de flujo de datos para representar la interacción entre los componentes.

https://github.com/nohbek/tech-internship-test/tree/main/arquitecta-software/docs
