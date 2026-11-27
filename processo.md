# Acordo de trabalho do grupo

Projecto: Caderneta Digital do Coordenador de Turno
Engenharia de Software I · ISPTEC · 2026/2027

Este documento é o acordo de trabalho do grupo. Descreve **como** trabalhamos com o Scrum e o Kanban. Muda raramente e sempre através de Pull Request revisto por outro membro. O que acontece em cada sprint fica registado em `sprints/sprint-N.md`.

## Objectivo do Produto
Uma aplicação web responsiva, para computador e telemóvel, que centraliza alunos, turmas, ocorrências e medidas aplicadas, para o coordenador de turno registar, acompanhar e consultar cada caso num só sítio.

## Definição de Pronto
Uma issue só está pronta quando:
- o Pull Request foi revisto e aprovado por outro membro;
- foi juntado à `main` e a issue foi fechada com `Closes #n` caso for feita faziadamente catalogar com `Refs #n`
- os critérios de aceitação da issue estão cumpridos;
- funciona localmente, seguindo o README;
- usar apenas dados fictícios;
- a interface é usável no computador e no telemóvel (quando aplicável).

Um item que não cumpre a Definição de Pronto no fim da sprint não é entregue nem conta como Incremento: volta à lista do produto e é reavaliado pelo Product Owner.

## Equipa
| Membro | Responsabilidade | Tarefas no projecto |
|---|---|---|
| Orlando Cumandala | Scrum Master (e Developer) | Organizar os eventos da sprint, manter o quadro e o `processo.md` actualizados, remover impedimentos, garantir que os PRs são revistos; implementar issues como Developer |
| Sabino Gaspar | Product Owner e (developer) | Definir e esclarecer os requisitos do projecto, organizar e priorizar o Product Backlog, criar e descrever as issues, validar as funcionalidades desenvolvidas de acordo com os critérios de aceitação; implementar issues como Developer. |
| Augusto Nangayafina | Developer | Analisar as issues atribuídas, desenvolver as funcionalidades do sistema, escrever e testar o código, corrigir erros, actualizar a documentação técnica quando necessário e submeter Pull Requests para revisão. |

Regra: cada membro preenche **apenas a sua própria linha**, no seu próprio ramo, através de Pull Request revisto por outro membro. Ninguém edita a linha de outro!

## Regras do quadro
O quadro está no GitHub Projects e cada tarefa é uma issue.

| Coluna | Significado |
|---|---|
| Lista do produto | Tarefas ordenadas por prioridade, ainda não escolhidas para uma sprint |
| Sprint Actual | Tarefas escolhidas no planeamento da sprint em curso, ainda não iniciadas |
| Em curso | Alguém já está a trabalhar nela, com ramo criado |
| Em revisão | Pull Request aberto, à espera da revisão de outro membro |
| Concluído | Pull Request aprovado e junto à `main`; cumpre a Definição de Pronto |

Limite do "Em curso": (número de membros do grupo + 1 ) tarefas ao mesmo tempo, para ninguém começar muita coisa sem acabar.


Convenções:
- Cada issue tem um responsável (Assignee) e a sua sprint no campo de iteração (Sprint 1 a 5).
- Um ramo por issue; commits com mensagens claras.
- Cada Pull Request liga-se à sua issue: usa `Closes #n` quando o PR conclui a issue, e `Refs #n` quando a issue ainda precisa de mais PRs. O último PR de cada issue leva sempre `Closes #n`.
- Nenhum Pull Request entra na `main` sem revisão de outro membro; ninguém aprova o próprio PR.
- Correcções a um PR ainda aberto fazem-se no mesmo ramo; uma alteração nova depois do merge usa um ramo novo.


## Eventos
As sprints duram 4 dias reais (2 semanas simuladas). Os eventos são leves e registados no ficheiro `sprints/sprint-N.md`, através de Pull Request, no próprio dia em que acontecem.

| Evento | Propósito | Quem participa | Máximo no Guia (sprint de 1 mês) | Duração escolhida | O que sai |
|---|---|---|---|---|---|
| Sprint | Ciclo de duração fixa em que se produz um Incremento | Toda a equipa | 1 mês | 4 dias | Incremento a funcionar, etiqueta `sprint-N` |
| Planeamento da sprint | Decidir o que fazer e como | Toda a equipa | 8 horas | 30 minutos, no primeiro dia | Objectivo da Sprint e lista da sprint |
| Reunião diária | Inspeccionar o progresso e ajustar o plano | Developers | 15 minutos | Escrita: 3 linhas por membro, por dia | Entrada diária no ficheiro da sprint |
| Revisão da sprint | Mostrar o Incremento e recolher retorno | Toda a equipa e o coordenador de turno | 4 horas | 20 minutos, no último dia | Demonstração e retorno registados |
| Retrospectiva | Melhorar a forma de trabalhar | Toda a equipa | 3 horas | 20 minutos, na mesma sessão da revisão | Melhorias para a sprint seguinte |

Justificação: como a sprint dura 4 dias, os tempos foram reduzidos proporcionalmente. A reunião diária é escrita para ficar registada no GitHub com data, e a revisão e a retrospectiva fazem-se na mesma sessão, cada uma cumprindo o seu propósito. Estas durações devem ser confirmadas pelo grupo.

## Valores do grupo
| Valor do Manifesto Ágil | Decisão do grupo | O que continua a ter valor (lado direito) |
|---|---|---|
| Indivíduos e interacções mais do que processos e ferramentas | Combinar dúvidas e bloqueios por conversa no grupo antes de abrir tarefas ou tickets | Processos e ferramentas (quadro, Git, PRs) |
| Software funcional mais do que documentação abrangente | Mostrar um protótipo ao coordenador de turno antes de escrever documentos extensos | Documentação (requisitos, README) |
| Colaboração com o cliente mais do que negociação de contratos | Enviar uma demonstração ao coordenador no fim de cada sprint e registar o retorno | Contrato (o enunciado e o produto mínimo obrigatório) |
| Responder a mudanças mais do que seguir um plano | Reordenar a lista do produto na retrospectiva, quando o retorno do coordenador o justificar | Plano (objectivo da sprint e calendário) |



## Como combinamos o Scrum e o Kanban
(a preencher: o que vem do Scrum, o que vem do Kanban e como as medidas de fluxo apoiam a reunião diária e a retrospectiva)

## Ferramentas
- Git e GitHub: controlo de versões, ramos, Pull Requests e revisão de código.
- GitHub Projects: quadro Kanban, campo de iteração e vistas.
- WhatsApp: comunicação do grupo e envio da demonstração ao coordenador.
- Inteligência artificial: ferramenta de apoio, com as regras abaixo.

Qualquer ferramenta adicional só entra aqui depois de funcionar, de ser usada por todos e de ter evidência de uso no relatório.

## Desafio a vigiar
(a preencher após a leitura do artigo de Ahmad, Markkula e Oivo, 2013, e a rever em todas as retrospectivas)

## Regras de uso da IA
- Verificamos nas fontes oficiais (Scrum Guide, Kanban Guide, GitHub Docs) tudo o que a IA disser.
- Indicamos no relatório onde e como a usámos (ferramenta, finalidade e parte do trabalho).
- Cada membro consegue explicar, sozinho, qualquer parte do código e do relatório.
- O processo é do grupo: issues, ramos, revisões e registos das sprints são feitos pelos membros e ficam registados no GitHub.
