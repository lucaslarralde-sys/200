ARCHIVOS QUE DEBÉS SUBIR / REEMPLAZAR

1) Video del héroe
   - public/video/hero.mp4   (MP4 H.264 + AAC)

2) Íconos de ÁREAS (SVG) — se cargan automáticamente
   Carpeta: public/icons/iconos/
   Usados actualmente por cada área:
   - Aguas →   public/icons/iconos/gota-white.svg   (en bandas AZULES)
   - Efluentes urbanos → public/icons/iconos/cloaca-gray.svg  (en bandas BLANCAS; se verá NEGRO por CSS)
   - Efluentes industriales y bioenergía → public/icons/iconos/fabrica-white.svg (en bandas VERDES)
   - Aire y gases → public/icons/iconos/aire-gray.svg   (en bandas BLANCAS; se verá NEGRO por CSS)
   - Equipamiento electromecánico → public/icons/iconos/agitador-white.svg (en bandas AZULES)

   Si preferís íconos negros nativos para las bandas blancas, también podés subir:
   - cloaca-black.svg, aire-black.svg
   (En ese caso avisame y actualizo las rutas en el HTML para usar -black.svg directo en lugar de filtro CSS.)

3) Imágenes de ÁREAS (JPG)
   Carpeta: public/images/areas/
   Nombres requeridos (4 por área):
   - aguas-1.jpg, aguas-2.jpg, aguas-3.jpg, aguas-4.jpg
   - efluentes-urbanos-1.jpg, efluentes-urbanos-2.jpg, efluentes-urbanos-3.jpg, efluentes-urbanos-4.jpg
   - efluentes-industriales-y-bioenergia-1.jpg, ...-2.jpg, ...-3.jpg, ...-4.jpg
   - aire-1.jpg, aire-2.jpg, aire-3.jpg, aire-4.jpg
   - equipos-1.jpg, equipos-2.jpg, equipos-3.jpg, equipos-4.jpg

4) Textos extendidos (HTML) para “Leer más…”
   Carpeta: public/textos/
   - more-aguas.html
   - more-efluentes-urbanos.html
   - more-efluentes-industriales-y-bioenergia.html
   - more-aire-y-gases.html
   - more-equipamiento-electromecanico.html

NOTAS
- Los colores de las bandas usan el AZUL y el VERDE extraídos del logo de Ecowatt:
  * AZUL: #0b457d
  * VERDE: #5fa879
- En bandas BLANCAS, los íconos se ven NEGROS automáticamente (se aplica filtro CSS sobre la versión gris).
- Estructura y layout no se modificaron, sólo estilos y mapeos de recursos.