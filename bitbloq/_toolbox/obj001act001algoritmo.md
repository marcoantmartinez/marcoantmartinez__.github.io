<!--
edited  : Marco Antonio Martínez Ramos
email   : marcoantmartinez@gmail.com
release : 2017.04.01 v01
review  : na
github  : https://github.com/marcoantmartinez/marcoantmartinez.github.io/tree/master/bitbloq
license : CC BY-SA This learning resource is provided for free by marcoantmartinez@gmail.com under a Creative Commons Attribution-ShareAlike 4.0 International License.
others  : Bitbloq is a project provided for free by BQ (c)
-->

<link href="https://fonts.googleapis.com/css?family=Roboto+Slab:100,300,400,700|Roboto:100,100i,300,300i,400,400i,500,500i,700,700i,900,900i" rel="stylesheet" type='text/css'>
<!-- <link href="https://github.com/marcoantmartinez/marcoantmartinez.github.io/blob/master/bitbloq/html/mystyles.css" rel="stylesheet" type="text/css" media="screen"/> 
 -->

<div id="div_exterior" class="fontbody" > 

<div class="fontheader" >
	<a  style="color:#476419;" href="http://bitbloq.bq.com" title="View this resource on Bitbloq site">Bitbloq is a project provided for free by BQ (c)</a>
</div>

<div class="bannerheader">
	<a href="a" target="_blank">
	    <img src="http://i.imgur.com/srtYM4W.png" alt="">
	</a>
<div class="bannerfooter">

<h1>
    <div class="fonth1tittle">
        <span class="fa-stack fa-lg">
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-sitemap fa-stack-1x colortools"></i>
        </span> 
        Bloques de control
    </div>
</h1>



<div class="linksheader">
	<a href="#recursos-necesarios"><i class="fa fa-check-square-o"></i> Recursos</a> |
	<a href="#resumen-de-leccion"><i class="fa fa-check-square-o"></i> Resumen</a> |
	<a href="#objetivos-de-aprendizaje"><i class="fa fa-check-square-o"></i> Objetivos</a> |
	<a href="#aplicaciones-transversales"><i class="fa fa-check-square-o"></i> Transversales</a> |
	<a href="#inicio"><i class="fa fa-check-square-o"></i> Inicio</a> |
	<a href="#desarrollo"><i class="fa fa-check-square-o"></i> Desarrollo</a> |
	<a href="#puesta-en-comun"><i class="fa fa-check-square-o"></i> En común</a> |
	<a href="#reto"><i class="fa fa-check-square-o"></i> Reto</a> |
	<a href="#evaluacion"><i class="fa fa-check-square-o"></i> Evaluación</a>
</div>

<h1>
    <div class="fonth1subtittle">
    <span> Algoritmos</span> 
    </div>
</h1>

En esta lección tú ...
- Entenderás que es un algoritmo.
- Comprenderás cuáles son sus partes principales
- Serás capaz de inicializar, preparar y ejecutar un algoritmo básico de Arduino.


<h2>
    <div id="que-es" class="fonth2tittle">
        <span class="fa-stack fa-lg" >
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-wrench fa-stack-1x colortools"  ></i>
        </span> ¿ Qué es un algoritmo ?
    </div>
</h2>

Diariamente todos utilizamos algoritmos sin saberlo, forman parte de todas nuestras actividades cotidianas, por ejemplo todos los días al levantarnos hacemos una serie de cosas rutinarias antes de llegar al colegio:
- Suena el despertador
- Nos levantamos
- Desayunamos
- Nos aseamos
- Nos vestimos
- Preparamos la cartera
- Nos desplazamos al colegio

Esa listas de cosas que hacemos sería un ejemplo de **algoritmo sencillo** que podríamos llamar **Cosas que hacer antes de ir al colegio**.

Ahora imagina a dos niños **Juan** y **Clara** que van al mismo colegio, Juan vive a **1 km** de la escuela y el Clara a **6 km**, el algoritmo **Cosas que hacer antes de ir al colegio** ¿serviría para los dos? o se podría mejorar adaptándolo a las necesidades de **Juan** y **Clara**.

> Preguntate si Juan y Clara se tendrán que levantar a la misma hora ?

> Preguntate si utilizan los mismos medios para ir al colegio ?

Habrás llegado a la conclusión de que el algoritmo se puede adaptar a cada niño y hacerlo más preciso, por ejemplo:

::: success
 Cosas que hace **Juan** antes de ir al colegio : 
- Suena el despertador a las 8:00 de la mañana
- Se levanta en menos de 10 minutos
- Desayuna en 20 minutos
- Se asea en 10 minutos
- Se viste en 10 minutos
- Prepara la cartera en 5 minutos
- Su madre le acompaña hasta el colegio andando en 5 minutos
:::

::: success
 Cosas que hace **Clara** antes de ir al colegio
- Suena el despertador a las 8:00 de la mañana
- Se levanta en menos de 5 minutos
- Desayuna en 15 minutos
- Se asea en 15 minutos
- Se viste en 10 minutos
- Prepara la cartera en 5 minutos
- Su padre la lleva en coche hasta el colegio en 10 minutos
:::

