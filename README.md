# CRUD de Usuários com PHP e MySQL

Este é um projeto simples de CRUD (Create, Read, Update, Delete) desenvolvido com PHP puro, MySQL, HTML, CSS e Bootstrap. Foi criado com fins educativos e para abater horas complementares na faculdade de Análise e Desenvolvimento de Sistemas.

## 🔧 Tecnologias Utilizadas
- PHP
- MySQL
- HTML5
- CSS3
- Bootstrap 5

## 📋 Funcionalidades
- Listar usuários cadastrados
- Adicionar novo usuário
- Visualizar detalhes de um usuário
- Editar dados de usuário
- Excluir usuário do banco de dados

## ⚙️ Como Rodar o Projeto

### Pré-requisitos:
- PHP instalado (ex: via XAMPP, WAMP ou Linux)
- MySQL
- Navegador Web

### Passos:
1. Clone o repositório:
   ```bash
   git clone https://github.com/wsantl/projeto-facudd.git
   ```

2. Configure a conexão no arquivo `conexao.php`:
   ```php
   $conexao = mysqli_connect("localhost", "usuario", "senha", "nome_do_banco");
   ```

3. Rode no navegador:
   - Coloque os arquivos no diretório do servidor (ex: `htdocs` no XAMPP)
   - Ou
   - Rode o servidor php na pasta onde encontra-se o projeto
   - Acesse via navegador: `http://localhost:8000/index.php`

## 📂 Estrutura do Projeto
```
crud-php/
├── acoes.php
├── conexao.php
├── index.php
├── mensagem.php
├── navbar.php
├── usuario-create.php
├── usuario-edit.php
├── usuario-view.php

```

## 📄 Licença
Este projeto foi desenvolvido apenas para fins de estudo e não possui licença comercial.

## 🎓 Projeto para horas complementares
Este sistema foi desenvolvido como exercício prático para reforçar conhecimentos em PHP e MySQL, sendo apresentado como atividade complementar universitária.

---

✨ Sinta-se à vontade para clonar, estudar e modificar o projeto para fins educativos. Contribuições e sugestões são bem-vindas!

