## Variables
 
Las variables deben ser declaradas antes de poder usarse. Para 
declararlas se usa `let` o `const`:
  
- Let permite cambiar el contenido de la variable a posteriori
- Const no permite cambiar el contenido de la variable 

Una vez se ha declarado la variable, ya se puede usar.

```js
// Declaración de una variable.
// Hay que declarar las variables (const o let) antes de poder usarlas
// Let permite la reasignación de una variable y const no lo permite
let nombre = 'Juan';

// Re-asignación de una variable
nombre = 'Alice';
nombre = 'Bob';

// Imprimimos el valor de la variable
console.log(nombre);
```
### Tipos de variables 

Las variables tienen tipos:

- Boolean
- Number
- String
- Object (y Arrays)
- Function

También existen los tipos:

- BigInt
- Symbol

Estructuras de control:

- if/else
- for/while
- switch

Promesas y async/await

Ejemplo con booleans:

```js
// Declaro una variable de tipo boolean cuyo valor es "false"
let esMayorDeEdad = true;

if (esMayorDeEdad) {
  // Si "esMayorDeEdad" es "true" se ejecuta esta línea
  console.log('Bienvenido, entre por favor');
} else {
  // En caso contrario se ejecuta esta línea
  console.log('Lo siento, debe ser mayor de edad para entrar');
}
```

Ejemplo con números:

```js
let edad = 21;
let edadMinima = 18;

let suma = edad + edadMinima;
let resta = edad - edadMinima;
let multiplicacion = edad * edadMinima;
let division = edad / edadMinima;
let mayorQue = edad > edadMinima;
let menorQue = edad < edadMinima;
let menorOIgualQue = edad <= edadMinima;
let mayorOIgualQue = edad >= edadMinima;

// Comparación de igualdad, es con tres signos de igual
let sonIguales = edad === edadMinima;
```

Ejemplo con strings:

```js
// Declaro una variable de tipo number cuyo valor es 21
let nombre = 'Juan';
let apellidos = 'García Herrera';

// Concatenación
let nombreCompleto = nombre + ' ' + apellidos;

// Interpolación
let texto = `Mi nombre es ${nombreCompleto}`;

// Ejemplo de llamada a un método de String
let resultado = texto.toUpperCase();
```