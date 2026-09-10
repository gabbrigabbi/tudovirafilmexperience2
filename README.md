[README.md](https://github.com/user-attachments/files/32035290/README.md)
# Tudo Vira Filme Experience 2026

## Antes de publicar

Edite as constantes no topo do `index.html`:

```js
const KIWIFY_EXPERIENCE_URL = "https://SEU_LINK_EXPERIENCE";
const KIWIFY_BLACK_URL      = "https://SEU_LINK_BLACK";
```

Para o vídeo, procure o comentário `<!-- Para inserir vídeo -->` e substitua pelo embed do YouTube ou arquivo .mp4.

## Deploy

```bash
git init && git add . && git commit -m "TVF Experience 2026"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/tudo-vira-filme.git
git push -u origin main
```
Vercel: Add New Project → importar → Deploy.
