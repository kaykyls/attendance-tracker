# Attendance Tracker

Sistema de controle de presença com Laravel, Vue.js e Inertia.js.

## 📋 Pré-requisitos

**Windows:**
- [Docker Desktop](https://www.docker.com/products/docker-desktop/)
- [XAMPP](https://www.apachefriends.org/download.html) (inclui PHP 8.2+ e Composer)
- [Git](https://git-scm.com/download/win)

**Linux:**
- [Docker](https://docs.docker.com/engine/install/)
- [Docker Compose](https://docs.docker.com/compose/install/)
- [PHP 8.2+](https://www.php.net/downloads.php)
- [Composer](https://getcomposer.org/download/)
- [Git](https://git-scm.com/download/linux)

## 🚀 Instalação

### 1. Clone o repositório
```bash
git clone https://github.com/kaykyls/attendance-tracker-backend
cd attendance-tracker
```

### 2. Configure o .env

**Windows (PowerShell):**
```powershell
# Copie o arquivo de ambiente
copy .env.example .env
```

**Linux:**
```bash
# Copie o arquivo de ambiente
cp .env.example .env
```

### 3. Instale as dependências
```bash
composer install
```

## 🎯 Executar o projeto

> **⚠️ Importante para Windows:** É necessário usar o terminal do WSL (Windows Subsystem for Linux) para evitar avisos de sistema não suportado. Você pode abrir o WSL digitando `wsl` no PowerShell ou usar o terminal integrado do VS Code.

**Desenvolvimento:**
```bash
# Inicie o ambiente
./vendor/bin/sail up -d

# Execute o servidor de desenvolvimento
./vendor/bin/sail npm run dev
```

**Acesse a aplicação:**
- 🌐 **URL:** http://localhost

## 🐛 Problemas comuns

**Windows:**
- Docker Desktop não está rodando → Abra o Docker Desktop
- Erro de permissão → Execute PowerShell como Administrador

**Linux:**
- Permissões de arquivo → `sudo chown -R $USER:$USER .`
- Docker não está rodando → `sudo systemctl start docker`
- Usuário não está no grupo docker → `sudo usermod -aG docker $USER`

## 📝 Tecnologias

- Laravel 12.x
- Vue.js 3 + Inertia.js
- Tailwind CSS
- MySQL 8.0
- Redis
- Docker + Laravel Sail
