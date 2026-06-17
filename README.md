# PassaporteIO


Sistema web desenvolvido em Laravel para gerenciar eventos.

---

## Tecnologias Utilizadas

* PHP 8.3
* Laravel 12
* SQLite / MySQL
* Laravel Breeze
* Tailwind CSS
* JavaScript
* Vite

---

## Funcionalidades

### Usuário

* Criar conta
* Realizar login
* Editar perfil
* Recuperar senha
* Visualizar informações do sistema

### Administrador

* Gerenciar usuários
* Criar registros
* Editar registros
* Excluir registros
* Visualizar relatórios
* Dashboard administrativo

### Sistema

* Controle de permissões
* Validação de dados
* Responsividade para dispositivos móveis
* Interface moderna e intuitiva
* Notificações em tempo real

---

## Requisitos

* PHP 8.3 ou superior
* Composer
* Node.js
* NPM
* Banco de dados SQLite ou MySQL

---

## Instalação

Clone o repositório:

```bash
git clone https://github.com/seu-usuario/seu-projeto.git
```

Acesse a pasta do projeto:

```bash
cd seu-projeto
```

Instale as dependências do PHP:

```bash
composer install
```

Instale as dependências do frontend:

```bash
npm install
```

Configure o arquivo de ambiente:

```bash
cp .env.example .env
```

Gere a chave da aplicação:

```bash
php artisan key:generate
```

Execute as migrações:

```bash
php artisan migrate
```

Inicie o servidor:

```bash
php artisan serve
```

Execute os assets:

```bash
npm run dev
```

---

## Estrutura de Perfis

### Visitante

* Visualizar conteúdo público
* Criar conta
* Realizar login

### Usuário

* Acessar funcionalidades do sistema
* Gerenciar seus dados
* Consultar histórico

### Administrador

* Gerenciar usuários
* Gerenciar conteúdo
* Acessar relatórios e dashboard
