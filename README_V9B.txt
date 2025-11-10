ACADEMIA DA HARMONIA MILITAR — Landing Page (V9B)
-------------------------------------------------
O que está incluso:
- index.html (comenta: VERSION: V9B no <head>)
- policy.html
- /assets/amostra1.png e /assets/amostra2.png

Como validar que está certo (checklist):
[ ] No topo (MOBILE): apenas o ícone 🎖️ + botão "Amostra ESA" + botão "Comprar" + menu hambúrguer.
[ ] Botão flutuante do WhatsApp (mobile): "Conversar com professor" abrindo wa.me/5561994304159
[ ] Seções: Início / Produto / Amostra / FAQ (sem Depoimentos).
[ ] Galeria com duas miniaturas; ao tocar abre lightbox.
[ ] Sticky bar no rodapé com "Garantir agora" + "Política".
[ ] Formulários enviam para Formspree: https://formspree.io/f/xwpakeqr

Publicação:
1) Envie TUDO para o repositório do GitHub Pages (index.html, policy.html, pasta assets/).
2) Se já houver versões antigas publicadas, limpe o cache do navegador (Ctrl+F5) ou abra em janela anônima.
3) Caso use Cloudflare, limpe o cache lá também.

Edite no index.html:
- const CHECKOUT_URL = "https://pay.seu-gateway.com.br/SEU_ID?src=harmonia_militar"
- const WHATS_PHONE = "5561994304159"
