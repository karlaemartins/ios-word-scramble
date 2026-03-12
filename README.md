# Jogo das palavras - Projeto de estudo

Este projeto é um **jogo de palavras desenvolvido em Swift utilizando UIKit**, criado como parte do processo de aprendizado no curso **100 Days of Swift**.

O jogador recebe uma palavra base e precisa formar novas palavras utilizando apenas as letras disponíveis nela.

---

## Objetivo do projeto

Praticar conceitos fundamentais do desenvolvimento iOS, incluindo:

* Uso de **UITableViewController**
* Manipulação de **arrays e strings**
* Validação de entrada do usuário
* Uso de **UIAlertController**
* Uso do **UITextChecker** para validar palavras
* Estruturação de lógica de jogo

---

## Como funciona

1. O aplicativo seleciona uma palavra aleatória a partir de um arquivo (`start.txt`).
2. O jogador precisa formar novas palavras usando apenas as letras dessa palavra.
3. Cada palavra enviada passa por validações:

* Deve poder ser formada com as letras disponíveis
* Não pode ter sido usada anteriormente
* Deve existir no dicionário
* Deve ter pelo menos **3 letras**
* Não pode ser igual à palavra original

Se a palavra for válida, ela é adicionada à lista exibida na tabela.

---

## Funcionalidades

* Inserção de palavras através de **alert com campo de texto**
* Lista dinâmica de palavras válidas
* Validação automática de palavras
* Botão para **reiniciar o jogo**

---


## Tecnologias utilizadas

* Swift
* UIKit
* UITableViewController
* UIAlertController
* UITextChecker
