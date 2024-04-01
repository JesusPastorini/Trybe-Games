# 🎮 Projeto: Trybe Games

## ℹ️ Sobre o Projeto

O projeto Trybe Games consiste no desenvolvimento de métodos e consultas LINQ para manipulação de coleções de dados relacionados a jogadores, estúdios de jogos e jogos em si. O objetivo é implementar funcionalidades que permitam adicionar novos jogadores, estúdios e jogos ao banco de dados, além de realizar consultas para obter informações específicas sobre esses elementos.

## 📸 Tela de Login da Aplicação

![TrybeGames](public/login.gif)

## 🛠️ Tecnologias e Habilidades

- **Plataforma Utilizada:** .NET
- **Linguagem Utilizada:** C#
- **Manipulação de Coleções de Dados**
- **Consultas LINQ**
- **Testes Unitários**

## 📋 Funcionalidades Implementadas

1. **Adicionar Novo Jogador:**
   - Método `AddPlayer()` no arquivo `src/TrybeGames/TrybeGamesController.cs`.
   - Permite adicionar um novo jogador ao banco de dados, solicitando os dados necessários via console e inserindo-os na coleção de jogadores existente.

2. **Adicionar Novo Estúdio de Jogos:**
   - Método `AddGameStudio()` no arquivo `src/TrybeGames/TrybeGamesController.cs`.
   - Permite adicionar um novo estúdio de jogos ao banco de dados, solicitando o nome via console e inserindo-o na coleção de estúdios existente.

3. **Adicionar Novo Jogo:**
   - Método `AddGame()` no arquivo `src/TrybeGames/TrybeGamesController.cs`.
   - Permite adicionar um novo jogo ao banco de dados, solicitando os dados necessários via console e inserindo-os na coleção de jogos existente.

4. **Buscar Jogos Desenvolvidos por um Estúdio de Jogos:**
   - Método `GetGamesDevelopedBy()` no arquivo `src/TrybeGames/Database/TrybeGamesDatabase.cs`.
   - Retorna todos os jogos desenvolvidos por um determinado estúdio de jogos.

5. **Buscar Jogos Jogados por um Jogador:**
   - Método `GetGamesPlayedBy()` no arquivo `src/TrybeGames/Database/TrybeGamesDatabase.cs`.
   - Retorna todos os jogos jogados por um determinado jogador.

6. **Buscar Jogos Comprados por um Jogador:**
   - Método `GetGamesOwnedBy()` no arquivo `src/TrybeGames/Database/TrybeGamesDatabase.cs`.
   - Retorna todos os jogos comprados por um determinado jogador.

7. **Buscar Todos os Jogos com o Nome do Estúdio Desenvolvedor:**
   - Método `GetGamesWithStudio()` no arquivo `src/TrybeGames/Database/TrybeGamesDatabase.cs`.
   - Retorna as informações de todos os jogos juntamente com o nome do estúdio desenvolvedor.

8. **Buscar Todos os Diferentes Tipos de Jogos:**
   - Método `GetGameTypes()` no arquivo `src/TrybeGames/Database/TrybeGamesDatabase.cs`.
   - Retorna as informações dos diferentes tipos de jogos cadastrados.

