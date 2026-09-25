CARPESANOS v21 · PUBLIC READY
================================

DESTINO RECOMENDADO
https://viandavisual.github.io/carpesanos/

CÓMO PUBLICAR EN viandavisual.github.io
---------------------------------------
1. Crea dentro del repositorio una carpeta llamada:
   carpesanos

2. Sube DENTRO de esa carpeta el contenido de este paquete:
   - index.html
   - manifest.webmanifest
   - sw.js
   - icon-192.png
   - icon-512.png
   - icon-source.png
   - carpeta assets/

3. La estructura final debe quedar:
   /carpesanos/index.html
   /carpesanos/manifest.webmanifest
   /carpesanos/sw.js
   /carpesanos/icon-192.png
   /carpesanos/icon-512.png
   /carpesanos/assets/materials/...

4. No subas carpesanos-v21.html a esa carpeta como página principal.
   Ese archivo standalone se entrega solo como copia de conveniencia.

5. Publica los cambios en la rama que use GitHub Pages.
   La app quedará disponible en:
   https://viandavisual.github.io/carpesanos/

NOTAS
-----
- La PWA está configurada con id /carpesanos/, start_url ./ y scope ./.
- El Service Worker usa rutas relativas compatibles con GitHub Pages.
- Los archivos del USER permanecen locales. CARPESANOS no incluye una función
  para subir sus documentos a un servidor de CARPESANOS.
- El backup JSON guarda la configuración, pero no los archivos del USER ni
  los permisos de acceso a carpetas del sistema.
- Para la mejor experiencia con carpetas locales se recomienda Chrome o Edge
  de escritorio.
