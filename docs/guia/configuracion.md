# Configuración

## Configuración Inicial

Después de instalar el proyecto es necesario configurar algunas opciones básicas.

## Variables de Entorno

Crea un archivo llamado `.env` en la raíz del proyecto.

Ejemplo de contenido:

```env
PORT=3000
MODE=development
API_URL=https://api.ejemplo.com
```

## Configuración del Editor

Se recomienda utilizar Visual Studio Code junto con las siguientes extensiones:

- Prettier
- ESLint
- Markdown Preview

## Configuración del Puerto

Puedes cambiar el puerto modificando el valor de `PORT`.

Ejemplo:

```env
PORT=8080
```

## Ejecutar el Proyecto

Una vez configurado, inicia el servidor:

```bash
npm run dev
```

## Resultado

Accede desde el navegador a:

```text
http://localhost:3000
```

Si la configuración es correcta, verás la aplicación funcionando.