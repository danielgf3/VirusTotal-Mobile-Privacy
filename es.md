# VirusTotal Mobile — Aviso de privacidad

*Última actualización: 1 de noviembre de 2026 · [English](./)*

Este Aviso de privacidad describe cómo la app Android **VirusTotal Mobile** (paquete `com.funnycat.virustotal`, «la app»), desarrollada por Funnycat, recoge y trata información. La app permite comprobar apps instaladas, archivos y URLs con el servicio VirusTotal. No tiene cuentas de usuario, publicidad, analítica ni librerías de seguimiento, y no operamos ningún servidor que almacene tus datos. Este aviso no cubre el servicio VirusTotal, que se rige por el suyo (<https://docs.virustotal.com/docs/privacy-policy>).

## Información que recoge y trata la app

- **Información de apps instaladas.** Para comprobar tus apps, la app lee la lista de apps instaladas (nombre, paquete, versión, permisos solicitados) y calcula el hash SHA-256 de cada APK. Los hashes se envían a VirusTotal para consultar la reputación de la app.
- **Archivos que envías.** El APK de una app instalada que VirusTotal aún no conoce se sube **solo si la Subida automática está activada** en Ajustes (se puede desactivar en cualquier momento; solo en redes sin tarifa por datos y con batería no baja). Los archivos y URLs que eliges analizar se suben solo cuando inicias el análisis.
- **Tu clave API de VirusTotal.** Si introduces una clave personal, se guarda cifrada en tu dispositivo y se envía a VirusTotal solo con las peticiones de archivos y URLs que haces.
- **Historial y ajustes.** Resultados, hashes, nombres y preferencias se guardan en una base de datos local del dispositivo.
- **Datos técnicos para notificaciones.** La app usa Firebase Cloud Messaging; Google asigna al dispositivo un token de registro para entregar notificaciones (<https://firebase.google.com/support/privacy>).

**No** recogemos nombre, correo, ubicación, contactos ni ID de publicidad.

## Para qué lo tratamos

- Para realizar las comprobaciones que solicitas: análisis de apps, archivos y URLs.
- Para ejecutar análisis y mostrar resultados y notificaciones en segundo plano si lo activas.
- Para guardar tu historial y ajustes en el dispositivo.

## Comparticiones

No vendemos tu información ni la recibimos: los datos van del dispositivo directamente a VirusTotal (operado por Google) y, para notificaciones, a Firebase Cloud Messaging (Google). **Los archivos y URLs enviados a VirusTotal pueden compartirse con la comunidad de seguridad**, así que no analices archivos con información privada.

## Conservación

Los datos del dispositivo permanecen hasta que borres el historial, limpies el almacenamiento de la app o la desinstales. La conservación de lo enviado a VirusTotal se rige por el aviso de VirusTotal.

## Seguridad

La clave API se cifra en el dispositivo. Toda la comunicación con VirusTotal usa HTTPS.

## Tus opciones y derechos

Puedes desactivar el análisis en segundo plano y la subida automática, borrar tu clave API, borrar el historial o desinstalar la app en cualquier momento. Como no guardamos datos personales tuyos en servidores propios, las solicitudes sobre datos enviados a VirusTotal deben dirigirse a VirusTotal.

## Permisos

Internet y estado de red (conectar con VirusTotal); consultar todos los paquetes (listar las apps instaladas para comprobarlas, función principal de la app); notificaciones; servicio en primer plano de sincronización, wake lock e inicio tras reinicio (análisis en segundo plano).

## Menores

La app no está dirigida a menores de 13 años ni recoge conscientemente su información.

## Cambios

Si este aviso cambia, la nueva versión se publicará en esta dirección con la fecha actualizada.

## Contacto

Abre una incidencia en <https://github.com/danielgf3/VirusTotal-Mobile-Privacy/issues>.
