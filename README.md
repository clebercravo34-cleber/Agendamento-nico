# Agendador — PWA para GitHub Pages

## Estrutura
- `index.html` — aplicação
- `manifest.webmanifest` — configuração PWA
- `sw.js` — Service Worker/offline shell
- `icons/` — ícones

## Publicar no GitHub
1. Crie um repositório no GitHub.
2. Envie todos os arquivos mantendo as pastas.
3. Vá em **Settings → Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**.
5. Escolha `main` e `/ (root)`.
6. Salve e aguarde o GitHub Pages publicar.

Depois abra o endereço do GitHub Pages pelo Chrome no celular. O navegador poderá oferecer **Instalar aplicativo**.

Observação: o PWA funciona em HTTPS, como no GitHub Pages. A conexão com o Supabase continua sendo feita pela própria aplicação.
