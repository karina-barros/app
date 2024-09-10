# Aula 01 - Fundamentos da programação
## Linguagem de programação
Possibilita dar instruções ao computador.

**Algoritmo**: Sequência de passos lógica e finita para resolução de um problema.

## Peças de uma linguagem
- Comentários
- Declaração de variáveis (const, let)
- Operadores (atribuição, concatenação, matemáticos, lógicos)
- Tipos de dados (str, number, bool)
- Estrutura de dados (functions, object, array)
- Controle de fluxo (if/else)
- Estrutura de repetição (for, while)

## Fases das resolução de um problema
- Coletar os dados
- Processar os dados (manipular, alterar...)
- Apresentar os dados

## Exemplos
### Hello world
~~~javascript
// hello world - comment
console.log("Hello world!");
// objeto - console; função - log
let mensagem = "Olá, mundo." // const mensagem = "Olá, mundo."


{
    const mensagem = "Olá." // var. local
    console.log(mensagem);
}

console.log(mensagem);
~~~
### Arrays
Lista que contém qualquer tipo de dados
~~~javascript
// arrays
let metas = ["nina", "hi"]

console.log(metas);
console.log(metas[0])
console.log(metas[1] + ", " + metas[0])
~~~
### Objetos
~~~javascript
// objetos {}
let meta = {
    value: 'Ler um livro por semana',
    checked: true,
    isChecked: () => {}
}

console.log(meta.value)
~~~
### Function
~~~javascript
// function - "fora de um objeto" 
const criarMeta = () => {} // arrow function

function criarMeta() {}
~~~