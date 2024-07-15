# Função que verifica números

#### Você é uma pessoa desenvolvedora de software que trabalha com JavaScript e precisa criar uma função que verifique se um número é positivo, negativo ou zero. Sua tarefa é implementar uma função que recebe como parâmetro um número inteiro e exibe uma mensagem no console conforme as seguintes regras:

- Se o número for maior que zero, a mensagem deve ser: "O número é positivo."

- Se o número for menor que zero, a mensagem deve ser: "O número é negativo."

- Se o número for igual a zero, a mensagem deve ser: "O número é zero."

#### Você pode utilizar a estrutura de controle if-else para verificar as condições e exibir a mensagem correspondente no console. Sabendo disso, analise as alternativas abaixo e marque aquela que possui o código que atende todas as regras citadas acima.

###### Selecione uma alternativa

A -

```javascript
function verificarNumero(numero) {
  if (numero < 0) {
    console.log("O número é positivo.")
  } else if (numero > 0) {
    console.log("O número é negativo.")
  } else {
    console.log("O número é zero.")
  }
}
```

B -

```javascript
function verificarNumero(numero) {
  if (numero < 0) {
    console.log("O número é positivo.")
  } else if (numero > 0) {
    console.log("O número é negativo.")
  } else {
    console.log("O número é zero.")
  }
}
```

C -

```javascript
if (numero > 0) {
  console.log("O número é positivo.")
} else if (numero < 0) {
  console.log("O número é negativo.")
} else {
  console.log("O número é zero.")
}
```

D -

```javascript
function verificarNumero(numero) {
  if (numero > 0) {
    console.log("O número é positivo.")
  } else if (numero < 0) {
    console.log("O número é negativo.")
  } else {
    console.log("O número é zero.")
  }
}
```

<details>
    <summary>Resposta</summary>
D -

```javascript
function verificarNumero(numero) {
  if (numero > 0) {
    console.log("O número é positivo.")
  } else if (numero < 0) {
    console.log("O número é negativo.")
  } else {
    console.log("O número é zero.")
  }
}
```

<p>Neste código, usamos a estrutura de controle if-else para verificar as três possibilidades: se o número é maior que zero, se é menor que zero ou se é igual a zero. Dependendo da condição, a função imprime a mensagem correspondente no console.</p>
</details>
