<!--lenguaje markdown
objetivo: proporcionar una herramienta para documentar codigo, o aspectos tecnicoa para compartirlos o tenerlos de refenrecia en mi git hub o otra plataforma.

markdown es un lenguaje de marcado ligero 

el objetivo de su creador fue hacer quela gente pudiera escribir usando un formato de texto plano facil de leer
facil de escribir y con la posibilidad de convertir su documento en html valido.

la gran simpleza de su sintaxis hizo que tuviera una rapida adopcion y popularidad en la comunidad de desarrolladores.

actualmente aparte de permitir generar contenido html de forma dinamica, tambien se emplea (casi de forma estandar)
para la creacion de documentacion tecnica y con la proliferacion de la arquitectura JAM Stack para la creacion de sitios estaticos a traves de herramientas de tipo SSG(static site generator) y ssr (sergey side rendering) como hugo, gatsby, eleventy, next js, sergey-->

### conocer sintaxis Markdown

### 1.-parrafos
Lorem Ipsum es simplemente el texto de relleno de las imprentas y archivos de texto. Lorem Ipsum ha sido el texto de relleno estándar de las industrias desde el año 1500, cuando un impresor (N. del T. persona que se dedica a la imprenta) desconocido usó una galería de textos y los mezcló de tal manera que logró hacer un libro de textos especimen.

_Cursiva_  
**Negrita**  
~Tachado~ 
**_Cursiva y Negrita_**  
_~Cursiva y Tachado~_  
**_Negrita y Tachado_**  
**_~Cursiva, Negrita y Tachado`~_**


#     encabezado nivel 1
##    encabezado nivel 2
###   encabezado nivel 3
####  encabezado nivel 4
##### encabezado nivel 5
###### encabezado nivel 6

### divisiones

un bloque de contenido
---
este es otro bloque de contenido

### listas
podemos utilizar las listas ordenadas y desordenadas

1. html5
1. css
1. javascript
1. ajax
1. json

### citas
podemos dar formato de cita a un texto, anteponiendo a la linea de texto un caracter de mayor que (>).

la IA en el futuro reemplazara muchas profeciones de TI. -Ad Nasser

chatgpt debe potenciar mi aprendizaje, no suprimir mi estado autodidacta.

Ad Nasser

### enlaces 
[youtube](https://www.youtube.com)

[enlace a google](https://www.google.com)

### imagenes
![texto alternativo](URLdelaimagen)

### tablas
|columna 1 |columna 2|columna 3|
|----------|---------|---------|
|A         |B        |C        |
|D         |E        |F        |
|G         |H        |I        |

### codigo
podemos dar formato de codigo aun texto para ello se usa el cento grave (`).

esto es`codigo` en linea.

en javascript  una variables se define asi:
`let saludo = "Hola Mundo";`

pero si queremos sacar un bloque completo de codigo utilizamos':

```js
let estudiante="juan perez";
let edad=19;
let isestudiante=true;
let calificacion=90.0;

//1 operadores aritmeticos
let A=10;
let B=3;

console.log(a+b);//suma
console.log(a-b);//resta
console.log(a*b);//multi
console.log(a/b);//div
console.log(a%b);//modulo

//2. operadores de asignacion
let x=10;
x += 5; //x=15
x -= 2;//x=13
x *= 3;//x=39
x /= 3;//x=13
x %= 5;//x=3

//3. operadores de comparacion
let a=5; let b='5';
console.log(a == b); //true (compara el valor, pero no el tipo)
console.log(a === b);
console.log(a != b);
console.log(a !== b);
console.log(a > 3);
console.log(a <= 5);

//4. operadores logicos 
let d= true;
let f=false;*/

//alert("estamos en el archivo de estruturas de ciclo");

//estrutura de control for
for (let i=0; i<=10;i++){
    console.log("no iteracion: "+ i);
}

//estructura while
let contador=1;

while (contador<10){
    console.log("[while] no iteracion: "+ contador)
    contador++;
}

//estructura do while
let numero=1;
do{
    console.log("[do while]no iteracion: "+ numero);
    numero++;
}while(numero <10);

//for in
let estudiante ={nombre:"Don Totis", edad:50,calificacion:70};

for (let propiedad in estudiante){
    console.log(propiedad + ": " + estudiante[propiedad]);
}
//for ...of 
//este ciclo itera sobre los valores de un objeto iterable (como un array).
let misnumeros=[10,20,30,40,50];

for(let numero of misnumeros){
    console.log(numero);
}

```

<!--esto es un comentario-->



