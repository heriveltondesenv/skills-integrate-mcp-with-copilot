# Adicionar autenticação JWT e controle de acesso

Descrição:
Adicionar suporte à autenticação baseada em JWT e proteção de rotas/endpoints no backend, além de verificação de permissões no frontend (áreas administrativas).

Motivação:
Atualmente a API é pública e não há controle de acesso; precisamos proteger recursos sensíveis (criação/edição de atividades, administração de usuários).

Critérios de aceitação:
- Endpoints críticos exigem token JWT válido.
- Fluxo de login retorna JWT para uso no frontend.
- Diretiva/guardas no backend para verificar permissões de admin/teacher.
- Frontend armazena token de forma segura e redireciona para login quando necessário.

Etiquetas sugeridas: `feature`, `backend`, `security`.

Estimativa: 3-5 dias.