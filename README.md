# Me Sirve Android

Proyecto Android para compilar la app Me Sirve en un APK de prueba usando GitHub Actions. No publica la aplicación en Play Store ni despliega una web.

## Generar APK
1. Abre la pestaña **Actions**.
2. Selecciona **Construir APK de Me Sirve**.
3. Pulsa **Run workflow**.
4. Cuando termine, abre la ejecución y descarga el artefacto **me-sirve-apk**.
5. Descomprime el artefacto para obtener `app-debug.apk`.

La compilación requiere acceso a los servicios de GitHub Actions y está sujeta a los límites gratuitos de la cuenta. Los datos de la app se guardan localmente en el dispositivo; no hay sincronización en la nube.

**Nota:** la aplicación web actualizada debe estar en `app/src/main/assets/www/index.html`.
