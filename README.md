# ProyectoCI
Proyecto de Comercialización de productos via WEB.

## Integración Continua (CI)

Este proyecto cuenta con integración continua utilizando Jenkins.

El pipeline está definido en el archivo [Jenkinsfile](./Jenkinsfile) y se encarga de:

- Clonar el repositorio
- Levantar contenedores con Docker Compose
- Instalar dependencias
- Ejecutar migraciones y pruebas
- Apagar los contenedores al finalizar

Para más información, consultar el Jenkinsfile directamente.
