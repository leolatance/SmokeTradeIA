# SmokeTradeIA

Sistema de trading automatizado, gera sinais através de API e Métricas RSI para daytrade. O termo IA no app foi uma decisão de marketing. O app tem 12 usuários atualmente, todos com feedback positivo.

## 🚀 Tecnologias

- React 18
- Vite
- TailwindCSS
- ESLint
- Node.js

## 📋 Pré-requisitos

- Node.js (versão 18 ou superior)
- npm ou yarn
- Git

## 🔧 Instalação

1. Clone o repositório:
```bash
git clone https://github.com/leolatance/SmokeTradeIA.git
cd SmokeTradeIA
```

2. Instale as dependências do frontend:
```bash
cd frontend
npm install
```

3. Configure as variáveis de ambiente:
```bash
cp .env.example .env
```
Edite o arquivo `.env` com suas configurações.

## 🚀 Executando o projeto

### Frontend

```bash
cd frontend
npm run dev
```

O frontend estará disponível em `http://localhost:5173`

## 📦 Scripts Disponíveis

- `npm run dev` - Inicia o servidor de desenvolvimento
- `npm run build` - Cria a build de produção
- `npm run lint` - Executa o linter
- `npm run preview` - Visualiza a build de produção localmente

## 🔒 Segurança

Este projeto contém arquivos sensíveis que não devem ser compartilhados. Certifique-se de:

1. Nunca commitar arquivos `.env`
2. Manter suas chaves de API seguras
3. Não compartilhar credenciais de acesso

## 📁 Estrutura do Projeto

```
SmokeTradeIA/
├── frontend/
│   ├── src/
│   │   ├── auth/        # Autenticação e usuários
│   │   ├── components/  # Componentes React
│   │   ├── lib/         # Utilitários e lógica de negócio
│   │   └── assets/      # Recursos estáticos
│   ├── public/          # Arquivos públicos
│   └── dist/           # Build de produção
└── .gitignore
```

