# Local Video Gallery Generator 🎬 / Generador de Galerías de Video Local

An elegant, dependency-free, and single-file web tool to instantly turn your local folders of video files into an interactive, bilingual (EN/ES), and continuous-playback media player gallery.

Una herramienta web elegante, sin dependencias y de un solo archivo para convertir instantáneamente tus carpetas locales de videos en una galería interactiva, bilingüe (EN/ES) y con reproducción continua.

---

## 🚀 Features / Características

* **Zero Setup:** No server, Node.js, or installation required. It's pure HTML5/JavaScript.
* **Bilingual Support:** Interface automatically switches between English and Spanish based on browser language, with manual toggles on both the creator and the final gallery.
* **Continuous Playback:** Autoplay seamlessly transitions to the next video even across pagination.
* **Modern UI:** Built-in dark/light theme toggle, pagination, instant video search by title, and format filtering.
* **Keyboard Shortcuts:** Spacebar (Play/Pause), Up/Down Arrows (Volume), Left/Right Arrows (Seek).

---

* **Sin Instalación:** No requiere servidor, Node.js ni configuraciones. Es puro HTML5/JavaScript.
* **Soporte Bilingüe:** La interfaz cambia automáticamente entre inglés y español según el navegador, con botones de cambio manual.
* **Reproducción Continua:** El autoplay salta automáticamente al siguiente video, incluso cambiando de página.
* **Interfaz Moderna:** Selector de tema claro/oscuro, paginación integrada, buscador instantáneo por título y filtro por formatos.
* **Atajos de Teclado:** Espacio (Play/Pausa), Flechas Arriba/Abajo (Volumen), Flechas Izquierda/Derecha (Retroceder/Avanzar).

---

## 🛠️ How to Use / Cómo Usar

### 1. Generate the Gallery / Generar la Galería
1. Open `index.html` in any modern web browser.
2. Enter your desired **Gallery Title** and **File Name**.
3. Click on **"Choose Root Folder"** and select the main directory containing your videos (it will scan all subfolders dynamically).
4. Click **"Generate and Download HTML File"**.

---

1. Abre `index.html` en cualquier navegador moderno.
2. Introduce el **Título de la galería** y el **Nombre del archivo** que desees.
3. Haz clic en **"Elegir Carpeta Raíz"** y selecciona el directorio principal que contiene tus videos (escaneará todas las subcarpetas automáticamente).
4. Haz clic en **"Generar y Descargar Archivo HTML"**.

### 2. File Placement (CRITICAL) / Ubicación del Archivo (CRUCIAL)

> ⚠️ **Important / Importante:** 
> For the gallery to play the videos, you **MUST** place the generated HTML file inside the **exact root folder** you indexed.

> Para que la galería pueda reproducir los videos, **DEBES** mover el archivo HTML generado dentro de la **carpeta raíz exacta** que indexaste.

```text
📂 My Video Folder (Root / Carpeta Raíz)
 ├── 📄 galeria.html  <-- PLACE GENERATED FILE HERE! / ¡PON EL ARCHIVO GENERADO AQUÍ!
 ├── 🎥 video1.mp4
 ├── 🎥 video2.mkv
 📂 Subfolder 1
 │   ├── 🎥 video3.mp4
 ```

 ## 📦 Supported Formats / Formatos Compatibles

The indexer automatically filters and lists the following HTML5-compatible video formats:
El indexador filtra y añade automáticamente los siguientes formatos compatibles con HTML5:

    .mp4, .webm, .ogg, .m4v, .mov, .mkv, .avi

(Note: Playback support for formats like .mkv or .avi depends entirely on your browser's internal codecs).

(Nota: La compatibilidad de reproducción para formatos como .mkv o .avi depende exclusivamente de los códecs internos de tu navegador).

## 🔒 Privacy & Security / Privacidad y Seguridad

This tool does not upload your videos or filenames to any server. All processing, indexing, and gallery generation happen 100% locally inside your web browser.

Esta herramienta no sube tus videos ni sus nombres a ningún servidor. Todo el procesamiento, la indexación y la generación de la galería ocurren 100% en local dentro de tu navegador web.