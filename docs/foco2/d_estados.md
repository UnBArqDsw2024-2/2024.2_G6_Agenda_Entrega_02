# Diagrama de Estados

## Introdução

O diagrama de estados é uma ferramenta essencial na modelagem de software, projetada para ilustrar o comportamento dinâmico de sistemas. Ele integra a UML (Unified Modeling Language), uma linguagem padrão de modelagem que possibilita a visualização, definição e documentação de diversos aspectos de um sistema de software.

Seu objetivo principal é representar os diferentes estados que um objeto ou sistema pode assumir durante seu ciclo de vida, além das transições entre esses estados, acionadas por eventos específicos. Esse tipo de diagrama oferece uma compreensão detalhada do comportamento interno do sistema e de como ele responde a estímulos externos, sendo especialmente útil para modelar sistemas reativos ou com fluxos de controle complexos.

## Resultados

### Versão Extendida

<p align="center" > <strong> Diagrama 1:</Strong> Diagrama de Estados - Agenda</font> <gitbr></p>
<iframe frameborder="0" style="width:100%;height:800px;" src="https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&layers=1&nav=1&title=diagrama_estados.drawio#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1fa0urfy05bsMGvvUzM8FoYJRFKt2y9K8%26export%3Ddownload"></iframe>

<font size="3"><p style="text-align: center"><b>Autores:</b> [Johnny Lopes](https://github.com/JohnnyLopess), [Vitor Feijó](https://github.com/vitorfleonardo) e [Paulo Borba](https://github.com/paulohborba), 2024.</p></font>

### Legenda do Diagrama de Estados

#### Estados

    Representados por caixas amarelas com os nomes das ações ou etapas específicas do sistema.

#### Transições

    As setas conectam os estados, indicando os possíveis fluxos de navegação ou ações executadas pelo usuário.

#### Estado Inicial

    Um círculo sólido indica o ponto de início do fluxo.

#### Estado Final

    Um círculo com borda grossa ao redor de outro círculo sólido representa o término do fluxo.

#### Eventos ou Ações

    Etiquetas nas setas descrevem os eventos que causam a transição de um estado para outro, como "cadastrar()", "salvar", ou "voltar".

## Breve explicação
Este diagrama de estados ilustra o comportamento dinâmico do sistema, destacando os diferentes estados possíveis e as transições acionadas por eventos específicos durante a interação do usuário. Aqui estão os principais aspectos do diagrama:

**Estados principais:**
* **Não Cadastrado:** Representa o estado inicial do usuário antes de efetuar login ou registro.
* **Autenticado:** O estado do usuário após realizar login com sucesso.
* **Gerenciando Eventos:** Reflete ações relacionadas a eventos, como criar, editar e compartilhar.
* **Gerenciando Tarefas:** Estado que cobre a criação, edição e definição de lembretes para tarefas.
* **Configurando Perfil:** Estado em que o usuário ajusta preferências, notificações e sincronizações.

**Transições:**
* As setas no diagrama representam as transições entre estados, acionadas por eventos como "cadastrar()", "acessarEventos", "criarEvento()", entre outros.
* Por exemplo, ao acessar o estado "Gerenciando Eventos", o usuário pode criar ou editar eventos, com ações como "salvar" e "confirmar" registradas.

**Detalhes internos:**
* Cada estado maior, como "Gerenciando Eventos" ou "Gerenciando Tarefas", é subdividido em estados menores para detalhar o fluxo interno de ações.
* Isso ajuda a compreender o ciclo de vida de atividades específicas, como o fluxo desde "Criando Evento" até "Visualizando Eventos".

**Ponto inicial e final:**
* O ponto preenchido representa o início do fluxo.
* O ponto preenchido com um círculo ao redor indica o término da interação, como no logout.

## Referências

> <a>1.</a> UML Diagrams. **State Machine Diagrams**. Disponível em: [UML diagrams State Machine Diagrams](https://www.uml-diagrams.org/state-machine-diagrams.html)  Acesso em: 19/11/2024. <br>
> <a>2.</a> Lucid Software Inc. (s.d.). Lucidchart. Disponível em: [LucidChart](https://www.lucidchart.com/pages/pt/o-que-e-diagrama-de-maquina-de-estados-uml). Acesso em: 19/11/2024. <br>

## Histórico de Versão

| Versão | Data | Descrição | Autor(es) | Data de revisão | Revisor(es) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| `1.0` | 09/11/2024  | Versão inicial do artefato. | [Vitor Feijó](https://github.com/vitorfleonardo) | 19/11/2024  | [Paulo Borba](https://github.com/paulohborba) |
| `1.1` | 20/11/2024  | Adicionando as Referências e a parte dos Resultados do artefato. | [Paulo Borba](https://github.com/paulohborba) | 24/11/2024 | [Johnny Lopes](https://github.com/JohnnyLopess)  |
| `1.2` | 24/11/2024  | Adicionando introdução, breve explicação e iframe do diagrama. | [Johnny Lopes](https://github.com/JohnnyLopess) | 24/11/2024 |  [Paulo Borba](https://github.com/paulohborba) |
