# Lector Sereno

Lector de textos en el navegador: sube un `.txt`, ajusta el tema y el tamaño de la letra,
y escúchalo en voz alta en español latino.

- **Temas:** Auto, Claro, Papel, Penumbra, Nocturno y Contraste.
- **Tamaño de letra:** de 16 a 38 px.
- **Voz del sistema:** elige sola la mejor voz latina de cada equipo (Paulina en macOS,
  Dalia o Sabina en Windows, Google español de Estados Unidos en Chrome y Android).
- **Voz descargable:** Piper `es_MX-claude-high`. Se descarga una vez (63 MB), queda
  guardada en el navegador y suena idéntica en cualquier plataforma, incluso sin conexión.

Todo ocurre en el navegador: el texto que abres no se envía a ningún servidor.

## Publicar en GitHub Pages

Settings → Pages → Source: *Deploy from a branch* → rama `main`, carpeta `/ (root)`.
En un minuto queda en `https://<usuario>.github.io/<repositorio>/`.

## Uso local

La voz descargable necesita `http://` o `https://`: con doble clic directo (`file://`) el
navegador bloquea la descarga del modelo. En macOS, doble clic en `Abrir Lector.command`
levanta un servidor local y abre el lector.

## Créditos

Voz Piper del proyecto [Rhasspy](https://github.com/rhasspy/piper) (MIT), servida vía
[vits-web](https://github.com/diffusionstudio/vits-web). Tipografías Literata y Archivo.
