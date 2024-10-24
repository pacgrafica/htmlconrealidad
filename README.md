# Halloween Realidad Aumentada

## Descripción
Este proyecto es una página web de realidad aumentada que utiliza las tecnologías **A-Frame** y **AR.js** para ofrecer una experiencia de realidad aumentada (RA) directamente desde el navegador. La aplicación está estructurada en pasos simples que guían al usuario a través de la configuración y visualización de la experiencia en RA. Además, se utiliza **Bootstrap 5** para una interfaz moderna y receptiva.

## Tecnologías utilizadas
- **HTML5**: Para la estructura de la página.
- **CSS3**: Utilizando estilos personalizados y la integración de **Bootstrap 5** para mejorar el diseño.
- **JavaScript**: Para la integración de la realidad aumentada y la interacción.
- **A-Frame**: Un framework basado en WebVR para construir experiencias de realidad aumentada y virtual.
- **AR.js**: Biblioteca que extiende A-Frame para añadir funcionalidad de realidad aumentada.
- **Bootstrap 5.3.3**: Librería de diseño para crear una interfaz visual atractiva y responsiva.

## Estructura del proyecto
El proyecto está dividido en diferentes secciones que guían al usuario a través de la experiencia de realidad aumentada:

1. **Paso 1**: Descarga o impresión del marcador que será utilizado para la experiencia de realidad aumentada.
2. **Paso 2**: Acceso a la aplicación de realidad aumentada embebida en el sitio web.
3. **Paso 3**: Permiso para acceder a la cámara y vivir la experiencia de realidad aumentada.

## Características principales
- **Realidad aumentada integrada**: A través de la etiqueta `iframe`, embebemos un archivo HTML externo que contiene la configuración de **A-Frame** y **AR.js**. Esta configuración permite el acceso a la cámara y la visualización de los objetos de realidad aumentada.
  
- **Interfaz simple y guiada**: Los usuarios son guiados a través de tres pasos sencillos, asegurando que tengan todo lo necesario para interactuar con la aplicación de RA.

- **Responsividad**: Gracias a **Bootstrap**, la página es completamente responsiva y adaptable a diferentes dispositivos.

## Instrucciones de uso

1. **Clonar el repositorio**:
   ```bash
   git clone <url-del-repositorio>

2. **Abrir el archivo HTML**: El archivo principal de la aplicación es index.html. Este archivo contiene toda la estructura de la página, incluyendo el iframe que embebe la aplicación de realidad aumentada.

3. **Marcar y activar la cámara**: En el archivo index.html, se encuentra un iframe que carga un archivo externo con la funcionalidad de A-Frame y AR.js. Asegúrate de que el navegador tenga acceso a la cámara para poder interactuar con la experiencia de realidad aumentada.

4. **Estructura del código**:

Sección de pasos: Cada uno de los pasos está claramente definido en la interfaz con botones interactivos y descriptivos.
Sección de la aplicación de RA: La aplicación principal de realidad aumentada se encuentra embebida en un iframe que carga el archivo bananita.js/index.html, el cual contiene el código necesario para la funcionalidad de A-Frame y AR.js.

<iframe src="bananita.js/index.html" frameborder="0" allow="camera; microphone" width="800px" height="600px"></iframe>

Esta sección se encuentra en la parte inferior de la página, y el botón "Ver Aplicación" permite al usuario abrir la experiencia de RA en una nueva pestaña.

**Estructura del directorio**

.
├── index.html
├── styles.css
├── images/
│   └── slider.jpg
├── bananita.js/
│   └── index.html
└── README.md

index.html: Archivo principal que estructura el flujo de la aplicación.
styles.css: Archivo de estilos que define la apariencia de la página.
images/: Directorio que contiene las imágenes usadas en la aplicación.
bananita.js/: Directorio que contiene el archivo HTML embebido en el iframe para la experiencia de realidad aumentada.

**Instalación de dependencias**
La aplicación no requiere instalación de dependencias adicionales. Solo es necesario tener un servidor web local que soporte la visualización de archivos estáticos, como XAMPP o WAMP, para visualizar correctamente el contenido embebido en el iframe.

**Permisos del navegador**
Es importante asegurarse de que el navegador permita el acceso a la cámara y al micrófono, ya que la funcionalidad de realidad aumentada depende de estos permisos.

**Créditos**
A-Frame: Para la creación de la experiencia de realidad virtual y aumentada.
AR.js: Para la funcionalidad adicional de realidad aumentada.
Bootstrap 5: Para la interfaz de usuario.
Licencia
Este proyecto se distribuye bajo la licencia MIT. Puedes consultar el archivo LICENSE para más detalles.
