# Asado Medieval · Halloween 2026 🏰🔥

Landing page para el **Asado Medieval de Halloween**.

## Datos del evento
- **Fecha:** Sábado 24 de octubre de 2026
- **Hora:** Desde las 4:00 PM en adelante
- **Lugar:** Calle 148 #21 - 50
- **Aporte:** $50.000 por persona (incluye **cerveza**, **salchichas alemanas** y **palomitas**)
- **Dress code:** Disfraz de temática medieval / Edad Media

## Cómo ver la página
Abre `index.html` en tu navegador (doble clic), o levanta un servidor local:

```bash
python3 -m http.server 8000
```
Luego entra a http://localhost:8000

## 📌 Agregar la imagen de ideas de disfraces
El botón **"Abrir ideas de disfraces"** muestra un pop-up con una imagen.

La imagen actual está en `images/disfraces.png` y se muestra dentro del pop-up.
Para cambiarla, reemplaza ese archivo (mismo nombre) o actualiza el `src` de la
etiqueta `<img id="costumeImage" ...>` en `index.html`.

## Archivos
- `index.html` — estructura y contenido
- `styles.css` — estilos (crema + verde mate oscuro + rojo medieval)
- `script.js` — lógica del pop-up de disfraces
- `images/` — aquí va la imagen de disfraces
