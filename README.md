# 🕸️ Spider-Man: Brand New Day - Official fan Countdown

Una espectacular y cinematográfica web de cuenta regresiva para el estreno de la película **Spider-Man: Brand New Day** (previsto para el 31 de julio de 2026). Este proyecto es un tributo interactivo creado por y para fans, diseñado con un enfoque moderno y de alto rendimiento.

## 🚀 Características Principales

*   **Diseño Mobile-First e Interactivo**: Optimizado al 100% para pantallas móviles y de escritorio, con una estética premium inspirada en el cine, glows de neón, gradientes balanceados de azul y rojo, y un logo Stark Suit animado.
*   **Fondo Arácnido Interactivo (Canvas)**: Un sistema de partículas sensible al cursor del usuario en el escritorio y toques en móvil, simulando hilos de telaraña interactivos.
*   **Carrusel Cinematic Fusión (Doble Capa)**: Galería de imágenes de fondo (incluyendo el póster oficial Brand New Day y artes conceptuales de Hulk y Spidey) usando una técnica de doble capa (blur en cover + contain en primer plano) para evitar recortes de personajes en móviles verticales.

*   **Tráiler Oficial Integrado**: Modal responsivo con el tráiler de YouTube, accesible mediante transiciones suaves, controles de cerrado con tecla Esc, y click fuera del modal.
*   **Acciones Rápidas (Reminder & Share)**:
    *   **Agregar al Calendario**: Agrega el evento del estreno directamente a Google Calendar.
    *   **Compartir Web**: Integración nativa con la Web Share API en dispositivos compatibles, con copia de enlace al portapapeles en caso de no estar disponible.
*   **Optimización SEO Avanzada**:
    *   Configuración completa de etiquetas meta y protocolo Open Graph.
    *   Tarjetas personalizadas para **X (Twitter)** y **WhatsApp** con título, descripción optimizada en español e imagen oficial de previsualización.
    *   Favicon personalizado en formato SVG con la clásica máscara de Spider-Man.

## 🛠️ Stack Tecnológico

*   **Core**: [Astro](https://astro.build/) - Framework estático ultra rápido.
*   **Estilos**: [Tailwind CSS v4](https://tailwindcss.com/) - Con la nueva integración nativa de Vite `@tailwindcss/vite`.
*   **Interactividad**: HTML5 Canvas y Vanilla JavaScript para transiciones fluidas.
*   **Tipografías**: Google Fonts (Outfit & Inter).

## 🧑‍💻 Desarrollador

*   Desarrollado por **Leandro A. Canela**.

---

## 🧞 Comandos y Desarrollo Local

Todos los comandos se ejecutan desde la raíz del proyecto mediante la terminal:

```sh
# Instalar dependencias
npm install

# Iniciar servidor de desarrollo (Hot Reload)
npm run dev

# Compilar la web para producción
npm run build

# Previsualizar la compilación de producción localmente
npm run preview
```

---

## ☁️ Despliegue en Vercel

Esta web está completamente lista para ser desplegada en **Vercel** en cuestión de segundos:

1.  Sube el repositorio a GitHub, GitLab o Bitbucket.
2.  Inicia sesión en [Vercel](https://vercel.com/) y haz clic en **"Add New"** > **"Project"**.
3.  Importa el repositorio.
4.  Vercel detectará automáticamente que es un proyecto de **Astro** y configurará los comandos de construcción (`npm run build`) y directorio de salida (`dist`).
5.  Haz clic en **"Deploy"**. ¡Listo! Obtendrás un dominio HTTPS seguro para compartir tu web.

---

## ⚖️ Temas de Copyright (Derechos de Autor)

> [!NOTE]
> Este sitio web es una **obra artística sin fines de lucro creada por fans** y para fans (Fan Tribute). 
> 
> *   **Marcas y Personajes**: *Spider-Man*, *Bruce Banner / Hulk*, y todos los elementos asociados son marcas comerciales y derechos de autor registrados de **Marvel Entertainment, LLC** y **Sony Pictures Entertainment Inc.**

> *   **Uso Legítimo (Fair Use)**: El uso de artes, nombres y logotipos en este proyecto cae bajo las pautas de *Uso Legítimo* en los derechos de autor (propósito ilustrativo, tributo y no comercialización). No se genera ningún tipo de ingreso directo ni indirecto con esta página.
