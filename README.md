# Carrusel legible

Pega el texto de un post de LinkedIn y descarga un carrusel en PDF con letra grande y buen contraste. Todo pasa en el navegador: el texto no se envía a ningún sitio.

Web: https://jrebate.github.io/carrusel_accesible/

## Qué hace

- La primera idea es la portada. Cada párrafo va en su diapositiva (o se juntan en modo compacto).
- Tamaño de letra mínimo fijo (46, 54 o 62 px sobre 1080 px). Si el texto no cabe, pasa a la siguiente diapositiva.
- Cuatro estilos con contraste de 10:1 o más. Formato vertical 4:5 o cuadrado.
- Pasa las letras «de fantasía» (negritas Unicode copiadas de generadores) a texto normal y las dibuja en negrita de verdad.
- Deja fuera las líneas de hashtags y avisa de enlaces y diapositivas con demasiadas palabras.
- El PDF lleva el texto invisible bajo cada imagen, para que se pueda buscar y copiar.
- Diapositiva final con cierre, firma y la marca «Hecho con Carrusel legible».

## Medición

GoatCounter (jrebate), eventos con prefijo `carrusel-`: `carrusel-descargar-pdf`, `carrusel-ejemplo`, `carrusel-copiar-texto`, `carrusel-pro-me-interesa`, `carrusel-pro-quitar-marca`, `carrusel-pro-marca-propia`, `carrusel-pro-guardar-estilo`, `carrusel-kofi-pro`, `carrusel-kofi-pie`, `carrusel-contacto-email`, `carrusel-error-pdf`.

## Técnica

HTML estático sin compilación. Usa [jsPDF 2.5.1](https://github.com/parallax/jsPDF) (licencia MIT, copia en `vendor/`) y el CSS base de CentaurUX.

Los avisos son orientativos. No está afiliado a LinkedIn.

Creado por Jorge Rebate Serrano · Licencia CC BY 4.0 (el código de jsPDF mantiene su licencia MIT).
