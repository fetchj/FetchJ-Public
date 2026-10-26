# FetchJ – Descarga

**Español** · [Deutsch](README.de.md) · [English](README.en.md)

FetchJ („Fetch Judicial“) descarga a su computadora todos los documentos de sus expedientes de **Gestión en Línea** del Poder Judicial de Costa Rica, los mantiene al día y le muestra lo nuevo de cada expediente.

> **Producto independiente – no es un producto del Poder Judicial.**

Este repositorio contiene solo lo que se descarga: el instalador, los complementos y esta ayuda. El código del programa no es público.

---

## Descargar

| Qué | Dónde |
|---|---|
| **FetchJ para Windows** (versión más reciente) | [**Descargar FetchJ_Setup.exe**](https://github.com/fetchj/FetchJ-Public/releases/latest/download/FetchJ_Setup.exe) |
| **Manual del usuario** (PDF) | [Español](https://github.com/fetchj/FetchJ-Public/releases/latest/download/FetchJ_Manual_ES.pdf) · [Deutsch](https://github.com/fetchj/FetchJ-Public/releases/latest/download/FetchJ_Handbuch_DE.pdf) · [English](https://github.com/fetchj/FetchJ-Public/releases/latest/download/FetchJ_Manual_EN.pdf) · [Português](https://github.com/fetchj/FetchJ-Public/releases/latest/download/FetchJ_Manual_PT.pdf) |
| Complemento **OCR** (reconocimiento de texto para la Investigación) | [Release addons-1.0.0](https://github.com/fetchj/FetchJ-Public/releases/tag/addons-1.0.0) → `FetchJ_OCR_1.0.0.zip` |
| Complemento **FFmpeg** (grabaciones de audiencias en un solo .mp4) | [Release addons-1.0.0](https://github.com/fetchj/FetchJ-Public/releases/tag/addons-1.0.0) → `FetchJ_FFmpeg_1.0.0_windows-x64.zip` |

El manual completo también está dentro de FetchJ: *Ayuda e información → Manual del usuario* (con búsqueda).

Normalmente **no hace falta descargar los complementos a mano**: FetchJ los instala con un clic („Instalar complemento OCR“ / „Instalar ffmpeg“). El archivo zip sirve para computadoras sin Internet o cuando el administrador lo prefiere („Desde archivo …“).

Cada release trae un archivo `SHA256_….txt` con las sumas de control.

## Instalar

1. Descargue `FetchJ_Setup.exe` y ábralo.
2. Windows puede mostrar „Windows protegió su PC“ → **Más información** → **Ejecutar de todas formas** (las versiones de prueba aún no están firmadas).
3. Siga el asistente. Una versión nueva se instala encima de la anterior; sus expedientes, ajustes y la licencia se quedan.

**Requisitos:** Windows 10 u 11 (64 bits), conexión a Internet, una cuenta de Gestión en Línea con su usuario, contraseña y código de verificación (2FA).

## Primeros pasos

1. Inicie FetchJ y elija dónde se guardan los expedientes.
2. Pulse **Iniciar actualización**. Se abre la ventana del portal: **usted mismo** inicia sesión (usuario, contraseña, código).
3. FetchJ lee „Mis expedientes“ y descarga los documentos nuevos. Las siguientes actualizaciones solo traen lo nuevo.

## Preguntas frecuentes

**¿FetchJ guarda mi contraseña?** No. FetchJ nunca escribe, lee ni guarda su usuario, contraseña o código. Usted inicia sesión en la ventana del portal.

**¿Envía FetchJ mis expedientes a algún lugar?** No. Los documentos quedan solo en su computadora. FetchJ habla únicamente con el portal del Poder Judicial (y, si usted lo usa, con Nexus.PJ para la Investigación de jurisprudencia).

**El portal no entrega un documento.** Algunos documentos fallan en el propio portal. FetchJ lo intenta otra vez en las siguientes actualizaciones y los marca como „No descargables“ con el motivo.

**¿Para qué sirve el complemento OCR?** Lee el texto de documentos escaneados (imágenes) para la Investigación. Sin OCR, los escaneos no aportan palabras clave.

**¿Para qué sirve FFmpeg?** Une imagen y sonido de una grabación de audiencia en un solo archivo .mp4, sin cambiar su contenido.

## Soporte

Correo: **fetchjudicial@gmail.com** – en FetchJ: *Ayuda e información → Enviar datos de soporte* (sin contraseñas).

## Licencias de terceros

Los complementos contienen software libre de terceros; detalles en [ADDONS.md](ADDONS.md) y en la carpeta [LICENSES](LICENSES/).

---
Página de descarga 1.1.0 · 22/10/2026
