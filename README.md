# Artículo de Compose

Aplicación Android desarrollada con Jetpack Compose. Este proyecto muestra cómo crear una interfaz de usuario simple utilizando funciones declarativas en Kotlin.

## Descripción

La app presenta un artículo informativo sobre Jetpack Compose, empleando imágenes y textos estructurados mediante funciones @Composable. Sirve como ejemplo básico de buenas prácticas de UI declarativa en Android.

## Instalación

Para ejecutar el proyecto sigue estos pasos:

1. Clona este repositorio.
2. Ábrelo en Android Studio.
3. Asegúrate de tener configurado correctamente el SDK de Android.
4. Ejecuta el proyecto en un emulador o dispositivo físico.

## Uso

La actividad principal (`MainActivity.kt`) inicia el tema de la app y muestra el componente `GreetingPreview`. Este componente utiliza la función composable `Greeting`, que recibe tres cadenas y una imagen de fondo, presentando:

- Un título principal.
- Dos párrafos justificados con información sobre Jetpack Compose.

Los textos se encuentran en el archivo `strings.xml` para facilitar la internacionalización. El recurso de imagen debe estar ubicado en la carpeta adecuada del proyecto (`drawable`).

## Tecnologías

- Kotlin
- Android Studio
- Jetpack Compose
- Material 3

## Estructura principal

- `MainActivity.kt`: Punto de entrada, configuración del tema, llamada a la UI.
- `Greeting`: Función @Composable que estructura el contenido.
- `GreetingPreview`: Permite previsualizar el componente en tiempo de diseño.
- `strings.xml`: Valores de texto reutilizables para distintas lenguas.

