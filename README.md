# Brow Muu · Menu de Natal

Cardápio virtual de encomendas de Natal da Brow Muu (guirlandas e bolos de brownie).
A pessoa escolhe sabores e quantidades, preenche os dados e o pedido é enviado pronto pelo WhatsApp.

## Como rodar

É um site estático: basta abrir o `index.html` no navegador, ou publicar a pasta no GitHub Pages.

## Como editar produtos e preços

No início do `<script>` do `index.html`:

- `WHATSAPP` — número que recebe os pedidos (formato `55DDDNUMERO`).
- `PRODUTOS` — produtos, sabores, preços e fotos (as fotos ficam em `assets/`).
