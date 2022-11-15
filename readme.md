## DESAFIO - LÓGICA

# Fase 1
- crie um array dinâmico com três posições [2,1,2]
- crie uma iteração que retorne números aleatórios entre 1 e 3
 -a cada retorno, altere o valor do array respectivamente

# Fase 2
- utilize as linhas já codificadas e insira em uma função
- crie uma verificação que identifica se os números do array são iguais
- Se sim: escreva 'Porta 1: aberta'
- Se não: escreva 'Tente de novo!'

# Fase 3

- crie uma variável de controle para acumular a quantidade de vezes que os números se repetem
- crie uma variável que armazene o valor do último sorteio
- compare a valor do último sorteio com o valor do sorteio atual
-- Se os valores forem iguais: escreva 'Porta (x)' : aberta
-- Se os valores forem diferentes: 
        escreva 'Tente de novo' (Com a exceção do resultado ser de números iguais)

As portas serão abertas quando: 
    - a sequência dos números do array forem iguais ou
    - a sequência de números do array for igual a sequência de números do último sorteio
  
Fim do jogo acontece quando a terceira porta for aberta. 


[1,3,2] 1º // ant - porta fechada
[3,2,2] 2º //sorteio = porta fechada
[3,2,2] 3º //porta1 aberta - variavelControle++
[2,2,2] 4º //porta2 aberta - variavelControle++
[1,2,3] 5º //porta fechada 
[3,2,1] 6º //porta fechada
[3,3,3] 7º //porta3 aberta - variavelControle++
Ok, você conseguiu!!!!
 - Interromper o loop de teste
 - Imprimir um log de resultados


[1,2,3]
[2,2,2]
[2,2,2]