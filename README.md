# Portfólio Carlos Rodero — Site pronto para deploy

Site estático completo, pronto para subir em qualquer serviço de hospedagem gratuito.

## 🚀 Como colocar no ar (3 formas)

### Opção 1 — GitHub Pages (recomendado, grátis para sempre)

1. Crie um repositório público no GitHub. **Duas opções de nome:**
   - `portfolio` → site fica em `https://gutorodero.github.io/portfolio/`
   - `GutoRodero.github.io` → site fica em `https://gutorodero.github.io/` (URL limpa!)

2. Suba TODOS os arquivos desta pasta (não a pasta em si, os arquivos dentro dela).

   Via terminal:
   ```bash
   cd portfolio-deploy
   git init
   git add .
   git commit -m "🚀 primeiro deploy do portfólio"
   git branch -M main
   git remote add origin https://github.com/GutoRodero/portfolio.git
   git push -u origin main
   ```

3. No GitHub, vá em **Settings → Pages**:
   - **Source:** Deploy from a branch
   - **Branch:** `main` / `(root)` → Save

4. Aguarde 1 minuto. Pronto!

---

### Opção 2 — Netlify Drop (mais rápido, sem git)

1. Compacte esta pasta em zip
2. Acesse [app.netlify.com/drop](https://app.netlify.com/drop)
3. Arraste o zip. Ganha uma URL pública instantânea.

---

### Opção 3 — Vercel

1. Acesse [vercel.com](https://vercel.com) e faça login com GitHub
2. Após subir o repo no GitHub (Opção 1), clique em **Add New → Project**
3. Importe o repo `portfolio` → Deploy

---

## 📁 Estrutura

```
portfolio-deploy/
├── index.html              → página inicial
├── projetos.html           → lista de projetos
├── assets/
│   ├── style.css
│   └── project-page.css
└── projetos/
    ├── taskflow.html
    ├── petcare.html
    ├── barpos.html
    ├── snippet-vault.html
    ├── devweather.html
    └── qr-menu.html
```

## ✅ Depois de publicar

Adicione a URL do portfólio:
- Na sua bio do **GitHub**
- No seu **LinkedIn** (seção Site)
- No seu **currículo** (topo, ao lado dos contatos)
