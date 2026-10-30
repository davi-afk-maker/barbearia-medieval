# ⚔️ Barbearia Medieval — Cortes de Nobreza

Site estático de uma barbearia de tema medieval, com duas abas internas: a página principal (cortes e preços) e a aba de Reclamações e Sugestões.

## 🌐 Publicar no GitHub Pages

1. Crie um repositório no GitHub (ex.: `barbearia-medieval`).
2. Envie os arquivos deste repositório para o branch `main`:

   ```bash
   git init
   git add .
   git commit -m "Site Barbearia Medieval"
   git branch -M main
   git remote add origin https://github.com/SEU-USUARIO/barbearia-medieval.git
   git push -u origin main
   ```

   *(Alternativa: arraste os arquivos direto na aba "Uploads" ou "Add file" do GitHub.)*

3. No repositório, acesse **Settings → Pages**.
4. Em **Source**, escolha **Deploy from a branch** → branch `main` → pasta `/ (root)` → **Save**.
5. Em 1–2 minutos o site ficará disponível em:

   ```
   https://SEU-USUARIO.github.io/barbearia-medieval/
   ```

## 📁 Estrutura

```
.
├── index.html   ← página principal (raiz)
└── .nojekyll    ← evita processamento Jekyll no Pages
```

## ℹ️ Notas

- Não há dependências nem build — é HTML/CSS puro.
- As imagens são carregadas de URLs externas HTTPS (não precisam estar no repositório).
