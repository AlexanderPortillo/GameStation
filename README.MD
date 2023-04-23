<h1 align="center">DOCUMENTACION - GAME STATION</h1>

## Tabla de contenido

- [Descripción general](#Descripción-general)
  - [Indicaciones](#Indicaciones)
  - [Como usar la libreria](#como-usar-la-libreria)
  - [Descripción del proyecto](#Descripción-del-proyecto)
  - [Nombre de la librería](#Nombre-de-librería)
  - [Versión del proyecto](#Versión-del-proyecto)
  - [Enlaces](#Enlaces)
  - [Que incluye](#que-incluye)
  - [Documentación](#Documentación)
  - [Elementos creados con la libreria](#Elemntos-creados-con-la-libreria)
- [Procesos](#Procesos)
  - [Construido con](#Construido-con)
  - [Herramientas utilizadas](#Herramientas-utilizadas)
- [Desarrolladores](#Desarrolladores)

## Descripción general

## Indicaciones

Si desea utilizar nuestra libreria es necesario conocer que procesos se deben de segui, para poder hacer uso correcto de la libreria.

- Primero necesitamos descargar la libreria, [Pulse para iniciar descarga](https://github.com/Jesse-Miranda), luego de haberla descargado es necesario desconprimir el achivo que se genera, veras una carpeta a la hora de descomprimir y a la hora de entrar en esta misma habran otras carpetas donde se encuentran distintos elementos de la libreria por lo cual te dare una lista de carpetas y elementos que puedes eliminar sin que se afecte la libreria, primero puedes empezar eliminando la carpeta HTML si asi lo desea, esta contiene diferentes elementos, como por ejemplo, alerts, badges, buttons, cards, container entre otros elementos, la siguiente carpeta que puedes eliminar es la de de Img ya que en esta solo se encuentran unas imagenes utilizadas unicamente para un diseño en especifico y la ultima carpeta que puedes eliminar es la que se llama Design ya que en esta solo se encuentran capturas de distintos elementos creados.

- Lista de carpetas que no se deben borrar o modificarr, la primera seria la carpeta que se llama Scss esta misma no se debe de modificar ni de eliminar ya que ahi se encuentran la mayoria de elementos, si en un futuro desea agregar un elemnto nuevo y esta carpeta no se encuentra sera imposible agregar algo nuevo, otra carpeta que no se debe de tocar es la de Css, ya que aqui se encuentra la compilacion de los elementos creados en la carpeta Scss, ojo el unico archivo que no se puede eliminar de esta carpeta es el style.css y el style.css.map ya que es esta estan todos los elementos, si usted desea eliminar los otros archivos que se encuentran en esta carpeta, no hay problema alguno en hacerlo.

- Despues de haber aclarado todo lo anterior, podemos empezar a decirte como hacer uso de la libreria, como podras ver en el archivo descargado se encuentra un archivo index.html, puedes borrar todo lo que se muestra en el y agregar las siguientes lineas que se muetran, ahora puedes empezar a hacer uso de la libreria, sigue leyendo la documentacion para que te des cuenta de que se puede crear con la libreria.

```Html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- CSS only -->
    <link rel="stylesheet" href="./Css/style.css">
    <title>GameStation</title>
</head>

<body>

</body>

</html>
```

## Descripción del proyecto

- La página estará centrada en mostrar información acerca de juegos en actualidad y próximos a salir.

## Nombre de la librería

- Game Station

## Versión del proyecto

- versión 0.1

## Enlaces

- Repositorio URL: [GitHub](https://github.com/AlexanderPortillo/GameStation.git)
- Sitio en vivo URL: [GitHub Page]()

## Que incluye

Dentro de la descarga, encontrará los siguientes directorios y archivos, que agrupan lógicamente los activos comunes y brindan variaciones tanto compiladas como minimizadas y tambien encontrará un par de ejemplos demostrando el uso de la libreria.

<details>
  <summary>Ver contenido</summary>

```text
GameStation/
├── css/
│   ├── alerts.css
│   ├── alerts.css.map
│   ├── badges.css
│   ├── badges.css.map
│   ├── border-radius.css
│   ├── border-radius.css.map
│   ├── btn.css
│   ├── btn.css.map
│   ├── colors.css
│   ├── colors.css.map
│   ├── containers.css
│   ├── containers.css.map
│   ├── flexBox.css
│   ├── flexBox.css.map
│   ├── font-size.css
│   ├── font-size.css.map
│   ├── form.css
│   ├── form.css.map
│   ├── margin-padding-border.css
│   ├── margin-padding-border.css.map
│   ├── navbars.css
│   ├── navbars.css.map
│   ├── style.css
│   └── style.css.map
└── Html/
    ├── alerts.html
    ├── badges.html
    ├── buttons.html
    ├── cards.html
    ├── containers.html
    ├── form.html
    ├── navbar.html
    └── row-col.html
```

</details>

## Documentación

| Clases                        | Etiquetas que representa la clase   | unidad | Descripción |
| ----------------------------- | ----------------------------------- | ------ | ----------- |
| `alert`                       | Sin representacion                  | -      |             |
| `alert-warning`               | Sin representacion                  | -      |             |
| `alert-succes`                | Sin representacion                  | -      |             |
| `alert-succes`                | Sin representacion                  | -      |             |
| `alert-link`                  | Sin representacion                  | -      |             |
| `alert-normal`                | Sin representacion                  | -      |             |
| `badges`                      | Sin representacion                  | -      |             |
| `badges-indigo`               | Sin representacion                  | -      |             |
| `badges-olive`                | Sin representacion                  | -      |             |
| `badges-paynes`               | Sin representacion                  | -      |             |
| `badges-red`                  | Sin representacion                  | -      |             |
| `circle-1`                    | border-radius                       | px     |             |
| `circle-t-l-1`                | border-top-left-radius              | px     |             |
| `circle-t-r-1`                | border-top-right-radius             | px     |             |
| `circle-b-l-1`                | border-bottom-left-radius           | px     |             |
| `circle-b-r-1`                | border-bottom-right-radius          | px     |             |
| `box-s-cg-1`                  | box-shadow                          | px     |             |
| `box-s-cg-h-1`                | box-shadow                          | px     |             |
| `box-s-id-1`                  | box-shadow                          | px     |             |
| `box-s-id-h-1`                | box-shadow                          | px     |             |
| `box-s-pb-1`                  | box-shadow                          | px     |             |
| `box-s-pb-h-1`                | box-shadow                          | px     |             |
| `btn`                         | Sin representacion                  | -      |             |
| `btn-gold`                    | Sin representacion                  | -      |             |
| `btn-prusian`                 | Sin representacion                  | -      |             |
| `btn-kelly`                   | Sin representacion                  | -      |             |
| `btn-blue`                    | Sin representacion                  | -      |             |
| `btn-h`                       | Sin representacion                  | -      |             |
| `btn-h-x`                     | Sin representacion                  | -      |             |
| `card`                        | Sin representacion                  | -      |             |
| `card-img`                    | Sin representacion                  | -      |             |
| `card-title`                  | Sin representacion                  | -      |             |
| `card-text`                   | Sin representacion                  | -      |             |
| `card-row`                    | Sin representacion                  | -      |             |
| `card-title`                  | color                               | -      |             |
| `color-red`                   | color                               | -      |             |
| `color-selective-yellow`      | color                               | -      |             |
| `color-olive`                 | color                               | -      |             |
| `color-forrest-green`         | color                               | -      |             |
| `color-dark-pastel-green`     | color                               | -      |             |
| `color-old-gold`              | color                               | -      |             |
| `color-white`                 | color                               | -      |             |
| `color-coquelicot`            | color                               | -      |             |
| `color-peach`                 | color                               | -      |             |
| `color-sandy-brown`           | color                               | -      |             |
| `color-black`                 | color                               | -      |             |
| `color-bistre`                | color                               | -      |             |
| `color-kelly-green`           | color                               | -      |             |
| `color-drab-dark-brown`       | color                               | -      |             |
| `color-hunter-green`          | color                               | -      |             |
| `color-flame`                 | color                               | -      |             |
| `color-prusian-blue`          | color                               | -      |             |
| `color-indigo-dye`            | color                               | -      |             |
| `color-cadet-gray`            | color                               | -      |             |
| `color-engineering-orange`    | color                               | -      |             |
| `color-beaer`                 | color                               | -      |             |
| `color-chamoisee`             | color                               | -      |             |
| `color-satin-sheen-gold`      | color                               | -      |             |
| `color-paynes-gray`           | color                               | -      |             |
| `color-dim-gray`              | color                               | -      |             |
| `bg-red`                      | background-color                    | -      |             |
| `bg-selective-yellow`         | background-color                    | -      |             |
| `bg-olive`                    | background-color                    | -      |             |
| `bg-forrest-green`            | background-color                    | -      |             |
| `bg-dark-pastel-green`        | background-color                    | -      |             |
| `bg-old-gold`                 | background-color                    | -      |             |
| `bg-white`                    | background-color                    | -      |             |
| `bg-coquelicot`               | background-color                    | -      |             |
| `bg-peach`                    | background-color                    | -      |             |
| `bg-sandy-brown`              | background-color                    | -      |             |
| `bg-black`                    | background-color                    | -      |             |
| `bg-bistre`                   | background-color                    | -      |             |
| `bg-kelly-green`              | background-color                    | -      |             |
| `bg-drab-dark-brown`          | background-color                    | -      |             |
| `bg-hunter-green`             | background-color                    | -      |             |
| `bg-flame`                    | background-color                    | -      |             |
| `bg-prusian-blue`             | background-color                    | -      |             |
| `bg-indigo-dye`               | background-color                    | -      |             |
| `bg-cadet-gray`               | background-color                    | -      |             |
| `bg-engineering-orange`       | background-color                    | -      |             |
| `bg-beaer`                    | background-color                    | -      |             |
| `bg-chamoisee`                | background-color                    | -      |             |
| `bg-satin-sheen-gold`         | background-color                    | -      |             |
| `bg-paynes-gray`              | background-color                    | -      |             |
| `bg-dim-gray`                 | background-color                    | -      |             |
| `container`                   | Sin representacion                  | -      |             |
| `container-xxl`               | Sin representacion                  | -      |             |
| `container-xl`                | Sin representacion                  | -      |             |
| `container-ld`                | Sin representacion                  | -      |             |
| `container-md`                | Sin representacion                  | -      |             |
| `container-sd`                | Sin representacion                  | -      |             |
| `center-content`              | Sin representacion                  | -      |             |
| `d-center`                    | Sin representacion                  | -      |             |
| `d-flex`                      | display: flex                       | -      |
| `d-direction-row`             | flex-direction: row                 | -      |             |
| `d-direction-row-reverse`     | flex-direction: row-reverse         | -      |             |
| `d-direction-col`             | flex-direction: column              | -      |             |
| `d-direction-col-reverse`     | flex-direction: row                 | -      |             |
| `d-flex-nowrap`               | flex-wrap: nowrap                   | -      |             |
| `d-flex-wrap `                | flex-wrap: wrap                     | -      |             |
| `d-flex-wrap-reverse`         | flex-wrap: wrap-reverse             | -      |             |
| `d-align-items-start `        | align-items: flex-start             | -      |             |
| `d-align-items-end `          | align-items: flex-end               | -      |             |
| `d-align-items-center`        | align-items: center                 | -      |             |
| `d-align-items-baseline `     | align-items: baseline               | -      |             |
| `d-align-items-stretch`       | align-items: stretch                | -      |             |
| `d-justify-content-start`     | justify-content: flex-start         | -      |             |
| `d-justify-content-end`       | justify-content: flex-end           | -      |             |
| ` d-justify-content-center`   | justify-content: center             | -      |             |
| `d-justify-content-space-ar`  | justify-content: space-around       | -      |             |
| `d-justify-content-space-bet` | justify-content: space-between      | -      |             |
| `d-justify-content-space-ev`  | justify-content: space-evenly       | -      |             |
| `d-align-content-start`       | align-content: flex-start           | -      |             |
| `d-align-content-end`         | align-content: flex-end             | -      |             |
| `d-align-content-center`      | align-content: center               | -      |             |
| `d-align-content-space-ar`    | align-content: space-around         | -      |             |
| `d-align-content-space-bet`   | align-content: space-between        | -      |             |
| `d-align-content-space-ev`    | align-content: space-evenly         | -      |             |
| `d-align-content-stretch`     | align-content: stretch              | -      |             |
| `d-align-self-auto`           | align-self: auto                    | -      |             |
| `d-align-self-start `         | align-self: start                   | -      |             |
| `d-align-self-end`            | align-self: end                     | -      |             |
| `d-align-self-center`         | align-self: center                  | -      |             |
| `d-align-self-baseline`       | align-self: baseline                | -      |             |
| `d-align-self-stretch`        | align-self: stretch                 | -      |             |
| `float-none`                  | float: none                         | -      |             |
| `float-left`                  | float: left                         | -      |             |
| `float-right`                 | float: right                        | -      |             |
| `d-block`                     | display: block                      | -      |             |
| `d-none`                      | display: none                       | -      |             |
| `visible `                    | visibility: visible                 | -      |             |
| `invisible`                   | visibility: hidden                  | -      |             |
| `order-1`                     | order                               | -      |             |
| `gap-1`                       | gap                                 | px     |             |
| `height-1`                    | height                              | vh     |             |
| `font-size-px-1`              | font-size                           | px     |             |
| `font-size-rem-1`             | font-size                           | rem    |             |
| `font-w-100`                  | font-weight: 100                    | -      |             |
| `font-w-200`                  | font-weight: 200                    | -      |             |
| `font-w-300`                  | font-weight: 300                    | -      |             |
| `font-w-400`                  | font-weight: 400                    | -      |             |
| `font-w-500`                  | font-weight: 500                    | -      |             |
| `font-w-600`                  | font-weight: 600                    | -      |             |
| `font-w-700`                  | font-weight: 700                    | -      |             |
| `font-w-800`                  | font-weight: 800                    | -      |             |
| `font-w-900`                  | font-weight: 900                    | -      |             |
| `font-w-bold`                 | font-weight: bold                   | -      |             |
| `font-style-italic`           | font-style: italic                  | -      |             |
| `font-style-oblique`          | font-style: oblique                 | -      |             |
| `text-center`                 | text-align: center                  | -      |             |
| `text-justify`                | text-align: justify                 | -      |             |
| `text-justify-end`            | text-align: end                     | -      |             |
| `text-justify-left`           | text-align: left                    | -      |             |
| `text-justify-right`          | text-align: right                   | -      |             |
| `text-justify-start`          | text-align: start                   | -      |             |
| `pointer`                     | Sin representacion                  | -      |             |
| ``                            |                                     |        |             |
| ``                            |                                     |        |             |
| ``                            |                                     |        |             |
| ``                            |                                     |        |             |
| `m-1`                         | margin                              | px     |             |
| `m-t-1`                       | margin-top                          | px     |             |
| `m-b-1`                       | margin-bottom                       | px     |             |
| `m-l-1`                       | margin-left                         | px     |             |
| `m-r-1`                       | margin-right                        | px     |             |
| `m-t-b-1`                     | margin-top, margin-bottom           | px     |             |
| `m-l-r-1`                     | margin-left, margin-right           | px     |             |
| `p-1`                         | padding                             | px     |             |
| `p-t-1`                       | padding-top                         | px     |             |
| `p-b-1`                       | padding-bottom                      | px     |             |
| `p-l-1`                       | padding-left                        | px     |             |
| `p-r-1`                       | padding-top                         | px     |             |
| `p-t-b-1`                     | padding-top, padding-bottom         | px     |             |
| `p-l-r-1`                     | padding-left, padding-right         | px     |             |
| `b-1`                         | border                              | px     |             |
| `b-t-1`                       | border-top                          | px     |             |
| `b-b-1`                       | border-bottom                       | px     |             |
| `b-l-1`                       | border-left                         | px     |             |
| `b-r-1`                       | border-right                        | px     |             |
| `b-t-b-1`                     | border-top, border-bottom           | px     |             |
| `b-l-r-1`                     | border-left, border-right           | px     |             |
| `nav`                         | Sin representacion                  | -      |             |
| `nav-item`                    | Sin representacion                  | -      |             |
| `nav-lik`                     | Sin representacion                  | -      |             |
| `nav-border`                  | Sin representacion                  | -      |             |
| `active`                      | pointer-events: visible             | -      |             |
| `disabled`                    | pointer-events: none                | -      |             |
| `text-d-under`                | text-decoration: underline          | -      |             |
| `text-d-over`                 | text-decoration: overline           | -      |             |
| `text-d-line`                 | text-decoration: line-through       | -      |             |
| `text-d-blink`                | text-decoration: blink              | -      |             |
| `text-d-none`                 | text-decoration: none               | -      |             |
| `text-d-underover`            | text-decoration: underline overline | -      |             |
| `row`                         | Sin representacion                  | -      |             |
| `row-1`                       | grid-template-rows                  | fr     |             |
| `col-1`                       | grid-template-columns               | fr     |             |
| `span-c-1`                    | grid-column: span                   | -      |             |
| `span-r-1`                    | grid-row: span                      | -      |             |
| `xxl-row-1`                   | grid-template-rows                  | fr     |             |
| `xxl-col-1`                   | grid-template-columns               | fr     |             |
| `xxl-span-c-1`                | grid-column: span                   | -      |             |
| `xxl-span-r-1`                | grid-row: span                      | -      |             |
| `xl-row-1`                    | grid-template-rows                  | fr     |             |
| `xl-col-1`                    | grid-template-columns               | fr     |             |
| `xl-span-c-1`                 | grid-column: span                   | -      |             |
| `xl-span-r-1`                 | grid-row: span                      | -      |             |
| `ld-row-1`                    | grid-template-rows                  | fr     |             |
| `ld-col-1`                    | grid-template-columns               | fr     |             |
| `ld-span-c-1`                 | grid-column: span                   | -      |             |
| `ld-span-r-1`                 | grid-row: span                      | -      |             |
| `md-row-1`                    | grid-template-rows                  | fr     |             |
| `md-col-1`                    | grid-template-columns               | fr     |             |
| `md-span-c-1`                 | grid-column: span                   | -      |             |
| `ld-span-r-1`                 | grid-row: span                      | -      |             |
| `sd-row-1`                    | grid-template-rows                  | fr     |             |
| `sd-col-1`                    | grid-template-columns               | fr     |             |
| `sd-span-c-1`                 | grid-column: span                   | -      |             |
| `ld-span-r-1`                 | grid-row: span                      | -      |             |

## Elementos creados con la libreria

<h1 align="center">Alerts</h1>

![](./Design/alert1.png)

```Html
<span class="alert alert-warning" style="width: 450px">
    <i class="fas fa-exclamation-triangle"></i> An example alert whit warning icon
</span>

<span class="d-flex bg-flame bg-red b-1 circle-5 p-10 font-size-px-25 gap-10"
    style="width: 450px; font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;">
    <i class="fas fa-exclamation-triangle"></i> An example alert whit warning icon
</span>
```

![](./Design/alert2.png)

```Html
<span class="alert alert-succes" style="width: 450px">
    <i class="far fa-check-circle"></i> An example alert whit succes icon
</span>

<span class="d-flex bg-dark-pastel-green bg-forrest-green b-1 circle-5 p-10 font-size-px-25 gap-10"
    style="width: 450px; font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;">
    <i class="far fa-check-circle"></i> An example alert whit succes icon
</span>
```

![](./Design/alert3.png)

```Html
<span class="alert alert-link" style="width: 450px">
    An example alert whit an link
    <a href="#">push here</a>
</span>

<span class="d-flex bg-cadet-gray bg-indigo-dye b-1 circle-5 p-10 font-size-px-25 gap-10"
    style="width: 450px; font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS' sans-serif;">
    An example alert whit an link
    <a href="#">push here</a>
</span>
```

![](./Design/alert4.png)

```Html
<span class="alert alert-normal" style="width: 450px"> This is a normal alert</span>

<span class="d-flex bg-beaer color-chamoisee b-1 circle-5 p-10 font-size-px-25 gap-10"
    style="width: 450px; font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS' sans-serif;">
    This is a normal alert
</span>
```

<h1 align="center">Badges</h1>

![](./Design/badge1.png)

```Html
<span class="badges b-2 circle-4 bg-indigo-dye color-coquelicot d-flex d-align-items-center d-justify-content-center">
    Insiginia roja
</span>

<span class="badges badges-indigo d-flex d-align-items-center d-justify-content-center">
    Insiginia roja
</span>
```

![](./Design/badge2.png)

```Html
<span
    class="badges b-2 bg-olive color-selective-yellow d-flex d-align-items-center d-justify-content-center max-content circle-t-l-20 circle-t-r-15 circle-b-r-15"
    style="width: 150px;">
    Insignia dorada
</span>

<span class="badges badges-olive d-flex d-align-items-center d-justify-content-center max-content"
    style="width: 150px;">
    Insignia dorada
</span>
```

![](./Design/badge3.png)

```Html
<span
    class="badges b-2 circle-4 bg-paynes-gray color-sandy-brown d-flex d-align-items-center d-justify-content-center max-content"
    style="width: 170px;">
    Insignia plateada
</span>

<span class="badges badges-paynes d-flex d-align-items-center d-justify-content-center max-content"
    style="width: 170px;">
    Insignia plateada
</span>
```

![](./Design/badge4.png)

```Html
<span
    class="badges b-2 bg-paynes-gray color-red d-flex d-align-items-center d-justify-content-center max-content circle-t-l-20 circle-b-r-20 pointer font-style-italic box-s-id-h-15"
    style="width: 170px;">
    Insignia especial
</span>

<span
    class="badges badges-red d-flex d-align-items-center d-justify-content-center max-content pointer box-s-id-h-15"
    style="width: 170px;">
    Insignia especial
</span>
```

<h1 align="center">Buttons</h1>

![](./Design/button1.png)

```Html
<button
    class="btn font-w-bold font-style-italic color-old-gold bg-paynes-gray b-1 circle-b-l-15 circle-t-r-15 pointer box-s-pb-10 font-size-px-25 max-content btn-h"
    style="width: 150px; height: 60px;">
    <i class="far fa-paper-plane"></i>
    Enviar
</button>

<button class="btn btn-gold font-w-bold font-style-italic box-s-pb-px-10 font-size-px-25"
    style="width: 150px; height: 60px;">
    <i class="far fa-paper-plane"></i>
    Enviar
</button>
```

![](./Design/button2.png)

```Html
<button
    class="btn btn-h-x font-w-bold font-style-italic color-red bg-prusian-blue pointer circle-4 box-s-pb-10 font-size-px-25 max-content p-10"
    style="width: 180px; height: 60px;">
    <i class="fas fa-download"></i>
    Descargar
</button>

<button class="btn btn-prusian font-w-bold font-style-italic box-s-pb-10 font-size-px-25"
    style="width: 180px; height: 60px;">
    <i class="fas fa-download"></i>
    Descargar
</button>
```

![](./Design/button3.png)

```Html
<a href="#" target="_blank"
    class="btn d-center color-white bg-kelly-green pointer circle-4 font-size-px-20 max-content gap-4"
    style="width: 160px; height: 40px;">
    Sigueme en
    <i class="fab fa-github font-size-px-30"></i>
</a>

<a href="#" target="_blank" class="btn btn-kelly d-center font-size-px-20 gap-4"
    style="width: 160px; height: 40px;">
    Sigueme en
    <i class="fab fa-github font-size-px-30"></i>
</a>
```

![](./Design/button4.png)

```Html
<a href="#" target="_blank"
    class="btn center-content color-white bg-prusian-blue pointer circle-30 box-s-pb-30 max-content gap-4 b-8 box-s-cg-h-50"
    style="width: 40px; height: 40px;">
    <i class="fab fa-facebook-f font-size-px-30"></i>
</a>

<a href="#" target="_blank" class="btn btn-blue center-content box-s-pb-30 gap-4 box-s-cg-h-50"
    style="width: 40px; height: 40px;">
    <i class="fab fa-facebook-f font-size-px-30"></i>
</a>
```

<h1 align="center">Cards</h1>

![](./Design/card1.png)

```Html
<article class="card" style="width:350px;">
    <img src="../Img/dusky-grey-sky-background.jpg" alt="" class="card-img">
    <hr>
    <div class="card-title">Card Title</div>
    <p class="card-text">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Consectetur, sunt quae fugiat
        nobis voluptas optio debitis enim suscipit accusantium placeat rem, voluptatibus laboriosam corporis est
        architecto non ullam eum eius?</p>

    <a href="#" target="_blank" class="btn btn-kelly d-center font-size-px-20 gap-4"
        style="width: 150px; height: 40px;">
        Go somewhere
    </a>
</article>
```

![](./Design/card2.png)

```Html
<article class="card-row" style="width:600px">
    <article>
        <img src="../Img/pngtree-dark-gray-wall-advanced-frosted-texture-background-image_959040.jpg" alt=""
            class="card-img">
    </article>

    <article>
        <div class="card-title ">Card Title</div>
        <p class="card-text">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Consectetur, sunt quae
            fugiat nobis voluptas optio debitis enim suscipit accusantium placeat rem, voluptatibus laboriosam
            corporis est architecto non ullam eum eius?</p>

        <button class="btn btn-gold font-w-bold font-style-italic box-s-pb-10 font-size-px-25"
            style="width: 150px; height: 60px;">
            <i class="far fa-paper-plane"></i>
            Enviar
        </button>
    </article>
</article>
```

![](./Design/card3.png)

```Html
<article class="row col-2 b-1 p-10" style="width:700px;">
    <article class="card" style="width:300px;">
        <div class="card-title">Card Title</div>
        <p class="card-text">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Consectetur, sunt quae
            fugiat nobis voluptas optio debitis enim suscipit accusantium placeat rem, voluptatibus laboriosam
            corporis est architecto non ullam eum eius?
        </p>

        <a href="#" target="_blank" class="btn btn-kelly d-center font-size-px-20 gap-4"
            style="width: 150px; height: 40px;">
            Go somewhere
        </a>
    </article>

    <article class="card" style="width:300px;">
        <div class="card-title">Card Title</div>
        <p class="card-text">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Consectetur, sunt quae
            fugiat nobis voluptas optio debitis enim suscipit accusantium placeat rem, voluptatibus laboriosam
            corporis est architecto non ullam eum eius?
        </p>

        <a href="#" target="_blank" class="btn btn-kelly d-center font-size-px-20 gap-4"
            style="width: 150px; height: 40px;">
            Go somewhere
        </a>
    </article>
</article>
```

<h1 align="center">Columns</h1>

![](./Design/column1.png)

```Html
<div class="text-center m-t-10">
    <div class="row col-5 ld-col-1 gap-10">
        <div class="p-10 span-c-3 ld-span-c-1 col-style">custom column padding</div>
        <div class="p-10 span-c-2 ld-span-c-1 col-style">custom column padding</div>
    </div>
</div>

```

![](./Design/column2.png)

```Html
<div class="text-center m-t-10">
    <div class="row col-5 gap-10">
        <div class="p-10 span-c-1 col-style">custom column padding</div>
        <div class="p-10 span-c-3 col-style">custom column padding</div>
        <div class="p-10 span-c-1 col-style">custom column padding</div>
    </div>
</div>
```

![](./Design/column3.png)

```Html
<div class="text-center m-t-10">
    <div class="row col-1 gap-10">
        <div class="p-10 col-style">custom column padding</div>
    </div>
</div>
```

![](./Design/column4.png)

```Html
<div class="text-center">
    <div class="row col-2 gap-10">
        <div class="p-10 col-style">custom column padding</div>
        <div class="p-10 col-style">custom column padding</div>
    </div>
</div>

```

![](./Design/column5.png)

```Html
<div class="row">
    <div class="text-center row-3 b-1 gap-10">
        <div class="col-4 gap-10">
            <div class="p-10 col-style">custom column padding</div>
            <div class="p-10 col-style">custom column padding</div>
            <div class="p-10 col-style">custom column padding</div>
            <div class="p-10 col-style">custom column padding</div>
        </div>

        <div class="col-4 gap-10">
            <div class="p-10 col-style">custom column padding</div>
            <div class="p-10 col-style">custom column padding</div>
            <div class="p-10 col-style">custom column padding</div>
            <div class="p-10 col-style">custom column padding</div>
        </div>
    </div>
</div>
```

![](./Design/column6.png)

```Html
<div class="row">
    <div class="text-center row-2 b-1 gap-10">
        <div class="col-12 gap-10">
            <div class="p-10 col-style">column</div>
            <div class="p-10 col-style">column</div>
            <div class="p-10 col-style">column</div>
            <div class="p-10 col-style">column</div>
            <div class="p-10 col-style">column</div>
            <div class="p-10 col-style">column</div>
            <div class="p-10 col-style">column</div>
            <div class="p-10 col-style">column</div>
            <div class="p-10 col-style">column</div>
            <div class="p-10 col-style">column</div>
            <div class="p-10 col-style">column</div>
            <div class="p-10 col-style">column</div>
        </div>

        <div class="col-12 gap-10">
            <div class="p-10 col-style">column</div>
            <div class="p-10 col-style">column</div>
            <div class="p-10 col-style">column</div>
            <div class="p-10 col-style">column</div>
            <div class="p-10 col-style">column</div>
            <div class="p-10 col-style">column</div>
            <div class="p-10 col-style">column</div>
            <div class="p-10 col-style">column</div>
            <div class="p-10 col-style">column</div>
            <div class="p-10 col-style">column</div>
            <div class="p-10 col-style">column</div>
            <div class="p-10 col-style">column</div>
        </div>
    </div>
</div>
```

![](./Design/column7.png)

```Html
<div class="row">
    <div class="col-3 gap-10">
        <div class="p-10 col-style span-c-2">custom column padding</div>
        <div class="p-10 col-style span-c-1">custom column padding</div>
        <div class="p-10 col-style span-r-2">custom column padding</div>
        <div class="p-10 col-style">custom column padding</div>
        <div class="p-10 col-style span-r-2">custom column padding</div>
        <div class="p-10 col-style">custom column padding</div>
    </div>
</div>
```

<h1 align="center">Containers</h1>

![](./Design/container1.png)

```Html
<!-- $XX-l: 1400px; -->
<div class="container-xxl">
    <div class="container text-center bg-kelly-green">
        <h1>xx-l</h1>
    </div>
</div>
```

![](./Design/container2.png)

```Html
<!-- $X-l: 1200px; -->
<div class="container-xl">
    <div class="container text-center bg-sandy-brown">
        <h1>x-l</h1>
    </div>
</div>
```

![](./Design/container3.png)

```Html
<!-- $L-d: 992px; -->
<div class="container-ld">
    <div class="container text-center bg-black color-white">
        <h1>l-d</h1>
    </div>
</div>
```

![](./Design/container4.png)

```Html
<!-- $M-d: 768px; -->
<div class="container-md">
    <div class="container text-center bg-flame">
        <h1>m-d</h1>
    </div>
</div>
```

![](./Design/container5.png)

```Html
<!-- $S-d: 576px; -->
<div class="container-sd">
    <div class="container text-center bg-cadet-gray">
        <h1>s-d</h1>
    </div>
</div>
```

![](./Design/container6.png)

```Html
<div class="container-xxl">
    <div class="container text-center bg-kelly-green">
        <h1>xx-l</h1>
    </div>
</div>

<div class="container-xl">
    <div class="container text-center bg-sandy-brown">
        <h1>x-l</h1>
    </div>
</div>

<div class="container-ld">
    <div class="container text-center bg-black color-white">
        <h1>l-d</h1>
    </div>
</div>

<div class="container-md">
    <div class="container text-center bg-flame">
        <h1>m-d</h1>
    </div>
</div>

<div class="container-sd">
    <div class="container text-center bg-cadet-gray">
        <h1>s-d</h1>
    </div>
</div>
```

<h1 align="center">Form</h1>

![](./Design/navbar1.png)

```Html
<form action="" class="bg-prusian-blue p-10 m-20 col bg-flame circle-5 b-1">
    <div class="m-1" style="width: 300px;">
        <label for="email">Correo Electronico</label>
        <input type="email" name="" id="name" placeholder="noobmaster69@example.com" class="m-t-2 m-b-10">

        <label for="textarea">Mensaje</label>
        <textarea name="" id="" cols="30" rows="5" class="textarea m-t-2 m-b-10"></textarea>
        <button type="submit" class="m-4">Enviar</button>
    </div>
</form>
```

![](./Design/navbar1.png)

```Html
<form action="" class="row bg-prusian-blue p-10 m-20 bg-flame circle-5 b-1">
    <div class="col-2 gap-10">
        <label for="email" class="d-flex">Correo Electronico</label>
        <input type="text">

        <label for="password">Contraseña</label>
        <input type="password" placeholder="Contraseña">

        <button class="m-4 height-5" style="width: 100px;" type="submit">Ingresar</button>
    </div>
</form>
```

![](./Design/navbar1.png)

```Html
<div class="form b-1 p-10 circle-10" style="width: 300px;">
    <label for="email">Email Address</label>
    <input type="email" name="" id="email" placeholder="Email">

    <label for="password">password</label>
    <input type="password" name="" id="password" placeholder="password">

    <div class="checkbox">
        <label for="checkbox">
            <input type="checkbox" name="" id="checkbox">Check me ou
        </label>
    </div>

    <a href="#" target="_blank" class="btn btn-kelly d-center font-size-px-20 gap-4"
        style="width: 100px; height: 40px;">
        Submit
    </a>
</div>
```

![](./Design/navbar1.png)

```Html
<div class="form b-1 p-10 circle-10" style="width: 500px;">
    <label for="email">Email Address</label>
    <input type="email" name="" id="email" placeholder="name@example.com">

    <label for="textarea">Example textarea</label>
    <textarea name="" id="textarea" cols="30" rows="10"></textarea>
</div>
```

![](./Design/navbar1.png)

```Html
<div class="form b-1 p-10 circle-10" style="width: 300px;">
    <label for="name">Fist name</label>
    <input type="text" name="" id="name" placeholder="Name">

    <label for="name">Last Name</label>
    <input type="text" name="" id="name" placeholder="Name">

    <label for="email">Email Address</label>
    <input type="email" name="" id="email" placeholder="Email">

    <label for="password">password</label>
    <input type="password" name="" id="password" placeholder="password">

    <div class="checkbox">
        <label for="checkbox">
            <input type="checkbox" name="" id="checkbox">Check me ou
        </label>
    </div>

    <a href="#" target="_blank" class="btn btn-kelly d-center font-size-px-20 gap-4"
        style="width: 100px; height: 40px;">
        Submit
    </a>
</div>
```

![](./Design/navbar1.png)

```Html
<div class="form b-1 p-10 circle-10 disabled" style="width: 500px;">
    <label for="email">Email Address</label>
    <input type="email" name="" id="email" placeholder="name@example.com">

    <label for="textarea">Example textarea</label>
    <textarea name="" id="textarea" cols="30" rows="10"></textarea>
</div>
```

<h1 align="center">Navbars</h1>

![](./Design/navbar1.png)

```Html
<div class="nav bg-prusian-blue p-10 circle-4 d-justify-content-space-bet d-align-items-center">
    <div class="nav-icon">
        <a href="#" class="nav-link d-flex d-align-items-center gap-16">
            <i class="fas fa-atom font-size-px-50 color-red"></i>
            <h3 class="color-red font-w-bold">GameStation</h3>
        </a>
    </div>

    <div class="nav-item gap-40 d-justify-content-space-bet d-align-items-center max-content text">
        <a href="#" class="nav-link text-d-under">Link</a>
        <a href="#" class="nav-link">Link</a>
        <a href="#" class="nav-link text-d-line">Link</a>

        <div class="nav-item gap-10">
            <input type="search" name="" id="" placeholder="Buscar" class="p-4 font-size-px-20"
                style="width: 260px;">

            <a href="#" target="_blank"
                class="nav-link btn d-center color-black active b-1 pointer circle-4 font-size-px-20 max-content gap-4"
                style="width: 100px; height: 30px;">
                Search
            </a>
        </div>
    </div>
</div>
```

![](./Design/navbar2.png)

```Html
<div class="nav bg-prusian-blue p-10 circle-4 d-justify-content-center d-align-items-center">
    <a href="#" class="nav-link">Link</a>
    <a href="#" class="nav-link">Link</a>
    <a href="#" class="nav-link">Link</a>
</div>
```

![](./Design/navbar3.png)

```Html
<div class="nav bg-prusian-blue p-10 circle-4 d-justify-content-space-ar d-align-items-center">
    <a href="#" class="nav-link">Link</a>
    <a href="#" class="nav-link">Link</a>
    <a href="#" class="nav-link">Link</a>
</div>
```

![](./Design/navbar4.png)

```Html
<div class="nav bg-prusian-blue p-10 circle-4">
    <a href="#" class="nav-link">Link</a>
    <a href="#" class="nav-link">Link</a>
    <a href="#" class="nav-link">Link</a>
</div>
```

![](./Design/navbar5.png)

```Html
<div class="nav bg-prusian-blue p-10 circle-4 d-justify-content-end">
    <a href="#" class="nav-link">Link</a>
    <a href="#" class="nav-link">Link</a>
    <a href="#" class="nav-link">Link</a>
</div>
```

![](./Design/navbar6.png)

```Html
<div class="nav bg-prusian-blue p-10 circle-4 d-direction-col">
    <a href="#" class="nav-link">Link</a>
    <a href="#" class="nav-link">Link</a>
    <a href="#" class="nav-link">Link</a>
</div>
```

![](./Design/navbar7.png)

```Html
<div class="nav bg-prusian-blue p-10 circle-4 d-direction-row-reverse d-justify-content-end d-align-items-center">
    <a href="#" class="nav-link">Link</a>
    <a href="#" class="nav-link">Link</a>
    <a href="#" class="nav-link">Link</a>
    <input type="search" name="" id="" placeholder="Buscar" class="p-4 font-size-px-20">
</div>
```

![](./Design/navbar8.png)

```Html
<div class="nav bg-prusian-blue p-10 circle-4 d-justify-content-space-bet d-align-items-center">
    <li class="nav-item">
        <a href="#" target="_blank"
            class="nav-link btn d-center color-black active b-1 pointer circle-4 font-size-px-20 max-content gap-4"
            style="width: 160px; height: 40px;">
            Link
        </a>
    </li>

    <li class="nav-item">
        <a href="#" target="_blank"
            class="nav-link btn d-center disabled color-black b-1 pointer circle-4 font-size-px-20 max-content gap-4"
            style="width: 160px; height: 40px;">
            Disabled
        </a>
    </li>

    <li class="nav-item">
        <a href="#" target="_blank"
            class="nav-link btn d-center color-white bg-kelly-green pointer circle-4 font-size-px-20 max-content gap-4"
            style="width: 160px; height: 40px;">
            Link
        </a>
    </li>
</div>
```

## Procesos

## Construido con

- Marcado semántico HTML5
- Propiedades personalizadas de CSS
- Flex box
- Css Grid
- Diseño responsivo
- Sass
- Git

## Herramientas utilizadas

- [VSCode](https://code.visualstudio.com/)
- [Sass](https://sass-lang.com/)
- [Git](https://git-scm.com/)
- [GitHub](https://github.com/)
- [TinyPNG](https://tinypng.com/)
- [Font Awesome](https://fontawesome.com/)
- [Icons](https://iconos8.es/icons/set/ico)
- [Xtrafondos](https://www.xtrafondos.com/)
- [Color Hunt](https://colorhunt.co/)
- [Google Fonts](https://fonts.google.com/)
- [Coolors](https://coolors.co/image-picker)

## Desarrolladores

- Denis Alexander Martel Portillo MP20002 - [AlexanderPortillo](https://github.com/AlexanderPortillo)
- Gerardo Alexander López Medrano LM20003 - [MedranoGerardo](https://github.com/MedranoGerardo)
- Jesse Antonio Miranda Pérez MP20049 - [Jesse-Miranda](https://github.com/Jesse-Miranda)
