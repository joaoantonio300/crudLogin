# 📋 CrudCadastro

Um **CRUD simples** para gerenciar usuários, desenvolvido com **PHP** e estilizado com **Bootstrap**.  

---

## ⚙️ Funcionalidades
- ➕ Adicionar novos usuários  
- 📄 Listar usuários  
- ✏️ Editar usuários existentes  
- ❌ Deletar usuários  

---

## 📂 Estrutura do Projeto

**Repositorys/**  
- `UsuarioRepository.php` – Funções de acesso ao banco  
- `DatabaseConnection.php` – Conexão com o banco de dados  

**Scripts principais**  
- `index.php` – Página inicial  
- `listarUsuario.php` – Lista todos os usuários  
- `novoUsuario.php` – Formulário para criar usuário  
- `salvarUsuario.php` – Salva novo usuário  
- `editarUsuario.php` – Formulário para editar usuário  
- `salvarEdicao.php` – Salva alterações de edição  
- `deletarUsuario.php` – Deleta um usuário  

---

## 🛠 Tecnologias
- **PHP**  
- **MySQL**  
- **Bootstrap**  

---

## 🚀 Como Rodar
1. Coloque os arquivos em um servidor local (XAMPP, WAMP ou similar)  
2. Configure a conexão no `DatabaseConnection.php`  
3. Abra `index.php` no navegador para usar o CRUD
