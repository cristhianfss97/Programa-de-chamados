# Sistema de Chamados Moderno - TODO

## Fase 1: Banco de Dados e Estrutura
- [x] Criar schema de chamados (tickets) com campos: id, título, descrição, prioridade, categoria, status, criador, criado_em, atualizado_em
- [x] Criar schema de histórico de atualizações (ticket_history) para rastrear mudanças
- [x] Criar schema de categorias de chamados
- [x] Executar migrações do banco de dados
- [x] Criar rotas tRPC para gerenciamento de chamados

## Fase 2: Dashboard e Componentes
- [x] Criar layout do dashboard com indicadores visuais
- [x] Implementar gráficos de status (novo, em andamento, resolvido, fechado)
- [x] Implementar indicadores de prioridade
- [x] Criar componentes de card de chamado
- [x] Implementar tema elegante com Tailwind CSS 4
- [x] Adicionar animações suaves com Framer Motion
- [x] Criar página Home com apresentação do sistema

## Fase 3: Funcionalidades de Chamados
- [x] Criar página de listagem de chamados
- [x] Implementar filtros por status, prioridade e categoria
- [x] Criar formulário de criação de chamado
- [x] Implementar atualização de status de chamado
- [x] Criar página de detalhes do chamado
- [x] Implementar busca de chamados
- [x] Implementar histórico de alterações

## Fase 4: Painel Administrativo
- [ ] Criar painel administrativo (visível apenas para admins)
- [ ] Implementar visualização de todos os chamados
- [ ] Implementar histórico de atualizações
- [ ] Criar sistema de comentários/notas em chamados
- [ ] Implementar atribuição de chamados a usuários

## Fase 5: Testes e Otimização
- [ ] Escrever testes unitários com Vitest
- [ ] Testar fluxos de autenticação
- [ ] Testar criação e atualização de chamados
- [ ] Otimizar performance
- [ ] Criar checkpoint final
