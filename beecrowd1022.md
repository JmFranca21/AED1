# [TDA Racional](https://judge.beecrowd.com/pt/problems/view/1022)  

A tarefa aqui neste problema é ler uma expressão matemática na forma de dois números Racionais (numerador / denominador) e apresentar o resultado da operação. Cada operando ou operador é separado por um espaço em branco. A sequência de cada linha que contém a expressão a ser lida é: número, caractere, número, caractere, número, caractere, número. A resposta deverá ser apresentada e posteriormente simplificada. Deverá então ser apresentado o sinal de igualdade e em seguida a resposta simplificada. No caso de não ser possível uma simplificação, deve ser apresentada a mesma resposta após o sinal de igualdade.  

Considerando N1 e D1 como numerador e denominador da primeira fração, segue a orientação de como deverá ser realizada cada uma das operações:  
Soma: (N1*D2 + N2*D1) / (D1*D2)  
Subtração: (N1*D2 - N2*D1) / (D1*D2)  
Multiplicação: (N1*N2) / (D1*D2)  
Divisão: (N1/D1) / (N2/D2), ou seja (N1*D2)/(N2*D1)  

**Entrada**  
A entrada contem vários casos de teste. A primeira linha de cada caso de teste contem um inteiro N (1 ≤ N ≤ 1*104), indicando a quantidade de casos de teste que devem ser lidos logo a seguir. Cada caso de teste contém um valor racional X (1 ≤ X ≤ 1000), uma operação (-, +, * ou /) e outro valor racional Y (1 ≤ Y ≤ 1000).  

**Saída**  
A saída consiste em um valor racional, seguido de um sinal de igualdade e outro valor racional, que é a simplificação do primeiro valor. No caso do primeiro valor não poder ser simplificado, o mesmo deve ser repetido após o sinal de igualdade.  

**Exemplo de Entrada**  
4  
1 / 2 + 3 / 4  
1 / 2 - 3 / 4  
2 / 3 * 6 / 6  
1 / 2 / 3 / 4  

**Exemplo de Saída**  
10/8 = 5/4  
-2/8 = -1/4  
12/18 = 2/3  
4/6 = 2/3  

[Clique aqui para a resolução.](beecrowd1022.c)

