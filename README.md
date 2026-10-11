# Autorização de divulgação de locação — RE/MAX SOUL

Aplicação estática no GitHub Pages para preencher o documento original de autorização de divulgação de anúncio de locação de imóvel sem exclusividade.

## Como funciona

- O formulário está organizado em blocos, seguindo o padrão visual do EBIMOB Rent Tool.
- O DOCX original, já versionado neste repositório, é carregado automaticamente pelo navegador.
- **Gerar DOCX preenchido** preenche os campos sem reconstruir o documento Word do zero: cabeçalho, logo, tabelas, paginação e estilos do modelo são preservados.
- **Visualizar / PDF** monta uma versão de impressão com template string e abre a janela de impressão do navegador. Selecione “Salvar como PDF”.
- Não há login, backend ou banco de dados. Os dados do formulário são processados localmente no navegador.

## Publicação

- Página: https://andrebroncadev.github.io/autorizacao-locacao/
- Modelo DOCX: `modelo autorização de divulgação LOCACÃO REMAX SOUL sem exclusividade.docx`
- Arquivos da aplicação: `index.html`, `styles.css`, `app.js`

## Conferência recomendada

Antes de usar uma autorização real, gere um DOCX com dados de teste, abra no Word/LibreOffice e confirme campos, marcações de opções, quebras de linha e paginação. A versão DOCX utiliza o arquivo original como matriz; a versão PDF é uma composição de impressão baseada no mesmo texto e nos mesmos campos.
