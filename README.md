# Bootstrap — Investigación con Demostración Técnica en Vivo

**Curso:** ISW-521 · Programación en Ambiente Web I
**Universidad Técnica Nacional — Sede San Carlos**
**Cuatrimestre:** 2026 – II

## Descripción técnica

Demo que ilustra el uso de **Bootstrap 5.3** mediante una página de curso con:

- **Carousel** de imágenes (componente JS con Popper.js).
- **Accordion** colapsable.
- **Formulario con grid system** (`row`, `col-md-6`, `col-md-4`, `col-md-2`)
  para mostrar cómo el grid de 12 columnas distribuye campos de distinto
  ancho en la misma fila.
- Compilación de Bootstrap **vía Sass** (`main.scss` → `main.css`), no CDN,
  para poder mostrar en vivo cómo se sobrescriben variables del framework.

## Tecnologías

- HTML5
- Bootstrap 5.3.8 (instalado vía npm, compilado con Sass)
- Sass
- JavaScript (bundle de Bootstrap, incluye Popper.js)

## Instrucciones de instalación y ejecución

1. Clonar el repositorio:
   ```
   git clone https://github.com/Ulisesrod/BootstrapExample.git
   cd BootstrapExample
   ```
2. Instalar dependencias:
   ```
   npm install
   ```
3. Compilar el Sass a CSS (requiere el compilador de Sass; si no está
   instalado: `npm install -g sass`):
   ```
   sass src/main.scss src/main.css
   ```
4. Abrir `src/index.html` directamente en el navegador (doble clic o
   arrastrarlo a Chrome).

## Estructura del repositorio

```
BootstrapExample/
├── README.md
├── package.json
└── src/
    ├── index.html
    ├── main.scss        # Punto de entrada Sass (importa Bootstrap completo)
    ├── main.css          # CSS compilado (generado, no editar directamente)
    └── images/
        ├── images.jpg
        ├── collage.jpg
        └── boostrapImage.jpg
```

## Integrantes

- Samuel Fernández Ramírez
- Alejandro Corrales Rivera
- Ulises Rodriguez Navarro

## Notas de la investigación

Ver la comparativa Bootstrap vs. Tailwind, arquitectura interna y datos de
adopción del ecosistema en la presentación entregada junto con este
repositorio.
