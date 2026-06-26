# ♟️ Sistema de Xadrez

Um sistema completo de xadrez desenvolvido em **Java**, utilizando os principais conceitos de **Programação Orientada a Objetos (POO)**. O projeto simula uma partida real de xadrez diretamente pelo console, implementando todas as regras fundamentais do jogo, incluindo movimentos especiais, validações e condições de vitória.

---

## 📖 Sobre o projeto

Este projeto foi desenvolvido com o objetivo de colocar em prática conceitos avançados de Programação Orientada a Objetos por meio da implementação completa da lógica de um jogo de xadrez.

Toda a lógica do jogo foi construída manualmente, sem utilização de bibliotecas externas para gerenciamento das regras, permitindo um maior aprofundamento em modelagem de objetos, algoritmos e organização de código.

---

## 🚀 Funcionalidades

- Tabuleiro completo de xadrez (8x8)
- Controle de turnos
- Movimentação de todas as peças
- Validação de movimentos permitidos
- Captura de peças
- Destaque de movimentos possíveis
- Detecção de Xeque (Check)
- Detecção de Xeque-Mate (Checkmate)
- Roque pequeno e grande (Castling)
- En Passant
- Promoção de peão
- Exibição das peças capturadas
- Validação de entradas do usuário
- Tratamento de exceções para movimentos inválidos

---

## 🛠️ Tecnologias utilizadas

- Java
- Programação Orientada a Objetos (POO)
- Java Collections Framework
- Tratamento de Exceções

---

## 📂 Estrutura do projeto

```
application/
│
├── Program.java
└── UI.java

boardgame/
│
├── Board
├── Piece
├── Position
└── BoardException

chess/
│
├── ChessMatch
├── ChessPiece
├── ChessPosition
├── ChessException
├── Color
└── pieces/
    ├── Bishop
    ├── King
    ├── Knight
    ├── Pawn
    ├── Queen
    └── Rook
```

---

## 🧠 Conceitos aplicados

Durante o desenvolvimento foram utilizados diversos conceitos importantes da Programação Orientada a Objetos, como:

- Encapsulamento
- Herança
- Polimorfismo
- Abstração
- Composição
- Responsabilidade única
- Modelagem de domínio
- Tratamento de exceções

---

## ♟️ Regras implementadas

O sistema implementa as principais regras oficiais do xadrez:

- ✔ Movimentação correta de todas as peças
- ✔ Captura de peças
- ✔ Controle de turnos
- ✔ Xeque
- ✔ Xeque-Mate
- ✔ Roque
- ✔ En Passant
- ✔ Promoção de peão
- ✔ Impedimento de movimentos ilegais
- ✔ Impedimento de deixar o próprio rei em xeque

---

## ▶️ Como executar o projeto

Clone o repositório:

```bash
git clone https://github.com/seuusuario/chess-system.git
```

Entre na pasta do projeto:

```bash
cd chess-system
```

Compile o projeto:

```bash
javac application/Program.java
```

Execute:

```bash
java application.Program
```

---

## 📸 Exemplo de execução

```text
8 R N B Q K B N R
7 P P P P P P P P
6 - - - - - - - -
5 - - - - - - - -
4 - - - - - - - -
3 - - - - - - - -
2 P P P P P P P P
1 R N B Q K B N R
  a b c d e f g h

Turno: 1
Jogador: BRANCO

Origem: e2
Destino: e4
```

---

## 🎯 Objetivos de aprendizagem

Este projeto foi desenvolvido para aprofundar conhecimentos em:

- Programação Orientada a Objetos
- Modelagem de sistemas
- Estruturas de dados
- Algoritmos
- Organização de código
- Implementação de regras de negócio complexas

---

## 👨‍💻 Autor

**Breno Souza**

Projeto desenvolvido durante os estudos de Java com foco em Programação Orientada a Objetos e implementação de regras de negócio complexas.
