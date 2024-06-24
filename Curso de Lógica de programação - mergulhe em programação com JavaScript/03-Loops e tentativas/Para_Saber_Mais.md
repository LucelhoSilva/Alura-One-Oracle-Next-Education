# Para saber mais: operadores lógicos

Quando escrevemos programas em JavaScript, frequentemente nos deparamos com a necessidade de tomar decisões com base em condições. É aqui que os operadores lógicos entram em cena e nos ajudam a criar uma lógica robusta e eficaz.

A seguir, vamos explorar os operadores lógicos de uma forma simples e fácil de entender. Teremos exemplos claros para ilustrar seu funcionamento.

## AND (&&)

O operador **AND**, representado pelos símbolos **"&&"**, é utilizado para combinar duas condições e avaliar se ambas são verdadeiras. Se ambas as condições forem verdadeiras, o resultado será… verdadeiro. Caso contrário, logicamente será falso. Por exemplo:

```javascript
let idade = 25
let possuiCarteira = true

// se idade é maior que 18 e possui carteira…
if (idade > 18 && possuiCarteira) {
  console.log("Pode dirigir!")
} else {
  console.log("Não pode dirigir.")
}
```

## OR (||)

O operador **OR**, representado pelos símbolos **"||"**, é usado para verificar se pelo menos uma das condições é verdadeira. Se uma das condições for verdadeira, o resultado será verdadeiro. Se ambas forem falsas, o resultado será falso. Veja um exemplo:

```javascript
let temMaça = false
let temBanana = true

// se tem maça ou tem banana…
if (temMaça || temBanana) {
  console.log("Você tem frutas!")
} else {
  console.log("Não tem frutas.")
}
```

## Outros tipos de operadores lógicos

<img src="./assets/img/Operadores lógicos.png" alt="operadores lógios">

## Operadores Lógicos

<img src="./assets/img/Operadores lógicos2.png" alt="operadores lógios">
