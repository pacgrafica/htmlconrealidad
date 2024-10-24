# <img src="https://em-content.zobj.net/source/microsoft-teams/363/grinning-face-with-smiling-eyes_1f604.png" width=25> REALIDAD AUMENTADA CON A-FRAME

<img src="https://user-images.githubusercontent.com/6317076/27866704-452eaed6-618f-11e7-9cdd-2deaef865e3e.png">

<br>

### ¡Bienvenido al emocionante mundo de la programación de Realidad Aumentada con A-Frame!

<a href="https://danielo27.github.io/Realidad-Aumentada-A-frame.js/" target="_blank">Demostracion en Vivo</a>
<br>

<iframe width="560" height="315" src="https://www.youtube.com/embed/qlcu0q00FxI?si=FRJ6MgXCFjaWuc2x" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" ></iframe>

A-Frame es un framework de código abierto basado en javascript enfocado a el desarrollo Web, que te permite crear experiencias de Realidad Aumentada (AR) de manera sencilla y accesible. Con A-Frame, puedes construir escenas interactivas de AR utilizando componentes HTML y JavaScript, y visualizarlas en navegadores compatibles con tecnología WebXR. Aquí tienes una breve introducción para empezar con A-Frame:

<br>

Configuración: Comienza por incluir el archivo de A-Frame en tu proyecto HTML. Puedes descargarlo e incluirlo localmente o utilizar la versión alojada en línea. Aquí tienes un ejemplo de cómo agregarlo desde una URL de CDN:

``` html
<!DOCTYPE html>
<html>
<head>
    <script src="https://aframe.io/releases/1.3.0/aframe.min.js"></script>
    <script src="https://raw.githack.com/AR-js-org/AR.js/dev/aframe/build/aframe-ar.js"></script>

    <!--Importante agregar estos dos archivos para cargar animaciones que traigan los modelos-->
    <script src="https://unpkg.com/aframe-environment-component@1.3.2/dist/aframe-environment-component.min.js"></script>
    <script src="https://cdn.jsdelivr.net/gh/c-frame/aframe-extras@7.1.0/dist/aframe-extras.min.js"></script>
</head>
<body>
  <!-- Tu contenido de realidad aumentada aquí -->
</body>
</html>
```

Escena y Entidades: En A-Frame, todo se coloca dentro de una etiqueta: <a-scene>. Puedes agregar entidades como modelos 3D, imágenes, luces, etc. utilizando las etiquetas <a-entity> dentro de la escena. Por ejemplo, puedes añadir un cubo en la posición (0, 0, -5) utilizando el siguiente código:

```html 
<a-scene>
  <a-entity geometry="primitive: box" position="0 0 -5" color="red"></a-entity>
</a-scene>

```

 Componentes y Interacciones: A-Frame permite extender la funcionalidad de las entidades mediante componentes personalizados. Puedes crear tus propios componentes JavaScript para controlar el comportamiento de los objetos en la escena, como movimientos, animaciones o interacciones con el usuario.

 Assets: Puedes cargar recursos como modelos 3D, imágenes o sonidos utilizando la etiqueta <a-assets>. Esto te permite reutilizar los activos en diferentes partes de tu escena. Por ejemplo, puedes cargar un modelo 3D llamado "my-model" utilizando el siguiente código:

``` html
<a-assets>
  <a-asset-item id="my-model" src="assets/my-model.gltf"></a-asset-item>
</a-assets>
```

#### Luego, puedes utilizar el modelo en una entidad de la siguiente manera:

``` html
<a-entity gltf-model="#my-model"></a-entity>
``` 

Ahora te estaras preguntando y como detecta este proyecto el marcador usado para este recurso; la respuesta es muy sencilla, este marcador que aprecias en el video es un codigo de barras de una matriz de 3x3 que es igual a 5 es por ello que nuestro proyecto lo detecta, si tu cambias este valor tendrias que cambiar tu marcador por el codigo de barras respectivo al valor que colocaste. 

<img src="https://user-images.githubusercontent.com/252962/27870433-c18f6e10-619a-11e7-8479-4cb662798740.png">

Estos son solo los conceptos básicos para comenzar con A-Frame. A medida que te familiarices más con la herramienta, podrás explorar características adicionales como animaciones, físicas, efectos visuales y mucho más.

Recuerda consultar la documentación oficial de A-Frame (https://aframe.io/docs/1.2.0/) para obtener más información, ejemplos y tutoriales detallados que te ayudarán a aprovechar al máximo este poderoso framework de Realidad Aumentada.

#### ¡Disfruta explorando y creando experiencias de Realidad Aumentada emocionantes con A-Frame! Si tienes más preguntas, ¡no dudes en preguntar!

<br>

#### Gracias a McCarthy3D y a Jesus Dorado quienes son los creadores de los dos modelos usados en el tutorial: 
- https://sketchfab.com/3d-models/spartan-armour-mkv-halo-reach-57070b2fd9ff472c8988e76d8c5cbe66
- https://sketchfab.com/3d-models/banana-dancing-fortnite-c1db1b10f9b14717ba731d7f49d25443

<br>

<hr>

### <img src='https://em-content.zobj.net/source/microsoft-teams/363/winking-face-with-tongue_1f61c.png' width='20'> Sigueme en mis redes Sociales y enterate del contenido que hago: .

<a target="_blank" href="https://www.linkedin.com/in/henry-daniel-quintero-henriquez/">![Likending](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)</a>
<a target="_blank" href="https://www.youtube.com/@DanielQuinteroHenriquez">![Youtube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)</a> 
<a target="_blank" href="mailto:danielquinterohenriquez@gmail.com">![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)</a>

## <img src="https://em-content.zobj.net/source/microsoft-teams/363/nerd-face_1f913.png" width=20> Daniel Quintero 




