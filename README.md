# Hola Mundo CI

Integración continua con GitHub Actions.

- `hola.js`: programa Hola Mundo en JavaScript (`node hola.js`).
- `.github/workflows/alerta.yml`: al subir código a la rama `main`, ejecuta el
  programa y envía una notificación a [ntfy.sh/devops-itla](https://ntfy.sh/devops-itla).

## Cómo probarlo

Haz cualquier cambio, súbelo a `main` y revisa la notificación en https://ntfy.sh/devops-itla.
