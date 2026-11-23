# CatFlix: distribución

Este repositorio público guarda únicamente las versiones aprobadas para distribuir. No almacenar código fuente, credenciales Xtream, claves de firma ni datos de usuarios.

## Descargas directas

- [CatFlix Usuario Android](https://github.com/renatosalinas-proyectos/catflix-distribucion/releases/download/v0.12.9-distribucion/CatFlix-Android.apk)
- [CatFlix Google TV 0.15.2 PiP (prueba)](https://github.com/renatosalinas-proyectos/catflix-distribucion/releases/download/v0.15.2-google-tv-pip-preview/CatFlix-Google-TV-0.15.2-PiP.apk)
- [CatFlix Windows x64 0.1.7 alfa](https://github.com/renatosalinas-proyectos/catflix-distribucion/releases/download/catflix-windows-0.1.7/CatFlix-Windows-x64-0.1.7-ALFA.zip)

La sincronización de listas M3U compartidas sigue pendiente. La publicación PiP de Google TV es de prueba; su APK está firmado con la misma firma de distribución para permitir instalarla sobre la versión firmada anterior y conservar los datos.

## Flujo de distribución

| Plataforma | Distribución | Actualización |
| --- | --- | --- |
| Android Usuario | Enlace directo y QR en CatFlix Administrador | Consulta manual en la aplicación y confirmación de Android |
| Google TV | Instalador residente en el televisor, autorizado desde CatFlix Administrador | Descarga en el televisor con confirmación del sistema |
| Windows | Enlace directo para primera instalación | Búsqueda manual en la aplicación, sin interrumpir reproducción |
| Android Administrador | Distribución controlada | Búsqueda manual en la propia aplicación |

## Requisitos

- Conservar el identificador y la firma digital al actualizar los APK. Las claves de firma permanecen fuera de este repositorio.
- Mantener las credenciales Xtream en el almacenamiento privado de CatFlix del televisor. El instalador de Google TV no debe recibirlas.
- Antes de publicar, registrar versión, plataforma, tamaño y huella SHA-256 del archivo.
