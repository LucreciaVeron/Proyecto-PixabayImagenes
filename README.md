# 📷 Buscador de Imágenes con Pixabay API

Aplicación web en **JavaScript puro** que permite buscar imágenes desde la API de [Pixabay](https://pixabay.com/api/docs/), mostrando resultados paginados y con información detallada de cada imagen (likes y vistas).

Este proyecto fue creado como parte del curso de Udemy:  
[JavaScript Moderno: Guía Definitiva Construye +10 Proyectos](https://www.udemy.com/course/javascript-moderno-guia-definitiva-construye-10-proyectos)

---

## 🌐 Demo en línea

Podés probar el proyecto aquí:  
👉 [Ver proyecto en vivo]()

---

## 🚀 Características
- Búsqueda de imágenes por palabra clave.
- Integración con la **API REST de Pixabay**.
- Resultados mostrados con **TailwindCSS** para el diseño.
- Paginación dinámica con botones generados automáticamente.
- Alertas para manejar errores de validación (ej: búsqueda vacía).

---

## 🛠️ Tecnologías utilizadas
- **JavaScript (ES6+)**
- **Fetch API**
- **TailwindCSS** (para estilos)
- **Pixabay API**

---

## 🔑 API Key

Este proyecto utiliza la API de [Pixabay](https://pixabay.com/api/docs/).  
Debes registrar una cuenta gratuita y obtener tu **API Key**, luego reemplazarla en el archivo `app.js`:

```javascript
const key = 'TU_API_KEY_AQUI';
```

---

## 🚀 Cómo usar

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/LucreciaVeron/Proyecto-PixabayImagenes.git
