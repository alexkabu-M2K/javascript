# Fundamentos do JavaScript Clássico

## INTEGRAÇÕES

### Integrar JavaScript de forma interna

~~~ html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JavaScript</title>
</head>
<body>    
    <script>
        console.log("Hello World");
    </script>    
</body>
</html>

~~~

### Integrar javascript de forma externa

- Criar diretório ***scr*** na raiz do projeto
- Criar arquivo ***script.js*** na raiz do diretório ***src***
- Integrar de forma externa o arquivo ***script.js*** no arquivo ***index.html

~~~html

<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JavaScript</title>
</head>
<body>
    <script src="./src/script.cs"></script>   
</body>
</html>

~~~

## COMENTÁRIOS

### Comentário de Linha

~~~ javascript
./src/script.js

// comentário de linha

~~~

### Comentário de Bloco Simples

~~~ javascript
./src/script.js

/* comentário de bloco simples */

~~~

### Comentário de Bloco com Marcadores

~~~ javascript
./src/script.js

/**
 * comentário de bloco com marcador
**/
~~~

### VARIÁVEIS

### Declaração de Variáveis
### Atribuição de Valor

~~~ javascript
./src/script.js

var number;

number = 5;

~~~

### Declaração e Atribuição de Valor

~~~ javascript
./src/script.js

var number = 5;

~~~

### Reatribuição de Valor

~~~ javascript
./src/script.js

var number = 5;

number = 10;

~~~

### Nomeclaturas

- Caracteres permitidos para iniciar a nomeclatura de um identificador

~~~ javascript
./src/script.js

// letras (letters)

var number;
var Number;

// sublinhado (uderline)

var _number;

// Cifrão ($ Dolar)

var $number;

~~~

- Case-sensitive

~~~ javascript
./src/script.js

// "nummber" é lido diferente de "Number". O sistema diferencia caixa alta/baixa (Uppercase/Lowcase)

var number;
var Number;

~~~

- Nomeclaturas Compostas

~~~ javascript
./src/script.js

// Camel Case

var myNumber;

// Pascal Case

var MyName;

// Snake Case

var my_name;

~~~

## TIPOS DE DADOS

### Primitivos

~~~ javascript
./src/script.js

// string
var first name = "Alex"; // 1o nome
var surname = "Bessa"; // sobrenome
var last name = "Daniel"; // 2o nome

// number
var age = 29; // inteiro (whole)
var weight = 85.6; // fracionado (float)

// boolean (boleando)
var active = true;
var permission = false;

// undefined (não definido)
var contains;
console.log(contains);

// null (nulo)
var data = null;

~~~

### Não primitivos

~~~ javascript

./src/script.js

// array (lista)
var values = [1, "Alex", true, null],

// object literal
var person = {nome:"Alex", age: 29},

//function
var message = function() {};

// arr (lista)
var arr = [
    [1,2,3]
    [
        ["Alex", "Marcos", 'Daniel'],
        [29, 40, 35],
    ],
    [true, false],
];

console.log(arr[1[1]])

var arr = [
    {
        name: "Alex",
        age: 40
    },
    { 
        name: "Marcos",
        age: 35
    }
];

console.log(arr[1].name);




~~~







