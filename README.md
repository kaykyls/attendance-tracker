# Attendance Tracker

Sistema de controle de presença com Laravel, Vue.js e Inertia.js.

## 📋 Pré-requisitos

**Windows:**
- [Docker Desktop](https://www.docker.com/products/docker-desktop/)
- [Git](https://git-scm.com/download/win)

**Linux:**
- [Docker](https://docs.docker.com/engine/install/)
- [Docker Compose](https://docs.docker.com/compose/install/)
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

## 🎯 Executar o projeto

**Desenvolvimento:**
```bash
# Inicie o ambiente
./vendor/bin/sail up -d

# Execute o servidor de desenvolvimento
./vendor/bin/sail npm run dev
```

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
