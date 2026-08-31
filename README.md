- `styles.css` — visual limpo de app de finanças
- `scripts.js` — a IA lendo o comprovante (comentado passo a passo)

## Como usar

1. Toque na área 🧾 e fotografe (ou escolha) um comprovante — pode mandar **várias fotos de uma vez**, e também **arrastar** ou **colar (Ctrl+V)** a imagem.
2. A IA lê e o gasto entra na lista com emoji da categoria, itens e data.# 📸 Gasto na Foto

App de finanças pessoais no modo preguiçoso: **fotografe o comprovante e a IA anota o gasto** — estabelecimento, itens, valor e categoria. O total soma sozinho. Grátis, sem chave de API.

## Como abrir

1. Abra a pasta no **VS Code**.
2. Instale a extensão **Live Server**.
3. Clique com o botão direito no `index.html` → **Open with Live Server**.

## Arquivos

- `index.html` — total, área de foto e lista de gastos
3. O **total** no topo soma automaticamente.
4. Clique no **emoji** de um comprovante pra rever a foto original.
5. Errou? O **✕** apaga o comprovante (com botão de desfazer). Dá pra apagar tudo no link do rodapé.

Categorias: 🛒 Mercado · 🚗 Transporte · 🍔 Comida · 💊 Saúde · 🎉 Lazer · 🏠 Casa · 💸 Outros

## 💾 Onde ficam os gastos

Agora os gastos são salvos no **localStorage** do navegador: pode recarregar a página que a lista continua lá. Eles ficam só no seu navegador — limpar os dados do site apaga tudo.

## A IA

**Puter.js** (`https://js.puter.com/v2/`) — IA com visão, de graça, **sem chave**. Na primeira foto o navegador pode pedir uma conta gratuita no Puter. A foto é reduzida antes do envio pra resposta vir mais rápida, e a resposta é validada antes de entrar na lista.
