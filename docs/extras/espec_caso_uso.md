# Especificação de Casos de Uso

## Introdução

A especificação de casos de uso é uma parte fundamental no processo de modelagem e desenvolvimento de sistemas, pois descreve detalhadamente as interações entre os usuários (ou atores) e o sistema. O objetivo desta documentação é apresentar os principais casos de uso de um sistema de agenda, destacando as funcionalidades que permitem aos usuários interagir de maneira eficiente com a plataforma.

Neste documento, os casos de uso estão organizados de acordo com as ações principais que os usuários podem realizar, como visualizar, cadastrar e compartilhar eventos, além de gerenciar seu login, entre outros. A descrição dos fluxos de interação e os diferentes cenários apresentados nos fluxos alternativos garantem que todas as possíveis interações sejam cobertas, proporcionando uma base sólida para o desenvolvimento e testes do sistema.

Os casos de uso aqui apresentados foram estruturados para atender aos requisitos funcionais do sistema de agenda, levando em consideração as necessidades dos usuários finais, bem como as boas práticas de design e usabilidade. A documentação também busca garantir que as funcionalidades descritas sejam facilmente compreendidas por desenvolvedores, testadores e stakeholders envolvidos no projeto.

## Resultados

Abaixo estão os casos de uso principais para o sistema de agenda:

### Caso de Uso: Login/Cadastro

- **Descrição**: Permite que o usuário faça login na sua conta existente ou crie uma nova conta.
- **Ator Principal**: Usuário.
- **Fluxo Básico**:
  1. O usuário acessa a tela inicial da agenda.
  2. O sistema apresenta as opções de login ou cadastro.
     - **Login**:
       1. O usuário insere e-mail e senha e confirma.
       2. O sistema valida as credenciais.
       3. Caso as credenciais estejam corretas, o sistema autentica o usuário e redireciona para a agenda.
     - **Cadastro**:
       1. O usuário escolhe a opção "Criar Conta".
       2. O sistema apresenta um formulário para inserir e-mail, senha e outras informações pessoais (opcional).
       3. O usuário confirma o cadastro.
       4. O sistema salva os dados e redireciona o usuário para a agenda.
- **Fluxos Alternativos**:
  - **Login inválido**:
    1. O sistema exibe uma mensagem de erro informando que as credenciais estão incorretas.
  - **Cadastro inválido**:
    1. O sistema exibe uma mensagem indicando os problemas com o cadastro (ex.: e-mail já cadastrado).
- **Pré-condições**: O sistema deve estar acessível.
- **Pós-condições**: O usuário é autenticado ou uma nova conta é criada.

