# Sorteador de Amigo Secreto 🎁

Projeto prático desenvolvido a partir de um desafio da plataforma Alura. O objetivo foi aplicar conceitos fundamentais de lógica de programação para criar uma aplicação funcional e à prova de falhas.

## O que foi desenvolvido em JS:
* **Estrutura de Dados (Arrays):** Uso de arrays para armazenar e manipular a lista de participantes do sorteio.
* **Validações de Entrada:** Implementação de lógicas preventivas usando `if` para bloquear inputs vazios, impedir a inserção de nomes duplicados (com `.includes()`) e exigir um número mínimo de 4 participantes antes de permitir o sorteio.
* **Algoritmo de Embaralhamento:** Aplicação de lógica matemática (`Math.random` e `Math.floor`) para criar uma função que embaralha os índices da lista de forma aleatória e justa (inspirado no método Fisher-Yates).
* **Lógica Cíclica:** Uso de estrutura de repetição (`for`) para garantir que o último sorteado tire a primeira pessoa da lista, fechando o ciclo do Amigo Secreto sem que ninguém tire a si mesmo.
* **Manipulação de DOM:** Atualização dinâmica da interface mesclando `textContent` (para listas simples) e `innerHTML` (para gerar quebras de linha dinâmicas no resultado do sorteio).

## Tecnologias Utilizadas
* JavaScript (Regras de negócio e algoritmos)
* HTML e CSS (Base visual do desafio)
