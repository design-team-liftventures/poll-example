# Polls Playground — Hot Takes

Protótipo estático (HTML/CSS/JS inline em um único arquivo `index.html`). Não há
build nem backend — é servido diretamente como site estático.

## Deploy no Vercel

### Opção 1 — Dashboard (Git)
1. Faça push deste repositório para o GitHub/GitLab/Bitbucket.
2. Em [vercel.com/new](https://vercel.com/new), importe o repositório.
3. Em **Framework Preset**, selecione **Other** (sem framework).
4. Deixe **Build Command** e **Output Directory** vazios e clique em **Deploy**.

### Opção 2 — Vercel CLI
```bash
npm i -g vercel
vercel        # preview
vercel --prod # produção
```

## Rodar localmente
Basta abrir `index.html` no navegador, ou servir a pasta:
```bash
npx serve .
```