<font size="2"><p style="text-align: left">Autor: [Bianca Castro](https://github.com/BiancaPatrocinio7), 2024</p></font>

---

### Caso de Uso: Visualizar Agenda

- **Descrição**: Permite ao usuário visualizar todos os eventos organizados por dia, semana ou mês.
- **Ator Principal**: Usuário.
- **Fluxo Básico**:
  1. O usuário acessa a funcionalidade de "Visualizar Agenda".
  2. O sistema exibe uma visão geral dos eventos cadastrados organizados por padrão (ex.: visão mensal).
  3. O usuário pode alternar entre as visualizações (diária, semanal ou mensal).
  4. O sistema ajusta a exibição de acordo com a seleção.
- **Fluxos Alternativos**:
  - **Sem eventos cadastrados**:
    1. O sistema exibe uma mensagem informando que não há eventos cadastrados.
- **Pré-condições**: O usuário deve estar autenticado.
- **Pós-condições**: Os eventos são exibidos conforme a visualização escolhida.

<font size="2"><p style="text-align: left">Autor: [Bianca Castro](https://github.com/BiancaPatrocinio7), 2024</p></font>

---

### Caso de Uso: Compartilhar Evento

- **Descrição**: Permite ao usuário compartilhar um evento específico com outros usuários via e-mail ou link.
- **Atores**: Usuário, Sistema Externo (ex.: servidor de e-mail).
- **Fluxo Básico**:
  1. O usuário seleciona um evento existente na agenda.
  2. O sistema exibe a opção de compartilhar.
  3. O usuário escolhe entre enviar por e-mail ou gerar um link de compartilhamento.
  4. O sistema executa a ação escolhida:
     - **E-mail**: Envia um e-mail para os destinatários especificados.
     - **Link**: Gera um link único para acesso ao evento.
  5. O sistema exibe uma mensagem de confirmação.
- **Fluxos Alternativos**:
  - **Erro ao enviar e-mail**:
    1. O sistema exibe uma mensagem de erro e sugere tentar novamente ou escolher outro método.
- **Pré-condições**: O evento deve existir no banco de dados.
- **Pós-condições**: O evento é compartilhado com os destinatários.

<font size="2"><p style="text-align: left">Autor: [Bianca Castro](https://github.com/BiancaPatrocinio7), 2024</p></font>

---

### Caso de Uso: Cadastrar Evento

- **Descrição**: Permite ao usuário criar um evento na agenda com informações detalhadas.
- **Ator Principal**: Usuário.
- **Fluxo Básico**:
  1. O usuário acessa a funcionalidade de "Cadastrar Evento".
  2. O sistema apresenta um formulário para inserir informações como:
     - Título do evento.
     - Data e hora.
     - Descrição.
     - Localização (opcional).
     - Convidados (opcional).
  3. O usuário preenche os campos obrigatórios e confirma.
  4. O sistema valida os dados e salva o evento.
  5. Uma mensagem de confirmação é exibida.
- **Fluxos Alternativos**:
  - **Erro de validação**:
    1. O sistema exibe uma mensagem indicando os campos obrigatórios não preenchidos.
- **Pré-condições**: O usuário deve estar autenticado.
- **Pós-condições**: O evento é salvo no banco de dados e aparece na agenda.

<font size="2"><p style="text-align: left">Autor: [Bianca Castro](https://github.com/BiancaPatrocinio7), 2024</p></font>

---

### Caso de Uso: Buscar Eventos

- **Descrição**: Permite ao usuário localizar eventos cadastrados no sistema por meio de filtros específicos ou palavras-chave.
- **Ator Principal**: Usuário.
- **Fluxo Básico**:
  1. O usuário acessa a funcionalidade de "Buscar Eventos".
  2. O sistema apresenta uma barra de pesquisa e filtros disponíveis (ex.: data, categoria, palavras-chave).
  3. O usuário insere um termo de busca ou aplica os filtros desejados.
  4. O sistema processa a consulta e exibe os eventos correspondentes.
  5. O usuário seleciona um evento para visualizar os detalhes.
- **Fluxos Alternativos**:
  - **Sem eventos cadastrados**:
    1. Caso nenhum evento seja encontrado, o sistema exibe uma mensagem informando que não há resultados correspondentes e sugere ajustar os critérios de busca.
    2. O usuário pode optar por limpar os filtros e realizar uma nova busca.
- **Pré-condições**:
  - O usuário deve estar autenticado.
  - O sistema deve conter eventos cadastrados.
- **Pós-condições**: 
  - Os eventos correspondentes aos critérios de busca são exibidos.
  - O usuário pode visualizar os detalhes do evento selecionado.

<font size="2"><p style="text-align: left">Autor: [Paulo Borba](https://github.com/paulohborba), 2024</p></font>

### Caso de Uso: Personalizar perfil

- **Descrição**: Permite que o usuário configure as preferências de notificações acessando a aba de personalização do perfil.
- **Ator Principal**: Usuário.
- **Fluxo Básico**:
  1. O usuário acessa a tela de configurações no sistema.
  2. O sistema apresenta a opção "Personalizar Perfil".
  3. O usuário seleciona a opção e é redirecionado para a interface de personalização do perfil.
  4. O usuário navega até a seção de notificações.
  5. O usuário escolhe os tipos de notificações que deseja receber (ex.: e-mail, SMS, push).
  6. O usuário define as condições ou eventos que disparam as notificações (ex.: compromissos agendados, alterações em eventos).
  7. O usuário salva as alterações.
  8. O sistema armazena as preferências do usuário e confirma a personalização com uma mensagem de sucesso.
- **Fluxos Alternativos**:
  - **Configuração incompleta**:
    1. Caso o usuário não preencha todas as informações obrigatórias, o sistema exibe uma mensagem indicando os campos pendentes.
    2. O usuário corrige as informações e salva novamente.
  - **Erro no salvamento**:
    1. Se ocorrer um erro ao salvar as configurações, o sistema informa o problema.
    2. O sistema sugere tentar novamente ou procurar suporte.
- **Pré-condições**: 
    1. O usuário deve estar autenticado no sistema.
    2. O sistema deve ter a funcionalidade de notificações ativada.
- **Pós-condições**: As preferências de notificações do usuário são salvas e serão aplicadas a futuros eventos no sistema.

<font size="2"><p style="text-align: left">Autor: [Johnny Lopes](https://github.com/JohnnyLopess), 2024</p></font>

---

## Breve explicação

Os casos de uso descritos fornecem uma visão clara das funcionalidades principais do sistema de agenda. Eles foram elaborados com base em fluxos de trabalho típicos e fluxos alternativos que garantem que o sistema seja robusto e fácil de usar. A metodologia usada para a criação dos casos de uso segue as melhores práticas de desenvolvimento de software, garantindo que todas as possíveis interações com o sistema sejam abordadas.

## Referências

> <a>1.</a> "Use Case Modeling" de Kurt Bittner e Ian Spence. Disponível em: [Wikipedia](https://pt.wikipedia.org/wiki/Diagrama_de_sequ%C3%AAncia). <br>
> <a>2.</a> "Applying Use Case Driven Object Modeling with UML" de Doug Rosenberg e Matt Stephens. Disponível em: [Link](https://pja.mykhi.org/0sem/MAS/books/Addison.Wesley.Applying.Use.Case.Driven.Object.Modeling.pdf). <br>

## Histórico de Versão

| Versão | Data | Descrição | Autor(es) | Data de revisão | Revisor(es) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| `1.0` | 09/11/2024  | Versão inicial do artefato. | [Vitor Feijó](https://github.com/vitorfleonardo) | 24/11/2024 |  [Bianca](https://github.com/BiancaPatrocinio7) |
| `1.1` | 24/11/2024  | Introdução e alguns casos de uso. | [Vitor Feijó](https://github.com/vitorfleonardo) | 25/11/2024 |[Paulo Borba](https://github.com/paulohborba) |
| `1.2` | 25/11/2024  | Adicionando caso de uso: buscar eventos. | [Paulo Borba](https://github.com/paulohborba) | 27/11/2024 | [Johnny Lopes](https://github.com/JohnnyLopess)|
| `1.3` | 28/11/2024  | Adicionando caso de uso: Personalizar perfil. | [Johnny Lopes](https://github.com/JohnnyLopess) | 00/00/2024 | |
