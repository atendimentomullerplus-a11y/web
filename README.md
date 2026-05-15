# IPTV Web Pro - Plataforma Profissional

Uma plataforma IPTV completa com Painel Admin, rea do Usurio, Player HLS otimizado e Proxy Anti-CORS.

## 🚀 Tecnologias
- **Frontend**: React + Vite + TypeScript + TailwindCSS
- **Backend**: Node.js + Express
- **Player**: hls.js (Low Latency)
- **Database**: PostgreSQL
- **Estilo**: Dark Mode / Visual Netflix (Green Aesthetic)

## 📁 Estrutura do Projeto
- `/frontend`: Aplicao React com reas de usurio e admin.
- `/backend`: API Express com autenticao JWT e Proxy IPTV.

## 🛠️ Instalao

### 1. Requisitos
- Node.js (v16+)
- PostgreSQL

### 2. Backend
```bash
cd backend
npm install
# Configure o arquivo .env com suas credenciais do banco
npm run dev
```

### 3. Frontend
```bash
cd frontend
npm install
npm run dev
```

## 📺 Funcionalidades
- **Player Profissional**: Reproduo HLS com buffer inteligente e seleo de qualidade.
- **Painel Admin**: Gesto de usurios, estatsticas de banda e monitoramento de streams.
- **Área do Usuário**: Categorias (TV, Filmes, Sries), Favoritos e Histrico.
- **Proxy Anti-CORS**: Backend preparado para contornar bloqueios de CORS em streams externas.
- **EPG**: Guia de programao integrado (XMLTV ready).

## 🔒 Login (Mock)
- **Admin**: Usurio: `admin@admin.com` | Senha: `qualquer`
- **User**: Usurio: `user@user.com` | Senha: `qualquer`

## 🎨 Identidade Visual
O projeto utiliza uma paleta de cores moderna:
- **Principal**: Verde Vibrante (#00e676)
- **Fundo**: Dark Surface (#0a0a0a)
- **Efeitos**: Glow, Glassmorphism e Framer Motion.

---
Desenvolvido com foco em performance e experincia do usurio.
