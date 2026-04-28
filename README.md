# Inventario Pro - App de Gestión de Inventario

Esta es una aplicación móvil desarrollada con **Android Studio** y **Jetpack Compose** que simula un sistema de gestión de inventario para un almacén. El proyecto demuestra el uso de navegación moderna, componentes de Material 3 y manejo de estados.

## 🚀 Características

La aplicación consta de 4 pantallas principales conectadas mediante un flujo lógico:

1.  **Login:** Pantalla de acceso con validación de campos.
2.  **Dashboard (Inicio):** Resumen visual del estado del inventario (Total de productos y alertas de stock bajo) basado en datos reales.
3.  **Listado de Stock (Detalle):** Un catálogo completo de productos utilizando `LazyColumn`, con indicadores visuales de precio y disponibilidad.
4.  **Perfil de Administrador:** Configuración del usuario con elementos interactivos como un interruptor de notificaciones y cierre de sesión funcional.

## 🛠️ Tecnologías utilizadas

*   **Kotlin**: Lenguaje de programación principal.
*   **Jetpack Compose**: Kit de herramientas moderno para construir interfaces de usuario nativas.
*   **Compose Navigation**: Gestión de la navegación entre pantallas.
*   **Material 3**: Implementación de las últimas guías de diseño de Google.
*   **Material Icons Extended**: Biblioteca amplia de iconos para una mejor experiencia visual.

## 📋 Requisitos previos

*   **Android Studio Ladybug** (o superior).
*   **JDK 11** o superior.
*   **Android SDK 36** (configurado en el proyecto).

## 🏃 Instrucciones de Ejecución

1.  **Clonar o descargar** el repositorio del proyecto.
2.  Abrir Android Studio y seleccionar **"Open"**. Navega hasta la carpeta del proyecto y selecciónala.
3.  Espera a que **Gradle** sincronice las dependencias (asegúrate de tener conexión a internet).
4.  Conecta un dispositivo Android físico o inicia un Emulador.
5.  Haz clic en el botón **"Run"** (triángulo verde) en la barra superior de Android Studio.

## 🔑 Credenciales de prueba

Actualmente, la pantalla de Login permite el acceso con cualquier usuario y contraseña (siempre que no estén vacíos).

---
*Desarrollado como ejemplo de implementación de navegación y componentes en Jetpack Compose.*
