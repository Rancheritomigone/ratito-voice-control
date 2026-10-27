# Ratito Voice Control — prototipo Android

Este es un **prototipo de código fuente**, no un APK ya compilado ni una versión validada.

## Qué intenta hacer
- Servicio en primer plano con notificación.
- Reconocimiento de voz en español (usa el reconocedor de voz disponible en Android).
- Palabra de activación “Ratito” seguida de una orden.
- Botón flotante y controles multimedia básicos.
- Ajuste del volumen del sistema.

## Limitaciones conocidas
- Android puede impedir o interrumpir el reconocimiento continuo, especialmente con la pantalla apagada o por optimización de batería.
- El reconocimiento de voz puede usar servicios de Google/red y no es una detección local de palabra de activación de bajo consumo.
- Los comandos siguiente/anterior dependen de que la app multimedia activa acepte teclas multimedia.
- El servicio requiere permisos de micrófono, notificaciones y superposición. El usuario debe habilitarlos manualmente.
- Debe probarse y ajustarse en el Motorola G52 y su versión de Android antes de considerarlo funcional.
- Este proyecto no incluye Gradle Wrapper ni un APK compilado.

## Compilación
Abrir el proyecto en Android Studio actualizado y compilar el módulo `app`. Para una notebook con pocos recursos, es preferible usar un servicio de compilación en la nube, tras revisar el código.
