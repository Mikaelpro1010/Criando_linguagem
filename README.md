# Trabalho Final de Paradigmas

O projeto em Python apresentado é um interpretador simples para computar expressões matemáticas, que possue um analisador léxico e sintático

## Arquivo principal

O arquivo principal é: main.py

## Como executar

1 - Abra a pasta do projeto em sua IDE de preferência, ex: Visual Code
2 - Execute o arquivo principal
3 - Digite no terminal a expressão matemática que deseja ser computada
	Ex: (3+6) - (2*5)

## Características do código

Como visto, o código em questão consegue analisar e interpretar expressões matemáticas.
Ele consegue ler os tokens e lexemas e realizar os cálculos.


O analisador léxico é o que faz essa conversão do código-fonte em uma sequência de tokens.
Ele possui um método "criar_tokens" que percorre o código caractere por caractere e gera os seus tokens correspondentes.

O analisador sintático é responsável por transformar essa sequência de tokens em uma árvore de análise sintática.
Ele utiliza o método "expr" para analisar uma expressão matemática e construir a árvore de análise.

Interpretador:
Interpreta a árvore de análise sintática gerada.
Utiliza o método "visitar" para percorrer e executar os diferentes tipos de nós da árvore.
