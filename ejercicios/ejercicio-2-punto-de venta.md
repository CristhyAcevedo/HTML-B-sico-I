# Ejercicio 2: Estructura de Carpetas para un Proyecto Web de Punto de Venta Online

## 🚀 Ver tus ejercicios en tiempo real con Live Server

Para visualizar tus archivos HTML en el navegador mientras trabajas:

1. **Instala Live Server:** Ve a Extensiones en VS Code (Ctrl+Shift+X) y busca "Live Server" por Ritwick Dey
2. **Abre tu archivo HTML** y haz clic derecho → **"Open with Live Server"** o clic en **"Go Live"** en la barra inferior
3. **Los cambios se reflejarán automáticamente** en tu navegador al guardar

---

## Objetivo
Crear la estructura de carpetas básica para un proyecto web de un punto de venta online.

## Requerimientos:
1. **Crea la carpeta principal del proyecto** llamada `docs/punto-venta-online`.
2. Dentro de la carpeta principal del proyecto, crea las siguientes subcarpetas:
    - `frontend` (para archivos de la interfaz de usuario)
    - `backend` (para la lógica del servidor)
    - `database` (para scripts o archivos relacionados con la base de datos)
    - `docs` (para documentación del proyecto)
3. Dentro de la carpeta `frontend`, crea las siguientes subcarpetas:
    - `css`
    - `js`
    - `img`
4. Dentro de la carpeta `backend`, crea las siguientes subcarpetas:
    - `controllers`
    - `models`
    - `routes`
5. Dentro de la carpeta `database`, crea una carpeta llamada `migrations`.
**Ejemplo de estructura:**
```
docs/
└── punto-venta-online/
    ├── frontend/
    │   ├── css/
    │   ├── js/
    │   └── img/
    ├── backend/
    │   ├── controllers/
    │   ├── models/
    │   └── routes/
    ├── database/
    │   └── migrations/
    └── docs/
```
Una vez que hayas completado el ejercicio ejecuta:
``` npm
npm test ejercicio/2
```
Si pasa todos los test, haz commit de tus cambios y súbelos a tu repositorio de GitHub.   
¡Buena suerte y diviértete programando!