# juanparraga.es

Currículum personal de Juan Párraga Arroyo. Sitio estático, sin dependencias
ni proceso de compilación.

## Contenido

| Archivo | Qué es |
|---|---|
| `index.html` | La web del currículum. Autocontenido: estilos, fuentes y scripts van dentro. |
| `Juan-Parraga-Arroyo-CV.pdf` | Versión A4 de dos páginas, enlazada desde los botones de descarga. |
| `CNAME` | Dominio personalizado. Lo lee GitHub Pages; no se toca. |
| `robots.txt` | Impide que el PDF se indexe. La web usa `noindex` en su propia cabecera. |

## Publicar un cambio

1. Edita el archivo en VS Code.
2. Revisa el resultado abriendo `index.html` en el navegador.
3. Confirma y sube:

   ```bash
   git add .
   git commit -m "Describe el cambio"
   git push
   ```

GitHub Pages republica el sitio en menos de un minuto.

## Visibilidad

El sitio es accesible para cualquiera que tenga el enlace, pero no aparece en
buscadores: `index.html` incluye `<meta name="robots" content="noindex, nofollow">`.
Para hacerlo visible en Google, basta con quitar esa línea y publicar el cambio.
Publicado en https://juanparraga.es