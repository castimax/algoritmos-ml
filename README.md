# Descripción

Este parche introduce un nuevo requerimiento al archivo `requirements.txt` de la rama `ml-supervisado` del repositorio `algoritmos-ml`. El nuevo requerimiento es:

- **Nombre del paquete:** FACILITAR LA INSTALACIÓN
- **Versión:** V 1
- **Motivación:** CARGAR EL GITHUB EN GOOGLE COLAB O SIMILAR

Este parche no presenta incompatibilidades con la versión actual de la rama `ml-supervisado`.

## Prueba

Para probar el parche, puedes seguir estos pasos:

1. Clonar el repositorio `algoritmos-ml` en tu ordenador.
2. Cambiar a la rama `ml-supervisado`.

Aplicar el parche:
git apply patch-1.patch

Instalar los requisitos:
pip install -r requirements.txt

Ejecutar los tests:
pytest


## Implementación

Este parche ha sido implementado por Maximiliano Hdez. S.

## Contacto

Si tienes alguna pregunta o comentario sobre este parche, puedes contactar con el autor a través de:

- **Email:** castimax@gmail.com

## Fecha de creación

- **2024-02-12**

## Licencia

Este parche se distribuye bajo la licencia del repositorio original.
