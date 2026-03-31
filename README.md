# GitHub Landing Page

Projeto estático de página institucional baseado em uma landing page do GitHub.

## Visão geral

- Estrutura construída com HTML semântico (`index.html`).
- Estilo totalmente em CSS (`style.css`) sem bibliotecas ou frameworks externos.
- Layout responsivo usando `flex` e `grid` para cards e seções.
- Modelo de conteúdo organizado em seções: hero, features, pricing, team, FAQ, testimonials e footer.

## Tecnologias

- HTML5
- CSS3

## Principais características

- Navegação fixa (`sticky header`) com links internos.
- Seção hero chamativa com chamada para ação.
- Grade responsiva para planos (`pricing-grid`) e equipe (`team-grid`).
- Cartões estilizados com transições e sombras.
- Seção FAQ com perguntas e respostas.
- Rodapé simples com navegação e marca.

## Estrutura do projeto

- `index.html` — conteúdo e marcação da página.
- `style.css` — design, tipografia, cores e responsividade.
- `.gitignore` — arquivos e pastas que não são versionados.
- `restrito/` — diretório excluído do controle de versão pelo `.gitignore`.

## Modelagem e organização

- Cada área do site é separada em seções semânticas com IDs para navegação.
- Uso de classes reutilizáveis para elementos comuns, como cards, grids e botões.
- Cores e estilo principal definidos em variáveis CSS (`:root`), facilitando ajustes de tema.
- Acessibilidade básica com `aria-label` em navegação.

## Como usar

1. Abra `index.html` diretamente no navegador.
2. Ou sirva a pasta pelo seu servidor local preferido.

## Observações

- Não há dependências externas instaladas ou usadas.
- O projeto é ideal para uma página estática de apresentação ou protótipo visual.
- O diretório `restrito/` está configurado para ficar fora do repositório (`.gitignore`).

## Recomendações para expansão

- adicionar JavaScript para alternar entre temas claros e escuros;
- incluir formulário de contato funcional;
- criar mais páginas internas ou componentes reutilizáveis;
- adicionar testes de responsividade e compatibilidade de navegador.
