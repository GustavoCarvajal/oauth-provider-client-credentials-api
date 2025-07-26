# OAuth Provider - Client Credentials Grant (MuleSoft)

Este proyecto implementa un proveedor de OAuth 2.0 utilizando el flujo de autorización Client Credentials. Fue desarrollado en MuleSoft 4.x usando Anypoint Studio y sigue las mejores prácticas de seguridad y gestión de identidad.

## Características
- Token endpoint (`/oauth/token`)
- Validación de client_id y client_secret
- Emisión de tokens JWT
- Configuración dinámica desde archivos `.properties`

## Estructura
- `/src/main/mule`: contiene los flujos principales del proveedor OAuth
- `/src/main/resources`: archivos de configuración
- `/src/test`: pruebas unitarias o mocks

## Uso
1. Clona el repositorio
2. Importa en Anypoint Studio como proyecto Maven
3. Configura `client_id` y `client_secret` en `secure.properties`
4. Despliega y prueba con Postman o curl
