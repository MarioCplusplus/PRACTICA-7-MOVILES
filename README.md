# Práctica 7: Aplicación con Notificaciones Push y Servicios de Firebase

Este proyecto es parte de la materia de **Aplicaciones Móviles Nativas** y tiene como objetivo desarrollar una aplicación móvil que integre servicios de Firebase. La aplicación incluye un sistema de notificaciones push para que un administrador pueda enviar invitaciones a usuarios registrados y establecer conexiones entre ellos.

## Descripción
La aplicación demuestra el uso de los siguientes servicios de Firebase:

- **Firestore**: Para la gestión de datos estructurados en tiempo real.
- **Realtime Database**: Para sincronización de datos en tiempo real.
- **Cloud Storage**: Para almacenar y recuperar contenido multimedia.
- **Authentication**: Para gestionar el acceso de usuarios.
- **Cloud Messaging**: Para enviar y recibir notificaciones push.

### Funcionalidades principales:
- Registro y autenticación de usuarios.
- Sistema de notificaciones push que permite al administrador enviar invitaciones.
- Interacción entre usuarios registrados mediante conexiones establecidas en tiempo real.

## Requisitos
Antes de comenzar, asegúrate de tener lo siguiente:

- **Android Studio** (versión recomendada: Arctic Fox o superior).
- **JDK** (Java Development Kit) versión 8 o superior.
- Una cuenta de Firebase configurada con un proyecto.
- Archivo de configuración `google-services.json` descargado desde Firebase para la integración.

## Instalación
Sigue estos pasos para configurar y ejecutar el proyecto:

1. **Clona el repositorio**:
   ```bash
   git clone https://github.com/MarioCplusplus/PRACTICA-7-MOVILES.git
   ```

2. **Abre el proyecto en Android Studio**:
   - Abre Android Studio.
   - Selecciona `Open an existing project`.
   - Navega hasta la carpeta `Firebase` dentro del repositorio clonado y ábrela.

3. **Configura Firebase**:
   - Ve a [Firebase Console](https://console.firebase.google.com/).
   - Crea un nuevo proyecto o utiliza uno existente.
   - Descarga el archivo `google-services.json` para Android y colócalo en la carpeta `app` del proyecto.

4. **Sincroniza las dependencias**:
   - En Android Studio, sincroniza el proyecto con `Gradle` haciendo clic en `Sync Project with Gradle Files`.

5. **Ejecuta el proyecto**:
   - Conecta un dispositivo físico o inicia un emulador desde Android Studio.
   - Haz clic en el botón `Run` para compilar y ejecutar la aplicación.

## Uso
1. Abre la aplicación en tu dispositivo o emulador.
2. Registra una cuenta o inicia sesión.
3. Si eres administrador, accede a la sección de envío de notificaciones push para enviar invitaciones a usuarios registrados.
4. Los usuarios recibirán las notificaciones y podrán interactuar con las invitaciones directamente desde la aplicación.

## Estructura del Proyecto
- **`app/src/main/java`**: Contiene el código fuente principal de la aplicación.
- **`app/src/main/res`**: Contiene los recursos de la aplicación (diseños, imágenes, valores, etc.).
- **`google-services.json`**: Archivo de configuración para integrar Firebase.
- **`build.gradle`**: Archivos de configuración de Gradle para la construcción del proyecto.

## Contribución
Actualmente, este proyecto no está abierto a contribuciones externas, ya que es parte de una práctica académica.

## Licencia
Este proyecto fue desarrollado con fines educativos como parte de la materia **Aplicaciones Móviles Nativas** y no incluye licencia para distribución pública.

---

Si tienes dudas o comentarios sobre este proyecto, por favor contacta a través de este repositorio.
