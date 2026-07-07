# Sprint Planning 3

## 1. Identificacao da Sprint

- **Projeto:** Sistema de Reserva de Laboratorios e Emprestimo de Equipamentos
- **Sprint:** Sprint 3
- **Base de planejamento:** Resultados da Sprint Review 2 e backlog inicial da Etapa 01
- **Participantes:** Product Owner e Time Scrum

## 2. Objetivo da Sprint 3

Detalhar e evoluir as funcionalidades administrativas do sistema, permitindo maior controle sobre laboratorios, equipamentos, horarios disponiveis e acompanhamento das solicitacoes.

## 3. Historias Selecionadas

| ID | Historia de usuario | Prioridade | Observacao |
| --- | --- | --- | --- |
| US12 | Como administrador do sistema, quero cadastrar laboratorios e associa-los aos respectivos administradores para organizar a estrutura institucional da universidade. | Alta | Continua o escopo administrativo definido no backlog. |
| US13 | Como administrador do sistema, quero cadastrar colaboradores como administradores de um ou mais laboratorios para delegar a gestao dos recursos institucionais. | Alta | Complementa o cadastro de laboratorios. |
| US17 | Como administrador de laboratorio, quero consultar o calendario consolidado das reservas aprovadas para evitar conflitos de agendamento. | Alta | Melhora o controle das reservas. |
| US21 | Como administrador de laboratorio, quero cadastrar e atualizar informacoes dos equipamentos disponiveis para emprestimo para manter o inventario atualizado. | Alta | Fortalece o controle dos equipamentos. |
| US22 | Como administrador de laboratorio, quero gerenciar os horarios disponiveis dos laboratorios para organizar periodos de funcionamento, manutencao e bloqueios. | Media | Pode ser refinada conforme o tempo da Sprint. |

## 4. Criterios de Aceitacao

### US12 - Cadastrar laboratorios

- O administrador do sistema deve conseguir registrar nome, localizacao e capacidade do laboratorio.
- O laboratorio cadastrado deve ficar disponivel para associacao com administradores.
- Dados obrigatorios nao devem ser aceitos em branco.

### US13 - Associar administradores

- O administrador do sistema deve conseguir vincular um colaborador a um ou mais laboratorios.
- O sistema deve permitir visualizar quais administradores estao associados a cada laboratorio.
- A associacao deve ser editavel em caso de mudanca de responsabilidade.

### US17 - Calendario consolidado

- O administrador de laboratorio deve visualizar reservas aprovadas em uma visao consolidada.
- Reservas no mesmo laboratorio e horario nao devem aparecer como disponiveis.
- A visualizacao deve apoiar a tomada de decisao antes de aprovar novas solicitacoes.

### US21 - Gerenciar equipamentos

- O administrador de laboratorio deve conseguir cadastrar nome, descricao e disponibilidade do equipamento.
- O administrador deve conseguir atualizar dados de equipamentos ja cadastrados.
- Equipamentos indisponiveis nao devem ser apresentados como disponiveis para emprestimo.

### US22 - Gerenciar horarios

- O administrador deve conseguir definir horarios de funcionamento do laboratorio.
- Deve ser possivel bloquear horarios para manutencao ou indisponibilidade.
- Horarios bloqueados nao devem permitir novas reservas.

## 5. Tarefas da Sprint

| Tarefa | Responsavel | Status inicial |
| --- | --- | --- |
| Refinar regras de cadastro de laboratorios | Time Scrum | A Fazer |
| Detalhar fluxo de associacao de administradores | Time Scrum | A Fazer |
| Definir modelo de controle de equipamentos | Time Scrum | A Fazer |
| Detalhar calendario consolidado de reservas | Time Scrum | A Fazer |
| Criar ou atualizar prototipos das telas administrativas | Time Scrum | A Fazer |
| Atualizar documentacao da Sprint 3 | Time Scrum | A Fazer |

## 6. Definicao de Pronto

Um item sera considerado pronto quando:

- A historia de usuario estiver detalhada.
- Os criterios de aceitacao estiverem definidos.
- O fluxo estiver coerente com os diagramas e backlog ja existentes.
- A documentacao estiver registrada no repositorio.
- As evidencias necessarias estiverem adicionadas, quando aplicavel.

## 7. Riscos e Dependencias

- Necessidade de manter coerencia entre backlog, diagramas e prototipos.
- Possivel aumento de escopo ao detalhar funcionalidades administrativas.
- Dependencia de novos prints ou evidencias visuais, caso a entrega da disciplina solicite.

## 8. Resultado Esperado

Ao final da Sprint 3, espera-se que o projeto tenha uma definicao mais completa da area administrativa, incluindo cadastro de laboratorios, associacao de administradores, controle de equipamentos e gerenciamento de horarios.

