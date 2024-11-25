# Requisitos Elicitados

## Introdução

(texto da introdução)

## Resultados

| Identificador | Tipo | Requisito | Origem |
|---------------|------|-----------|--------|
| RE-001 | RF | O sistema deve permitir que os usuários criem, editem e excluam eventos com datas e horários específicos. | [Brainstorming](./extras/requisitos_elicitados/r_brainstorming.md) |
| RE-002 | RF | O sistema deve enviar notificações personalizáveis para lembrar os usuários dos compromissos futuros. | [Brainstorming](./extras/requisitos_elicitados/r_brainstorming.md) |
| RE-003 | RF | O sistema deve permitir a categorização dos eventos com etiquetas de prioridade, usando cores para distinguir entre compromissos de diferentes naturezas. | [Brainstorming](./extras/requisitos_elicitados/r_brainstorming.md) |
| RE-004 | RF | O sistema deve possibilitar o agendamento de eventos recorrentes, como reuniões semanais, sem a necessidade de recriá-los manualmente. | [Brainstorming](./extras/requisitos_elicitados/r_brainstorming.md) |
| RE-005 | RF | O sistema deve permitir a integração com assistentes de voz, como Alexa, para facilitar a criação de eventos via comando de voz. | [Brainstorming](./extras/requisitos_elicitados/r_brainstorming.md) |
| RE-006 | RF | O sistema deve permitir o compartilhamento de eventos e compromissos com outros usuários, oferecendo acesso a múltiplas pessoas. | [Brainstorming](./extras/requisitos_elicitados/r_brainstorming.md) |
| RE-007 | RF | O sistema deve integrar-se com ferramentas de videoconferência, como Google Meet, para gerar links de reuniões ao criar um evento. | [Brainstorming](./extras/requisitos_elicitados/r_brainstorming.md) |
| RE-008 | RF | O sistema deve permitir que os usuários acessem a agenda em múltiplos dispositivos, como smartphones, tablets e computadores. | [Brainstorming](./extras/requisitos_elicitados/r_brainstorming.md) |
| RE-009 | RF | O sistema deve permitir a visualização de compromissos por dia, semana e mês, proporcionando diferentes perspectivas de planejamento. | [Brainstorming](./extras/requisitos_elicitados/r_brainstorming.md) |
| RE-010 | RF | O sistema deve permitir a busca de eventos específicos por meio de uma barra de pesquisa. | [Brainstorming](./extras/requisitos_elicitados/r_brainstorming.md) |
| RE-011 | RF | O sistema deve permitir o envio de notificações automáticas por e-mail ou SMS, caso o usuário prefira ser notificado por esses meios. | [Brainstorming](./extras/requisitos_elicitados/r_brainstorming.md) |
| RE-012 | RNF | O sistema deve possuir autenticação de login com verificação de identidade para garantir acesso seguro. | [Brainstorming](./extras/requisitos_elicitados/r_brainstorming.md) |
| RE-013 | RNF | O sistema deve armazenar todas as informações de eventos e compromissos no banco de dados de maneira segura e criptografada. | [Brainstorming](./extras/requisitos_elicitados/r_brainstorming.md) |
| RE-014 | RNF | O sistema deve ser acessível a pessoas com deficiência, permitindo a navegação por teclado e compatibilidade com leitores de tela. | [Brainstorming](./extras/requisitos_elicitados/r_brainstorming.md) |
| RE-015 | RNF | O sistema deve garantir uma resposta rápida nas operações de criação, edição e consulta de eventos, com tempo de resposta inferior a 2 segundos. | [Brainstorming](./extras/requisitos_elicitados/r_brainstorming.md) |
| RE-016 | RNF | O sistema deve ser confiável, com um uptime mínimo de 99,9% durante o ano, para assegurar a disponibilidade da agenda. | [Brainstorming](./extras/requisitos_elicitados/r_brainstorming.md) |
| RE-017 | RNF | O sistema deve armazenar um histórico dos eventos e compromissos por, no mínimo, 1 ano para consultas futuras. | [Brainstorming](./extras/requisitos_elicitados/r_brainstorming.md) |
| RE-018 | RF | O sistema deve prevenir a sobreposição de horários para evitar conflitos de eventos na mesma data e horário. | [Brainstorming](./extras/requisitos_elicitados/r_brainstorming.md) |
| RE-019 | RF | O sistema deve permitir a configuração de notificações de backup, caso uma notificação inicial não seja recebida pelo usuário. | [Brainstorming](./extras/requisitos_elicitados/r_brainstorming.md) |
| RE-020 | RNF | O sistema deve suportar atualizações sem interrupção no serviço, permitindo que novos recursos sejam implementados sem afetar o uso atual. | [Brainstorming](./extras/requisitos_elicitados/r_brainstorming.md) |
| RE-021 | RNF | O sistema deve permitir a recuperação de senha de forma segura e prática para o usuário. | [Brainstorming](./extras/requisitos_elicitados/r_brainstorming.md) |
| RE-022 | RNF | O sistema deve ser compatível com APIs de outras ferramentas, como Trello e Google Calendar, para facilitar a sincronização de eventos. | [Brainstorming](./extras/requisitos_elicitados/r_brainstorming.md) |
| RE-023         | RNF  | O sistema deve ter uma interface intuitiva e fácil de navegar, livre de elementos desnecessários.                             | [Design Principles](./extras/requisitos_elicitados/r_design_principles.md) |
| RE-024         | RNF  | As informações essenciais (data, hora, título do evento) devem ter prioridade visual na interface.                            | [Design Principles](./extras/requisitos_elicitados/r_design_principles.md) |
| RE-025         | RNF  | O sistema deve utilizar cores, tamanhos e espaçamento para guiar o usuário pelas informações mais importantes (hierarquia visual). | [Design Principles](./extras/requisitos_elicitados/r_design_principles.md) |
| RE-026         | RF   | O sistema deve oferecer opções para personalizar a aparência da agenda (temas e cores).                                       | [Design Principles](./extras/requisitos_elicitados/r_design_principles.md) |
| RE-027         | RF   | O sistema deve permitir configurar diferentes modos de visualização da agenda (dia, semana, mês).                             | [Design Principles](./extras/requisitos_elicitados/r_design_principles.md) |
| RE-028         | RF   | O sistema deve permitir ao usuário exibir ou esconder informações na agenda.                                                  | [Design Principles](./extras/requisitos_elicitados/r_design_principles.md) |
| RE-029         | RF   | O sistema deve permitir a integração com outras plataformas para otimizar o fluxo de trabalho.                                | [Design Principles](./extras/requisitos_elicitados/r_design_principles.md) |
| RE-030         | RF   | O sistema deve ter uma interface amigável para criar, editar e remover eventos.                                               | [Design Principles](./extras/requisitos_elicitados/r_design_principles.md) |
| RE-031         | RF   | O sistema deve permitir configurações personalizadas para lembretes e notificações sobre eventos importantes.                 | [Design Principles](./extras/requisitos_elicitados/r_design_principles.md) |
| RE-032         | RF   | O sistema deve facilitar o compartilhamento de eventos e agendas com outros usuários.                                         | [Design Principles](./extras/requisitos_elicitados/r_design_principles.md) |
| RE-033         | RNF  | O sistema deve ter um design responsivo, ajustando-se automaticamente a diferentes dispositivos (computadores, tablets, smartphones). | [Design Principles](./extras/requisitos_elicitados/r_design_principles.md) |
| RE-034         | RNF  | O sistema deve atender aos padrões de acessibilidade WCAG para garantir a experiência de todos os usuários.                   | [Design Principles](./extras/requisitos_elicitados/r_design_principles.md) |
| RE-035         | RNF  | O sistema deve utilizar uma linguagem simples e fácil de entender, evitando termos técnicos.                                  | [Design Principles](./extras/requisitos_elicitados/r_design_principles.md) |
| RE-036         | RNF  | O sistema deve ter uma interface visualmente agradável, transmitindo profissionalismo e modernidade.                          | [Design Principles](./extras/requisitos_elicitados/r_design_principles.md) |
| RE-037         | RNF  | O sistema deve focar nos elementos essenciais, evitando sobrecarga visual (minimalismo).                                      | [Design Principles](./extras/requisitos_elicitados/r_design_principles.md) |
| RE-038         | RNF  | O sistema deve ter um design responsivo que se ajuste automaticamente a diferentes tamanhos de tela.                         | [Design Principles](./extras/requisitos_elicitados/r_design_principles.md) |
| RE-039       | RF   | O sistema deve funcionar como um calendário.                                  | [É, não é, faz, não faz](./extras/requisitos_elicitados/r_e_ne_faz_nfaz.md) |
| RE-040       | RF   | O sistema deve ser um organizador de tarefas.                                 | [É, não é, faz, não faz](./extras/requisitos_elicitados/r_e_ne_faz_nfaz.md) |
| RE-041       | RF   | O sistema deve gerenciar compromissos.                                        | [É, não é, faz, não faz](./extras/requisitos_elicitados/r_e_ne_faz_nfaz.md) |
| RE-042       | RNF  | O sistema deve ser acessível em qualquer dispositivo.                         | [É, não é, faz, não faz](./extras/requisitos_elicitados/r_e_ne_faz_nfaz.md) |
| RE-043       | RF   | O sistema deve ser uma ferramenta de organização.                             | [É, não é, faz, não faz](./extras/requisitos_elicitados/r_e_ne_faz_nfaz.md) |
| RE-044       | RNF  | O sistema deve ser personalizável.                                            | [É, não é, faz, não faz](./extras/requisitos_elicitados/r_e_ne_faz_nfaz.md) |
| RE-045       | RF   | O sistema deve convidar outras pessoas para compromissos.                     | [É, não é, faz, não faz](./extras/requisitos_elicitados/r_e_ne_faz_nfaz.md) |
| RE-046       | RF   | O sistema deve notificar os usuários.                                         | [É, não é, faz, não faz](./extras/requisitos_elicitados/r_e_ne_faz_nfaz.md) |
| RE-047       | RF   | O sistema deve possibilitar marcar compromissos e tarefas.                    | [É, não é, faz, não faz](./extras/requisitos_elicitados/r_e_ne_faz_nfaz.md) |
| RE-048       | RF   | O sistema deve oferecer gestão de metas.                                      | [É, não é, faz, não faz](./extras/requisitos_elicitados/r_e_ne_faz_nfaz.md) |
| RE-049       | RF   | O sistema deve permitir a categorização.                                      | [É, não é, faz, não faz](./extras/requisitos_elicitados/r_e_ne_faz_nfaz.md) |
| RE-050       | RF   | O sistema deve sincronizar com outros apps.                                   | [É, não é, faz, não faz](./extras/requisitos_elicitados/r_e_ne_faz_nfaz.md) |
| RE-051       | RF   | Fazer a agenda online mais intuitiva e fácil de usar, mesmo para usuários que não são familiarizados com ferramentas online. | [HMW](./extras/requisitos_elicitados/r_hmw.md) |
| RE-052       | RF   | Oferecer notificações personalizadas e eficazes que realmente lembrem os usuários de seus compromissos.                   | [HMW](./extras/requisitos_elicitados/r_hmw.md) |
| RE-053       | RF   | Criar uma visualização clara e organizada de eventos, evitando sobreposição de horários e facilitando a identificação de conflitos. | [HMW](./extras/requisitos_elicitados/r_hmw.md) |
| RE-054       | RF   | Oferecer ferramentas para a gestão de projetos com recursos para criação de listas de tarefas, definição de prazos, acompanhamento de progresso e colaboração em equipe. | [HMW](./extras/requisitos_elicitados/r_hmw.md) |
| RE-055       | RF   | Utilizar a inteligência artificial para auxiliar os usuários na organização de suas tarefas, priorização de compromissos e agendamento de eventos. | [HMW](./extras/requisitos_elicitados/r_hmw.md) |
| RE-056       | RF   | Criar um sistema de recompensas e incentivos para motivar os usuários a usar a agenda e alcançar seus objetivos.           | [HMW](./extras/requisitos_elicitados/r_hmw.md) |
| RE-057       | RF   | Permitir que os usuários compartilhem eventos e tarefas com outros usuários de forma simples e eficiente.                 | [HMW](./extras/requisitos_elicitados/r_hmw.md) |
| RE-058       | RF   | Integrar a agenda com outras ferramentas, como Google Workspace, Teams e Trello, de forma simples e intuitiva.            | [HMW](./extras/requisitos_elicitados/r_hmw.md) |
| RE-059       | RF   | Criar um sistema de análise de dados que permite os usuários identificar seus padrões de comportamento e otimizar a gestão do tempo. | [HMW](./extras/requisitos_elicitados/r_hmw.md) |
| RE-060       | RF   | Criar uma experiência personalizada para cada usuário, adaptando a interface, as notificações e os recursos de acordo com suas necessidades e preferências. | [HMW](./extras/requisitos_elicitados/r_hmw.md) |
| RE-061       | RF   | Criar um ambiente que motive os usuários a serem mais produtivos.                                                         | [HMW](./extras/requisitos_elicitados/r_hmw.md) |
| RE-062       | RF   | O sistema deve permitir o cadastro de novos usuários e login via credenciais ou integração com conta Google.                     | [Introspecção](./extras/requisitos_elicitados/r_introspeccao.md) |
| RE-063       | RF   | O sistema deve permitir que o usuário customize as configurações de sua conta (Segurança e Acessibilidade).                     | [Introspecção](./extras/requisitos_elicitados/r_introspeccao.md) |
| RE-064       | RNF  | O sistema deve implementar autenticação robusta e configurações de segurança para proteger as informações do usuário.            | [Introspecção](./extras/requisitos_elicitados/r_introspeccao.md) |
| RE-065       | RF   | O sistema deve exibir a data e hora atual, com opções de visualização por dia, semana e mês, incluindo feriados nacionais.        | [Introspecção](./extras/requisitos_elicitados/r_introspeccao.md) |
| RE-066       | RF   | O sistema deve permitir criar, ler, atualizar e excluir tarefas/compromissos.                                                   | [Introspecção](./extras/requisitos_elicitados/r_introspeccao.md) |
| RE-067       | RF   | O sistema deve permitir que as tarefas/compromissos sejam personalizadas com informações como prioridade, prazo, data de vencimento, categoria e lembretes. | [Introspecção](./extras/requisitos_elicitados/r_introspeccao.md) |
| RE-068       | RF   | O sistema deve permitir marcar tarefas como concluídas.                                                                         | [Introspecção](./extras/requisitos_elicitados/r_introspeccao.md) |
| RE-069       | RF   | O sistema deve permitir importar e exportar a agenda em diferentes formatos.                                                    | [Introspecção](./extras/requisitos_elicitados/r_introspeccao.md) |
| RE-070       | RF   | O sistema deve permitir categorizar as tarefas/compromissos e filtrá-las por diferentes critérios (categoria, prazo, prioridade, etc.). | [Introspecção](./extras/requisitos_elicitados/r_introspeccao.md) |
| RE-071       | RF   | O sistema deve permitir definir dependências entre tarefas, garantindo a execução na ordem correta.                              | [Introspecção](./extras/requisitos_elicitados/r_introspeccao.md) |
| RE-072       | RF   | O sistema deve permitir o convite de outros usuários para compartilhar agendas e participar de eventos.                          | [Introspecção](./extras/requisitos_elicitados/r_introspeccao.md) |
| RE-073       | RF   | O sistema deve explorar a integração com Inteligência Artificial para funcionalidades como sugestões de tarefas, otimização de agenda, etc. | [Introspecção](./extras/requisitos_elicitados/r_introspeccao.md) |
| RE-074       | RF   | O sistema deve permitir interação com assistentes por comandos de voz.                                                          | [Introspecção](./extras/requisitos_elicitados/r_introspeccao.md) |
| RE-075       | RF   | O sistema deve permitir a integração com outros serviços, como plataformas de email e calendários externos (Google Calendar, Outlook Calendar). | [Introspecção](./extras/requisitos_elicitados/r_introspeccao.md) |
| RE-076       | RF   | O sistema deve permitir uma visualização Kanban para gerenciamento de tarefas, permitindo a categorização e movimentação das tarefas entre diferentes estágios. | [Introspecção](./extras/requisitos_elicitados/r_introspeccao.md) |
| RE-077       | RF   | O sistema deve notificar os usuários sobre eventos e tarefas importantes, com opções de personalização das notificações.          | [Introspecção](./extras/requisitos_elicitados/r_introspeccao.md) |
| RE-078       | RNF  | O sistema deve garantir a acessibilidade do sistema para todos os usuários, incluindo aqueles com necessidades especiais.         | [Introspecção](./extras/requisitos_elicitados/r_introspeccao.md) |
| RE-079       | RF   | O sistema deve permitir a criação de uma conta e configuração de preferências iniciais.                                   | [Mapa Experiência](./extras/requisitos_elicitados/r_mapa_experiencia.md) |
| RE-080       | RF   | O sistema deve permitir adicionar, definir lembretes e consultar tarefas na agenda.                                       | [Mapa Experiência](./extras/requisitos_elicitados/r_mapa_experiencia.md) |
| RE-081       | RF   | O sistema deve permitir planejar a semana, visualizar a agenda e gerenciar compromissos.                                  | [Mapa Experiência](./extras/requisitos_elicitados/r_mapa_experiencia.md) |
| RE-082       | RF   | O sistema deve permitir compartilhar eventos com outras pessoas.                                                         | [Mapa Experiência](./extras/requisitos_elicitados/r_mapa_experiencia.md) |
| RE-083       | RF   | O sistema deve permitir definir e gerenciar lembretes para tarefas importantes.                                           | [Mapa Experiência](./extras/requisitos_elicitados/r_mapa_experiencia.md) |
| RE-084       | RNF  | O sistema deve oferecer um tutorial interativo e dicas de personalização.                                                | [Mapa Experiência](./extras/requisitos_elicitados/r_mapa_experiencia.md) |
| RE-085       | RNF  | O sistema deve integrar com outros aplicativos e permitir visualização customizável.                                     | [Mapa Experiência](./extras/requisitos_elicitados/r_mapa_experiencia.md) |
| RE-086       | RNF  | O sistema deve oferecer diferentes opções de visualização (lista, calendário, etc.) e permitir arrastar e soltar tarefas. | [Mapa Experiência](./extras/requisitos_elicitados/r_mapa_experiencia.md) |
| RE-087       | RNF  | O sistema deve integrar com outras plataformas de comunicação e oferecer opções de permissão de acesso.                  | [Mapa Experiência](./extras/requisitos_elicitados/r_mapa_experiencia.md) |
| RE-088       | RNF  | O sistema deve oferecer opções flexíveis de configuração de lembretes (repetições, horários personalizados, lembretes inteligentes, etc.). | [Mapa Experiência](./extras/requisitos_elicitados/r_mapa_experiencia.md) |
| RE-089       | RNF  | O sistema deve facilitar a comparação entre diferentes opções de agenda.                                                 | [Mapa Experiência](./extras/requisitos_elicitados/r_mapa_experiencia.md) |
| RE-090       | RNF  | O sistema deve evitar excesso de informações ou opções na configuração inicial.                                           | [Mapa Experiência](./extras/requisitos_elicitados/r_mapa_experiencia.md) |
| RE-091       | RNF  | O sistema deve facilitar a visualização de tarefas de longo prazo e evitar notificações intrusivas.                       | [Mapa Experiência](./extras/requisitos_elicitados/r_mapa_experiencia.md) |
| RE-092       | RNF  | O sistema deve facilitar a visualização da disponibilidade de tempo, oferecer flexibilidade para reagendar compromissos e informar a falta de compromissos. | [Mapa Experiência](./extras/requisitos_elicitados/r_mapa_experiencia.md) |
| RE-093       | RNF  | O sistema deve simplificar o processo de compartilhamento, gerenciamento de permissões e evitar complexidade.             | [Mapa Experiência](./extras/requisitos_elicitados/r_mapa_experiencia.md) |
| RE-094       | RNF  | O sistema deve facilitar a configuração de lembretes personalizados, evitar excesso de notificações e garantir que os lembretes sejam acionados corretamente. | [Mapa Experiência](./extras/requisitos_elicitados/r_mapa_experiencia.md) |
| RE-095       | RF   | O sistema deve permitir que os usuários criem, editem e excluam eventos com datas e horários específicos. | [Mapa jornada](./extras/requisitos_elicitados/r_mapa_jpersona.md) |
| RE-096       | RF   | O sistema deve permitir a configuração de eventos recorrentes (diários, semanais, mensais, anuais). | [Mapa jornada](./extras/requisitos_elicitados/r_mapa_jpersona.md) |
| RE-097       | RF   | O sistema deve permitir a categorização de eventos (ex: Esporte, pessoal, estudos).             | [Mapa jornada](./extras/requisitos_elicitados/r_mapa_jpersona.md) |
| RE-098       | RF   | O sistema deve permitir a associação de eventos a clientes específicos.                        | [Mapa jornada](./extras/requisitos_elicitados/r_mapa_jpersona.md) |
| RE-099       | RF   | O sistema deve permitir a definição de lembretes para eventos com opções de antecedência e tipo de alerta (notificação, e-mail, etc.). | [Mapa jornada](./extras/requisitos_elicitados/r_mapa_jpersona.md) |
| RE-100       | RF   | O sistema deve oferecer diferentes modos de visualização da agenda (diária, semanal, mensal).   | [Mapa jornada](./extras/requisitos_elicitados/r_mapa_jpersona.md) |
| RE-101       | RF   | O sistema deve permitir a busca de eventos por palavra-chave, data ou categoria.               | [Mapa jornada](./extras/requisitos_elicitados/r_mapa_jpersona.md) |
| RE-102       | RF   | O sistema deve destacar visualmente os eventos do dia atual.                                   | [Mapa jornada](./extras/requisitos_elicitados/r_mapa_jpersona.md) |
| RE-103       | RF   | O sistema deve gerar relatórios sobre o tempo gasto em diferentes categorias de eventos.        | [Mapa jornada](./extras/requisitos_elicitados/r_mapa_jpersona.md) |
| RE-104       | RF   | O sistema deve fornecer visualizações gráficas do uso do tempo.                                | [Mapa jornada](./extras/requisitos_elicitados/r_mapa_jpersona.md) |
| RE-105       | RF   | O sistema deve integrar-se com outros aplicativos de calendário (Google Calendar, Outlook, etc.). | [Mapa jornada](./extras/requisitos_elicitados/r_mapa_jpersona.md) |
| RE-106       | RF   | O sistema deve integrar-se com assistentes de voz.                                            | [Mapa jornada](./extras/requisitos_elicitados/r_mapa_jpersona.md) |
| RE-107       | RF   | O sistema deve permitir o cadastro de informações detalhadas sobre clientes.                   | [Mapa jornada](./extras/requisitos_elicitados/r_mapa_jpersona.md) |
| RE-108       | RF   | O sistema deve oferecer suporte ao gerenciamento de reuniões e marcação delas com outros usuários. | [Mapa jornada](./extras/requisitos_elicitados/r_mapa_jpersona.md) |
| RE-109       | RNF  | O sistema deve ter uma interface intuitiva e fácil de usar.                                   | [Mapa jornada](./extras/requisitos_elicitados/r_mapa_jpersona.md) |
| RE-110       | RNF  | O sistema deve ser fácil de aprender e utilizar, mesmo para usuários sem experiência.           | [Mapa jornada](./extras/requisitos_elicitados/r_mapa_jpersona.md) |
| RE-111       | RNF  | O sistema deve fornecer feedback claro e imediato às ações do usuário.                        | [Mapa jornada](./extras/requisitos_elicitados/r_mapa_jpersona.md) |
| RE-112       | RNF  | O sistema deve ser rápido e responsivo, com tempos de carregamento mínimos.                    | [Mapa jornada](./extras/requisitos_elicitados/r_mapa_jpersona.md) |
| RE-113       | RNF  | O sistema deve ser capaz de lidar com grande volume de dados sem comprometer o desempenho.     | [Mapa jornada](./extras/requisitos_elicitados/r_mapa_jpersona.md) |
| RE-114       | RNF  | O sistema deve proteger os dados do usuário contra acesso não autorizado.                      | [Mapa jornada](./extras/requisitos_elicitados/r_mapa_jpersona.md) |
| RE-115       | RNF  | O sistema deve garantir a confidencialidade e integridade dos dados.                          | [Mapa jornada](./extras/requisitos_elicitados/r_mapa_jpersona.md) |
| RE-116       | RNF  | O sistema deve ser acessível em diferentes dispositivos (desktops, smartphones, tablets).       | [Mapa jornada](./extras/requisitos_elicitados/r_mapa_jpersona.md) |
| RE-117       | RNF  | O sistema deve ser compatível com diferentes sistemas operacionais.                            | [Mapa jornada](./extras/requisitos_elicitados/r_mapa_jpersona.md) |
| RE-118       | RNF  | O sistema deve ser escalável para suportar um número crescente de usuários e eventos.           | [Mapa jornada](./extras/requisitos_elicitados/r_mapa_jpersona.md) |
| RE-119       | RNF  | O sistema deve ser estável e confiável, com o mínimo de erros e falhas.                       | [Mapa jornada](./extras/requisitos_elicitados/r_mapa_jpersona.md) |
| RE-120       | RNF  | O sistema deve ser acessível a pessoas com deficiências.                                      | [Mapa jornada](./extras/requisitos_elicitados/r_mapa_jpersona.md) |
| RE-121       | RF   | O sistema deve permitir a priorização das tarefas.                                            | [Mapa jornada](./extras/requisitos_elicitados/r_mapa_jpersona.md) |
| RE-122       | RF   | O sistema deve permitir que o usuário acesse a agenda online através de um navegador.                                    | [Golden Path](./extras/requisitos_elicitados/r_path_golden.md) |
| RE-123       | RF   | O sistema deve exibir uma tela de login ao acessar a agenda online.                                                     | [Golden Path](./extras/requisitos_elicitados/r_path_golden.md) |
| RE-124       | RF   | O sistema deve permitir que o usuário insira suas credenciais (login e senha) na tela de login para autenticação.        | [Golden Path](./extras/requisitos_elicitados/r_path_golden.md) |
| RE-125       | RF   | O sistema deve permitir que o usuário se cadastre caso não tenha uma conta, direcionando-o para uma tela de cadastro.    | [Golden Path](./extras/requisitos_elicitados/r_path_golden.md) |
| RE-126       | RF   | O sistema deve autenticar o usuário após a inserção correta das credenciais, permitindo o acesso à plataforma.           | [Golden Path](./extras/requisitos_elicitados/r_path_golden.md) |
| RE-127       | RF   | O sistema deve exibir uma tela de carregamento após o login e antes de acessar a plataforma.                            | [Golden Path](./extras/requisitos_elicitados/r_path_golden.md) |
| RE-128       | RF   | O sistema deve exibir uma tela de calendário como página inicial após a autenticação bem-sucedida.                      | [Golden Path](./extras/requisitos_elicitados/r_path_golden.md) |
| RE-129       | RF   | O sistema deve permitir que o usuário selecione um dia específico no calendário para visualizar as atividades desse dia. | [Golden Path](./extras/requisitos_elicitados/r_path_golden.md) |
| RE-130       | RF   | O sistema deve permitir que o usuário selecione opções de visualização no calendário, como "dia", "semana" ou "mês".    | [Golden Path](./extras/requisitos_elicitados/r_path_golden.md) |
| RE-131       | RF   | O sistema deve exibir uma tela detalhada das atividades ao selecionar um dia específico no calendário.                   | [Golden Path](./extras/requisitos_elicitados/r_path_golden.md) |
| RE-132       | RF   | O sistema deve permitir que o usuário acesse um "board específico" com as atividades do dia, organizadas conforme a seleção no calendário. | [Golden Path](./extras/requisitos_elicitados/r_path_golden.md) |
| RE-133       | RF   | O sistema deve permitir que o usuário crie ou edite tarefas diretamente na tela das atividades do dia.                   | [Golden Path](./extras/requisitos_elicitados/r_path_golden.md) |
| RE-134       | RF   | O sistema deve exibir uma tela de confirmação após a criação ou edição de uma tarefa para assegurar que a operação foi concluída com sucesso. | [Golden Path](./extras/requisitos_elicitados/r_path_golden.md) |
| RE-135       | RF   | O sistema deve permitir a criação e edição de eventos e tarefas na agenda.                                                          | [Personas](./extras/requisitos_elicitados/r_personas.md) |
| RE-136       | RF   | O sistema deve possibilitar a personalização das tarefas, como definir prioridades, prazos e datas de vencimento.                    | [Personas](./extras/requisitos_elicitados/r_personas.md) |
| RE-137       | RF   | O sistema deve disponibilizar diferentes formatos de visualização da agenda (diário, semanal, mensal, anual).                        | [Personas](./extras/requisitos_elicitados/r_personas.md) |
| RE-138       | RF   | O sistema deve oferecer filtros e buscas avançadas para encontrar eventos e tarefas específicos.                                     | [Personas](./extras/requisitos_elicitados/r_personas.md) |
| RE-139       | RF   | O sistema deve permitir a criação de lembretes personalizados para eventos e tarefas.                                               | [Personas](./extras/requisitos_elicitados/r_personas.md) |
| RE-140       | RF   | O sistema deve permitir a categorização das tarefas e eventos.                                                                      | [Personas](./extras/requisitos_elicitados/r_personas.md) |
| RE-141       | RF   | O sistema deve permitir o compartilhamento de agendas com outros usuários.                                                          | [Personas](./extras/requisitos_elicitados/r_personas.md) |
| RE-142       | RF   | O sistema deve permitir o envio de convites para outros usuários participarem de eventos.                                            | [Personas](./extras/requisitos_elicitados/r_personas.md) |
| RE-143       | RF   | O sistema deve sincronizar a agenda com outros calendários externos, como Google Calendar e Outlook Calendar.                       | [Personas](./extras/requisitos_elicitados/r_personas.md) |
| RE-144       | RF   | O sistema deve permitir a definição de dependências entre tarefas, assegurando a realização na ordem correta.                        | [Personas](./extras/requisitos_elicitados/r_personas.md) |
| RE-145       | RF   | O sistema deve incluir feriados nacionais para facilitar a organização da agenda.                                                   | [Personas](./extras/requisitos_elicitados/r_personas.md) |
| RE-146       | RNF  | O sistema deve permitir configurações de segurança para proteger as informações dos usuários.                                        | [Personas](./extras/requisitos_elicitados/r_personas.md) |
| RE-147       | RF   | O sistema deve notificar os usuários sobre eventos e tarefas importantes.                                                           | [Personas](./extras/requisitos_elicitados/r_personas.md) |
| RE-148       | RNF  | O sistema deve garantir acessibilidade para todos os usuários, incluindo aqueles com necessidades especiais.                         | [Personas](./extras/requisitos_elicitados/r_personas.md) |
| RE-149       | RF   | O sistema deve permitir a personalização das notificações para cada usuário.                                                        | [Personas](./extras/requisitos_elicitados/r_personas.md) |
| RE-150       | RF   | O sistema deve permitir a criação de um Kanban ou to-do list das tarefas diárias.                                                   | [Personas](./extras/requisitos_elicitados/r_personas.md) |
| RE-151       | RF   | O sistema deve permitir a integração com assistentes de voz para facilitar a interação.                                             | [Personas](./extras/requisitos_elicitados/r_personas.md) |
| RE-152       | RF   | O sistema deve conectar-se com outras plataformas, como sistemas de email, para automatizar a adição de eventos.                    | [Personas](./extras/requisitos_elicitados/r_personas.md) |
| RE-153       | RF   | O sistema deve permitir a edição de informações sobre o caso, incluindo dados sobre o cliente, como endereço, telefone e preferências. | [Personas](./extras/requisitos_elicitados/r_personas.md) |
| RE-154       | RF   | O sistema deve permitir o compartilhamento do cronograma com a equipe.                                                              | [Personas](./extras/requisitos_elicitados/r_personas.md) |
| RE-155       | RF   | O sistema deve permitir a criação de eventos e tarefas com links para outros aplicativos.                                           | [Personas](./extras/requisitos_elicitados/r_personas.md) |
| RE-156       | RF   | O sistema deve permitir a definição de prioridades para tarefas e eventos.                                                          | [Personas](./extras/requisitos_elicitados/r_personas.md) |
| RE-157       | RF   | O sistema deve permitir a edição de eventos e tarefas com links para outros aplicativos.                                            | [Personas](./extras/requisitos_elicitados/r_personas.md) |
| RE-158       | RF   | O sistema deve permitir a definição de prioridades para tarefas e eventos.                                                          | [Personas](./extras/requisitos_elicitados/r_personas.md) |


## Breve explicação

(Explicação da metodologia)

## Referências

(link para as referências, livros, artigos, sites)

## Histórico de Versão

| Versão | Data | Descrição | Autor(es) | Data de revisão | Revisor(es) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| `1.0` | 09/11/2024  | Versão inicial do artefato. | [Vitor Feijó](https://github.com/vitorfleonardo) |  |  |

