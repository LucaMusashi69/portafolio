# Portafolio Personal de Miguel Ángel Olivares Hernández

¡Bienvenido al repositorio del portafolio personal de Miguel Ángel Olivares Hernández! Este proyecto es una representación de mis habilidades y proyectos, diseñado para ser interactivo y fácil de navegar.

## Tabla de Contenidos

1.  [Descripción del Proyecto](#descripción-del-proyecto)
2.  [Características](#características)
    *   [Modo Oscuro](#modo-oscuro)
    *   [Descarga de CV](#descarga-de-cv)
    *   [Traducción a Inglés](#traducción-a-inglés)
    *   [Favicon Personalizado](#favicon-personalizado)
3.  [Configuración y Ejecución Local](#configuración-y-ejecución-local)
    *   [Requisitos](#requisitos)
    *   [Pasos para Ejecutar](#pasos-para-ejecutar)
4.  [Estructura del Proyecto](#estructura-del-proyecto)
5.  [Tecnologías Utilizadas](#tecnologías-utilizadas)
6.  [Contacto](#contacto)

## Descripción del Proyecto

Este portafolio personal es una aplicación web estática diseñada para mostrar mis proyectos, experiencia y habilidades. Está construido con HTML, CSS y JavaScript, enfocándose en una interfaz de usuario limpia y una experiencia de usuario fluida. El objetivo principal es proporcionar una plataforma accesible para que posibles empleadores y colaboradores puedan conocer mi trabajo.

## Características

Hemos implementado varias funcionalidades clave para mejorar la experiencia del usuario:

### Modo Oscuro

La aplicación incluye un modo oscuro que se puede activar y desactivar manualmente. Esta característica mejora la legibilidad en entornos con poca luz y ofrece una opción de personalización visual.

*   **Cómo usarlo:** Haz clic en el icono de la luna/sol (🌙/☀️) en la esquina superior derecha de la barra de navegación para alternar entre el modo claro y oscuro.
*   **Persistencia:** Tu preferencia de modo (claro u oscuro) se guarda en el almacenamiento local del navegador, por lo que se recordará en futuras visitas.
*   **Preferencia del Sistema:** El modo inicial respeta la preferencia de tema de tu sistema operativo si no has establecido una preferencia manual.

### Descarga de CV

Se ha integrado un botón que permite descargar mi currículum vitae directamente desde la página.

*   **Cómo usarlo:** Haz clic en el botón "Descargar CV" ubicado en la sección de inicio o contacto. Esto iniciará la descarga del archivo `MIGUEL ANGEL OLIVARES HERNANDEZ 2025 web version.docx`.

### Traducción a Inglés

Para una audiencia más amplia, el portafolio incluye una funcionalidad de traducción a inglés impulsada por el widget de Google Translate Element.

*   **Cómo usarlo:** Haz clic en el icono de traducción (🌐) en la esquina superior derecha de la barra de navegación. La página se traducirá automáticamente a inglés.
*   **Funcionamiento:** Esta característica utiliza el widget de Google Translate para traducir el contenido de la página en tiempo real en el navegador. Es importante ejecutar el portafolio en un servidor local para que esta funcionalidad opere correctamente.

### Favicon Personalizado

El sitio web ahora cuenta con un favicon personalizado en forma de triángulo (▲) para una identidad visual única en las pestañas del navegador.

## Configuración y Ejecución Local

Para ver y probar este portafolio en tu máquina local, sigue los siguientes pasos:

### Requisitos

Necesitarás un servidor web local para ejecutar el proyecto. Puedes usar Python, Node.js o cualquier otro servidor web de tu preferencia.

*   **Python (recomendado para simplicidad):** Viene preinstalado en la mayoría de los sistemas operativos.
*   **Node.js (opcional, si ya lo tienes):** Puedes usar `npx serve`.

### Pasos para Ejecutar

1.  **Clonar el Repositorio (si aplica) o Descargar los Archivos:**
    Asegúrate de tener todos los archivos del proyecto en una carpeta en tu máquina local.

2.  **Abrir una Terminal:**
    Navega hasta la carpeta raíz del proyecto (`c:\Users\Angel\Desktop\portafolio`) usando tu terminal o línea de comandos.

3.  **Iniciar un Servidor Web Local:**

    *   **Con Python:**
        Ejecuta el siguiente comando en la terminal:
        ```bash
        python -m http.server 8000
        ```
        Esto iniciará un servidor en el puerto 8000.

    *   **Con Node.js (si tienes `npx` instalado):**
        Ejecuta el siguiente comando en la terminal:
        ```bash
        npx serve -l 8000
        ```
        Esto iniciará un servidor en el puerto 8000.

4.  **Acceder al Portafolio:**
    Abre tu navegador web y navega a la siguiente dirección:
    ```
    http://localhost:8000
    ```
    Deberías ver el portafolio cargado en tu navegador.

## Estructura del Proyecto

El proyecto está organizado de la siguiente manera:

```
.
├── README.md               # Este archivo de documentación
├── documents/              # Contiene documentos como el CV
│   └── MIGUEL ANGEL OLIVARES HERNANDEZ 2025 web version.docx
├── images/                 # Almacena todas las imágenes y iconos utilizados
│   ├── france.svg
│   ├── google-cloud.svg
│   ├── hacker-cat.svg
│   ├── mike-IA.png
│   ├── spain.svg
│   └── united-kingdom-svgrepo-com.svg
├── script.js               # Contiene la lógica JavaScript para interactividad
├── styles.css              # Hoja de estilos CSS para el diseño
└── vicky.html              # El archivo HTML principal del portafolio
```

## Tecnologías Utilizadas

*   **HTML5:** Estructura del contenido.
*   **CSS3:** Estilos y diseño.
*   **JavaScript:** Interactividad y funcionalidades dinámicas.
*   **Google Translate Element:** Para la traducción de la página.
*   **Remix Icon:** Para los iconos utilizados en la interfaz.

## Contacto

Si tienes alguna pregunta o quieres ponerte en contacto conmigo, puedes encontrar mi información de contacto en la sección de "Contacto" del portafolio.

---
¡Gracias por visitar mi portafolio!