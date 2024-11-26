# Diagrama de Atividades

## Introdução

O Diagrama de Atividades é uma ferramenta essencial na modelagem de sistemas, permitindo representar visualmente o fluxo de trabalho de processos e cenários. Ele detalha a sequência de atividades, as decisões tomadas, os atores envolvidos e o fluxo de informações. Essa representação gráfica facilita a compreensão do comportamento do sistema, melhorando a comunicação entre a equipe de desenvolvimento e os stakeholders. Na aplicação Agenda Online, diversos Diagramas de Atividades serão utilizados para modelar os principais fluxos de interação dos usuários, como criação de eventos, configuração de lembretes, compartilhamento de agendas e gerenciamento de tarefas. Cada diagrama focará em um aspecto específico do sistema, proporcionando uma visão detalhada e completa das funcionalidades da aplicação.

## Resultados

<p align="center" > <strong> Versão 1:</Strong> Diagrama de Atividades - Agenda</font> <gitbr></p>

<center>

![Diagrama de Atividades](./DiagramaDeAtividades.png)

</center>

<font size="3"><p style="text-align: center"><b>Autor:</b> [Gabriel Moura](https://github.com/thegm445), 2024</p></font>

<p align="center" > <strong> Versão 2:</Strong> Diagrama de Atividades - Agenda</font> <gitbr></p>

<iframe width="768" height="432" src="https://miro.com/app/live-embed/uXjVLCDMVTY=/?moveToViewport=-11299,1231,7634,3705&embedId=245797611417" frameborder="0" scrolling="no" allow="fullscreen; clipboard-read; clipboard-write" allowfullscreen></iframe>

<font size="3"><p style="text-align: center"><b>Autor:</b> [Carlos Eduardo](https://github.com/CADU110) & [Hugo Queiroz](https://github.com/melohugo), 2024</p></font>

## Explicação

O Diagrama de Atividades apresentado modela o fluxo de um usuário interagindo com a aplicação Agenda Online para criar, editar e gerenciar eventos. O diagrama inicia com o usuário acessando a agenda e selecionando uma data. Em seguida, o usuário decide se deseja criar um novo evento ou selecionar um evento existente. 

Se o usuário optar por criar um novo evento, ele insere os detalhes do evento, como nome, horário, descrição e categoria. Se optar por um evento existente, o usuário pode editar os detalhes do evento selecionado. Após inserir ou editar os detalhes, o usuário salva o evento.  

Opcionalmente, o usuário pode configurar um lembrete para o evento, definindo a antecedência e o tipo de alerta (notificação, email).  Também é possível compartilhar o evento com outros usuários, caso desejado. O diagrama finaliza com o evento salvo e as configurações de lembrete e compartilhamento definidas.

### Como Executar/Interpretar o Diagrama

O fluxo do diagrama é representado pelas setas, que indicam a sequência das atividades.  Os losangos representam pontos de decisão, onde o fluxo pode seguir diferentes caminhos dependendo da condição.  As barras paralelas (bifurcação e junção) indicam atividades que podem ser executadas simultaneamente ou que convergem para um único fluxo.

No exemplo acima, o usuário primeiro acessa a agenda e seleciona a data. Depois, ele toma a decisão: criar um novo evento ou selecionar um já existente. Após a decisão, os fluxos convergem para a atividade "Editar detalhes do evento".  As atividades opcionais, "Configurar lembrete" e "Compartilhar evento", são representadas por fluxos alternativos.

Os símbolos utilizados em um diagrama de atividades, como o apresentado, possuem significados específicos para representar diferentes etapas e comportamentos dentro de um fluxo de trabalho. Seguem alguns dos principais:

- Círculo preenchido: Representa o início de um fluxo de atividades.

- Círculo branco com centro preto: Representa o fim de um fluxo de atividades. Pode haver múltiplos pontos de fim em um diagrama, representando diferentes conclusões possíveis.

- Retângulo com cantos arredondados: Representa uma atividade ou ação específica a ser executada.

- Losango: Representa um ponto de decisão ou ramificação condicional. O fluxo segue por diferentes caminhos dependendo da condição avaliada.

- Setas: Representam o fluxo de controle ou a sequência em que as atividades são executadas. Elas conectam os diferentes elementos do diagrama, mostrando a ordem das operações.

- Barras grossas horizontais: Representam bifurcação (divisão do fluxo em caminhos paralelos) e junção (convergência de fluxos paralelos de volta para um único fluxo). A bifurcação indica que as atividades subsequentes podem ser executadas simultaneamente ou em qualquer ordem. A junção indica que todas as atividades que a precedem devem ser concluídas antes de prosseguir.

- Retângulo com a lateral em forma de seta: Representa o envio de um sinal. No exemplo, "Notificar o evento".

- Ampulheta: Representa uma espera ou atraso. Indica que o fluxo de atividades é pausado por um determinado período ou até que uma condição seja atendida.

## Referências

## Histórico de Versão

| Versão | Data | Descrição | Autor(es) | Data de revisão | Revisor(es) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| `1.0` | 09/11/2024  | Versão inicial do artefato. | [Vitor Feijó](https://github.com/vitorfleonardo) |  |  |
| `1.1` | 18/11/2024 | Criação da Introdução e Explicação do Diagrama. | [Gabriel Moura](https://github.com/thegm445) | 20/11/2024 | [Hugo Queiroz](https://github.com/melohugo) |
| `1.2` | 20/11/2024 | Adicionando versão 2 do diagrama. | [Carlos Eduardo](https://github.com/CADU110) e [Hugo Queiroz](https://github.com/melohugo) |  | |
