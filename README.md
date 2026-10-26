# Alejo Tools Mobile

Una navaja suiza de herramientas personales para Android, en una sola app. Hecha con [Tauri 2](https://tauri.app) (Rust + web). Es una app de uso personal: se distribuye como APK directo, sin Play Store.

Este repositorio **solo contiene las releases** (el APK y sus notas). El código fuente es privado.

## Descargar

**[⬇ Bajar la última versión (alejo-tools.apk)](https://github.com/Amariless/alejo-tools-mobile-releases/releases/latest/download/alejo-tools.apk)**

Todas las versiones y sus notas están en [Releases](https://github.com/Amariless/alejo-tools-mobile-releases/releases).

### Cómo instalar

1. Descargá el `.apk` en el celular y abrilo.
2. Android te va a pedir permiso para "instalar apps de orígenes desconocidos" para tu navegador o explorador de archivos: activalo solo para esa instalación.
3. Si Google Play Protect avisa que la app no es conocida, es porque no viene de la Play Store; podés elegir "Instalar de todas formas".
4. Las versiones siguientes se instalan desde la propia app: **Configuración → Buscar actualización**.

Requiere Android 7.0 o superior. El APK es universal (sirve para todas las arquitecturas) y está firmado siempre con la misma clave, así que las actualizaciones se instalan encima de la versión anterior sin perder datos.

## Qué hace

| Herramienta | Para qué sirve |
|---|---|
| **Sincronización** | Cliente de [Syncthing-Android](https://github.com/syncthing/syncthing-android): ver estado, carpetas y dispositivos, y detectar conflictos y duplicados en lo que sincronizás. |
| **Descargar Música** | Baja canciones de YouTube, SoundCloud y otros sitios como mp3, con portada, artista y vista previa. También se puede usar desde el menú "Compartir" de otras apps. |
| **Reloj** | Pomodoro, reloj mundial y clima. |
| **Ideas rápidas** | Notas sueltas para no perder una idea. |
| **Gastos** | Registro de gastos mensuales por categoría. |
| **Paleta de Colores** | Extrae una paleta de colores desde una foto (galería o cámara). |
| **Creador de Texturas** | Convierte la foto de una superficie en un normal map y un set de texturas, con cámara macro propia. |
| **Generador de Escenas** | Genera ideas de escenas 3D con ambientación, estado y atmósfera. |
| **Lector de Documentos** | Lector de PDF y libros EPUB; puede ser el lector por defecto al abrir un PDF. |
| **Configuración** | Carpetas, tema y actualizaciones. |

Los datos de Gastos, Ideas y demás herramientas se guardan **solo en el celular**; la app no tiene cuentas ni servidores propios.

## Permisos y para qué se usa cada uno

La app pide pocos permisos y cada uno está ligado a una función concreta. Si no usás esa función, podés negarlo sin que el resto deje de andar.

| Permiso | Cómo se pide | Para qué lo usa | Si lo negás |
|---|---|---|---|
| **Internet** (`INTERNET`) | Automático al instalar | Buscar y bajar actualizaciones desde este repositorio; descargar música; consultar el clima ([Open-Meteo](https://open-meteo.com)); mostrar portadas; hablar con Syncthing, que corre en tu propio celular (`127.0.0.1`). | Seguirían andando las herramientas que no necesitan red (Gastos, Ideas, Lector, Texturas). |
| **Instalar apps desconocidas** (`REQUEST_INSTALL_PACKAGES`) | Ajuste de Android, la primera vez que actualizás desde la app | Instalar **la propia actualización** de Alejo Tools Mobile que bajó desde este repositorio. No instala ninguna otra app. Android siempre te muestra su diálogo de confirmación. | Tenés que actualizar bajando el APK a mano. |
| **Acceso a todos los archivos** (`MANAGE_EXTERNAL_STORAGE`) | Pantalla de Ajustes de Android, solo cuando abrís una función que lo necesita | Leer las carpetas que sincroniza Syncthing-Android (que viven fuera del espacio privado de la app) para detectar conflictos y duplicados, y guardar tus mp3 en la carpeta que vos elegiste. | Sincronización no puede analizar carpetas ni Descargar Música guardar en carpetas externas. |
| **Cámara** (`CAMERA`) | Diálogo normal de Android, al abrir una cámara dentro de la app | Cámara propia con enfoque manual/macro para el Creador de Texturas, y tomar una foto para la Paleta de Colores. | Podés seguir eligiendo fotos de la galería. |

### Advertencias

- **"Acceso a todos los archivos" es un permiso sensible.** Android lo reserva para apps que necesitan leer rutas de otras apps; por eso no lo pide al instalar y lo tenés que activar vos a mano. La app solo lo usa en las carpetas que configurás. Podés revocarlo cuando quieras desde *Ajustes → Apps → Alejo Tools → Permisos → Archivos*.
- **Instalar fuera de la Play Store** implica confiar en el origen del APK. Descargalo solo desde este repositorio y, ante la duda, compará el checksum `.sha256` publicado en la release cuando exista.
- **Descargar Música**: usá la herramienta solo con contenido que tengas derecho a descargar. Respetar los términos de cada sitio y los derechos de autor es responsabilidad de quien la usa.
- La app **no tiene analítica ni publicidad** ni envía tus datos a servidores del autor.

## Reportar un problema

Abrí un issue en este repositorio con la versión de la app (Configuración) y qué estabas haciendo.
