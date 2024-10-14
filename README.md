# Sistema de Gerenciamento de Biblioteca

## Descrição
Sistema de gerenciamento de biblioteca em C# que permite a administradores cadastrarem livros e usuários realizarem empréstimos e devoluções, com um limite de até três livros por usuário.

## Funcionalidades

- **Administrador:**
  - Cadastrar novos livros.

- **Usuário:**
  - Pegar até 3 livros emprestados.
  - Devolver livros.

## Estrutura do Projeto

- **Classes:**
  - `Program`: Classe principal com a lógica do sistema.
  - `Livro`: Representa um livro, com propriedades para autor, nome e gênero.

- **Estruturas de Dados:**
  - `List<Livro>`: Armazena os livros disponíveis.
  - `Dictionary<string, int>`: Armazena a contagem de livros emprestados por usuário.
