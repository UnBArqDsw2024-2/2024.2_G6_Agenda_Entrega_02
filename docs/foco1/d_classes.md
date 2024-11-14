# Diagrama de Classes

## Introdução

O diagrama de classes é um dos principais artefatos da modelagem de software, utilizado dentro da abordagem de desenvolvimento orientado a objetos. Ele faz parte da UML (Unified Modeling Language), uma linguagem de modelagem padrão que permite visualizar, especificar e documentar os diversos aspectos de um sistema de software.

O propósito do diagrama de classes é representar a estrutura estática do sistema, mostrando as classes envolvidas, seus atributos, métodos e as relações entre elas, como herança, associação, composição e agregação. Ao modelar essas interações, o diagrama de classes fornece uma visão clara e detalhada de como os objetos do sistema se relacionam e colaboram para atender aos requisitos de negócio.

## Resultados

<p align="center" > <strong> Diagrama 1:</Strong> Diagrama de Classes - Agenda</font> <gitbr></p>
<center>
<div style="width: 960px; height: 720px; margin: 10px; position: relative;"><iframe allowfullscreen frameborder="0" style="width:960px; height:720px" src="https://lucid.app/documents/embedded/5d7ba6bc-1e93-465d-880e-249fc4ee21b7" id="it4qDd1f4DKh"></iframe></div>
</center>

