# Numora Webcam — Política de privacidad


**Responsable:** Numora Software — Bryton Tomás Jiménez Roca (persona natural, titular de la marca Numora Software); contacto: numorasoftware.contacto@gmail.com.
**Última actualización:** 9 de noviembre de 2026.

## 1. Qué hace la aplicación
Numora Webcam usa la cámara y, si el usuario lo elige, el micrófono de su teléfono Android para enviar video y audio, **por la red local (Wi‑Fi) y cifrados**, a su propio computador con Windows, donde la aplicación Numora Webcam los presenta como una cámara (y opcionalmente reproduce el audio).

## 2. Qué datos se tratan
| Dato | Para qué | Dónde va | Se guarda |
|---|---|---|---|
| Video de la cámara | Mostrarlo en tu PC | Solo a tu PC, por tu red local, cifrado (AES‑256‑GCM) | **No se graba ni se guarda** en el teléfono ni en el PC |
| Audio del micrófono (si activas «Cámara y mic» o «Solo mic») | Reproducirlo/usarlo en tu PC | Igual que el video | **No se graba ni se guarda** |
| Clave de vinculación (aleatoria, de un solo uso, en el código QR del PC) y claves largas posteriores | Reconocer tu PC y no volver a escanear el código | Se guardan en el teléfono (almacén privado de la app) y en el PC (`%AppData%\NumoraCamera`) | Hasta que las olvides o desinstales |
| Ajustes (resolución, estilo de imagen, etc.) | Recordar tus preferencias | Solo en tu teléfono y tu PC | Hasta que se borren |
| Nombre del teléfono y del PC y direcciones IP de tu red | Encontrar el PC y mostrar el estado | Solo dentro de tu red local | No se guardan en servidores |

## 3. Qué NO se hace
- **No se envía nada a internet ni a servidores de Numora.** No hay cuentas, publicidad, rastreadores, ni telemetría.
- No se vende ni se comparte información con terceros.
- No existe ningún modo oculto: mientras transmite, el teléfono muestra una **notificación permanente** y una pantalla visible, y puedes detener la transmisión en cualquier momento.

## 4. Permisos del teléfono
- **Cámara**: para capturar el video que se envía a tu PC.
- **Micrófono**: solo si eliges un modo con audio.
- **Notificaciones**: para mostrar el aviso obligatorio mientras transmites.
- **Red/Wi‑Fi**: para conectar con tu PC y mantener la conexión de baja latencia.
- **Servicio en primer plano (cámara/micrófono)**: para que la transmisión continúe con la pantalla apagada o la app en segundo plano.

## 5. Permisos del PC
La instalación pide permisos de administrador una vez para registrar la cámara virtual y abrir el cortafuegos **solo para tu red local** (puertos TCP 5750 y UDP 5751). La cámara virtual aparece en *Configuración › Privacidad y seguridad › Cámara* como cualquier otra cámara.

## 6. Seguridad
La transmisión va cifrada de extremo a extremo entre tu teléfono y tu PC. La vinculación inicial usa un código QR con una clave aleatoria de 128 bits de un solo uso y, una vez vinculados, una clave larga de 128 bits. La app solo usa la cámara para leer ese código; no guarda imágenes. El canal interno entre el programa y el servicio de cámara de Windows solo puede abrirlo el propio servicio.

## 7. Menores
La aplicación no está dirigida a menores de 13 años.

## 8. Tus derechos
Como Numora no recopila tus datos en servidores propios, no tiene datos tuyos que acceder, rectificar o suprimir. Puedes borrar los datos locales desinstalando la app y usando «Olvidar teléfonos vinculados» en el PC. Para consultas: numorasoftware.contacto@gmail.com.

## 9. Responsabilidad del usuario
Debes usar la cámara y el micrófono de forma lícita y con el consentimiento de las personas que aparezcan o se escuchen. Numora no está diseñada para vigilancia encubierta.

## 10. Cambios
Si esta política cambia, se publicará la nueva versión con su fecha y se avisará en la app.

## 11. Compras dentro de la app (Premium)
La compra opcional «Numora Premium» (pago único) la procesa **Google Play**. Numora no recibe ni guarda tus datos de pago; solo consulta a Google Play si tu cuenta tiene la compra para activar las funciones. El teléfono informa al PC, por el canal cifrado de tu red local, si el Premium está activo.
