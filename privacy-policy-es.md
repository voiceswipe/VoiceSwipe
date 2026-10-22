# Política de Privacidad — Voice Swipe

*Última actualización: octubre 2026*

## 1. Qué no sale de tu teléfono

Voice Swipe no pide registro ni cuenta. No tenemos servidores propios. El audio del micrófono, las imágenes de la cámara, la información de la cara y lo que observa el servicio de accesibilidad se procesan en tu teléfono y no se envían a nosotros.

## 2. Micrófono

El permiso de micrófono se usa solo en el modo Voz, para reconocer comandos. El audio se procesa al momento en el teléfono con Vosk y Silero VAD. No se guarda en un archivo y no se envía a ningún servidor.

## 3. Cámara: gestos de la mano y Control gestual

La cámara frontal se usa en el modo Gestos y en Control gestual, solo mientras ese modo está activo. Cada imagen se analiza al momento y no se guarda ni se envía.

- **Gestos:** MediaPipe reconoce un gesto de la mano (por ejemplo, subir, bajar o pausar).
- **Control gestual:** MediaPipe Face Landmarker calcula puntos de la cara y el ángulo de la cabeza para detectar una inclinación (siguiente video, anterior, o pausa). No identifica quién eres, no crea una plantilla de tu rostro para reconocerte después y no guarda fotos.

La vista previa de la calibración y de la práctica también se queda en el teléfono.

## 4. Accesibilidad

El servicio de accesibilidad sirve para deslizar el feed y para pausar o reanudar en apps compatibles (TikTok, Instagram Reels, Facebook Reels y YouTube Shorts). Solo emite esos gestos cuando ocurre una de estas cosas: un comando de voz reconocido en el teléfono, un gesto de la mano, un movimiento de cabeza, o el intervalo de Autoscroll que tú elegiste.

También leemos qué app o ventana está en primer plano, para encender o apagar el micrófono, la cámara y Autoscroll según corresponda.

No leemos mensajes, conversaciones, publicaciones ni el texto de otras apps. No ofrecemos control remoto del teléfono. No modificamos archivos ni datos guardados dentro de otras aplicaciones.

## 5. Acceso al uso

En algunos teléfonos, por ejemplo Xiaomi, Android no indica con fiabilidad qué app está delante. En ese caso pedimos Acceso al uso y leemos solo el nombre del paquete que está en primer plano, en el teléfono, para decidir si el micrófono o la cámara deben estar activos. No leemos tu historial de uso y no enviamos ese dato.

## 6. Compras

Las compras para desbloquear apps compatibles las procesa Google Play. No recibimos el número de tu tarjeta ni tu dirección de facturación. Solo sabemos si la compra de esta app está activa en este dispositivo. Google trata los datos del pago según su propia política: [policies.google.com/privacy](https://policies.google.com/privacy).

## 7. Internet

Después de la configuración, Voice Swipe funciona sin conexión. Internet se usa para dos cosas:

- Descargar un paquete de idioma de Vosk cuando hace falta. El español viene incluido en la app. El inglés se descarga desde GitHub y el portugués desde el sitio del proyecto Vosk (alphacephei.com).
- Completar la compra en Google Play.

No subimos audio, imágenes ni datos de accesibilidad.

## 8. Analíticas y publicidad

No hay analíticas, publicidad ni informes de diagnóstico que salgan del teléfono. La notificación persistente la muestra el propio teléfono mientras el servicio está activo. No es un aviso enviado desde un servidor nuestro.

## 9. Bibliotecas

- Vosk: reconocimiento de voz, en el teléfono.
- Silero VAD, con ONNX Runtime: detecta si hay voz, en el teléfono.
- MediaPipe: gestos de la mano y puntos de la cara, en el teléfono.
- CameraX: acceso a la cámara, en el teléfono.
- Google Play Billing: se comunica con Google Play solo para la compra.

Estas bibliotecas de reconocimiento no transmiten tu audio, tus imágenes ni la información de tu cara.

## 10. Cambios

Si esta política cambia, lo verás en una actualización de la app en Google Play y en esta página.

## 11. Contacto

Para preguntas o comentarios sobre esta política de privacidad: [voiceswipe@gmail.com](mailto:voiceswipe@gmail.com)
