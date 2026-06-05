# Publicar en Vercel

## Carpeta a subir

Subi esta carpeta completa:

`outputs`

Tiene:

- `index.html`
- `assets/`
- logos e imagenes
- `vercel.json` con headers de seguridad

## Opcion 1: subir con GitHub

1. Entrar a [https://vercel.com](https://vercel.com)
2. Crear cuenta o iniciar sesion
3. Crear un repo en GitHub
4. Subir el contenido de `outputs`
5. En Vercel, elegir `Add New...` -> `Project`
6. Importar ese repo
7. Deploy automatico

## Opcion 2: subir con Vercel CLI

1. Instalar Node.js
2. Abrir una terminal dentro de `outputs`
3. Ejecutar `npm i -g vercel`
4. Ejecutar `vercel`
5. Seguir las preguntas del asistente

## Dominio

Despues del deploy:

1. Abrir el proyecto en Vercel
2. Ir a `Settings` -> `Domains`
3. Agregar tu dominio
4. Seguir los DNS que te muestre Vercel

## Seguridad ya incluida

`vercel.json` ya deja configurado:

- HTTPS/TLS en Vercel
- `Content-Security-Policy`
- `X-Frame-Options`
- `X-Content-Type-Options`
- `Referrer-Policy`
- `Permissions-Policy`
- `Strict-Transport-Security`

## Nota

La pagina usa Google Fonts y una imagen externa de Unsplash en una seccion. Eso ya esta contemplado en la politica de seguridad actual.
