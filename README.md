# Academia da Harmonia Militar — Landing Flashcards ESA

Landing estática (HTML + CSS + JS) com:
- Abas (SPA simples);
- Fundo interativo (canvas) verde/dourado;
- Lead magnet “Receba uma amostra dos Flashcards ESA (PDF)”;
- Mockup 3D do baralho;
- Sessões: Início, Produto, Amostra, Depoimentos, FAQ;
- Sticky CTA para compra.

## Publicar no GitHub Pages
1. Repositório público com `index.html`, `policy.html`, `README.md`.
2. Em **Settings → Pages**, use **Branch: main** e **Folder: /(root)**.
3. O site ficará em `https://SEU_USUARIO.github.io/NOME_DO_REPO/`.

## Checkout e Lead
No `index.html`, ajuste:
```js
const CHECKOUT_URL = "https://pay.seu-gateway.com.br/SEU_ID?src=harmonia_militar";
const LEAD_POST_URL = "https://formspree.io/f/SEU_ENDPOINT";
```
Se `LEAD_POST_URL` estiver vazio, o formulário usa `mailto:` como fallback.
