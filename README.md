# Protótipo FIRMES — apresentação comercial

Protótipo visual e navegável da loja **FIRMES** (moda cristã). Não altera o site original, não faz deploy e não se conecta a nenhum serviço.

## Como abrir
1. Baixe a pasta `firmes-prototipo`.
2. Dê dois cliques em `index.html` (abre no navegador). Não precisa instalar nada.
3. Opcional: para testar em servidor local, rode `python3 -m http.server 8000` dentro da pasta e acesse `http://localhost:8000`.

## Arquivos
- `index.html`: estrutura, textos e SEO on-page (title, meta description, H1 único, JSON-LD apenas com nome e URL).
- `style.css`: identidade visual (preto, branco, cinza claro e dourado), layout responsivo (360px, 768px, desktop).
- `script.js`: filtros por coleção, busca de demonstração, carrinho de demonstração, menu mobile, FAQ e voltar ao topo. **Os produtos de exemplo estão na lista `PRODUCTS`, no topo do arquivo.**
- `assets/`: favicon local. As imagens dos produtos são ilustrações de exemplo identificadas na tela.

## O que é demonstração
- "Adicionar ao carrinho" só mostra feedback visual.
- Links marcados "a confirmar" exibem um aviso em vez de abrir uma página.
- Preços, cores, tamanhos e nomes de produtos estão como "a confirmar" até receber o catálogo oficial.

## Links reais usados
Somente a home e as coleções públicas de https://lojafirmes.com.br, no rodapé.
