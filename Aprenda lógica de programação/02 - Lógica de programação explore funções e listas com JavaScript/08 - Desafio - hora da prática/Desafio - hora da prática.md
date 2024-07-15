Claro, vou corrigir o arquivo `readme.md` com as respostas dos desafios:

# Desafio: hora da prática

#### Saber como usar funções é um dos conceitos fundamentais da programação e do desenvolvimento de software. As funções desempenham um papel crucial na organização, modularização e reutilização de código.

#### Pensando nisso, criamos uma lista de atividades (não obrigatórias) focada em prática para melhorar ainda mais sua experiência de aprendizagem. Bora praticar então?

## Desafio

1. Criar uma função que exibe "Olá, mundo!" no console.

<details>
    <summary>Resposta</summary>
    
```javascript

function exibirOla() {
console.log("Olá, mundo!");
}

exibirOla();

````

</details>
<br>

2. Criar uma função que recebe um nome como parâmetro e exibe "Olá, [nome]!" no console.

<details>
    <summary>Resposta</summary>

```javascript
function exibirOlaNome(nome) {
  console.log(`Olá, ${nome}!`)
}

exibirOlaNome("Alice")
````

</details>
<br>

3. Criar uma função que recebe um número como parâmetro e retorna o dobro desse número.

<details>
    <summary>Resposta</summary>

```javascript
function calcularDobro(numero) {
  return numero * 2
}

let resultadoDobro = calcularDobro(5)
console.log(resultadoDobro)
```

</details>
<br>

4. Criar uma função que recebe três números como parâmetros e retorna a média deles.

<details>
    <summary>Resposta</summary>

```javascript
function calcularMedia(a, b, c) {
  return (a + b + c) / 3
}

let media = calcularMedia(4, 7, 10)
console.log(media)
```

</details>
<br>

5. Criar uma função que recebe dois números como parâmetros e retorna o maior deles.

<details>
    <summary>Resposta</summary>

```javascript
function encontrarMaior(a, b) {
  return a > b ? a : b
}

let maiorNumero = encontrarMaior(15, 9)
console.log(maiorNumero)
```

</details>
<br>

6. Criar uma função que recebe um número como parâmetro e retorna o resultado da multiplicação desse número por ele mesmo.

<details>
    <summary>Resposta</summary>

```javascript
function quadrado(numero) {
  return numero * numero
}

let resultado = quadrado(2)
console.log(resultado)
```

</details>
