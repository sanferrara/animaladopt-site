# AnimalAdopt – Guía para testers (iOS TestFlight y Android)

¡Gracias por ayudar a probar **AnimalAdopt**! Sigue estos pasos según tu dispositivo.

---

## iOS – TestFlight (recomendado)
1. Instala **TestFlight** desde la App Store.
2. Abre el enlace público de invitación: **PON_AQUÍ_TU_ENLACE_DE_TESTFLIGHT**
3. Toca **Instalar** y abre la app.
4. Para enviar feedback/crashes, usa la opción de **Enviar feedback** en TestFlight.

> Si aún no hay enlace público, el desarrollador puede invitarte por email desde App Store Connect.

### Permisos en iOS
- **Ubicación**: para mostrar animales cercanos. Puedes negarlo y la app seguirá funcionando, pero verás resultados menos relevantes.
- **Cámara/Fotos**: para subir imágenes de animales o de tu perfil.
- **Notificaciones**: para avisos de favoritos, mensajes, etc. Opcional.

---

## Android – APK
1. Descarga el APK desde: **PON_AQUÍ_TU_ENLACE_DE_APK**
2. Abre el archivo y acepta instalar de origen desconocido si te lo pide.
3. Abre la app y prueba con normalidad.

---

## Qué probar (sugerencias)
- Registro / inicio de sesión.
- Listado de animales y filtros (incluida ubicación).
- Detalle y favoritos.
- Subida de fotos (cámara y galería).
- Notificaciones (si están activadas en tu build).

---

## Reporte de problemas
Cuando informes un error, por favor incluye:
- **Dispositivo** (modelo) y **versión de iOS/Android**.
- **Versión de la app** (visible en TestFlight o en Ajustes de la app).
- Pasos para reproducir el problema.
- Capturas de pantalla o video si es posible.

Contacto: **tuemail@ejemplo.com** (sustituye por el tuyo).

---

## Notas para el desarrollador
- TestFlight: subir builds con `eas build -p ios --profile production` y luego `eas submit -p ios --profile production`.
- Enlace público de TestFlight: App Store Connect → TestFlight → Public Link.
- Política de privacidad: añade la URL pública en App Store Connect → App Information.
