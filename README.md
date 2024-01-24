forEach --> método arrays/lista-nodos ---> ejecutar un CALLBACK por cada uno de los elementos de la colección/array

LISTA/ARRAY.forEach(Callback)

callback --> tres argumentos --> elemento,índice,toda la colección de elementos 

map --> crea un nuevo array a partir de otro utilizando un CALLBACK 

filter ---> crea un nuevo array filtrando otro, como filtro, utiliza un CALLBACK, si el CALLBACK retorna TRUE, el elemento se queda en el nuevo array, de lo contrario es filtrado 


promesa ----> función asíncrona

new Promise(función)

.then ---> configurar el callback para cuando se cumpla la promesa 

PROMESA.then(callback)

2 callbacks ----> OK (fulfill) | KO (reject)

PROMESA
.then(callback_fulfill)
.catch(callback_reject)
.finally(callback_siempre)


async/await

try - catch

try{
    escribir código que puede tirar una excepción
}catch(excepción){

}
------------------------

ajax --> asynchronous javascript and xml

xhr xml http request 
JSON --> javascript object notation

{
    blabla : "bla",
    otro : 234
}

'{ "blabla" : "bla", "otro" : "234" }' <-- string codificado JSON



FETCH ---> peticiones asíncronas al servidor

fetch(URL,objeto petición-request) --> RETORNA UNA PROMESA con un objeto response

response ---> text/json 

.text()
.json()
AMBOS retornan promesas con el contenido (body) procesado


operador typeof

typeof x ---> retorna el TIPO de x

--------------------------------------

html ---> estructura/contenido
css ---> apariencia
js --> comportamiento

------------------------

1)servir ficheros estáticos (nginx/apache)
----------
2)conectarse a una base/fuente de datos
3)procesar datos/generar html dinámico

cualquier lenguaje de programación
a)http --> recibir y responder peticiones 
b)poder interactuar con el sistema de ficheros (abrir/crear/guardar,etc ficheros)


NODEjs ---> runtime de JS 
deno
bun 

CLI 

sistema de ventanas
aplicaciones
sistema operativo ---> APIs que permiten interactuar con la maquina

ls
cd --> change directory
cd ruta(absoluta o relativa)

clear
