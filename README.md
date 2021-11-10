# Ejercicios para sección reportes

1. Hacer la función `encontrarNumeroMayor` que reciba un array de números y retorne el mayor de todos ellos. (Pista: usá reduce)

```js

 const numeros = [2, 3, 4, 99, 5, 9, 65, 32]
 const masNumeros = [43, 21, 23, 66, 54, 32, 199, 54, 63]
 
 const encontrarNumeroMayor = (array) => {
 // codeá tu solución acá
 }
 
 console.log(encontrarNumeroMayor(numeros)) // deberias ver 99
 console.log(encontrarNumeroMayor(masNumeros)) // deberias ver 199

```


2. Una vez resuelto el ejercicio anterior, vamos a complicarlo. Dado un array de objetos, hacé la función `encontrarNumeroMayorEnArrayDeObjetos` que reciba un array de objetos y retorne el objeto que tiene el mayor número en la propiedad `monto`. La estrategia deberia ser similar al ejercicio anterior. Pista: recordá que en un reduce, si no le pasas un valor inicial a la acumuladora, la acumuladora tendrá el valor del primer elemento del array. 

```js

 const objetos = [
  {
    tipo: "ganancia",
    categoria: "comida",
    monto: 10,
  },
  {
    tipo: "ganancia",
    categoria: "salida",
    monto: 100,
  },
  {
    tipo: "gasto",
    categoria: "salida",
    monto: 1000,
  },
  {
    tipo: "gasto",
    categoria: "salida",
    monto: 10000,
  },
  {
    tipo: "ganancia",
    categoria: "comida",
    monto: 1000,
  },
];

 const masObjetos = [
  {
    tipo: "ganancia",
    categoria: "comida",
    monto: 99,
  },
  {
    tipo: "ganancia",
    categoria: "salida",
    monto: 999,
  },
  {
    tipo: "gasto",
    categoria: "salida",
    monto: 999999,
  },
  {
    tipo: "ganancia",
    categoria: "salida",
    monto: 999,
  },
  {
    tipo: "ganancia",
    categoria: "comida",
    monto: 99999,
  },
];
 
 const encontrarNumeroMayorEnArrayDeObjetos = (array) => {
 // codeá tu solución acá
 }
 
 console.log(encontrarNumeroMayor(objetos)) // deberias ver { tipo: "gasto", categoria: "salida", monto: 10000 }
 console.log(encontrarNumeroMayor(masObjetos)) // deberias ver { tipo: "gasto", categoria: "salida", monto: 999999 }

```


3. Una vez resuelto el ejercicio anterior, declará la función `obtenerObjetoConMayorGanancia` que reciba un array de objetos y retorne el objeto que tenga el mayor monto pero sólo si su tipo es `ganancia`. La estrategia debería ser similar a la del ejercicio anterior. Pista: recordá que podés usar `if` adentro de un reduce.  

```

// usá los mismos arrays de objetos que usamos en el ejercicio anterior

 const obtenerObjetoConMayorGanancia = (array) => {
 // codeá tu solución acá
 }
 
 console.log(encontrarNumeroMayor(objetos)) // deberias ver { tipo: "ganancia", categoria: "comida", monto: 1000 }
 console.log(encontrarNumeroMayor(masObjetos)) // deberias ver { tipo: "ganancia", categoria: "comida", monto: 99999 }
 
 ```



3. Una vez resuelto el ejercicio anterior, declará la función `obtenerCategoriaConMayorGanancia` que reciba un array de objetos y retorne *sólo la propiedad categoria* del objeto que tenga el mayor monto pero sólo si su tipo es `ganancia`. La estrategia debería ser similar a la del ejercicio anterior. Pista: recordá que podés usar el operador `&&` adentro de un if para encadenar varias condiciones.  

```

// usá los mismos arrays de objetos que usamos en el ejercicio anterior

 const obtenerCategoriaConMayorGanancia = (array) => {
 // codeá tu solución acá
 }
 
 console.log(encontrarNumeroMayor(objetos)) // deberias ver  "comida"
 console.log(encontrarNumeroMayor(masObjetos)) // deberias ver "comida"
 
 ```