```mermaid
gantt
    dateFormat  HH
    title Adding GANTT diagram to mermaid

    section A section
    Despertador            :done,    des1, 08,08:00
```


Los dos han tardado lo mismo pero el tiempo que han empleado para hacer las cosas es distinto.

::: info
Es decir un algoritmo necesita ser **Preciso** para cumplir bien su función
:::


**Pregunta 1**
- ¿ Los algoritmos sólo los utilizan las máquinas ?
- ¿ Crees que Leonado da Vincy utilizaba algoritmos ?


Definición formal de **Algoritmo**:
> Es un conjunto prescrito de instrucciones o reglas bien definidas, ordenadas y finitas que permite llevar a cabo una actividad mediante pasos sucesivos que no generen dudas a quien deba hacer dicha actividad.

> Dados un estado inicial y una entrada, siguiendo los pasos sucesivos se llega a un estado final y se obtiene una solución.


<h2>
    <div id="resumen-de-leccion" class="fonth2tittle">
        <span class="fa-stack fa-lg">
            <i class="fa fa-square fa-stack-2x fa-inverse" ></i>
            <i class="fa fa-list-ol fa-stack-1x colortools" ></i>
        </span> Resumen de lección
    </div>
</h2>



<br>
<br>

***
<div class="fontfooter">
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">
	<img alt="Creative Commons License" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" />
</a></br>This learning resource is provided for free by 
<a rel="email" href="marcoantmartinez@gmail.com">marcoantmartinez@gmail.com</a> under a 
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
</br>
<a href="https://github.com/marcoantmartinez/marcoantmartinez.github.io/tree/master/bitbloq" title="View and edit this resource on GitHub">
	<img src="http://i.imgur.com/MijfOYX.png" alt=""><br>View and edit this resource on GitHub  
</a>
</div>

</div>
</div>
</div>
<details>
	<style>
		.bannerheader{
			width:100%; 
			margin: 0 auto;
			display: table; 
			min-width: 800px; 
			max-width: 900px; 
			background-color:#ffffff; 
			border:10px solid #96c93e;
		}
		.bannerfooter{
			width:100%;
			background:#ffffff; 
			padding: 5%;
			position:relative; 
			top:0;  
			left:0; 
			background-image: url("https://s-media-cache-ak0.pinimg.com/originals/7f/6c/91/7f6c917473453d67602d42f38dfb94f2.png"); 
			background-repeat: no-repeat ;
			-webkit-background-size: cover;
			-moz-background-size: cover;
			-o-background-size: cover; 
			background-size:100% 40%; 
			background-position: bottom;
		}
		.linksheader{
			padding:10px;
			text-align:center; 
			font-size:14px; 
			color:#729e29
		}
		.fontnotes{
			width:33%;
			margin-left:auto; 
			margin-right:0;
			border-radius: 15px;
			padding:2px;
			text-align:center;
			background-color:#ff8000;
			padding: 0px;
			font-family: Roboto, serif; 
			font-size: 13px; 
			font-weight: 300; 
			letter-spacing: 0px
		}
		.fontbody{
			width: 100%; 
			overflow: auto; 
			background-color: #ffffff; 
			position: absolute; 
			top: 0px; 
			left: 0px; 
			font-size: 22px; 
			font-family: 'Europa', sans-serif ; 
			font-weight: lighter; 
			letter-spacing: 0px;
			line-height: 30px;
margin: 0 0; 
		}
		.fonth1tittle{
			position:absolute;
			left:0%;
			top:0px;
			width:100%; 
			border-radius: 0px;
			padding:0px;
			background: linear-gradient(to right, #96c93e, #96c93e 100%);
			line-height:0px;
			color:#ffffff;
			font-family:'Roboto Slab', serif;
			font-size:36px; 
			font-weight:700;
			text-align: center;
			border:0px solid blue;
		}
		.fonth1subtittle{
			position:relative;
			left:0px;
			top:0px;
			width:100%; 
			border-radius: 0px;
			padding:0px;
			background: linear-gradient(to right, white, white 100%);
			line-height:0px;
			color: #5e8421;
			font-family:'Roboto Slab', serif;
			font-size:36px; 
			font-weight:700;
			text-align: center;
			border:30px solid white;
		}
		.fonth2tittle{
			position:relative;
			left:-5%;
			width: 75%;
			border-radius: 15px;
			padding:0px; 
			background-color: #96c93e;
			line-height:0;
			color:#ffffff; 
			font-family:'Roboto Slab', serif;
			font-size:23px; 
			font-weight:700;
		}
		.fontheader{
			width:50%;
			margin: 0 auto;
			position: absolute;
			left: 25%; 
			top:0px; 
			border:0px solid #000000;
			text-align: center; 
			color:#476419;
			font-family: Roboto, serif; 
			font-size: 13px; 
			font-weight: 300; 
			letter-spacing: 0px
		}
		.fontfooter{
			width:52%;
			margin: 0 auto;
			text-align: center; 
			color: #729e29; 
			font-family: Roboto, serif; 
			font-size: 13px; 
			font-weight: 300; 
			letter-spacing: 0px
		}
		.colortools{
			color:#5e8421;
		}
		.colornotes{
			color:#ff8000;
		}
	</style>
</details>