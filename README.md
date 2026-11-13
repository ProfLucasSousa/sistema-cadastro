# Sistema de Cadastro

Projeto didático de CRUD em PHP e MySQL. A aplicação reúne cadastro, autenticação, listagem, pesquisa, edição e exclusão de usuários, além de controle de sessão.

## Tecnologias

- PHP
- MySQL
- Bootstrap 5
- HTML, CSS e JavaScript

## Estrutura

O código está na pasta `sistema-cadastro/`.

- `login.php`, `testLogin.php` e `logout.php`: autenticação.
- `formulario.php`: cadastro.
- `sistema.php`: listagem e pesquisa.
- `edit.php` e `saveEdit.php`: edição.
- `delete.php`: exclusão.
- `config.php`: conexão com o banco.

## Como executar

1. Configure um banco MySQL com a tabela esperada pelo projeto.
2. Ajuste a conexão em `sistema-cadastro/config.php`.
3. Inicie o servidor:

```bash
php -S localhost:8000 -t sistema-cadastro
```

4. Acesse `http://localhost:8000`.

## Aviso

Este código foi feito para estudo. Antes de usá-lo fora da aula, mova credenciais para variáveis de ambiente, use consultas preparadas, armazene senhas com hash seguro, remova a exibição de senhas e revise o controle de sessão.
