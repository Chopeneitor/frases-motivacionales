# Página Motivacional Interactiva

Una página web simple con frases motivadoras y colores de fondo cambiantes.

## Cómo usarla con Docker

1. Abre una terminal en esta carpeta.
2. Escribe estos comandos:

```bash
docker build -t frases-motivacionales .
docker run -d -p 8080:80 frases-motivacionales
