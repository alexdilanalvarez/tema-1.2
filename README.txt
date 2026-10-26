# Tema 1.2 Dilan Alvarez: Entorno portable de Dart y Flutter

## Características del Equipo

| Recurso | Dónde verlo | Mi equipo |
| :--- | :--- | :--- |
| **Memoria RAM** | Rendimiento > Memoria | 15,9 GB utilizable |
| **Espacio libre en disco** | Explorador > Este equipo | 50 GB |
| **Procesador** | Rendimiento > CPU | 1.80GHz (1.99 GHz) |
| **Virtualización** | Rendimiento > CPU > Virtualización | Deshabilitado |
| **Permisos de administrador** | ¿Puedo instalar programas? | SI |

## Entorno de Desarrollo

- **Versión de Flutter y Dart:** Flutter 3.13.7 / Dart 3.13.7 (obtenidas mediante `flutter --version`)
- **Ruta del Entorno:** `C:\dev\flutter\bin` (configurada en la variable de entorno PATH)
- **Destinos Disponibles:** Windows (desktop), Google Chrome (web) y Microsoft Edge (web)

## Problema Resuelto

Al ejecutar programas interactivos en Dart con `stdin.readLineSync()`, la consola interna de depuración de VS Code (*Debug Console*) no permitía ingresar texto por teclado. Se resolvió creando el archivo `.vscode/launch.json` con la propiedad `"console": "terminal"`, lo que redirige la ejecución a una terminal interactiva real.