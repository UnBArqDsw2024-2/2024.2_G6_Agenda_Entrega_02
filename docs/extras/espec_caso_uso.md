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

## Breve explicação

Os casos de uso descritos fornecem uma visão clara das funcionalidades principais do sistema de agenda. Eles foram elaborados com base em fluxos de trabalho típicos e fluxos alternativos que garantem que o sistema seja robusto e fácil de usar. A metodologia usada para a criação dos casos de uso segue as melhores práticas de desenvolvimento de software, garantindo que todas as possíveis interações com o sistema sejam abordadas.

## Referências

> <a>1.</a> "Use Case Modeling" de Kurt Bittner e Ian Spence. Disponível em: [Wikipedia](https://pt.wikipedia.org/wiki/Diagrama_de_sequ%C3%AAncia). <br>
> <a>2.</a> "Applying Use Case Driven Object Modeling with UML" de Doug Rosenberg e Matt Stephens. Disponível em: [Link](https://pja.mykhi.org/0sem/MAS/books/Addison.Wesley.Applying.Use.Case.Driven.Object.Modeling.pdf). <br>

## Histórico de Versão

| Versão | Data | Descrição | Autor(es) | Data de revisão | Revisor(es) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| `1.0` | 09/11/2024  | Versão inicial do artefato. | [Vitor Feijó](https://github.com/vitorfleonardo) | 24/11/2024 |  [Bianca](https://github.com/BiancaPatrocinio7) |
| `1.0` | 24/11/2024  | Introdução e alguns casos de uso. | [Vitor Feijó](https://github.com/vitorfleonardo) | | |
