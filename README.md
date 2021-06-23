# SO-08-threads

## Objetivo
Escreva um programa que realize o cálculo das somas dos valores das linhas de uma matriz qualquer de números inteiros e imprima o resultado na tela.

## Exemplo
#### Código
```c
int matrix[4][4] = { 1, 2, 3, 4, 
                     5, 6, 7, 8,
                     9, 10, 11, 12, 
                     13, 14, 15, 16};
```

#### Resultado: 
* Linha 1: 10 
* Linha 2: 26 
* Linha 3: 42 
* Linha 4: 58 
* Total: 136

## Observação
O cálculo do somatório de cada linha deve ser realizado em paralelo por *threads* diferentes.