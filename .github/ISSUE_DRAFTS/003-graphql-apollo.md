# Substituir/restaurar API para GraphQL com Apollo

Descrição:
Adicionar camada GraphQL (Apollo Server/Client ou alternativa) para concentrar queries/mutations, com types gerados para o frontend.

Motivação:
GraphQL facilita consultas flexíveis e reduz múltiplas chamadas REST no frontend; permite tipagem e codegen para DX melhor.

Critérios de aceitação:
- Esquema GraphQL com tipos principais: Activity, User, Center, Group, Student.
- Endpoints GraphiQL/Playground para desenvolvimento.
- Integração com Apollo Client no frontend e geração de tipos.

Etiquetas sugeridas: `feature`, `api`, `graphql`.

Estimativa: 3-6 dias.