# YWS Energia Solar — Dimensionador e Orçamento

Simulador fotovoltaico independente em HTML, CSS e JavaScript, pronto para publicação no GitHub Pages.

## Publicar no GitHub

1. Crie ou abra o repositório no GitHub.
2. Envie os arquivos desta pasta para a raiz do repositório.
3. No repositório, abra **Settings → Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**.
5. Selecione a branch `main` e a pasta `/(root)`, depois salve.
6. Aguarde a publicação do GitHub Pages.

O arquivo principal do site é `index.html`. Não precisa de instalação de dependências nem de build.

## O que o simulador faz

- Estima quantidade de painéis, potência, geração mensal e área.
- Calcula custo de painéis, inversor, fixação, perfis, emendas, mão de obra e extras.
- Calcula preço de venda sugerido com base na margem bruta desejada.
- Mostra economia bruta estimada, cobertura e retorno simples.
- Permite copiar o resumo e imprimir/salvar em PDF.

## Atenção aos preços e quantidades

Os valores cadastrados são referências editáveis e devem ser conferidos antes de emitir orçamento. O preço unitário de emendas começa em R$ 0, pois não foi informado na tabela original. Quantidades de fixação e perfis são estimativas e devem ser revisadas conforme o projeto e o fabricante. O simulador não substitui vistoria ou projeto técnico.
