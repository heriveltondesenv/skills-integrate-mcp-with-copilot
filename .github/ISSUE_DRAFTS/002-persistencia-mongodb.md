# Migrar persistência para MongoDB

Descrição:
Substituir o armazenamento em memória por persistência em MongoDB, com modelos para `activities`, `users`, `centers`, `groups`, `students`.

Motivação:
Persistência atual é volátil; precisamos dados duráveis entre deploys e maior escalabilidade.

Critérios de aceitação:
- Conectar à instância MongoDB via `MONGO_URL` e `DB_NAME`.
- CRUD básico para `activities` usando o banco.
- Scripts de seed para dados de exemplo.
- Testes básicos de integração local com Docker Compose.

Etiquetas sugeridas: `backend`, `database`, `infra`.

Estimativa: 2-4 dias.