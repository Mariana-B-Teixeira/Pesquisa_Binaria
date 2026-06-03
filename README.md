# 🔍 Pesquisa Binária

Implementação do algoritmo de busca binária em Python, baseada no livro "Entendendo Algoritmos".

## Sobre o algoritmo

A pesquisa binária é um algoritmo eficiente para encontrar um elemento em uma lista ordenada. Ela funciona dividindo repetidamente ao meio a parte da lista que pode conter o elemento desejado, reduzindo o espaço de busca pela metade a cada iteração.

- Entrada: uma lista ordenada e um item a ser procurado.
- Saída: o índice do item na lista (se encontrado) ou None (se não existir).

## Exemplo

Com a lista [1, 3, 5, 7, 9]:
- Procurando pelo número 3 → retorna o índice 1
- Procurando pelo número -1 → retorna None

## Complexidade

Tempo: O(log n) – eficiente mesmo para listas muito grandes.

## Base teórica

Algoritmo explicado no livro "Entendendo Algoritmos" de Aditya Bhargava. Conceito estudado em sala de aula como introdução à eficiência de algoritmos.

## Como executar

O código completo está no arquivo mariana.py. Para executar, tenha Python instalado e rode o arquivo.
