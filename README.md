# Actividad 3 - Taller práctico CSS3

## Dashboard administrativo GatoSoftware

### Descripción

Este proyecto consiste en el desarrollo de un dashboard administrativo utilizando HTML5 y CSS3.

El dashboard representa una interfaz para la administración de un sistema de gestión empresarial y presenta información relacionada con ventas, pedidos, clientes, productos, reportes y actividad reciente.

El diseño fue desarrollado aplicando CSS Grid para la estructura principal y Flexbox para la distribución interna de los componentes.

---

## Tecnologías utilizadas

* HTML5
* CSS3
* CSS Grid
* Flexbox
* Media Queries
* Variables CSS
* Pseudo-clases CSS
* WAI-ARIA
* Git
* GitHub

---

## Estructura del proyecto

```text
actividad-3-css3/
│
├── index.html
├── styles.css
├── README.md
│
└── evidencias/
    ├── escritorio.png
    ├── tablet.png
    └── movil.png
```

---

## Layout con CSS Grid

CSS Grid se utilizó para construir la estructura principal del dashboard.

Se definieron las siguientes áreas:

* `sidebar`: barra lateral de navegación.
* `header`: encabezado superior.
* `main`: contenido principal.
* `footer`: pie de página.

La estructura se definió mediante `grid-template-areas`, permitiendo modificar la distribución en diferentes tamaños de pantalla.

También se utilizó CSS Grid para organizar:

* Tarjetas de estadísticas.
* Área de gráfico y actividad.
* Tarjetas informativas inferiores.

---

## Uso de Flexbox

Flexbox se utilizó para organizar los componentes internos del dashboard.

Entre los elementos que utilizan Flexbox se encuentran:

* Navegación lateral.
* Encabezado.
* Perfil del usuario.
* Tarjetas de estadísticas.
* Gráfico de ventas.
* Lista de actividades.
* Elementos del footer.
* Botones y controles.

Esto permite que los elementos mantengan una correcta alineación y distribución cuando cambia el tamaño de la pantalla.

---

## Responsividad

El dashboard utiliza media queries para adaptarse a diferentes dispositivos.

### Escritorio

En pantallas grandes se presenta una barra lateral permanente y una distribución de varias columnas.

### Tablet

En tamaños intermedios se reduce el ancho de la barra lateral y se reorganizan las tarjetas y componentes.

### Móvil

En pantallas pequeñas el dashboard utiliza una sola columna y la navegación lateral se transforma en una navegación horizontal.

Las tarjetas también pasan a organizarse verticalmente para facilitar la lectura y navegación.

---

## Interactividad visual

Se utilizaron diferentes recursos de CSS para mejorar la experiencia de usuario:

* `:hover`
* `:focus-visible`
* `transition`
* Cambios visuales en botones.
* Elevación visual de las tarjetas.
* Efectos sobre los elementos del gráfico.
* Cambios visuales en los enlaces de navegación.

---

## Accesibilidad

Se implementaron diferentes buenas prácticas de accesibilidad:

* Uso del atributo `lang="es"`.
* Estructura semántica HTML5.
* Uso de etiquetas `header`, `nav`, `main`, `section`, `article`, `aside` y `footer`.
* Uso de etiquetas `aria-label` para elementos de navegación.
* Uso de `aria-labelledby` para relacionar secciones con sus títulos.
* Uso de `role="img"` para proporcionar una descripción accesible del gráfico.
* Los elementos decorativos utilizan `aria-hidden="true"`.
* Los enlaces y botones pueden recibir foco mediante teclado.
* Se implementó `:focus-visible` para hacer visible el foco.
* La tabla utiliza encabezados `<th>` con `scope="col"`.
* Se proporciona un título accesible para la tabla.

---

## Decisiones de diseño

Se utilizó una interfaz de estilo administrativo con una estructura limpia y organizada.

La barra lateral permite acceder a las principales áreas del sistema, mientras que el contenido central presenta indicadores importantes mediante tarjetas.

El uso de tarjetas permite identificar rápidamente información relevante como ventas, pedidos, clientes y productos.

Se utilizó una combinación de colores con suficiente contraste entre el texto y los fondos para facilitar la lectura.

Las variables CSS permiten centralizar colores, tamaños y otros valores utilizados por la interfaz, facilitando el mantenimiento del código.

---

## Evidencias

Las capturas de pantalla del dashboard se encuentran en la carpeta `evidencias`.

### Vista de escritorio

![Dashboard en escritorio](evidencias/escritorio.png)

### Vista de tablet

![Dashboard en tablet](evidencias/tablet.png)

### Vista móvil

![Dashboard en móvil](evidencias/movil.png)

---

## Visualización

Para visualizar el proyecto localmente se debe abrir el archivo:

```text
index.html
```

También puede utilizarse la extensión Live Server de Visual Studio Code.

---

## Autor

Actividad académica - Taller práctico implementado CSS3.

Proyecto: Dashboard administrativo GatoSoftware.

Año: 2026
