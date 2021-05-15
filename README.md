# Academia Soft   
![](https://raw.githubusercontent.com/AcademiaSoft/Pagina-Soft/master/img/logo.jpg)



## Tabla de contenido
- [Academia Soft](#academia-soft)
  - [tabla de contenido](#tabla-de-contenido)
  - [introduccion](#introduccion)
  - [reglas de negocio](#reglas-de-negocio)
  - [requerimientos](#requerimientos)
    - [levantamiento de requerimientos](#levantamiento-de-requerimientos)
    - [Analisis de requerimientos](#analisis-de-requerimientos)
    - [diseño de requerimientos](#diseño-de-requerimientos)
  - [desalloro](#desalloro)
  - [pruebas](#pruebas)
  - [implementacion](#implementacion)
  - [mantenimiento y fucionamiento](#mantenimiento )
  - [Documentacion](#documentacion)
    - [clientes](#clientes)
      - [*Diseño*](#diseño)

## introduccion 
  
   
   ***Esta página tiene la facilidad de interactuar con el usuario generándole información frenta a los curso que puede tomar en  Academia Soft que son:***

   - HTML 5
   - WED DESING 
   - VIDEO PRODUCTION 
   - SEO 
   - MARQUETINK 
   - INFOGRAMS 
  
## reglas de negocio 
   
  |reglas de negocio         |funciones | 
  |--------------------------|----------|
  | funciones de la pagina web|<lu><li>informacion de la pagina</li><li>programas de formacion </li><li>caja de interesados en el plan de estudio</li></ul> 
  |procesos |<lu><li>Atencion al cliente </li><li> Maestros de cada materia</li><li>programador web</li><li>Decano</li></ul> 

 
# requerimientos 

  - programador de base de datos. 
  - diseñador web. 
  - estudiantes. 
  - profesores. 
  - plande negocios. 
  - Area administrativa. 
  - Area de dudas y respuestas (correo, Telefonico ,redes sociales )
  

## levantamiento de requerimientos 


## Analisis de requerimientos 

## diseño de requerimientos 

## desalloro

 CSS 57.5%

  ```CSS 
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}


body {
    font-family: 'Roboto', sans-serif;
}

h1,
h2,
h3,
h4,
h5,
h6 {
    color: #1d273b;
    font-weight: 300;
}

.lds-ring {
    display: inline-block;
    position: relative;
    width: 80px;
    height: 80px;
  }
  .lds-ring div {
    box-sizing: border-box;
    display: block;
    position: absolute;
    width: 64px;
    height: 64px;
    margin: 8px;
    border: 8px solid #fff;
    border-radius: 50%;
    animation: lds-ring 1.2s cubic-bezier(0.5, 0, 0.5, 1) infinite;
    border-color: #fff transparent transparent transparent;
  }
 ```
 HTML 36.7%
 ```HTML 
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pagina Web Soft</title>
    <link rel="stylesheet" href="css/estilos.css">
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@100;300;400;700&display=swap" rel="stylesheet">
    <script src="https://kit.fontawesome.com/9b775dc524.js" crossorigin="anonymous"></script>
</head>
<body>
    <div class="lds-ring loader" id="loader"><div></div><div></div><div></div><div></div></div>
    <header>
        <nav>
            <section class="contenedor nav">
                <div class="logo">
                    <img src="img/logo.png" alt="">
                </div>
                <div class="enlaces-header">
                    <a href="#">Soft</a>
                    <a href="#">Soft</a>
                    <a href="#">Soft</a>
                    <a href="#">Soft</a>
                    <a href="#">Soft</a>
                </div>
                <div class="hamburguer">
                    <i class="fas fa-bars"></i>
                </div>
            </section>
        </nav>
```
JavaScript 5.8%

```JavaScript 
let ubicacionPrincipal = window.pageYOffset; //0

  AOS.init();

window.addEventListener("scroll", function(){
    let desplazamientoActual = window.pageYOffset; //180
    if(ubicacionPrincipal >= desplazamientoActual){ // 200 > 180
        document.getElementsByTagName("nav")[0].style.top = "0px"
    }else{
        document.getElementsByTagName("nav")[0].style.top = "-100px"
    }
    ubicacionPrincipal= desplazamientoActual; //200
})
// Menu
let enlacesHeader = document.querySelectorAll(".enlaces-header")[0];
let semaforo = true;
document.querySelectorAll(".hamburguer")[0].addEventListener("click", function(){
    if(semaforo){
        document.querySelectorAll(".hamburguer")[0].style.color ="#fff";
        semaforo= false;
    }else{
        document.querySelectorAll(".hamburguer")[0].style.color ="#000";
        semaforo= true;
    }
    enlacesHeader.classList.toggle("menudos")
    })
/* LOADER */
window.addEventListener("load", function(){
    document.getElementById("loader").classList.toggle("loader2")}
```


## pruebas 

## implementacion 

## mantenimiento y fucionamiento
 ![](https://raw.githubusercontent.com/AcademiaSoft/Pagina-Soft/master/img/diagrama_de_flujo_soft.jpg)


## Documentacion 

### clientes 

  - Etapas 

  - Tiempo 

  - Costo 

  - licencia: [Aqui](https://co.creativecommons.net/tipos-de-licencias/) 
  
  ![](https://raw.githubusercontent.com/AcademiaSoft/Pagina-Soft/master/img/licencia..jpeg) 
  
    * Atribución – No comercial – Compartir igual: Esta licencia permite a otros distribuir, remezclar, retocar, y crear a partir de tu obra de modo no comercial, siempre y cuando te den crédito y licencien sus nuevas creaciones bajo las mismas condiciones.*
#### *Diseño*
 ![](https://raw.githubusercontent.com/AcademiaSoft/Pagina-Soft/master/img/20210224_153809.gif)

  - mockups
  - reglas del negocio: cliente:
   - proceso 
   - acciones diarias 
   - estructura administrativa 
   





