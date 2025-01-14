# Práctica 7: Aplicación con Notificaciones Push y Servicios de Firebase

## Repositorio
[Repositorio en GitHub](https://github.com/MarioCplusplus/PRACTICA-7-MOVILES/tree/master/Firebase)

## Observaciones

El proyecto está desarrollado en **Android Studio** y utiliza varios servicios de Firebase, incluyendo:
- **Firestore**: Para la gestión de datos estructurados.
- **Realtime Database**: Para sincronización de datos en tiempo real.
- **Cloud Storage**: Para almacenamiento de contenido multimedia.
- **Authentication**: Para la gestión de usuarios.
- **Cloud Messaging**: Para notificaciones push.

## Instrucciones para ejecutar el proyecto

### 1. Clona el repositorio
```bash
git clone https://github.com/MarioCplusplus/PRACTICA-7-MOVILES.git
```

### 2. Abre el proyecto en Android Studio
1. Abre Android Studio.
2. Selecciona `Open an existing project`.
3. Navega hasta la carpeta `Firebase` dentro del repositorio clonado y ábrela.

### 3. Configura Firebase
1. Ve a [Firebase Console](https://console.firebase.google.com/).
2. Crea un nuevo proyecto o utiliza uno existente.
3. Agrega una nueva aplicación Android al proyecto de Firebase utilizando el nombre del paquete de tu aplicación.
4. Descarga el archivo `google-services.json` proporcionado por Firebase y colócalo en el directorio `app` de tu proyecto en Android Studio.
5. Asegúrate de que los servicios de Firebase que planeas utilizar estén habilitados en la consola de Firebase.

### 4. Configura las dependencias de Firebase
1. Abre el archivo `build.gradle` a nivel de proyecto y asegúrate de que el repositorio de Google esté incluido:

```groovy
buildscript {
    repositories {
        google()
        // Otros repositorios
    }
    // ...
}
allprojects {
    repositories {
        google()
        // Otros repositorios
    }
}
```

2. En el archivo `build.gradle` a nivel de módulo (generalmente en la carpeta `app`), aplica el plugin de servicios de Google y añade las dependencias de Firebase necesarias:

```groovy
apply plugin: 'com.google.gms.google-services'

dependencies {
    // Otras dependencias
    implementation platform('com.google.firebase:firebase-bom:31.2.3')
    implementation 'com.google.firebase:firebase-auth'
    implementation 'com.google.firebase:firebase-firestore'
    implementation 'com.google.firebase:firebase-database'
    implementation 'com.google.firebase:firebase-storage'
    implementation 'com.google.firebase:firebase-messaging'
}
```

### 5. Sincroniza el proyecto con Gradle
En Android Studio, haz clic en `Sync Project with Gradle Files` para asegurarte de que todas las dependencias se descarguen correctamente.

### 6. Ejecuta la aplicación
1. Conecta un dispositivo físico o configura un emulador con Google Play Services.
2. Haz clic en el botón `Run` en Android Studio para compilar y ejecutar la aplicación.

## Notas adicionales

- Asegúrate de que los servicios de Firebase estén correctamente configurados en la consola de Firebase, incluyendo las reglas de seguridad para Firestore y Realtime Database.
- Para probar las notificaciones push, es necesario que los dispositivos o emuladores tengan acceso a internet y que las configuraciones de Firebase Cloud Messaging estén correctamente implementadas.

---

Si tienes preguntas o comentarios sobre este proyecto, no dudes en contactarme a través del repositorio.
