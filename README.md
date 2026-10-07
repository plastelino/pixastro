<p align="center"><img src="icon.png" width="96" alt="PixAstro"></p>

# PixAstro

*[English below](#english)*

Procesado de astrofotografía para principiantes. Arrastras la carpeta con tus tomas,
pulsas **Procesar** y obtienes una imagen final presentable, sin necesidad de conocer
la teoría. Funciona sin conexión y no envía ningún dato. En español e inglés.

## Descarga

**[⬇ Descargar la última versión](https://github.com/plastelino/pixastro/releases/latest)**

| Sistema | Archivo | Cómo se abre |
|---|---|---|
| Windows 10/11 (64 bits) | `PixAstro-<versión>-windows-x64.exe` | Doble clic. No se instala nada. La primera vez Windows puede avisar: **Más información → Ejecutar de todas formas**. |
| Linux x86-64 (Ubuntu 22.04, Debian 12, Fedora 36, Mint 21 o posteriores) | `PixAstro-<versión>-linux-x86_64` | Dale permiso de ejecución una vez (Propiedades → Permisos → «Permitir ejecutar», o `chmod +x`) y ábrelo con doble clic. |
| macOS 12 o posterior, Mac con Apple Silicon (M1 o posterior) | `PixAstro-<versión>-macos-arm64.dmg` | Abre el `.dmg` y arrastra PixAstro a Aplicaciones. Firmado y notarizado por Apple. |

Cada archivo es la aplicación completa: no hace falta instalar nada más.

## Cómo se usa

1. **Cargar**: arrastra la carpeta de la sesión. PixAstro detecta qué es cada toma (light,
   dark, flat o bias).
2. **Procesar**: calibración, descarte de las peores tomas, alineado por estrellas, apilado,
   gradiente de fondo, color, estirado y reducción de ruido, todo automático.
3. **Exportar**: elige el tipo de objeto, compara antes/después y guarda en TIFF, FITS,
   PNG o JPG.

Admite FITS, RAW de cámara (CR2, CR3, NEF, ARW, RAF, DNG…), TIFF, PNG y JPG. Los archivos
originales nunca se modifican.

---

## English

Astrophotography processing for beginners. Drop in the folder with your frames, click
**Process** and get a presentable final image without needing to know the theory. Works
offline and never sends any data. In English and Spanish.

### Download

**[⬇ Download the latest version](https://github.com/plastelino/pixastro/releases/latest)**

| System | File | How to open it |
|---|---|---|
| Windows 10/11 (64-bit) | `PixAstro-<version>-windows-x64.exe` | Double-click. Nothing is installed. The first time Windows may warn: **More info → Run anyway**. |
| Linux x86-64 (Ubuntu 22.04, Debian 12, Fedora 36, Mint 21 or later) | `PixAstro-<version>-linux-x86_64` | Make it executable once (Properties → Permissions → "Allow executing", or `chmod +x`) and double-click it. |
| macOS 12 or later, Apple Silicon Mac (M1 or later) | `PixAstro-<version>-macos-arm64.dmg` | Open the `.dmg` and drag PixAstro to Applications. Signed and notarized by Apple. |

Each file is the complete application: nothing else to install.

### How it works

1. **Load**: drop in the session folder. PixAstro works out what each frame is (light,
   dark, flat or bias).
2. **Process**: calibration, rejection of the worst frames, star alignment, stacking,
   background gradient, colour, stretch and noise reduction, all automatic.
3. **Export**: pick the object type, compare before/after and save as TIFF, FITS, PNG or JPG.

Reads FITS, camera RAW (CR2, CR3, NEF, ARW, RAF, DNG…), TIFF, PNG and JPG. Your original
files are never modified.
