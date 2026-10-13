# Sitio del PRIGEPP

Sitio informativo del Programa Regional de Formación en Género y Políticas Públicas (PRIGEPP), Área Género, Sociedad y Políticas, FLACSO Argentina.

## Cómo publicarlo en GitHub Pages

1. Sube **todos** los archivos de esta carpeta a la raíz del repositorio (se pueden arrastrar juntos en «Add file → Upload files»). No hay subcarpetas.
2. En el repositorio: **Settings → Pages → Branch: main / (root)** y guarda.
3. El archivo `.nojekyll` (oculto) debe estar subido: evita que GitHub procese los archivos.

## Qué contiene

- `index.html` (Inicio), `el-prigepp.html`, `equipo.html`, `maestria.html`, `diploma-genero-justicia.html`, `admisiones.html`, `publicaciones.html`, `tesis.html`, `conferencias.html`, `contacto.html`.
- `tesis.json`: datos del repositorio de tesis (lo usa el buscador de `tesis.html`; debe estar junto a las páginas).
- Los logos van incluidos dentro de cada página: no hay archivos de imagen aparte.

## Diseño

- Paleta: azul FLACSO #172E4C dominante (encabezado, portadas, botones, bloques destacados), azul noche #0E1D33 (barra superior, menús desplegables, pie), amarillo #F1BC16 solo como acento (página activa, viñeta de antetítulo, botón sobre azul), neutros #F1F4F8 y #46566D.
- Tipografía: Archivo (Google Fonts), expandida para títulos y cifras, ancho normal para el texto.

## Contenido pendiente

Los textos marcados como **[COMPLETAR: …]** son datos que faltan confirmar (por ejemplo, la fecha de la próxima convocatoria).

## Cómo regenerar el sitio

Desde la carpeta del generador: `python3 src/build.py --final <carpeta>` (textos en `src/paginas/`, estilos en `src/plantilla/`).
