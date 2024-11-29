# Diagrama de Casos de Uso

## Introdução

Os Casos de Uso, também conhecidos como diagramas comportamentais na notação UML, são ferramentas essenciais para descrever as ações que um sistema, ou conjunto de sistemas (denominado "subject"), deve executar em colaboração com um ou mais usuários externos (os "actors"). Essa técnica desempenha um papel central na modelagem de sistemas, permitindo que profissionais de diversas áreas contribuam com suas perspectivas, enriquecendo o processo de desenvolvimento de maneira colaborativa.

Cada caso de uso visa entregar um resultado observável e valioso para os atores ou demais partes interessadas, assegurando que as funcionalidades do sistema atendam às reais necessidades dos usuários. Durante as sessões de planejamento e desenvolvimento, ideias são compartilhadas, debatidas e as mais relevantes são priorizadas para implementação. Esse método promove uma abordagem criativa e orientada à resolução de problemas específicos, sempre focada no benefício dos usuários finais.

## Resultados

<p align="center" > <strong> Diagrama 1:</Strong> Diagrama de Casos de Uso - Agenda</font> <gitbr></p>
<center>
<div style="width: 640px; height: 480px; margin: 10px; position: relative;"><iframe allowfullscreen frameborder="0" style="width:640px; height:480px" src="https://lucid.app/documents/embedded/e74ab12b-41e3-4d06-8b10-4f07ba55c5dc" id="XAvvh5DVNHr1"></iframe></div>
</center>

<font size="3"><p style="text-align: center"><b>Autores:</b> [Johnny Lopes](https://github.com/JohnnyLopess) & [João Barreto](https://github.com/JoaoBarreto03) & [Danilo Carvalho](https://github.com/Danilo-Carvalho-Antunes) & [Gabriel Moura](https://github.com/thegm445) & [Gabriel Souza](https://github.com/GabrielMS00) & [Paulo Borba](https://github.com/paulohborba), 2024.</p></font>

### Legenda do Diagrama de Casos de Uso - Agenda Online

1. **Ator (Actor):** Representado por figuras estilizadas (homens-palito), um ator é uma entidade externa que interage com o sistema.

   - **Usuário:** Pessoa que utiliza o sistema "Agenda Online".
   - **Serviço de Notificação:** Serviço externo responsável pelo envio de notificações.
   - **Serviço de Voz:** Serviço externo que suporta comandos de voz.

2. **Sistema (Subject):** Representado pelo retângulo "Agenda Online", delimita o que está dentro do escopo do sistema a ser desenvolvido.

3. **Casos de Uso (Use Cases):** Representados pelas elipses azuis, cada uma define uma funcionalidade do sistema.  
   Exemplo: "Fazer Login", "Agendar Eventos", "Receber Notificações".

4. **Relacionamentos:**

   - **Associação:** Linhas conectando os atores aos casos de uso, indicando que o ator pode iniciar ou interagir com a funcionalidade.
   - **Inclusão («include»):** Relacionamento que indica que um caso de uso sempre depende de outro para completar sua funcionalidade.
   - **Extensão («extend»):** Relacionamento opcional que ocorre somente sob certas condições.

## Breve explicação

A figura apresentada ilustra os casos de uso do sistema Agenda Online e descreve as interações principais entre os atores e o sistema. No contexto deste projeto, os seguintes casos de uso são destacados como centrais para a funcionalidade do sistema: Fazer Login, Gerenciar Eventos, Sincronizar Dispositivos, Agendar Eventos, Criar Eventos por Voz, entre outros. Cada caso de uso representa um conjunto de ações que os atores podem realizar para alcançar um objetivo específico.

O ator Usuário é o elemento central no sistema, pois está diretamente relacionado a quase todos os casos de uso. Ele pode realizar operações como personalizar seu perfil, agendar eventos, visualizar o calendário e gerenciar eventos. Além disso, o usuário interage com sistemas externos, como o Serviço de Notificação e o Serviço de Voz, para funcionalidades adicionais.

O Serviço de Notificação está associado a dois casos de uso principais: Receber Notificações e Gerar Notificações. Essa integração permite que o sistema informe o usuário sobre eventos futuros ou alterações importantes, garantindo a comunicação eficiente.

O Serviço de Voz está vinculado ao caso de uso Criar Eventos por Voz, que representa a funcionalidade de reconhecimento de comandos de voz para criar eventos no sistema. Essa associação permite maior acessibilidade e conveniência para o usuário.

Os casos de uso Gerenciar Eventos e Sincronizar Dispositivos são extensões importantes da funcionalidade central do sistema. Gerenciar Eventos inclui ações como categorizar eventos e verificar conflitos, enquanto Sincronizar Dispositivos permite a integração com outros dispositivos e plataformas externas.

Por fim, os casos de uso adicionais, como Compartilhar Eventos, Buscar Eventos e Personalizar Perfil, enriquecem a experiência do usuário, proporcionando maior controle, organização e colaboração dentro do sistema. Essas funcionalidades, combinadas, tornam a Agenda Online uma solução robusta e abrangente para gerenciamento de tempo e tarefas.

## Referências

> <a>1.</a> UML Diagrams. **Use Case Diagrams**. Disponível em: [UML Use Case Diagrams](https://www.uml-diagrams.org/use-case-diagrams.html)  Acesso em: 24/11/2024. <br>
> <a>2.</a> Lucid Software Inc. (s.d.). Lucidchart. Disponível em: [LucidChart](https://www.lucidchart.com/pages/pt/diagrama-de-caso-de-uso-uml#:~:text=um%20diagrama%20UML-,O%20que%20%C3%A9%20diagrama%20de%20caso%20de%20uso%3F,de%20s%C3%ADmbolos%20e%20conectores%20especializados.). Acesso em: 24/11/2024. <br>

## Histórico de Versão

| Versão | Data       | Descrição                          | Autor(es)                          | Data de revisão | Revisor(es)                    |
| :----: | :--------: | ---------------------------------- | ---------------------------------- | :-------------: | ------------------------------ |
| `1.0`  | 09/11/2024 | Versão inicial do artefato.        | [Vitor Feijó](https://github.com/vitorfleonardo) | 25/11/2024      | [Paulo Borba](https://github.com/paulohborba) |
| `1.1`  | 25/11/2024 | Adicionando Introdução no artefato. | [Paulo Borba](https://github.com/paulohborba)       | 27/11/2024      | [Johnny Lopes](https://github.com/JohnnyLopess) |
| `1.3`  | 28/11/2024 | Adicionando diagrama e legenda.    | [Johnny Lopes](https://github.com/JohnnyLopess)    | 28/11/2024      | [Paulo Borba](https://github.com/paulohborba) |
| `1.4`  | 28/11/2024 | Adicionando as outras partes do artefato. | [Paulo Borba](https://github.com/paulohborba) | 28/11/2024      | [Johnny Lopes](https://github.com/JohnnyLopess) |
| `1.5`  | 28/11/2024 | Corrigindo markdownlint.           | [Paulo Borba](https://github.com/paulohborba)       | 28/11/2024      | [Johnny Lopes](https://github.com/JohnnyLopess) |
