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
