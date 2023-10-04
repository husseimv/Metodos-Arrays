# Clase 10

## Igualdad Débil / Operador Comparación (==)

El operador de comparacion (==) comprueba si sus dos operandos son iguales y devuelve un resultado booleano. A diferencia del operador de igualdad estricta (= = =), es que este convierte y compara operandos que son de diferentes tipos.

### Ejemplos:

console.log(1 == 1);
// Expected output: true

console.log('hello' == 'hello');
// Expected output: true

console.log('1' == 1);
// Expected output: true

console.log(0 == false);
// Expected output: true

## Igualdad Estricta / Operador de Identidad (===)

El operador de estricta igualdad (= = =) revisa si dos operandos son iguales y produce un resultado Booleano. A diferencia del operador de igualdad regular (==), el operador de estricta igualdad siempre considera que los operandos de distinto tipo de valor son diferentes y nunca similares.

### Ejemplos:

console.log(1 === 1);
// Expected output: true

console.log('hello' === 'hello');
// Expected output: true

console.log('1' === 1);
// Expected output: false

console.log(0 === false);
// Expected output: false
