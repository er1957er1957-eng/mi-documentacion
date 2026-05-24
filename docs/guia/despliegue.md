# Despliegue

## Introducción

El despliegue consiste en publicar la aplicación o documentación en Internet para que otras personas puedan acceder a ella.

## Generar la Versión Final

Antes de desplegar, crea la versión optimizada del proyecto:

```bash
npm run build
```

## Subir Cambios a GitHub

Guarda todos los cambios con Git:

```bash
git add .
git commit -m "Versión lista para despliegue"
git push origin main
```

## Despliegue con GitHub Pages

GitHub Pages permite publicar páginas web directamente desde un repositorio.

Pasos:

1. Entrar en el repositorio de GitHub.
2. Abrir la pestaña **Settings**.
3. Ir a **Pages**.
4. Seleccionar la rama `main`.
5. Guardar los cambios.

## Verificación

Tras unos minutos, la documentación estará disponible en una URL pública.

## Ventajas del Despliegue Automático

- Actualizaciones rápidas
- Acceso desde cualquier lugar
- Fácil mantenimiento
- Integración con GitHub