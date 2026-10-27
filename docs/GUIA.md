# Guia de Resolucion: Laboratorio 03 Tienda TECSUP

Este documento explica paso a paso como configurar y solucionar los errores del proyecto de la Tienda TECSUP para el Laboratorio 03.

## Herramientas Necesarias

Para trabajar en este proyecto, asegurate de tener:
* Visual Studio Code
* Git instalado en tu computadora
* Cuenta activa en GitHub para hacer el Fork

## Instrucciones de Correccion

Sigue estos pasos en orden para iniciar:
1. Haz un Fork del repositorio del docente y clonalo en tu terminal.
2. Abre `script.js` y arregla la multiplicacion en la funcion calcularTotal.
3. Abre `index.html` y corrige el nombre del archivo CSS en la etiqueta link.

### Tareas del Proyecto

- [x] Reportar los errores mediante Issues
- [x] Corregir la logica de javascript y el enlace CSS
- [ ] Publicar los Pull Requests para el docente

## Archivos Principales

| Archivo | Funcion Principal |
|---|---|
| index.html | Estructura principal de la tabla de productos |
| estilos.css | Colores del curso y diseno visual |
| script.js | Logica matematica que calcula el total a pagar |

## Comandos Clave

Para subir tus correcciones a tu fork de GitHub, asegurate de revisar primero con `git status`.

```bash
git add .
git commit -m "Corrige el calculo del total del carrito"
git push origin fix-total-carrito