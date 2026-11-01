<p align="center">
  <img src="docs/icon.png" width="96" alt="Icono de Alejo Tools Mobile">
</p>

<h1 align="center">Alejo Tools Mobile</h1>

<p align="center">
  Una navaja suiza para Android: varias herramientas pequeñas en una sola app.
</p>

<p align="center">
  <a href="https://github.com/Amariless/alejo-tools-mobile-releases/releases/latest/download/alejo-tools.apk"><b>Descargar el APK</b></a>
  &nbsp;·&nbsp; Android 7.0 o superior
</p>

## Qué es

En lugar de instalar una app para cada cosa, Alejo Tools Mobile junta las que más uso en el celular. No tiene cuentas, publicidad ni analítica, y lo que guardas se queda en tu teléfono.

## Herramientas

| Herramienta | Para qué sirve |
|---|---|
| **Descargar Música** | Baja canciones de YouTube, SoundCloud y otros sitios como mp3, con portada y artista, y te deja escucharlas antes. También funciona desde el menú *Compartir* de otras apps. |
| **Gastos** | Lleva tus gastos del mes por categoría. |
| **Ideas rápidas** | Notas sueltas para no perder una idea. |
| **Reloj** | Pomodoro, reloj mundial y clima. |
| **Lector de Documentos** | Lee PDF y libros EPUB. Puede ser tu lector predeterminado de PDF. |
| **Paleta de Colores** | Saca una paleta de colores de una foto de la galería o de la cámara. |
| **Creador de Texturas** | Convierte la foto de una superficie en un set de texturas (con normal map) para 3D, usando una cámara con enfoque macro. |
| **Generador de Escenas** | Ideas de escenas 3D con ambientación, estado y atmósfera. |
| **Sincronización** | Revisa el estado de Syncthing en el celular y encuentra conflictos y archivos duplicados en tus carpetas sincronizadas. |

## Instalación

La app no está en Play Store; se instala con el APK.

1. Descarga [`alejo-tools.apk`](https://github.com/Amariless/alejo-tools-mobile-releases/releases/latest/download/alejo-tools.apk) desde el celular y ábrelo.
2. Android te pedirá permitir que tu navegador o gestor de archivos instale apps. Puedes activarlo solo para esta instalación.
3. Si Google Play Protect dice que no conoce la app, es porque no viene de la Play Store. Elige *Instalar de todas formas*.

Las versiones siguientes se instalan desde la propia app, en *Configuración → Buscar actualización*. Todas están firmadas con la misma clave, así que se instalan encima sin perder tus datos. El APK sirve para cualquier celular, sin importar su procesador.

Todas las versiones y sus notas están en [Releases](https://github.com/Amariless/alejo-tools-mobile-releases/releases).

## Permisos

La app pide pocos permisos, y cada uno lo usa una función concreta. Si no usas esa función, puedes negarlo y el resto sigue funcionando.

| Permiso | Para qué lo usa | Si lo niegas |
|---|---|---|
| **Internet** | Buscar actualizaciones, descargar música, consultar el clima ([Open-Meteo](https://open-meteo.com)), mostrar portadas y hablar con Syncthing, que corre en tu propio celular. | Funcionan las herramientas que no usan red: Gastos, Ideas, Lector y Texturas. |
| **Instalar apps** | Instalar las actualizaciones de la propia app. No instala nada más, y Android siempre te pide confirmar. | Tienes que actualizar descargando el APK a mano. |
| **Acceso a todos los archivos** | Revisar las carpetas que sincroniza Syncthing y guardar tus mp3 en la carpeta que elijas. Se pide solo cuando abres una de esas funciones. | Sincronización no puede revisar carpetas y la música se guarda solo en la carpeta de la app. |
| **Cámara** | La cámara macro del Creador de Texturas y las fotos para la Paleta de Colores. | Puedes elegir fotos de la galería. |

El acceso a todos los archivos es un permiso delicado, por eso tienes que activarlo tú desde los ajustes de Android y puedes quitarlo cuando quieras en *Ajustes → Apps → Alejo Tools → Permisos*. Descarga el APK solo desde este repositorio.

Usa Descargar Música solo con contenido que tengas derecho a descargar.

---

Este repositorio solo publica el APK; el código fuente es privado. Si algo falla, abre un [issue](https://github.com/Amariless/alejo-tools-mobile-releases/issues) con la versión de la app (la ves en Configuración) y qué estabas haciendo.
