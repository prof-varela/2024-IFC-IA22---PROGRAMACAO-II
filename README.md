# 2024-IFC-IA22---PROGRAMACAO-II
...

# 1.Revisão

## 1.1 Revisão: Banco de Dados

- [x] DDL - Data Definition Language
  - [x] CREATE, ALTER e DROP
- [x] DML - Data Manipulation Language
  - [x] INSERT, DELETE e UPDATE
- [x] DQL - Data Query Language
  - [x] SELECT
     
### 1.1.1 Exercício

Considere um banco de dados para uma aplicação de música que armazena informações sobre artistas, álbuns e músicas.

Criação das Tabelas:
- Crie um banco de dados SQLite que inclua três tabelas: Artista, Album e Musica.
- A tabela Artista deve conter as colunas: id (chave primária), nome e genero.
- A tabela Album deve ter as colunas: id (chave primária), titulo, ano e artista_id (chave estrangeira referenciando Artista).
- A tabela Musica deve incluir as colunas: id (chave primária), titulo, duracao e album_id (chave estrangeira referenciando Album).

Inserção de Dados:
- Insira pelo menos três artistas diferentes na tabela Artista.
- Adicione álbuns associados a esses artistas, com informações de título e ano.
- Inclua músicas vinculadas a esses álbuns, com títulos e duração.

Atualização de Dados:
- Atualize o gênero de um dos artistas na tabela Artista.
- Modifique o ano de lançamento de um álbum na tabela Album.

Exclusão de Dados:
- Remova uma música específica da tabela Musica (não exclua a última música).

Entrega:
- Envie o arquivo .sqlite no SIGAA

----------------------------------------------------------------

## 1.2 Revisão: Programação e Lógica de Programação

- [x] Conceitos Fundamentais:
  - [x] Variáveis e tipos de dados
  - [x] Operadores aritméticos, lógicos e relacionais
  - [x] Estruturas de controle (condicionais e loops)
    - [x] if, else, switch, for, while, do while
  - [x] Funções e procedimentos (ñ retorna valor)
- [x] Estruturas de Dados:
  - [x] Arrays (vetores) e matrizes
  - [ ] Listas encadeadas
  - [ ] Pilhas e filas
  - [ ] Árvores e grafos 
- [x] Paradigmas de Programação:
  - [x] Programação imperativa/estruturada
  - [x] Programação orientada a objetos
  - [x] Programação funcional
     
### 1.2.1 Exercício

Objetivo:
- Criar um programa em Node.js que simule um jogo de adivinhação, onde o computador escolhe um número aleatório e o jogador tenta adivinhar esse número.

Requisitos:
- O computador escolhe um número aleatório entre 1 e 100.
- O jogador tem um número limitado de tentativas para adivinhar o número escolhido pelo computador.
- O programa deve fornecer dicas ao jogador, dizendo se o número a ser adivinhado é maior ou menor do que a tentativa atual.
- Ao final, o programa deve informar se o jogador acertou o número ou não, e quantas tentativas foram necessárias.

### 1.2.2 Exercício

Objetivo:
- Criar um programa que represente uma lista de tarefas (to-do list) utilizando orientação a objetos.

Requisitos:
- Criar uma classe Tarefa que possua propriedades como descricao, prioridade e concluida.
- Implementar métodos para marcar uma tarefa como concluída e exibir informações da tarefa.
- Criar uma lista de tarefas utilizando essa classe.
- Imprimir na tela o status e descrição de todas as tarefas.
