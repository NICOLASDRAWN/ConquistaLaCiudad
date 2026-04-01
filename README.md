# Conquista la Ciudad 🏃‍♂️🗺️

¡Hola! Soy Nicolás. Este es mi proyecto personal **"Conquista la Ciudad"**, una aplicación Android nativa diseñada para darle un giro de *gamificación* al running y a las caminatas urbanas. 

La idea principal es simple pero poderosa: **La ciudad se divide en zonas. Para reclamar una zona y hacerla "tuya", debes ser la persona que más kilómetros haya recorrido en esa área durante la semana.**

Este repositorio documenta mi proceso de aprendizaje y desarrollo, construyendo una app moderna, eficiente y con altos estándares de la industria usando las herramientas recomendadas por Google en 2026.

## 🛠 Tech Stack y Arquitectura

Para asegurar un rendimiento óptimo y una interfaz fluida, estoy construyendo este proyecto utilizando:
- **Lenguaje:** Kotlin 
- **UI:** Jetpack Compose (Moderno, reactivo y de primera clase en Android)
- **Mapas y Geofencing:** Google Maps SDK for Compose & Google Places API
- **Arquitectura:** MVVM (Model-View-ViewModel) y Clean Architecture
- **Control de Versiones:** Git Flow (Trabajo mediante ramas estructuradas como `feat/`, `fix/`, etc.)
- **Seguridad:** Uso estricto de `secrets-gradle-plugin` para ocultar las API Keys y evitar vulnerabilidades desde el Día 1.

## 🚀 Progreso Actual

Trabajo en este proyecto mediante un sistema de fases (MVPs iterativos). Puedes seguir el historial de commits para ver mi evolución:

### Fase 0: Configuración y Arquitectura Base ✅
- Creación del andamiaje del proyecto Android con Kotlin DSL.
- Configuración de `.gitignore` para protección de credenciales (`local.properties`).
- Integración de catálogos de dependencias (`libs.versions.toml`).
- Inicialización de Google Maps en Jetpack Compose.

### Fase 1: MVP - Seguimiento Inmersivo de Rutas 🚧 (En Desarrollo)
- Implementación del SDK de Google Maps Compose.
- Manejo avanzado de permisos de GPS (`ACCESS_FINE_LOCATION`, `FOREGROUND_SERVICE`).
- Dibujo en tiempo real del recorrido del usuario utilizando `Polyline`.

### Próximas Fases:
- **Fase 2 (Exploración):** Integración de Puntos de Interés (POIs) interactivos mediante Google Places.
- **Fase 3 (Conquista):** Lógica matemática para calcular la propiedad de los polígonos del mapa usando Firebase en tiempo real.

## 💡 ¿Qué estoy aprendiendo con este proyecto?
Más allá del código, este proyecto es un reto personal para dominar:
1. **Foreground Services en Android:** Para mantener el rastreo activo y preciso incluso cuando la app está en el bolsillo.
2. **Eficiencia de Batería:** Manejar las llamadas del GPS sin destruir la batería del usuario.
3. **Gestión de Estado Compleja:** Usar Jetpack Compose para animaciones del mapa vinculadas en tiempo real a sensores físicos del dispositivo.

---
*Si eres un reclutador o un desarrollador curioso viendo este código, ¡siéntete libre de explorar mis ramas (`branches`) para ver cómo fragmento el trabajo en equipo (incluso siendo un desarrollador solista)!*
