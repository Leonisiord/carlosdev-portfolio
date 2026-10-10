# carlosdev · Portfolio de diseño web

Portfolio de una sola página donde presento mis webs para negocios pequeños y freelancers de Gran Canaria.

**Web en vivo:** https://carlosdev-web.netlify.app

## Qué incluye
- Galería con cuatro proyectos: dos demos completas hechas desde cero y dos plantillas.
- Servicios, precios, proceso de trabajo y preguntas frecuentes.
- Formulario de contacto y páginas legales (aviso legal, privacidad, cookies).

## Proyectos enlazados
| Proyecto | Tipo | Repositorio |
|---|---|---|
| Mala Tinta (estudio de tatuajes) | Demo completa | [demo-mala-tinta](https://github.com/Leonisiord/demo-mala-tinta) |
| Casa Migas (panadería) | Demo completa | [demo-casa-migas](https://github.com/Leonisiord/demo-casa-migas) |
| Salón (peluquería y estética) | Plantilla | [plantilla-salon](https://github.com/Leonisiord/plantilla-salon) |
| Restaurante (bares y cafeterías) | Plantilla | [plantilla-restaurante](https://github.com/Leonisiord/plantilla-restaurante) |

## Tecnología
- HTML, CSS y JavaScript sin frameworks ni paso de compilación.
- Diseño móvil primero.
- Fuentes alojadas en el propio sitio (`fonts/`) e imágenes en WebP (`img/`).
- `_headers` con cabeceras de seguridad y caché, compatible con Netlify y Cloudflare Pages.

## Estructura
```
index.html    página principal
legal.html    aviso legal, privacidad y cookies
fonts/        tipografías en woff2
img/          capturas de los proyectos
_headers      cabeceras HTTP
```

## Desplegar
No hay nada que compilar: se publica la raíz del repositorio tal cual.
En Cloudflare Pages: framework *None*, comando de build vacío y directorio de salida `/`.
