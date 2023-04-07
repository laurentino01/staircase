# Desafio - Starcase HackerRank

### O desafio consiste em escrever um programa que imprima uma escada de tamanho n, na qual a base e a altura são iguais a n, utilizando símbolos "#" e espaços em branco. A última linha da escada não deve conter nenhum espaço em branco antes dos símbolos "#".

Ex: Starcase que o tamanho N = 4

<code>
     #
    ##
   ###
  ####
</code>

## Solução

1. Cria uma função chamada "staircase" que recebe um parâmetro "n".
2. Define uma variável "a" como uma string vazia contendo apenas um espaço em branco.
3. Define uma variável "b" como uma string contendo apenas um símbolo "#".
4. Inicia um loop "for" que começa com o valor de "i" igual a 1 e continua enquanto "i" for menor que "n+1".
5. A cada iteração do loop, a função imprime no console uma string formada pela repetição de "a" "n-i" vezes e "b" "i" vezes, formando a escada desejada.
6. O loop continua até que "i" seja igual a "n+1".

<code>
  function staircase(n) {
    // Write your code here
    let a = " "
    let b = "#"
    for (let i = 1; i < n +1; i++) {
    console.log(a.repeat(n - i) + b.repeat(i));
    }
}
</code>

## Link Hacker Rank
https://www.hackerrank.com/gabriellaurenti1
  
## Tecnologia
<div style="display: inline_block"><br>
  <img align="center" alt="Gabriel-HTML" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg">
</div>
