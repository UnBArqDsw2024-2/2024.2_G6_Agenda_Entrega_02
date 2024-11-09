# Requisitos Elicitados do Golden Path

## Introdução

Neste artefato, apresenta-se uma tabela que consolida os requisitos funcionais durante o processo de Golden Path.

## Legenda das Colunas da Tabela de Requisitos

- **Identificador**: Código único para cada requisito, usado para identificação e referência rápida. "RE" significa Requisito Elicitado.
- **Tipo**: Tipo de requisito. "RF" representa Requisito Funcional (o que o sistema deve fazer) e "RNF" representa Requisito Não Funcional (como o sistema deve se comportar).
- **Requisito**: Descrição detalhada do que o sistema deve realizar (requisito funcional) ou das características que ele deve possuir (requisito não funcional).
- **Origem**: Indica a técnica utilizada para elicitar o requisito.

## Resultados

<font size="3"><p style="text-align: center"><b>Tabela 1</b>  Requisitos elicitados do Golden Path.</p></font>

| Identificador | Tipo | Requisito | Origem |
|---------------|------|-----------|--------|
| RE-001 | RF | O sistema deve permitir que o usuário acesse a agenda online através de um navegador. | [Golden Path](https://github.com/UnBArqDsw2024-2/2024.2_G6_Agenda_Entrega_01/blob/main/docs/Base/designSprint/define.md) |
| RE-002 | RF | O sistema deve exibir uma tela de login ao acessar a agenda online. | [Golden Path](https://github.com/UnBArqDsw2024-2/2024.2_G6_Agenda_Entrega_01/blob/main/docs/Base/designSprint/define.md) |
| RE-003 | RF | O sistema deve permitir que o usuário insira suas credenciais (login e senha) na tela de login para autenticação. | [Golden Path](https://github.com/UnBArqDsw2024-2/2024.2_G6_Agenda_Entrega_01/blob/main/docs/Base/designSprint/define.md) |
| RE-004 | RF | O sistema deve permitir que o usuário se cadastre caso não tenha uma conta, direcionando-o para uma tela de cadastro. | [Golden Path](https://github.com/UnBArqDsw2024-2/2024.2_G6_Agenda_Entrega_01/blob/main/docs/Base/designSprint/define.md) |
| RE-005 | RF | O sistema deve autenticar o usuário após a inserção correta das credenciais, permitindo o acesso à plataforma. | [Golden Path](https://github.com/UnBArqDsw2024-2/2024.2_G6_Agenda_Entrega_01/blob/main/docs/Base/designSprint/define.md) |
| RE-006 | RF | O sistema deve exibir uma tela de carregamento após o login e antes de acessar a plataforma. | [Golden Path](https://github.com/UnBArqDsw2024-2/2024.2_G6_Agenda_Entrega_01/blob/main/docs/Base/designSprint/define.md) |
| RE-007 | RF | O sistema deve exibir uma tela de calendário como página inicial após a autenticação bem-sucedida. | [Golden Path](https://github.com/UnBArqDsw2024-2/2024.2_G6_Agenda_Entrega_01/blob/main/docs/Base/designSprint/define.md) |
| RE-008 | RF | O sistema deve permitir que o usuário selecione um dia específico no calendário para visualizar as atividades desse dia. | [Golden Path](https://github.com/UnBArqDsw2024-2/2024.2_G6_Agenda_Entrega_01/blob/main/docs/Base/designSprint/define.md) |
| RE-009 | RF | O sistema deve permitir que o usuário selecione opções de visualização no calendário, como "dia", "semana" ou "mês". | [Golden Path](https://github.com/UnBArqDsw2024-2/2024.2_G6_Agenda_Entrega_01/blob/main/docs/Base/designSprint/define.md) |
| RE-010 | RF | O sistema deve exibir uma tela detalhada das atividades ao selecionar um dia específico no calendário. | [Golden Path](https://github.com/UnBArqDsw2024-2/2024.2_G6_Agenda_Entrega_01/blob/main/docs/Base/designSprint/define.md) |
| RE-011 | RF | O sistema deve permitir que o usuário acesse um "board específico" com as atividades do dia, organizadas conforme a seleção no calendário. | [Golden Path](https://github.com/UnBArqDsw2024-2/2024.2_G6_Agenda_Entrega_01/blob/main/docs/Base/designSprint/define.md) |
| RE-012 | RF | O sistema deve permitir que o usuário crie ou edite tarefas diretamente na tela das atividades do dia. | [Golden Path](https://github.com/UnBArqDsw2024-2/2024.2_G6_Agenda_Entrega_01/blob/main/docs/Base/designSprint/define.md) |
| RE-013 | RF | O sistema deve exibir uma tela de confirmação após a criação ou edição de uma tarefa para assegurar que a operação foi concluída com sucesso. | [Golden Path](https://github.com/UnBArqDsw2024-2/2024.2_G6_Agenda_Entrega_01/blob/main/docs/Base/designSprint/define.md) |

<font size="3"><p style="text-align: center"><b>Autor:</b>  [Vitor Feijó](https://github.com/vitorfleonardo), 2024.</p></font>

## Breve explicação

A técnica do Golden Path consiste em mapear o fluxo ideal de navegação do usuário desde o momento em que ele acessa o sistema até o cumprimento de suas tarefas principais. Esse método permite que a equipe visualize o caminho mais direto e simplificado que um usuário deve seguir, sem distrações ou complexidades desnecessárias. Durante a aplicação do Golden Path, a equipe de desenvolvimento identificou as etapas centrais que um usuário percorreria ao utilizar a agenda online, como login, navegação no calendário, visualização de atividades e criação de eventos. Essa técnica ajudou a priorizar funcionalidades e eliminar barreiras, garantindo que o sistema proporcione uma experiência eficiente e intuitiva para o usuário final.

## Referências

><a>1.</a> GOTHELF, J.; SEIDEN, J. Lean UX: Applying Lean Principles to Improve User Experience. Sebastopol, CA: O'Reilly Media, 2013.

## Histórico de Versão

| Versão | Data | Descrição | Autor(es) | Data de revisão | Revisor(es) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| `1.0` | 09/11/2024  | Versão inicial do artefato e preenchimento. | [Vitor Feijó](https://github.com/vitorfleonardo) |  |  |
