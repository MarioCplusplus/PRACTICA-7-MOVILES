# Práctica 7: Aplicación con Notificaciones Push y Servicios de Firebase

Este proyecto es parte de la materia de **Aplicaciones Móviles Nativas** y tiene como objetivo desarrollar una aplicación móvil que integre varios servicios de Firebase, incluyendo notificaciones push para interacciones entre usuarios.

## Descripción
La aplicación utiliza los siguientes servicios de Firebase:

- **Firestore**: Para la gestión de datos estructurados.
- **Realtime Database**: Para sincronización de datos en tiempo real.
- **Cloud Storage**: Para almacenamiento de contenido multimedia.
- **Authentication**: Para la gestión de usuarios.
- **Cloud Messaging**: Para notificaciones push.

## Requisitos
Antes de comenzar, asegúrate de tener lo siguiente:

- **Android Studio** instalado.
- Cuenta de Firebase configurada.
- Archivo `google-services.json` descargado desde Firebase.
- Emulador o dispositivo físico con Google Play Services.

## Instalación
Sigue estos pasos para configurar y ejecutar el proyecto:

1. **Clona el repositorio**:
   ```bash
   git clone https://github.com/MarioCplusplus/PRACTICA-7-MOVILES.git
   ```
2. **Abre el proyecto en Android Studio**:
   - Selecciona `Open an existing project`.
   - Navega a la carpeta `Firebase` dentro del repositorio.

3. **Configura Firebase**:
   - Ve a [Firebase Console](https://console.firebase.google.com/) y crea un proyecto.
   - Descarga el archivo `google-services.json` y colócalo en la carpeta `app` del proyecto.

4. **Configura las dependencias**:
   - Asegúrate de que los archivos `build.gradle` incluyan las dependencias necesarias de Firebase.

5. **Sincroniza el proyecto**:
   - Haz clic en `Sync Project with Gradle Files` en Android Studio.

6. **Ejecuta la aplicación**:
   - Conecta un dispositivo físico o inicia un emulador.
   - Haz clic en `Run` para compilar y ejecutar la aplicación.

## Uso
1. Inicia sesión o registra una nueva cuenta.
2. Envía notificaciones push desde la consola de Firebase o desde la aplicación si eres administrador.
3. Recibe e interactúa con las notificaciones en tiempo real.

---
