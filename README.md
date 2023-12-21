# 2024-IFC-IA22---PROGRAMACAO-II
...

# 1.Revisão

## 1.1 Revisão: HTML/CSS

### 1.1.1 HTML
- [x] Estrutura Básica:
  - [x] ```<html>, <head>, <body>``` 
  - [x] ```<!DOCTYPE html>```
- [x] Tags e Elementos:
  - [x] Sintaxe básica: ```<tag></tag> ou <tag />``` para tags vazias
  - [x] Elementos de bloco e de linha
- [x] Semântica HTML5:
  - [x] Elementos semânticos: ```<header>, <footer>, <section>, <article>,``` etc.
- [x] Formatação de Texto:
  - [x] Tags para texto: ```<h1> a <h6>, <p>, <em>, <strong>,``` etc.
- [x] Links, Imagens e Mídia:
  - [x] <a> para links, <img> para imagens
  - [x] Atributos href, src, alt, title
- [x] Formulários:
  - [x] ```<form>, <input>, <textarea>, <select>, <button>```
  - [x] Atributos type, name, value, placeholder, required
- [x] Metadados e SEO:
  - [x] <meta> para metadados como descrição, palavras-chave, autor, etc.
- [x] Boas Práticas:
  - [x] Validação de código HTML
- [x] Uso correto de tags e atributos
  - [x] Acessibilidade: alt em imagens, estrutura semântica

### 1.1.2 CSS
- [x] Seletores e Propriedades:
  - [x] Revisão dos seletores CSS: por elemento, por classe, por ID, etc.
  - [x] Propriedades básicas de formatação: color, font-size, background, padding, margin, border, etc.
- [x] Box Model:
  - [x] Compreensão do modelo de caixa (box model) e suas propriedades: width, height, border, padding, margin
- [x] Layout e Posicionamento:
  - [x] Posicionamento: position, relative, absolute, fixed
  - [x] Layout: float, display, flexbox, grid
- [x] Estilização Avançada:
  - [x] Pseudo-classes e pseudo-elementos: :hover, :focus, :has, :not ::before, ::after etc
  - [x] Transições e animações: transition, animation
- [x] Responsividade:
  - [x] Media Queries para estilos responsivos em diferentes dispositivos e tamanhos de tela
- [x] Unidades de Medida:
  - [x] Revisão de unidades de medida como px, %, em, rem, vh, vw
     
### 1.1.3 Exercício HTML/CSSS

Objetivo:
- Criar uma página simples de perfil pessoal que inclua informações básicas e estilização utilizando HTML e CSS.

Requisitos:
- Criar um arquivo HTML com estrutura básica.
- Incluir informações como nome, foto, descrição, lista de habilidades, e contato.
- Utilizar estilos CSS para formatar e posicionar os elementos na página.

Passos:
- Estrutura HTML:
  - Crie um arquivo HTML (perfil.html) com elementos básicos (```<!DOCTYPE html>, <html>, <head>, <body>```).
  - Adicione um cabeçalho (```<header>```) com o nome e uma foto.
  - Crie seções para a descrição, habilidades e informações de contato.
- Conteúdo HTML:
  - Adicione informações como nome, uma breve descrição, lista de habilidades e informações de contato (e-mail, telefone, links para redes sociais).
- Estilização com CSS:
  - Crie um arquivo CSS (estilos.css) e vincule ao arquivo HTML.
  - Utilize seletores para estilizar os elementos HTML.
  - Aplique cores, fontes, espaçamento e alinhamento para tornar a página mais visualmente atraente.
  - Experimente diferentes propriedades CSS para aprimorar o layout e a estética da página.

## 1.2 Revisão: Banco de Dados

- [x] DDL - Data Definition Language
  - [x] CREATE, ALTER e DROP
- [x] DML - Data Manipulation Language
  - [x] INSERT, DELETE e UPDATE
- [x] DQL - Data Query Language
  - [x] SELECT
     
### 1.2.1 Exercício

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

## 1.3 Revisão: Programação e Lógica de Programação

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
     
### 1.3.1 Exercício

Objetivo:
- Criar um programa em Node.js que simule um jogo de adivinhação, onde o computador escolhe um número aleatório e o jogador tenta adivinhar esse número.

Requisitos:
- O computador escolhe um número aleatório entre 1 e 100.
- O jogador tem um número limitado de tentativas para adivinhar o número escolhido pelo computador.
- O programa deve fornecer dicas ao jogador, dizendo se o número a ser adivinhado é maior ou menor do que a tentativa atual.
- Ao final, o programa deve informar se o jogador acertou o número ou não, e quantas tentativas foram necessárias.

### 1.3.2 Exercício

Objetivo:
- Criar um programa que represente uma lista de tarefas (to-do list) utilizando orientação a objetos.

Requisitos:
- Criar uma classe Tarefa que possua propriedades como descricao, prioridade e concluida.
- Implementar métodos para marcar uma tarefa como concluída e exibir informações da tarefa.
- Criar uma lista de tarefas utilizando essa classe.
- Imprimir na tela o status e descrição de todas as tarefas.
