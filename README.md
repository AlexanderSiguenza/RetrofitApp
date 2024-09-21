# RetrofitApp
Ejemplo de Retrofit para consumir una api https://dog.ceo/api/breeds/list/all

## Descripción
**RetrofitApp** es una aplicación Android que utiliza la biblioteca Retrofit para realizar solicitudes a una API REST y obtener imágenes de perros por raza. Permite al usuario buscar imágenes de perros a través de un `SearchView`, mostrando los resultados en un `RecyclerView`.

## Estructura del Proyecto

RetrofitApp/ ├── app/ │ ├── src/ │ │ ├── main/ │ │ │ ├── java/ │ │ │ │ └── com/ │ │ │ │ └── example/ │ │ │ │ └── retrofitapp/ │ │ │ │ ├── ApiService.kt │ │ │ │ ├── DogsResponse.kt │ │ │ │ ├── DogAdapter.kt │ │ │ │ ├── DogViewHolder.kt │ │ │ │ └── MainActivity.kt │ │ │ ├── res/ │ │ │ │ ├── layout/ │ │ │ │ │ ├── activity_main.xml │ │ │ │ │ └── item_dog.xml │ │ │ │ └── mipmap/ │ │ │ │ └── ic_launcher.png │ │ │ ├── AndroidManifest.xml │ │ │ └── ... │ │ └── ... │ └── build.gradle └── ...


## Funcionalidades
- **Búsqueda de Imágenes de Perros**: Permite al usuario buscar imágenes de perros por raza utilizando un `SearchView`.
- **Visualización de Resultados**: Muestra los resultados en un `RecyclerView`, que se actualiza dinámicamente con cada búsqueda.
- **Manejo de Errores**: Notifica al usuario si ocurre un error durante la búsqueda.

## Requisitos
- Android SDK
- Retrofit
- Gson
- Picasso

## Instalación
1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu_usuario/RetrofitApp.git

<img src="https://github.com/AlexanderSiguenza/RetrofitApp/blob/main/img/akita.png" alt="Descripción de la imagen" width="300" height="600">
<img src="https://github.com/AlexanderSiguenza/RetrofitApp/blob/main/img/bulldog.png" alt="Descripción de la imagen" width="300" height="600">
