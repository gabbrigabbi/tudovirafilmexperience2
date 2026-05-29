# Tudo Vira Filme Experience

Landing page — Novembro 2026, São Paulo.

## Estrutura

```
/
├── index.html     # Landing page completa (self-contained)
├── vercel.json    # Configuração Vercel
└── .gitignore
```

## Subir no GitHub

```bash
# 1. Entre na pasta depois de extrair o ZIP
cd tvf-site

# 2. Inicie o repositório
git init
git add .
git commit -m "feat: landing page Tudo Vira Filme Experience"

# 3. Crie o repositório no github.com e rode:
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/tudo-vira-filme.git
git push -u origin main
```

## Deploy no Vercel

**Opção 1 — via GitHub (recomendado):**
1. Suba o repositório no GitHub (passos acima)
2. Acesse [vercel.com](https://vercel.com) → "Add New Project"
3. Importe o repositório → clique **Deploy**

**Opção 2 — arrastar e soltar:**
1. Acesse [vercel.com/new](https://vercel.com/new)
2. Arraste a pasta `tvf-site` direto na tela

**Opção 3 — CLI:**
```bash
npm i -g vercel
vercel --prod
```
