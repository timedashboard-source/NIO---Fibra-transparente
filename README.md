# Consumo de Materiais - Fibra Transparente

## Estrutura
- `index.html`
- `.nojekyll`
- `dados/consolidado.json`
- `dados/consulta_estoque.json`

O dashboard lê sempre os JSONs publicados em `dados/`, com `cache: no-store` e parâmetro de versão. Os dados incorporados ao HTML são usados somente como contingência quando um JSON não estiver disponível.

Para atualizar: gere os JSONs na aba Auxiliar, substitua os dois arquivos da pasta `dados`, faça o commit e aguarde o GitHub Pages concluir o deployment.
