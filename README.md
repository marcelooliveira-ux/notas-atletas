# Notas de atletas

Script em JavaScript que calcula a média das notas de atletas no formato usado em competições de ginástica: a maior e a menor nota de cada atleta são descartadas e a média sai das restantes. Projeto de certificação da formação em desenvolvimento web do SENAI RN.

## Como funciona

Cada atleta é um objeto com nome e um array de cinco notas. Para cada um deles, o script ordena as notas em ordem crescente, descarta a menor e a maior, calcula a média das três restantes e imprime no console o nome, as notas ordenadas e a média válida.

Conceitos exercitados: manipulação de arrays e objetos, ordenação com sort e comparador numérico, recorte de intervalo com slice e laços de repetição.

## Stack

JavaScript (ES6+), sem dependências.

## Como executar

```
node notas-atletas.js
```

Também funciona colando o conteúdo do arquivo no console do navegador.

## Exemplo de saída

```
Atleta: Cesar Abascal
Notas Obtidas: 7.88,8.42,9.34,10,10
Média Válida: 9.253333333333332
```
