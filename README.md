# CatFlix: distribución

Este repositorio público guarda únicamente las versiones aprobadas para distribuir. No almacenar código fuente, credenciales Xtream, claves de firma ni datos de usuarios.

## Descargas directas permanentes

- [CatFlix Usuario Android](https://github.com/renatosalinas-proyectos/catflix-distribucion/releases/latest/download/CatFlix-Android.apk)
- [CatFlix Google TV](https://github.com/renatosalinas-proyectos/catflix-distribucion/releases/latest/download/CatFlix-Google-TV.apk)

El QR de Android debe codificar exactamente la primera dirección. GitHub redirige `latest/download` al archivo adjunto en la versión marcada como más reciente. Al publicar una versión nueva, incluir **ambos APK** con esos nombres fijos, incluso si una plataforma no cambió. Así los dos enlaces siguen funcionando. Verificar la descarga antes de cambiar la marca `latest`.

Windows se incorporará cuando exista un instalador aprobado para distribuir. La versión alfa no ocupa el canal `latest`.

## Flujo previsto

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
