# Índice de produtos da Drip Coffee Label

Ponto de partida para quem precisa das artes de produto (projeto do site, loja, atendimento). Mantido pelo projeto Drip Coffee Label: cada produto novo ou arte nova atualiza este arquivo no mesmo commit.

## Como usar
- Cada produto tem um código e uma pasta: `produtos/<código>/`.
- Site e loja: use só a subpasta `loja/`, com as imagens 1500 x 1500 em PNG (`<código>_loja_<nº>_<peça>_v<n>.png`, em ordem pelo número), a descrição em HTML (`<código>_loja_descricao_v<n>.html`), os textos prontos (nome, descrição curta e SEO em `<código>_loja_textos_v<n>.txt`) e, quando houver, o vídeo.
- `ml/` (Mercado Livre) e `shopee/` são versões para marketplace: sem @, WhatsApp e links. Não servem para o site. Cada uma tem seu arquivo de textos pronto para colar (`<código>_<canal>_textos_v<n>.txt`: título, cadastro, descrição, mensagem pós-venda e respostas).
- Vale sempre a maior versão (`_v<n>`). Versões antigas vão para `_arquivo/` dentro da pasta.
- Status: **pronto** (arte entregue, ainda não está no site) ou **no ar** (já publicado). Quando o site publicar um produto, avise o projeto Drip Coffee Label para mudar o status aqui.

## Produtos

| Código | Produto | Linha | Status no site | Pasta do site | Vídeo para o site | Atualizado |
|---|---|---|---|---|---|---|
| DCL-PD-VIR01-BP | Drip Pitágoras (Branco Premium 10 x 15, meme do teorema) | Padronizado (arte pronta, venda direta) | pronto | [produtos/DCL-PD-VIR01-BP/loja/](DCL-PD-VIR01-BP/loja/) | [ml/DCL-PD-VIR01-BP_ml_video_9x16_v1.mp4](DCL-PD-VIR01-BP/ml/DCL-PD-VIR01-BP_ml_video_9x16_v1.mp4) (9:16, serve ao site) | 24/11/2026 |
| DCL-PD-NAT26-PR | Kit Drip de Natal (20 sachês, 5 artes de Natal, 4 de cada; Kraft e Branco Premium 10 x 15) | Padronizado (arte pronta, venda direta) | pronto (só ML e Shopee) | sem pasta `loja/` | [ml/DCL-PD-NAT26-PR_ml_video_9x16_v1.mp4](DCL-PD-NAT26-PR/ml/DCL-PD-NAT26-PR_ml_video_9x16_v1.mp4) | 28/11/2026 |
| DCL-KC-1012 | Kraft Clássico 10 x 12 | Personalizado | no ar | sem pasta `loja/` (arte do site feita no projeto do site) | não | 24/11/2026 |
| DCL-BP-1015 | Branco Premium 10 x 15 | Personalizado | no ar | sem pasta `loja/` (arte do site feita no projeto do site) | não | 24/11/2026 |
| DCL-KP-1015 | Kraft Premium 10 x 15 | Personalizado | no ar | sem pasta `loja/` (arte do site feita no projeto do site) | não | 24/11/2026 |

Os três personalizados têm material só para marketplace, em `2026-11/mercado-livre/<linha>/` e `2026-11/shopee/<linha>/` (linhas: kraft, branco, kraft-premium). Não use esse material no site.
