# DESAFIO - LÓGICA

## Fase 1
- crie um array dinâmico com três posições [2,1,2]
- crie uma iteração que retorne números aleatórios entre 1 e 3
- a cada retorno da iteração, altere o valor do array respectivamente

## Fase 2
- insira as linhas já codificadas uma função
- crie uma verificação que identifica se a sequência de números do array são iguais (Ex: 111,222 ou 333)
   - Se sim: escreva 'Porta x: aberta'
   - Se não: escreva 'Tente de novo!'

## Fase 3

- crie uma variável de controle para acumular a quantidade de vezes em que a sequência obtida exibe números iguais
- na verificação 'se sim /se não' substitua 'Porta x' por `Porta${variável de controle}`
- crie uma variável que armazene o valor do último sorteio
- compare a valor do último sorteio com o valor do sorteio atual
             - Se os valores forem iguais: escreva 'Porta (x)' : aberta
             - Se os valores forem diferentes: escreva 'Tente de novo' (Com a exceção do resultado ser de números iguais)

As portas serão abertas quando: 
    - a sequência dos números do array forem iguais ou
    - a sequência de números do array for igual a sequência de números do último sorteio
  
Fim do jogo acontece quando a terceira porta for aberta. 

### Opcionalmente:
- contabilize a quantidade de tentativas necessárias para ganhar o jogo
- contabilize a quantidade de ocorrências onde a sequência de números do array é composta de números idênticos
- contabilize a quantidade de ocorrencias onde o resultado anterior é igual ao resultado atual


### Exemplo

- [1,3,2] 1º //porta fechada
- [3,2,2] 2º //porta fechada
- [3,2,2] 3º //porta1 aberta - variavelControle++
- [2,2,2] 4º //porta2 aberta - variavelControle++
- [1,2,3] 5º //porta fechada 
- [3,2,1] 6º //porta fechada
- [3,3,3] 7º //porta3 aberta - variavelControle++  Ok, você conseguiu!!!!
             - Interromper o loop de teste
             - Imprimir um log de resultados
