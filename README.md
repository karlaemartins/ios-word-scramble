# iOS Word Scramble - Projeto de Estudo

Aplicativo desenvolvido em **UIKit** onde o jogador recebe uma palavra base e precisa formar novas palavras utilizando apenas as letras disponíveis nela.

Este projeto faz parte do **Project 5** do curso **100 Days of Swift**, mas foi desenvolvido com o objetivo de praticar conceitos fundamentais de manipulação de strings, validação de dados e construção de interfaces utilizando UIKit.

## O que o app faz

- Seleciona uma palavra aleatória a partir de um arquivo (`start.txt`)
- Permite formar novas palavras utilizando apenas as letras da palavra base
- Valida se a palavra pode ser formada com as letras disponíveis
- Impede o uso de palavras repetidas
- Valida a existência da palavra utilizando `UITextChecker`
- Exige que a palavra tenha pelo menos 3 letras
- Impede o uso da própria palavra original
- Exibe dinamicamente a lista de palavras válidas
- Permite reiniciar o jogo

## Arquitetura

O projeto foi estruturado utilizando **UIKit**, separando a interface da lógica responsável pela validação das palavras e gerenciamento do estado do jogo.

## Decisões importantes

- UIKit programático
- Uso de UITableViewController
- Validação de palavras utilizando UITextChecker
- Inserção de palavras através de UIAlertController
- Manipulação de arrays e strings
- Estruturação da lógica de validação das respostas

## Conceitos praticados

- UIKit
- UITableViewController
- UIAlertController
- UITextChecker
- Manipulação de Arrays
- Manipulação de Strings
- Validação de dados

## Créditos

Projeto baseado no **Project 5**, do curso **100 Days of Swift**, criado por **Paul Hudson (Hacking with Swift)**.
