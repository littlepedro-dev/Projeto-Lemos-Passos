# ValeFlow — Gestão de Vale-Transporte

Versão organizada do código fornecido, separando HTML, CSS e JavaScript sem alterar intencionalmente as regras de negócio.

## Estrutura

- `index.html`: estrutura da página e carregamento das dependências.
- `css/styles.css`: estilos e responsividade.
- `js/app.js`: estado da aplicação, cálculos, importação, telas e eventos.

## Como executar

1. Extraia a pasta do ZIP.
2. Abra `index.html` no navegador ou use a extensão Live Server no VS Code.
3. A importação de `.xlsx`, `.xls` e `.csv` utiliza a biblioteca SheetJS carregada por CDN; é necessária conexão com a internet para carregar essa dependência.

## Observação importante

Esta versão mantém o armazenamento local via `localStorage` (`vf1`). Os dados ficam neste navegador/dispositivo e não são sincronizados entre usuários. A autenticação existente no código original é local e não substitui um sistema de autenticação seguro em servidor.