<font size="3"><p style="text-align: center"><b>Autor:</b> [Bianca Castro](https://github.com/BiancaPatrocinio7) & [Gabriel Souza](https://github.com/GabrielMS00) & [Johnny Lopes](https://github.com/JohnnyLopess) & [Julia Silva](https://github.com/Juhvitoria4) & [Paulo Borba](https://github.com/paulohborba), 2024</p></font>

### Legenda do Diagrama de Classes - Agenda Online

1. **Classes**: Cada retângulo representa uma classe do sistema de agenda online, contendo:
   - **Nome da Classe**: No topo de cada retângulo (ex.: `Usuario`, `Agenda`, `Evento`).
   - **Atributos**: Listados na parte central do retângulo, indicam as propriedades dos objetos da classe. Por exemplo:
     - `Usuario` possui atributos como `nome`, `email`, e `senha`.
     - `Evento` possui atributos como `titulo`, `data`, e `descricao`.
   - **Métodos**: Localizados na parte inferior de cada retângulo, representam ações que os objetos da classe podem realizar. Exemplo:
     - Na classe `Usuario`, os métodos `cadastrar()` e `logarGoogle()` permitem o cadastro e o login.
     - Na classe `Evento`, métodos como `criarEvento()` e `editarEvento()` manipulam os eventos.

2. **Relacionamentos**:
   - **Associação**: Linhas entre as classes indicam interações diretas. Por exemplo:
     - A classe `Usuario` se associa à classe `Agenda` para representar o vínculo entre o usuário e sua agenda.
   - **Cardinalidade**: Próxima às extremidades das linhas, a cardinalidade define a quantidade de instâncias permitidas em cada lado do relacionamento.
     - `1` indica uma única instância.
     - `0..1` indica zero ou uma instância (opcional).
     - `*` indica múltiplas instâncias. Exemplo: um `Usuario` pode ter várias `Agendas`.
   - **Composição**: Representada por um losango preenchido em uma extremidade da linha (não presente explicitamente no diagrama). Em uma composição, a existência de uma classe depende de outra.

3. **Enumerações**:
   - Algumas classes têm atributos que possuem valores pré-definidos, que restringem as possíveis opções. Por exemplo:
     - `status` na classe `Evento` pode ter valores como "Agendado", "Em andamento", "Concluído" e "Cancelado".
     - `prioridade` na classe `Tarefa` pode ser "Alta", "Média" ou "Baixa".

4. **Dependências**:
   - Linhas pontilhadas (não visíveis neste diagrama) indicariam que uma classe depende temporariamente de outra para realizar uma ação específica. Um exemplo disso seria um método em `Sincronizacao` que poderia depender de informações da classe `Usuario` para sincronizar a agenda.

5. **Classes Principais do Sistema**:
   - **Usuario**: Gerencia informações do usuário e métodos para cadastro e login.
   - **Agenda**: Organiza as informações e visualizações de eventos para o usuário.
   - **Evento**: Representa eventos com detalhes como data, título e status.
   - **Tarefa**: Define tarefas associadas a uma agenda, com informações como prioridade e status.
   - **ConfiguracaoUsuario**: Permite ao usuário personalizar configurações da sua experiência com a agenda.
   - **Compartilhamento**: Gerencia as permissões de acesso e edição entre usuários e agendas compartilhadas.
   - **Sincronizacao**: Oferece funcionalidades para sincronizar a agenda com outras plataformas, como Google Calendar e Outlook.

## Breve explicação

A Figura ilustra as classes que serão desenvolvidas neste projeto. No contexto do projeto, temos as seguintes classes principais: **Usuario**, **Agenda**, **Evento**, **Tarefa**, **Categoria**, **Lembrete**, **Compartilhamento** e **Sincronização**. Cada uma dessas classes possui atributos e métodos específicos que definem seu comportamento e funcionalidade dentro do sistema.

A classe **Usuario** é central nesse sistema, pois está relacionada a várias outras classes, indicando as diferentes interações que um usuário pode ter dentro do sistema.

A classe **Agenda** está diretamente relacionada à classe Usuario. Essa relação indica que um usuário pode criar múltiplas agendas e cada agenda está associada a um único usuário.

A classe **Evento** é associada tanto à Agenda quanto ao Usuario. Isso representa que uma agenda pode conter vários eventos e cada evento está vinculado a uma única agenda. A classe CompartilhamentoEvento está relacionada com Evento e Usuario, permitindo que eventos possam ser compartilhados entre usuários com diferentes permissões.

A classe **Tarefa** está vinculada ao Evento, indicando que um evento pode ter múltiplas tarefas associadas, mas uma tarefa pertence a um único evento. Além disso, a Tarefa possui uma associação com Categoria, representando que uma categoria pode agrupar várias tarefas, mas cada tarefa pertence a uma única categoria.

A classe **Lembrete** também é associada à Tarefa. Isso indica que uma tarefa pode ter vários lembretes para auxiliar o usuário na conclusão das atividades, mas cada lembrete pertence a uma única tarefa.

A classe **Sincronização** representa as funcionalidades para sincronizar o sistema com calendários externos, como Google Calendar, Outlook e Apple, proporcionando integração com outras plataformas.

Por fim, a classe **ConfiguracoesUsuario** está relacionada ao Usuario e armazena configurações personalizadas, como notificações e idioma, permitindo que cada usuário personalize a experiência de uso do sistema. 

## Referências

> <a>1.</a> Fowler, M. (2003). UML Distilled: Um Guia Rápido para a Linguagem de Modelagem de Objetos Padrão. Addison-Wesley Professional.
> <a>2.</a> Lucid Software Inc. (s.d.). Lucidchart. Disponível em: [LucidChart](https://www.lucidchart.com/pages/pt/diagrama-de-componentes-uml). Acesso em: 13/11/2024

## Histórico de Versão

| Versão | Data | Descrição | Autor(es) | Data de revisão | Revisor(es) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| `1.0` | 09/11/2024  | Versão inicial do artefato. | [Vitor Feijó](https://github.com/vitorfleonardo) | 13/11/2024 | [Johnny da Ponte](https://github.com/JohnnyLopess)   |
| `1.1` | 13/11/2024  | Adicionando a Introdução. | [Paulo Borba](https://github.com/paulohborba) | 13/11/2024 | [Bianca Patrocínio](https://github.com/BiancaPatrocinio7)   |
| `1.2` | 13/11/2024  | Adicionando Resultados e breve explicação. |  [Paulo](https://github.com/paulohborba), [Gabriel](https://github.com/GabrielMS00), [Johnny](https://github.com/JohnnyLopess), [Bianca](https://github.com/BiancaPatrocinio7) e [Julia](https://github.com/juhvitoria4) | 13/11/2024 |   |
