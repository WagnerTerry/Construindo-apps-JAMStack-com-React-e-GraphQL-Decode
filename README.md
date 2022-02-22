# Jamstack

Projeto feito em uma live com o Diego da Rocketseat, abordando o uso do JamStack, Next e Graphql

- rodar o projeto com yarn dev

## Dependecias

- yarn add typescript @types/node @types/react -D
- yarn add urql
- yarn add graphql
- yarn add @graphql-codegen/cli @graphql-codegen/import-types-preset @graphql-codegen/typescript @graphql-codegen/typescript-operations @graphql-codegen/typescript-urql -D
- Acresscentar no package.json a linha em baixo de lint
  "codegen": "graphql-codegen --config codegen.yml"
- rodar o yarn codegen
- yarn add tailwindcss postcss autoprefixer -D
- yarn tailwindcss init -p
- yarn add @tailwindcss/forms @tailwindcss/typography -D
- yarn add @headlessui/react @heroicons/react
