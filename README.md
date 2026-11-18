# Consumo de Materiais - Fibra Transparente

Dashboard operacional para acompanhamento de consumo e estoque de fibra transparente.

## Publicação no GitHub Pages

1. Crie um repositório no GitHub.
2. Faça o upload dos arquivos deste pacote diretamente na raiz do repositório:
   - `index.html`
   - `.nojekyll`
   - `README.md`
3. No repositório, acesse **Settings > Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**.
5. Escolha a branch **main** e a pasta **/(root)**.
6. Clique em **Save**.
7. Aguarde a publicação. O endereço será exibido na própria tela do GitHub Pages.

## Atualização das bases

1. Abra o dashboard publicado ou o arquivo `index.html` localmente.
2. Use **Atualizar consolidado** para atualizar o consumo.
3. Use **Atualizar estoque** para atualizar o estoque dos centros N490 e N491.
4. Clique em **Baixar index.html**.
5. Substitua o `index.html` no repositório e confirme o commit.

## Regras incorporadas

- Consumo baseado em `Data de atendimento (WO)`.
- Painel de autonomia usado como apoio para Parceira, SAP, UF e Município.
- Estoque limitado aos centros N490 e N491.
- Registros de estoque zerados são desconsiderados.
- Uma bobina equivale a 100 metros.
- Bobinas equivalentes são arredondadas para o inteiro mais próximo.

## Segurança

O painel não armazena credenciais do GitHub e não realiza publicação automática. A alteração do repositório deve ser confirmada por um usuário autorizado.
