# Site iMarcas

Site estático (HTML + CSS + JS puro). Sem build, sem dependências.

## Publicar no GitHub Pages
1. Crie um repositório (ex.: `imarcas-site`) e suba `index.html` e a pasta `assets/` na raiz.
2. Settings → Pages → Source: branch `main`, pasta `/ (root)` → Save.
3. O site fica em `https://SEU-USUARIO.github.io/imarcas-site/`.
4. Domínio próprio: em Settings → Pages → Custom domain, e um registro CNAME no seu DNS.

## Antes de publicar, troque no index.html
- `5517999999999` → seu WhatsApp (DDI + DDD + número, só dígitos) (aparece 2x)
- `[SEU-EMAIL]` e `[SEU-PERFIL]` no rodapé
- `[DEFINIR: prazo mínimo de contrato]` no FAQ
- Showreel: substitua o botão de play por `<video src="assets/showreel.mp4" autoplay muted loop playsinline>`
- Foto "Quem faz": instrução em comentário no HTML
