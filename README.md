# Sitio web simple con CI/CD usando GitHub Actions

## Descripción del proyecto

Este proyecto consiste en un sitio web estático sencillo desarrollado con HTML y CSS básico. El objetivo del proyecto es demostrar cómo se puede implementar un flujo de CI/CD (Integración Continua y Despliegue Continuo) utilizando GitHub Actions.

El sitio web contiene una página simple que sirve como ejemplo para mostrar cómo los cambios en el repositorio pueden desplegarse automáticamente mediante un pipeline de automatización.

## Tecnologías utilizadas

- HTML
- CSS
- GitHub
- GitHub Actions
- GitHub Pages

## Flujo de CI/CD implementado

Se configuró un workflow de GitHub Actions para automatizar el despliegue del sitio web. Cada vez que se realiza un cambio en el repositorio y se hace un **push a la rama main**, el pipeline se ejecuta automáticamente.

El workflow realiza las siguientes acciones:

1. Clona el repositorio.
2. Prepara los archivos del sitio web.
3. Publica el sitio automáticamente en GitHub Pages.

De esta manera, cada actualización del proyecto se despliega sin necesidad de hacerlo manualmente.

## Problema que resuelve la automatización

La automatización permite evitar el proceso manual de subir archivos al servidor cada vez que se realiza una modificación en el sitio web. Esto reduce errores humanos, mejora la eficiencia del proceso y permite que las actualizaciones se publiquen de forma rápida y confiable.

## Resultado

Gracias al flujo de CI/CD implementado, el sitio web se publica automáticamente en GitHub Pages cada vez que se actualiza el repositorio.
