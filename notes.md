# Módulo 1

## Estrutura de diretorio

- /app
  - Contém todas as rotas, componentes e a lógica para a aplicação. É aonde mais vamos trabalhar

    - app/lib
        - Contém as funções usadas na aplicação que podem ser usadas em mais de um lugar, como funções de fetch e utility
    - app/ui
        - Contém todos os componentes de UI da aplicação com estilos pré definidos

- /public
    - Contém todos os assets estaticos da aplicação como imagens

- Scripts
  - Contém os scripts que serão usados para popular o banco de dados

# Banco de dados
- O Next.js possui uma integração da Vercel com postgres
- E já popula as tabelas com valores iniciais usando um arquivo js chamado placeholder-data.js

# /app/lib/definitions.ts
É nesse arquivo em que o Next.js armazena os types das classes da aplicação

# Módulo 2

## Estilos globais
A orientação do Next.js é que o global.css sejá adicionado ao arquivo de root layout em /app/layout.tsx

## Estilos condicionais
Para adicionar estilos condicionais o next.js sugere o uso da biblioteca CLSX para esse fim
[clsx-link](https://github.com/lukeed/clsx)