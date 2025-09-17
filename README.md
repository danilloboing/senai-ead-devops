# Página de Login - DevOps

Uma página de login simples e responsiva com deploy automatizado via GitHub Actions.

## 🚀 Funcionalidades

- Design responsivo e moderno
- Interface de login limpa e intuitiva
- Deploy automatizado para GitHub Pages
- Build otimizado com minificação

## 🛠️ Tecnologias

- HTML5
- CSS3
- GitHub Actions
- GitHub Pages

## 📦 Scripts Disponíveis

```bash
# Instalar dependências
npm install

# Build do projeto (minifica HTML/CSS/JS)
npm run build

# Servir versão de desenvolvimento
npm run dev

# Servir versão de produção
npm run serve
```

## 🚀 Deploy

O deploy é feito automaticamente via GitHub Actions quando há push para a branch `main`. A página será disponibilizada no GitHub Pages.

## 📁 Estrutura do Projeto

```
├── .github/
│   └── workflows/
│       └── deploy.yml          # Pipeline de CI/CD
├── dist/                       # Build de produção (gerado automaticamente)
├── index.html                  # Página principal
├── package.json                # Dependências e scripts
├── .gitignore                  # Arquivos ignorados pelo Git
└── README.md                   # Este arquivo
```
