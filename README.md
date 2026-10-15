# Centro de estética Logoipsum

Sitio web responsive para un centro de estética. La página presenta los servicios disponibles, promociones, testimonios de clientas, información del equipo y un formulario para solicitar una hora.

![Logo del centro de estética](./img/LOGO.png)

## Características

- Diseño responsive con enfoque mobile-first.
- Navegación interna hacia las secciones principales:
  - Nosotros
  - Servicios
  - Ofertas
  - Agenda
- Sección principal con llamada a la acción para agendar una hora.
- Promociones especiales para el Día de la Madre.
- Testimonios de clientas.
- Tarjetas de servicios:
  - Depilación láser
  - Peluquería
  - Limpieza facial
- Formulario de agenda con selección de servicio, fecha y hora.
- Barra de navegación fija en pantallas grandes.
- Tipografías [Inter](https://fonts.google.com/specimen/Inter) y [DM Sans](https://fonts.google.com/specimen/DM+Sans), cargadas desde Google Fonts.

## Tecnologías

- HTML5
- CSS3
- Google Fonts

El proyecto no utiliza frameworks, JavaScript ni dependencias de Node.js.

## Requisitos

Solo necesitas un navegador web moderno. Para utilizar un servidor local, puedes instalar cualquiera de estas alternativas:

- [Visual Studio Code](https://code.visualstudio.com/) con la extensión Live Server.
- Python 3.
- Cualquier servidor HTTP estático.

## Uso local

### Opción 1: abrir directamente el archivo

Abre [`index.html`](./index.html) en tu navegador.

### Opción 2: utilizar un servidor local con Python

Desde la raíz del proyecto, ejecuta:

```bash
python3 -m http.server 8000
```

Luego visita <http://localhost:8000> en el navegador.

### Opción 3: utilizar Live Server

1. Abre la carpeta del proyecto en Visual Studio Code.
2. Instala la extensión **Live Server**.
3. Haz clic derecho en [`index.html`](./index.html).
4. Selecciona **Open with Live Server**.

## Estructura del proyecto

```text
.
├── index.html          # Estructura y contenido de la página
├── styles.css          # Estilos, colores y diseño responsive
└── img/                # Logos, fotografías e iconos
    ├── LOGO.png
    ├── LOGO_footer.png
    ├── avatar1.png
    ├── avatar2.png
    ├── banner-fondo.jpg
    ├── depilacion.jpeg
    ├── equipo.jpg
    ├── limpieza.webp
    ├── peluqueria.jpg
    ├── promo1.jpeg
    ├── promo2.jpeg
    ├── promo3.jpeg
    └── iconos de redes sociales
```

## Personalización

### Contenido

Edita [`index.html`](./index.html) para modificar:

- El nombre y los textos del sitio.
- Las promociones.
- Los testimonios.
- Los servicios y sus precios.
- Las opciones disponibles en el formulario.
- Los enlaces de navegación y redes sociales.

### Diseño

Edita [`styles.css`](./styles.css) para cambiar:

- Colores principales, como el rosa `#FEF0FD` y el magenta `#DF0CCA`.
- Tipografías y tamaños.
- Espaciados y distribución de las secciones.
- Punto de quiebre responsive para escritorio (`920px`).
- Imágenes utilizadas como fondos y fotografías.

## Formulario de agenda

El formulario está preparado visualmente para solicitar:

- Nombre y apellido.
- Celular.
- Correo electrónico.
- Servicio.
- Fecha.
- Hora.

Actualmente, [`index.html`](./index.html) referencia `action_page.php` en el atributo `action` del primer formulario, pero ese archivo no está incluido en este repositorio. Para procesar las reservas es necesario conectar el formulario a un backend o servicio externo y configurar validación, almacenamiento y envío de datos.

## Estado del proyecto

Este repositorio contiene la interfaz frontend de una landing page estática. Los precios y algunos textos de ejemplo todavía deben reemplazarse por la información definitiva del centro de estética antes de publicar el sitio.

## Licencia

No se ha definido una licencia para este proyecto.
