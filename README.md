# CatFlix: distribución

Este repositorio público guarda únicamente las versiones aprobadas para distribuir. No almacenar código fuente, credenciales Xtream, claves de firma ni datos de usuarios.

## Plataformas

| Plataforma | Archivo de cada versión | Distribución |
| --- | --- | --- |
| Android | `CatFlix-Android.apk` | Enlace directo y QR en CatFlix Administrador |
| Google TV | `CatFlix-Google-TV.apk` | Instalador residente en el televisor, autorizado desde CatFlix Administrador |
| Windows | `CatFlix-Windows-x64.exe` | Enlace directo para la primera instalación y búsqueda manual de actualizaciones en la aplicación |

Los nombres de los archivos de descarga deben permanecer idénticos en cada versión publicada. Las versiones se publicarán como GitHub Releases; solo se marcará como `latest` una versión aprobada para distribución. No publicar prototipos o versiones alfa en ese canal.

## Requisitos de actualización

- Conservar el identificador y la firma digital de cada aplicación Android/Google TV al publicar una actualización.
- Mantener las credenciales Xtream en el almacenamiento privado de CatFlix del televisor. El instalador de Google TV no debe recibirlas.
- Android solicitará la confirmación de instalación del sistema.
- Windows buscará actualizaciones cuando el usuario lo solicite, sin interrumpir la reproducción. Descargará e instalará solo después de su aceptación.
- Antes de publicar, registrar versión, plataforma, tamaño y huella SHA-256 del instalador.
