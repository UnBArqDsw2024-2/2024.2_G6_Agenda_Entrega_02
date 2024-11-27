# Diagrama de Sequência

## Introdução

O diagrama de sequência, utilizado na UML (Unified Modeling Language), descreve a ordem de interação entre objetos de um sistema, mostrando as mensagens trocadas. É especialmente útil para entender o fluxo geral de comportamento em projetos com muitas classes e métodos. Ele organiza essas interações de forma clara e lógica.

### **Principais Conceitos**

- **Atores**: Entidades externas que iniciam interações, como usuários ou sistemas.
- **Objetos**: Instâncias de classes envolvidas no processo.
- **Gate**: Pontos que conectam mensagens para dentro ou fora do sistema.
- **Fragmento**: Representa partes da interação, como:
  - **Alt**: Condições alternativas.
  - **Loop**: Repetições.
  - **Break**: Interrupções.
- **Linha de vida**: Representa a existência de um objeto durante a interação, com:
  - Uma linha vertical tracejada.
  - Um cabeçalho exibindo o objeto e, opcionalmente, seus atributos.

## Resultados

### Versão Inicial

Explicação no tópico de [Breve explicação](http://localhost:3000/#/./foco2/d_sequencia?id=breve-explica%c3%a7%c3%a3o):

<p align="center" > <strong> Diagrama 1:</Strong> Diagrama de Sequência - Agenda</font> <gitbr></p>
<center>
<div style="width: 640px; height: 480px; margin: 10px; position: relative;"><iframe allowfullscreen frameborder="0" style="width:640px; height:480px" src="https://lucid.app/documents/embedded/9650c958-45df-4e3f-bf58-e1e6b7f7a289" id="0l0sjicccPD1"></iframe></div>
</center>

<font size="3"><p style="text-align: center"><b>Autor:</b> [Bianca Castro](https://github.com/BiancaPatrocinio7) & [Julia Silva](https://github.com/Juhvitoria4) & [Yago Passos](https://github.com/yagompassos), 2024</p></font>

### Diagramas Baseados em Casos de Uso

Explicação na página de [Especificação de Casos de Uso](https://unbarqdsw2024-2.github.io/2024.2_G6_Agenda_Entrega_02/#/./extras/espec_caso_uso):

<p align="center" > <strong> Diagrama 2:</Strong> Diagrama de Sequência - Login/Cadastro </font> <gitbr></p>
<center>
<div style="width: 840px; height: 480px; margin: 10px; position: relative;"><iframe allowfullscreen frameborder="0" style="width:640px; height:480px" src="https://lucid.app/documents/embedded/23042634-02f2-489c-99df-5f1836953d31" id="K7Du_4XURyNP"></iframe></div>
</center>

<font size="3"><p style="text-align: center"><b>Autor:</b> [Bianca Castro](https://github.com/BiancaPatrocinio7), 2024</p></font>

<p align="center" > <strong> Diagrama 3:</Strong> Diagrama de Sequência - Cadastro de Evento </font> <gitbr></p>
<center>
<div style="width: 840px; height: 480px; margin: 10px; position: relative;"><iframe allowfullscreen frameborder="0" style="width:640px; height:480px" src="https://lucid.app/documents/embedded/50c78de8-8177-4b28-a2b6-3a1a35577e3f" id="FHEu3T-Uhm-X"></iframe></div>
</center>

<font size="3"><p style="text-align: center"><b>Autor:</b> [Bianca Castro](https://github.com/BiancaPatrocinio7), 2024</p></font>

<p align="center" > <strong> Diagrama 4:</Strong> Diagrama de Sequência - Compartilhamento </font> <gitbr></p>
<center>
<div style="width: 640px; height: 480px; margin: 10px; position: relative;"><iframe allowfullscreen frameborder="0" style="width:640px; height:480px" src="https://lucid.app/documents/embedded/11c66da3-9aaf-437c-aad0-41efcb73fe28" id="ZcWuoLOcmViW"></iframe></div>
</center>

<font size="3"><p style="text-align: center"><b>Autor:</b>  [Yago Passos](https://github.com/yagompassos), 2024</p></font>

<p align="center" > <strong> Diagrama 5:</Strong> Diagrama de Sequência - Visualizar Agenda </font> <gitbr></p>
<center>
<div style="width: 640px; height: 480px; margin: 10px; position: relative;"><iframe allowfullscreen frameborder="0" style="width:640px; height:480px" src="https://lucid.app/documents/embedded/3e98f2ee-e6ce-4a5b-9a57-e3d1e683acea" id="radvtz2IvKE0"></iframe></div>

<font size="3"><p style="text-align: center"><b>Autor:</b>  [Julia Vitoria](https://github.com/Juhvitoria4), 2024</p></font>

## Breve explicação

A construção do diagrama aconteceu, segundo o IBM, na fase de design do projeto, onde diagramas de seqüência explicam como o sistema funciona para realizar as interações. A tabela 1, expôe dados da modelagem do diagrama.

Na data indicada, o diagrama de sequência foi desenvolvido seguindo os princípios da UML (Unified Modeling Language) para representar as interações entre os objetos do sistema de agenda em diferentes cenários de uso. Foram encontrados 5 objetos que compuseram o diagrama em sua versão final:

- Autenticação
- Agenda
- Evento
- Sincronização
- Plataformas

Desses objetos, traçamos as linhas de vida e então começamos a definir as principais mensagens que seriam trocadas por eles. Mapeamos então, os *gates* e, as mensagens que por eles comunicavam, foram mais tarde especificadas dentro dos fragmentos. 

A tabela 1 expressa quais as mensagens mapeadas e, se estão dentro de um fragmento.

| Mensagem          | Objeto Ator | Objeto Receptor | Tipo de Fragmento |
|-------------------|-------------|-----------------|-------------------|
| Realiza cadastro/Login | Usuário  | Autenticação    | N/A  |
| Selecionar Evento | Autenticação | Agenda          | N/A |
| Visualizar detalhes do evento  | Agenda     | Evento          | Loop |
| Retornar detalhes do evento  | Evento     | Agenda          | Loop  |
| Visualiza a agenda  | Autenticação      | Agenda   | N/A |
| Listar Eventos | Agenda | Evento     | Loop |
| Retornar Eventos | Evento | Agenda     | Loop  |
| Editar evento | Autenticação | Agenda     | N/A  |
| Alterar evento | Agenda | Evento     | Loop |
| Confirmar alteração de evento | Evento | Agenda     | Loop |
| Sincronizar agenda | Agenda | Sincronização     | N/A |
| Sincronizar com plataformas | Sincronização | Plataformas | Loop |
| Confirmar sincronização | Plataformas | Sincronização | Loop |

<font size="2"><p style="text-align: center">Tabela 1: Mensagens modeladas no diagrama. Autor: [Yago Passos](https://github.com/yagompassos), 2024</p></font>

Como visto, utilizamos fragmentos de interação do tipo "loop" para indicar operações repetitivas, como listagem de eventos ou sincronização com plataformas externas. A representação gráfica do fluxo de mensagens foi organizada de cima para baixo, indicando a ordem sequencial dos processos e destacando as dependências entre os objetos. Esse diagrama é essencial para validar o comportamento do sistema, identificar pontos de integração e garantir que todos os cenários de uso estejam contemplados no design do software.

## Referências

> <a>1.</a> "Diagrama de sequência". *Wikipedia*. Disponível em: [Wikipedia](https://pt.wikipedia.org/wiki/Diagrama_de_sequ%C3%AAncia). <br>
> <a>2.</a> Lucid Software Inc. (s.d.). Lucidchart. Disponível em: [LucidChart](https://www.lucidchart.com/pages/pt/diagrama-de-componentes-uml). <br>
> <a>3.</a> IBM Diagramas de Seqüência, 2024. Disponível em: [IBM Rational Software Modeler](https://www.ibm.com/docs/pt-br/rsm/7.5.0?topic=uml-sequence-diagrams)<br>

## Histórico de Versão

| Versão | Data | Descrição | Autor(es) | Data de revisão | Revisor(es) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| `1.0` | 09/11/2024  | Versão inicial do artefato. | [Vitor Feijó](https://github.com/vitorfleonardo) | 20/11/2024 | [Bianca](https://github.com/BiancaPatrocinio7) |
| `1.1` | 20/11/2024  | Adicionando introdução e arquivo base. | [Bianca](https://github.com/BiancaPatrocinio7) | 21/11/2024 | [Yago Passos](https://github.com/yagompassos) |
| `1.2` | 21/11/2024  | Seção de explicação e metodologia | [Yago Passos](https://github.com/yagompassos) | 24/11/2024 |   [Bianca](https://github.com/BiancaPatrocinio7) |
| `1.3` | 25/11/2024  | Versões detalhadas do diagrama | [Bianca](https://github.com/BiancaPatrocinio7) | 26/11/2024 |   [Yago Passos](https://github.com/yagompassos) |
| `1.4` | 26/11/2024  | Diagrama de compartilhamento  | [Yago Passos](https://github.com/yagompassos) | 27/11/2024 | [Julia Vitoria](https://github.com/Juhvitoria4) |  
| `1.5` | 26/11/2024  | Diagrama de visualizar agenda | [Julia Vitoria](https://github.com/Juhvitoria4) |  |  |