# Requisitos Elicitados do Mapa de Jornada da Persona

## Introdução

Neste artefato, apresenta-se uma tabela que consolida os requisitos funcionais e não funcionais identificados durante o processo de mapa de Jornada da Persona.  A análise das jornadas permitiu identificar as necessidades e expectativas dos usuários, representados pelas personas, resultando numa lista detalhada de requisitos para o desenvolvimento da aplicação Agenda Online.

## Legenda das Colunas da Tabela de Requisitos

- **Identificador**: Código único para cada requisito, usado para identificação e referência rápida. "RE" significa Requisito Elicitado.
- **Tipo**: Tipo de requisito. "RF" representa Requisito Funcional (o que o sistema deve fazer) e "RNF" representa Requisito Não Funcional (como o sistema deve se comportar).
- **Requisito**: Descrição detalhada do que o sistema deve realizar (requisito funcional) ou das características que ele deve possuir (requisito não funcional).
- **Persona**: Indica a persona que originou o requisito, refletindo suas necessidades e expectativas.
- **Origem**: Indica a técnica utilizada para elicitar o requisito (neste caso, Mapa de Jornada da Persona).


## Resultados

| Identificador | Tipo | Requisito                                                                                                                            | Persona                  | Origem                                      |
|-----------------|------|-----------------------------------------------------------------------------------------------------------------------------------------|--------------------------|---------------------------------------------|
| RE-001          | RF   | O sistema deve permitir a criação, edição e exclusão de eventos com datas e horários específicos.                                          | Paulo, Ana, Eduardo, Juliana | Mapa de Jornada da Persona                  |
| RE-002          | RF   | O sistema deve permitir a configuração de eventos recorrentes (diários, semanais, mensais, anuais).                                      | Paulo                     | Mapa de Jornada da Persona                  |
| RE-003          | RF   | O sistema deve permitir a categorização de eventos (ex: Esporte, pessoal, estudos, trabalho, clientes).                               | Paulo, Ana, Eduardo, Juliana | Mapa de Jornada da Persona                  |
| RE-004          | RF   | O sistema deve permitir a associação de eventos a clientes específicos, incluindo informações detalhadas sobre cada cliente.                 | Juliana, Eduardo          | Mapa de Jornada da Persona                  |
| RE-005          | RF   | O sistema deve permitir a definição de lembretes para eventos com opções de antecedência (horas, dias) e tipo de alerta (notificação, e-mail, etc.). | Todas                     | Mapa de Jornada da Persona                  |
| RE-006          | RF   | O sistema deve oferecer diferentes modos de visualização da agenda (diária, semanal, mensal, anual).                                      | Todas                     | Mapa de Jornada da Persona                  |
| RE-007          | RF   | O sistema deve permitir a busca de eventos por palavra-chave, data, categoria ou cliente.                                                 | Todas                     | Mapa de Jornada da Persona                  |
| RE-008          | RF   | O sistema deve destacar visualmente os eventos do dia atual.                                                                               | Todas                     | Mapa de Jornada da Persona                  |
| RE-009          | RF   | O sistema deve gerar relatórios sobre o tempo gasto em diferentes categorias de eventos.                                                       | Eduardo, Ana              | Mapa de Jornada da Persona                  |
| RE-010          | RF   | O sistema deve fornecer visualizações gráficas (gráficos, tabelas) do uso do tempo.                                                        | Eduardo                   | Mapa de Jornada da Persona                  |
| RE-011          | RF   | O sistema deve permitir a integração com outros aplicativos de calendário (Google Calendar, Outlook, etc.).                              | Ana                       | Mapa de Jornada da Persona                  |
| RE-012          | RF   | O sistema deve permitir a integração com assistentes de voz (ex: Google Assistant, Alexa).                                               | Ana                       | Mapa de Jornada da Persona                  |
| RE-013          | RF   | O sistema deve permitir o cadastro de informações detalhadas sobre clientes (endereços, telefones, preferências, etc.).                   | Juliana, Eduardo          | Mapa de Jornada da Persona                  |
| RE-014          | RF   | O sistema deve oferecer suporte ao gerenciamento de reuniões, incluindo criação de eventos e marcação com outros usuários.                   | Eduardo                   | Mapa de Jornada da Persona                  |
| RE-015          | RNF  | O sistema deve ter uma interface intuitiva e fácil de usar, com navegação simples e clara.                                                  | Todas                     | Mapa de Jornada da Persona                  |
| RE-016          | RNF  | O sistema deve ser fácil de aprender e utilizar, mesmo para usuários sem experiência.                                                       | Todas                     | Mapa de Jornada da Persona                  |
| RE-017          | RNF  | O sistema deve fornecer feedback claro e imediato às ações do usuário.                                                                     | Todas                     | Mapa de Jornada da Persona                  |
| RE-018          | RNF  | O sistema deve ser rápido e responsivo, com tempos de carregamento mínimos.                                                              | Todas                     | Mapa de Jornada da Persona                  |
| RE-019          | RNF  | O sistema deve ser capaz de lidar com grande volume de dados sem comprometer o desempenho.                                                    | Todas                     | Mapa de Jornada da Persona                  |
| RE-020          | RNF  | O sistema deve proteger os dados do usuário contra acesso não autorizado (criptografia, autenticação robusta).                             | Todas                     | Mapa de Jornada da Persona                  |
| RE-021          | RNF  | O sistema deve garantir a confidencialidade e integridade dos dados.                                                                    | Todas                     | Mapa de Jornada da Persona                  |
| RE-022          | RNF  | O sistema deve ser acessível em diferentes dispositivos (desktops, smartphones, tablets).                                                 | Todas                     | Mapa de Jornada da Persona                  |
| RE-023          | RNF  | O sistema deve ser compatível com diferentes sistemas operacionais (Windows, macOS, iOS, Android).                                         | Todas                     | Mapa de Jornada da Persona                  |
| RE-024          | RNF  | O sistema deve ser escalável para suportar um número crescente de usuários e eventos.                                                        | Todas                     | Mapa de Jornada da Persona                  |
| RE-025          | RNF  | O sistema deve ser estável e confiável, com o mínimo de erros e falhas.                                                                  | Todas                     | Mapa de Jornada da Persona                  |
| RE-026          | RNF  | O sistema deve ser acessível a pessoas com deficiências (seguir as diretrizes de acessibilidade WCAG).                                      | Todas                     | Mapa de Jornada da Persona                  |
| RE-027          | RF   | O sistema deve permitir a priorização das tarefas.                                                                                         | Paulo                     | Mapa de Jornada da Persona                  |


## Breve explicação

O mapeamento da jornada do usuário, técnica utilizada para a elicitação dos requisitos, permitiu visualizar a experiência do usuário com a aplicação, desde o início até o fim. Através da análise das etapas da jornada de cada persona, foram identificados os pontos críticos, as necessidades e as expectativas de cada tipo de usuário.  Esta análise resultou na identificação dos requisitos funcionais e não funcionais apresentados na tabela acima.


## Referências


## Histórico de Versão

| Versão | Data       | Descrição                                                                     | Autor(es)                                      | Data de revisão | Revisor(es) |
|--------|------------|---------------------------------------------------------------------------------|-------------------------------------------------|-----------------|-------------|
| `1.0`  | 09/11/2024  | Versão inicial do artefato.                                                | [Vitor Feijó](https://github.com/vitorfleonardo) |                 |             |
| `1.1`  | 14/11/2024  | Adição da classificação dos requisitos como RF ou RNF.                        | [Gabriel Moura](https://github.com/thegm445)     |                 |             |
