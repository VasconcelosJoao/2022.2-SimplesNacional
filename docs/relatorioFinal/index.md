# Post Mortem

## <a>Histórico de Versão</a>

| Data de Realização | Data Prevista de Revisão | Versão |                 Descrição                 |                     Autor                      |                    Revisor                     |
| :----------------: | :----------------------: | :----: | :---------------------------------------: | :--------------------------------------------: | :--------------------------------------------: |
|     27/01/2023     |        28/01/2023        |  1.0   |           Criação do Documento            |     [Ana Luiza](https://github.com/AnHoff)     | [Thiago Oliveira](https://github.com/Thiab394) |
|     29/01/2023     |        30/01/2023        |  1.1   |         Adiciona artefatos e V&V          |     [Ana Luiza](https://github.com/AnHoff)     | [Thiago Oliveira](https://github.com/Thiab394) |
|     31/01/2023     |        01/02/2023        |  1.2   | Adição Das seções Planejamento e execução | [Thiago Oliveira](https://github.com/Thiab394) |   [Pedro Lucas](https://github.com/PedroLSF)   |
|     31/01/2023     |        01/02/2023        |  1.3   |        Criação da seção de Design         |   [Pedro Lucas](https://github.com/PedroLSF)   |   [Arthur Taylor](https://github.com/Eruel6)   |
|     01/02/2023     |        01/02/2023        |  1.4   |        Adição do modelo de design         |   [Arthur Taylor](https://github.com/Eruel6)   |   [João Lucas](https://github.com/HacKairos)   |
|     01/02/2023     |        01/02/2023        |  1.5   |          Técnicas e Ferramentas           |   [João Lucas](https://github.com/HacKairos)   |           [Ana Luiza](https://github.com/AnHoff)            |
|     01/02/2023     |        01/02/2023        |  1.6   |          Objetivos e Descrição do Simples Nacional           |   [Eduardo](https://github.com/edudsan)   |           [Ana Luiza](https://github.com/AnHoff)            |

## <a>Introdução</a>
O presente documento visa reunir os materiais requisitados pelo professor André Barros de Sales, da disciplina Interação Humano Computador da Universidade de Brasília, para a realização da apresentação final. O conteúdo presente abaixo aborda os seguintes tópicos detalhadamente:

* O **site** selecionado;
* O **ciclo de vida** escolhido;
* **Planejamento** de recursos e entregas;
* **Execução** do projeto;
* **Resultados** alcançados;
* Tabelas sintetizando as **técnicas** utilizadas, **artefatos** criados, métodos de **verificação e validação**, **ferramentas** e seu uso, vídeos das **apresentações**, **avaliações** dos protótipos;
* Facilidades e dificuldades.

Vale destacar que o documento foi elaborado seguindo o template utilizado pelo projeto do YouTube [1], realizado no semestre 2022.1.

## <a>Objetivo</a>
A disciplina de Interação Humano-Computador tem como objetivo principal fornecer aos alunos conhecimentos sobre teorias, princípios e métodos para projetar interfaces de usuário intuitivas e eficientes. Além disso, a disciplina busca desenvolver habilidades práticas para projetar e implementar soluções interativas e familiarizar os alunos com tendências e tecnologias emergentes na área. O curso também aborda técnicas de avaliação de sistemas interativos e a importância de considerar as necessidades dos usuários sobre o site do Simples Nacional.


## <a>Simples Nacional</a>
### <a>Sobre o Simples Nacional</a>
O Simples Nacional é um regime tributário simplificado para microempresas e empresas de pequeno porte no Brasil. Ele permite a unificação de diversos impostos em uma única guia, facilitando o pagamento de tributos e reduzindo a carga tributária para essas empresas. Além disso, o Simples Nacional também oferece incentivos fiscais e facilitações administrativas para as empresas que se enquadram nesse regime. Em resumo, o Simples Nacional é uma opção vantajosa para microempresas e empresas de pequeno porte que buscam simplificação e redução de carga tributária.

### <a>Por quê o Simples Nacional?</a>
O site do Simples Nacional foi escolhido dentre outros sites analisados pela equipe. Os fatores utilizados para esta seleção foram as heurísticas de Interação Humano-Computador que são regras de ouro para avaliar a qualidade de interfaces de usuário. Elas foram propostas por Jakob Nielsen e consistem em uma lista de critérios que os designers de interfaces devem considerar ao projetar sistemas interativos. Algumas das heurísticas mais conhecidas incluem:

**Visibilidade do sistema de status:** O sistema deve sempre informar ao usuário sobre o que está acontecendo, de forma clara e objetiva.

**Correspondência entre sistema e mundo real:** O sistema deve usar linguagem e conceitos familiares ao usuário, de acordo com sua cultura e experiência.

**Prevenção de erros:** O sistema deve prevenir erros, alertando o usuário sobre ações potencialmente prejudiciais ou irreversíveis.

**Flexibilidade e eficiência de uso:** O sistema deve permitir ao usuário realizar tarefas de maneira rápida e eficiente, oferecendo múltiplas formas de realizar ações.

**Consistência e padrões:** O sistema deve seguir padrões conhecidos pelo usuário, garantindo a consistência da interface ao longo do tempo.

**Reconhecimento ao invés de recall:** O sistema deve apresentar informações e opções de maneira clara e fácil de reconhecer, sem exigir que o usuário as memorize.

Estas heurísticas são usadas como uma lista de verificação para avaliar e melhorar a qualidade da interação entre humanos e computadores. Ao utilizar estas heurísticas para avaliar o Simples Nacional, chegamos a conclusão que o site possuia melhorias a serem feitas nele.

## <a>O ciclo de vida de Mayhew</a>

Para a execução de um projeto de IHC deve ser selecionado um modelo de design para ser seguido, existem vários modelos, podem ser citados exemplos como o ciclo de vida em estrela, design baseado em cenários e o ciclo de vida de Mayhew, cada um possui certas vantagens e desvantagens, não existindo um melhor ou pior, mas cada um pode se sair melhor em certas situações.

Com isso sendo considerado, o grupo achou melhor optar por utilizar o ciclo de vida de Mayhew no projeto realizado na disciplina, por ser um modelo com artefatos completos, tendo um fluxo a ser seguido para ajudar a visualização das etapas que serão realizadas, estes motivos auxiliam equipes não muito maduras no processo de avaliação. 

O ciclo de vida de Mayhew é subdividido em 3 grandes etapas, sendo elas:

- Análise de Requisitos;
- Projeto, testes e implementação;
- Instalação.

Explicações mais detalhadas sobre o modelo podem ser encontradas no documento de [Modelo de Design](../Planejamento/ModeloDesign/)

## <a>Planejamento</a>
Esta seção tem como objetivo relatar o planejamento feito ao decorrer da disciplina, que consiste basicamente nos documentos realizadas como um meio de "preparação" para o bom desenvolvimento da mesma.

Em tal etapa temos diversos documentos, tais como sites analisados, metodologia e processos, Ferramentas, etc, que estão listados e podem ser visualizados na seção de [Artefatos - Etapa 1](#etapa 1), porém aqui será mostrado apenas o cronograma planejado do projeto, que seria a essência do planejamento do mesmo, por possuir em detalhes a realização de cada artefate e de cada "Sub-artefato" ou até documentos e etapas auxiliares para que seja realizada uma boa execução.

O Cronograma Planejado pode ser visto [aqui](https://interacao-humano-computador.github.io/2022.2-SimplesNacional/Planejamento/Roadmap/#cronograma-planejado), porém também será listado logo abaixo, nas Tabelas de 1-7 Relacionadas ás etapas 1-7 respectivamente:

<center>

### <a>Etapa 1</a>

|               Tarefa               |               Responsáveis                |   Início   |    Fim     |  Revisão   | Revisor |
| :--------------------------------: | :---------------------------------------: | :--------: | :--------: | :--------: | :-----: |
|       Listar sites avaliados       |                Ana e Pedro                | 28/10/2022 | 01/11/2022 | 02/11/2022 |  João   |
| Discorrer sobre o site selecionado |                Ana e Pedro                | 01/11/2022 | 19/11/2022 | 20/11/2022 |  Pedro  |
|       Ferramentas do projeto       |         Arthur, Eduardo e Thiago          | 12/11/2022 | 19/11/2022 | 20/11/2022 |   Ana   |
|      Planejamento Individual       | Ana, Arthur, Pedro, João, Thiago, Eduardo | 12/11/2022 | 19/11/2022 | 20/11/2022 | Thiago  |
|      Cronograma de atividades      |              Arthur e Thiago              | 16/11/2022 | 23/11/2022 | 24/11/2022 | Eduardo |
|              Heatmap               |                  Eduardo                  | 16/11/2022 | 23/11/2022 | 24/11/2022 | Thiago  |
|            Metodologias            |              Arthur e Thiago              | 16/11/2022 | 23/11/2022 | 24/11/2022 |  Pedro  |
|               Equipe               |                  Thiago                   | 16/11/2022 | 23/11/2022 | 24/11/2022 |  João   |
|                Atas                |                  Arthur                   | 16/11/2022 | 23/11/2022 | 24/11/2022 |   Ana   |
|         Processo de Design         |              João e Eduardo               | 16/11/2022 | 23/11/2022 | 24/11/2022 | Arthur  |

*Tabela 1 - Tarefas para a Etapa 1*<br><br>

### <a>Etapa 2</a>

|          Tarefa           |     Responsáveis      |   Início   |    Fim     |  Revisão   |  Revisor  |
| :-----------------------: | :-------------------: | :--------: | :--------: | :--------: | :-------: |
| Traçar perfil de usuários | Eduardo, João e Pedro | 23/11/2022 | 30/11/2022 | 01/12/2022 | João, Ana |
|         Personas          |         Pedro         | 23/11/2022 | 06/12/2022 | 07/12/2022 |   João    |
|   Perfil - Questionário   |        Eduardo        | 23/11/2022 | 29/11/2022 | 30/11/2022 |  Thiago   |
|   Mapear possibilidades   |         Pedro         | 30/11/2022 | 06/12/2022 | 07/12/2022 |  Arthur   |
|     Mapear limitações     |        Eduardo        | 30/11/2022 | 06/12/2022 | 07/12/2022 |  Arthur   |
| Análise de tarefas - HTA  |          Ana          | 23/11/2022 | 06/12/2022 | 07/12/2022 |  Eduardo  |
| Análise de tarefas - GOMS |         Pedro         | 23/11/2022 | 06/12/2022 | 07/12/2022 |  Thiago   |

*Tabela 2 - Tarefas para a Etapa 2*<br><br>

### <a>Etapa 3</a>

|            Tarefa             | Responsáveis |   Início   |    Fim     |  Revisão   | Revisor |
| :---------------------------: | :----------: | :--------: | :--------: | :--------: | :-----: |
| Princípios gerais do projeto  | Ana e Thiago | 04/12/2022 | 08/12/2022 | 09/12/2022 | Arthur  |
|        Guia de estilo         |    Arthur    | 04/12/2022 | 08/12/2022 | 09/12/2022 | Thiago  |
| Características da plataforma |   Eduardo    | 07/12/2022 | 11/12/2022 | 12/11/2022 |  João   |
|     Metas de usabilidade      | Pedro e João | 07/12/2022 | 11/12/2022 | 12/11/2022 | Eduardo |

*Tabela 3 - Tarefas para a Etapa 3*<br><br>

### <a>Etapa 4</a>

|                                  Tarefa                                   | Responsáveis  |   Início   |    Fim     |  Revisão   | Revisor |
| :-----------------------------------------------------------------------: | :-----------: | :--------: | :--------: | :--------: | :-----: |
|                  Storyboard - planejamento da avaliação                   |     Pedro     | 09/12/2022 | 13/12/2022 | 14/12/2022 |   Ana   |
|              Análise de tarefas - planejamento de avaliação               | João e Thiago | 09/12/2022 | 13/12/2022 | 14/12/2022 |  Pedro  |
|     Storyboard - planejamento dos relatos dos resultados da avaliação     | Arthur e Ana  | 13/12/2022 | 14/12/2022 | 15/12/2022 |  João   |
| Análise de tarefas - planejamento dos relatos dos resultados da avaliação |    Eduardo    | 13/12/2022 | 14/12/2022 | 15/12/2022 | Arthur  |

*Tabela 4 - Tarefas para a Etapa 4*<br><br>

### <a>Etapa 5</a>

|                           Tarefa                           |  Responsáveis   |   Início   |    Fim     |  Revisão   | Revisor |
| :--------------------------------------------------------: | :-------------: | :--------: | :--------: | :--------: | :-----: |
|                     Análise de tarefas                     | Thiago e Arthur | 14/12/2022 | 01/01/2023 | 02/01/2023 |   Ana   |
|       Protótipo de papel - planejamento da avaliação       |   João e Ana    | 14/12/2022 | 01/01/2023 | 02/01/2023 |  Pedro  |
|             Storyboard - relato dos resultados             |     Eduardo     | 14/12/2022 | 01/01/2023 | 02/01/2023 | Thiago  |
| Protótipo de papel - planejamento do relato dos resultados |      Pedro      | 14/12/2022 | 01/01/2023 | 02/01/2023 |  João   |

*Tabela 5 - Tarefas para a Etapa 5*<br><br>

### <a>Etapa 6</a>

|                  Tarefa                   |      Responsáveis       |   Início   |    Fim     |  Revisão   | Revisor |
| :---------------------------------------: | :---------------------: | :--------: | :--------: | :--------: | :-----: |
| Definir os padrões de design de interface | Pedro, Thiago e Eduardo | 01/01/2023 | 10/01/2023 | 11/01/2023 |  João   |
|    Protótipos dos designs de interface    |   João, Ana e Arthur    | 01/01/2023 | 10/01/2023 | 11/01/2023 | Thiago  |

*Tabela 6 - Tarefas para a Etapa 6*<br><br>

### <a>Etapa 7</a>

|                          Tarefa                          |  Responsáveis   |   Início   |    Fim     |  Revisão   | Revisor |
| :------------------------------------------------------: | :-------------: | :--------: | :--------: | :--------: | :-----: |
| Protótipo de alta fidelidade - planejamento de avaliação | Arthur e Thiago | 11/01/2023 | 17/01/2023 | 18/01/2023 |   Ana   |
|    Coleta de opinião dos usuários e melhorias de IHC     |  Pedro e João   | 16/01/2023 | 24/01/2023 | 25/01/2023 | Eduardo |
|        Protótipo de papel - relato dos resultados        |  Ana e Eduardo  | 17/01/2023 | 20/01/2023 | 21/01/2023 |  João   |

*Tabela 7 - Tarefas para a Etapa 7*<br><br>

</center>

## <a>Execução</a>
Esta seção tem como objetivo relatar a execução dos artefatos ao decorrer da disciplina. Tal etapa diz respeito á como foram feitos os artefatos, por quem, quando e quem foi o revisor, também podem ser acrescentadas técnicas de cada uma das etapas do projeto, porém elas estão disponiveis numa seção mais abaixo de [tecnicas](#técnicas).

Em tal etapa temos grande parte dos documentos,  e todos os artefatos realizados para a conclusão da disciplina, como Aspectos Éticos, personas, cenários, storyboard, entre outros que estão listados e podem ser visualizados na seção de [Artefatos](#artefatos), da etapa 1 em diante, porém aqui será mostrado apenas o cronograma executado do projeto, que seria a essência da execução do mesmo, por possuir em detalhes a realização de cada artefato e de cada "Sub-artefato" ou até documentos e etapas auxiliares realizadas para o desenvolvimento dos artefatos.

O Cronograma Executa pode ser visto [aqui](https://interacao-humano-computador.github.io/2022.2-SimplesNacional/Planejamento/Roadmap/#cronograma-realizado), porém também será listado logo abaixo, nas Tabelas de 8-14 Relacionadas ás etapas 1-7 respectivamente:

### <a>Etapa 1</a>

|               Tarefa               |               Responsáveis                |  Entrega   |  Revisão   |    Revisor     |
| :--------------------------------: | :---------------------------------------: | :--------: | :--------: | :------------: |
|       Listar sites avaliados       |                Ana e Pedro                | 23/11/2022 | 23/11/2022 |   Ana, Pedro   |
| Discorrer sobre o site selecionado |                   Pedro                   | 23/11/2022 | 23/11/2022 |      Ana       |
|       Ferramentas do projeto       |                Ana e João                 | 14/11/2022 | 14/11/2022 |   Ana, João    |
|      Planejamento Individual       | Ana, Arthur, Pedro, João, Thiago, Eduardo | 22/11/2022 | 22/11/2022 |     Thiago     |
|      Cronograma de atividades      |              Arthur e Thiago              | 22/11/2022 | 23/11/2022 | Arthur, Thiago |
|              Heatmap               |                  Eduardo                  | 22/11/2022 | 22/11/2022 |      João      |
|            Metodologias            |              Arthur e Thiago              | 20/11/2022 | 21/11/2022 | Arthur, Thiago |
|               Equipe               |                   João                    | 20/11/2022 | 20/11/2022 |     Thiago     |
|                Atas                |                  Arthur                   | 22/11/2022 | 23/11/2022 |      Ana       |
|         Processo de Design         |                   Pedro                   | 22/11/2022 | 22/11/2022 |      João      |

*Tabela 8 - Tarefas executadas para a Etapa 1*<br><br>

### <a>Etapa 2</a>

|          Tarefa           |  Responsáveis   |  Entrega   |  Revisão   | Revisor |
| :-----------------------: | :-------------: | :--------: | :--------: | :-----: |
| Traçar perfil de usuários |     Eduardo     | 05/12/2022 | 06/12/2022 |  João   |
|         Personas          |      João       | 07/12/2022 | 08/12/2022 | Eduardo |
|   Perfil - Questionário   |     Eduardo     | 03/12/2022 | 05/12/2022 | Thiago  |
|      Aspectos éticos      | Thiago e Arthur | 07/12/2022 | 07/12/2022 | Arthur  |
| Análise de tarefas - HTA  |       Ana       |  07/2022   | 07/12/2022 |  Pedro  |
| Análise de tarefas - GOMS |      Pedro      |  06/2022   | 07/12/2022 |  João   |

*Tabela 9 - Tarefas  executadas para a Etapa 2*<br><br>

### <a>Etapa 3</a>

|            Tarefa             |    Responsáveis     |  Entrega   |  Revisão   |     Revisor     |
| :---------------------------: | :-----------------: | :--------: | :--------: | :-------------: |
|    Termo de Consentimento     |       Thiago        | 08/12/2022 | 09/12/2022 |       Ana       |
|   Refatoração do cronograma   |         Ana         | 08/12/2022 | 09/12/2022 |     Arthur      |
|          Ajustes HTA          |         Ana         | 11/12/2022 | 11/12/2022 |     Thiago      |
| Princípios gerais do projeto  |        Pedro        | 11/12/2022 | 12/12/2022 |       Ana       |
|        Guia de estilo         | Arthur, Ana, Thiago | 11/12/2022 | 12/12/2022 | Thiago, Eduardo |
| Características da plataforma |        João         | 11/12/2022 | 12/12/2022 |     Eduardo     |
|     Metas de usabilidade      |    Pedro e João     | 11/12/2022 | 12/12/2022 |     Eduardo     |
|           Cenários            |        João         | 11/12/2022 | 12/12/2022 |      Pedro      |

*Tabela 10 - Tarefas executadas para a Etapa 3*<br><br>

### <a>Etapa 4</a>

|                          Tarefa                           |      Responsáveis      |  Entrega   |  Revisão   |    Revisor     |
| :-------------------------------------------------------: | :--------------------: | :--------: | :--------: | :------------: |
|          Planejamento da Avaliação - Storyboard           |          Ana           | 13/12/2022 | 13/12/2022 |     Arthur     |
|      Planejamento da Avaliação - Análise de Tarefas       | Arthur, Eduardo, Pedro | 13/12/2022 | 14/12/2022 | Thiago, Arthur |
|     Planejamento de relato de resultados - Storyboard     |          João          | 14/12/2022 | 14/12/2022 |      Ana       |
| Planejamento de relato de resultados - Análise de Tarefas |         Thiago         | 14/12/2022 | 14/12/2022 |      João      |

*Tabela 11 - Tarefas executadas para a Etapa 4*<br><br>

### <a>Etapa 5</a>

|                     Tarefa                     | Responsáveis  |  Entrega   |  Revisão   |   Revisor   |
| :--------------------------------------------: | :-----------: | :--------: | :--------: | :---------: |
|             Avaliação - Storyboard             |     João      | 20/12/2022 | 21/12/2022 | Arthur, Ana |
|         Avaliação - Análise de Tarefas         |    Arthur     | 20/12/2022 | 21/12/2022 |    João     |
|         Desenvolvimento do Storyboard          | Ana, Eduardo  | 18/12/2022 | 19/12/2022 |   Arthur    |
| Teste piloto - Storyboard e Análise de Tarefas | Pedro, Thiago | 18/12/2022 | 19/12/2022 |     Ana     |

*Tabela 12 - Tarefas executadas para a Etapa 5*<br><br>

### <a>Etapa 6</a>

|                               Tarefa                                |  Responsáveis   |  Entrega   |  Revisão   |       Revisor        |
| :-----------------------------------------------------------------: | :-------------: | :--------: | :--------: | :------------------: |
|      Planejamento da Avaliação - Protótipo de Alta Fidelidade       |       Ana       | 05/01/2023 | 06/01/2023 |       Eduardo        |
|           Planejamento da Avaliação - Protótipo de Papel            |       Ana       | 01/01/2023 | 02/01/2023 |        Thiago        |
|               Criação do Protótipo de Alta Fidelidade               |   João Lucas    | 05/01/2023 | 06/01/2023 |       Eduardo        |
| Planejamento de relato de resultados - Protótipo de Alta Fidelidade |      João       | 05/01/2023 | 06/01/2023 |        Thiago        |
|      Planejamento de relato de resultados - Protótipo de Papel      |      João       | 05/01/2023 | 06/01/2023 |        Thiago        |
|                   Avaliação - Protótipo de Papel                    |  Pedro, Arthur  | 05/01/2023 | 06/01/2023 |         João         |
|                 Gravação de Avaliação - Storyboard                  |  Pedro, Arthur  | 05/01/2023 | 06/01/2023 |         João         |
|             Gravação de Avaliação - Análise de Tarefas              |  Pedro, Arthur  | 05/01/2023 | 06/01/2023 |         João         |
|                Desenvolvimento do Protótipo de Papel                |       Ana       | 03/01/2023 | 03/01/2023 | Arthur, João, Thiago |
|             Gravação de Avaliação - Protótipo de Papel              |  Pedro, Arthur  | 05/01/2023 | 06/01/2023 |         João         |
|                  Teste piloto - Protótipo de Papel                  | Eduardo, Thiago | 05/01/2023 | 06/01/2023 |        Arthur        |
|           Teste piloto - Storyboard e Análise de Tarefas            | Eduardo, Thiago | 05/01/2023 | 06/01/2023 |         João         |
|             Relato dos Resultados - Protótipo de Papel              |  Thiago, Pedro  | 11/02/2023 | 11/02/2023 |       Eduardo        |
|                 Relato dos Resultados - Storyboard                  |  Thiago, Pedro  | 11/02/2023 | 11/02/2023 |         Ana          |
|             Relato dos Resultados - Análise de Tarefas              |  Thiago, Pedro  | 11/02/2023 | 11/02/2023 |        Arthur        |
|    Ajustes no Planejamento de Relato dos Resultados - Storyboard    |       Ana       | 05/01/2023 | 06/01/2023 |       Eduardo        |

*Tabela 13 - Tarefas executadas para a Etapa 6*<br><br>

### <a>Etapa 7</a>

|                                  Tarefa                                  | Responsáveis  |  Entrega   |  Revisão   |    Revisor    |
| :----------------------------------------------------------------------: | :-----------: | :--------: | :--------: | :-----------: |
|                       Planejamento da Verificação                        |     Pedro     | 15/01/2023 | 16/01/2023 |  João Lucas   |
|                      Verificação - Sites Analisados                      |  Pedro Lucas  | 18/01/2023 | 18/01/2023 |  João Lucas   |
|                      Verificação - Modelo de Design                      |      Ana      | 18/01/2023 | 18/01/2023 |  Pedro Lucas  |
|                      Verificação - Aspectos Éticos                       |      Ana      | 16/01/2023 | 17/01/2023 |  João Lucas   |
|                   Verificação - Termo de Consentimento                   |      Ana      | 14/01/2023 | 15/01/2023 |  Pedro Lucas  |
|                     Verificação - Princípios Gerais                      |      Ana      | 18/01/2023 | 18/01/2023 | Arthur Taylor |
|                     Verificação - Analise de Tarefas                     |  João Lucas   | 16/01/2023 | 17/01/2023 |      Ana      |
|                     Verificação - Perfil de Usuário                      | Arthur Taylor | 18/01/2023 | 18/01/2023 |  João Lucas   |
|                          Verificação - Cenários                          |    Thiago     | 15/01/2023 | 16/01/2023 |      Ana      |
|                    Verificação - Metas de Usabilidade                    |    Eduardo    | 17/01/2023 | 18/01/2023 | Arthur Taylor |
|               Verificação - Caracteristicas da Plataforma                | Arthur Taylor | 17/01/2023 | 18/01/2023 |      Ana      |
|                       Verificação - Guia de Estilo                       |    Eduardo    | 17/01/2023 | 18/01/2023 |  João Lucas   |
|       Verificação - Planejamento da Avaliação da Análise de Tarefa       |  Pedro Lucas  | 16/01/2023 | 17/01/2023 |    Thiago     |
| Verificação - Planejamento do Relato de Resultados da Análise de Tarefa  |  Pedro Lucas  | 18/01/2023 | 18/01/2023 |    Thiago     |
|              Verificação - Avaliação da Analise de Tarefas               |  Pedro Lucas  | 18/01/2023 | 18/01/2023 |    Thiago     |
|        Verificação - Relato dos Resultados Da Analise de Tarefas         |  Pedro Lucas  | 16/01/2023 | 17/01/2023 |    Thiago     |
|          Verificação - Planejamento da Avaliação do Storyboard           |  João Lucas   | 16/01/2023 | 17/01/2023 |  Pedro Lucas  |
|                  Verificação - Plan. Relato Storyboard                   |  João Lucas   | 16/01/2023 | 17/01/2023 |    Eduardo    |
|                  Verificação - Avaliação do Storyboard                   |  João Lucas   | 16/01/2023 | 17/01/2023 |  Pedro Lucas  |
|            Verificação - Relato dos Resultados do Storyboard             |  João Lucas   | 18/01/2023 | 18/01/2023 |  Pedro Lucas  |
|      Verificação - Planejamento da Avaliação do Prototipo de Papel       | Arthur Taylor | 18/01/2023 | 18/01/2023 |  João Lucas   |
| Verificação - Planejamento do Relato de Resultados do Prototipo de Papel | Arthur Taylor | 18/01/2023 | 18/01/2023 |  João Lucas   |
|        Verificação - Relato dos Resultados do Prototipo de Papel         | Arthur Taylor | 18/01/2023 | 18/01/2023 |  João Lucas   |
|                Verificação - Plan. Avaliação Prot. Alta.                 |  João Lucas   | 16/01/2023 | 17/01/2023 |    Eduardo    |
|                  Verificação - Plan. Relato Prot. Alta.                  |  João Lucas   | 16/01/2023 | 17/01/2023 |    Eduardo    |

*Tabela 14 - Tarefas executadas para a Etapa 7*<br><br>

E para representar melhor cada etapa da Execução do projeto foi realizada uma apresentação, com o grupo apresentando os principais artefatos de cada apresentação, esses videos podem ser encontrados a seguir:

<center>

| Etapa |                   Video                   |
| :---: | :---------------------------------------: |
|  1ª   | [Link aqui](https://youtu.be/fPk5NnAmyGs) |
|  2ª   | [Link aqui](https://youtu.be/GDX784RFX-8) |
|  3ª   | [Link aqui](https://youtu.be/S741_WSpXfQ) |
|  4ª   | [Link aqui](https://youtu.be/AFbbv57W1wM) |
|  5ª   | [Link aqui](https://youtu.be/qlIrAinpoTk) |
|  6ª   | [Link aqui](https://youtu.be/oYBB8K6VYdk) |
|  7ª   | [Link aqui](https://youtu.be/BoS_l0CFmos) |
|  8ª   | [Link aqui](https://youtu.be/wzy8QC-K0A4) |

*Tabela 15 - Lista das gravações realizadas*
</center>


## <a>Ferramentas</a>

Na tabela a seguir pode ser encontrada as ferramentas utilizadas durante o projeto e suas principais funções:
<center>

|                                               Logo                                               |    Nome da ferramenta     |                Etapa                |                                            Utilidade                                             |
| :----------------------------------------------------------------------------------------------: | :-----------------------: | :---------------------------------: | :----------------------------------------------------------------------------------------------: |
|        <img src="./../../assets/ferramentasLogo/docs.svg" width="100" height="100"></img>        |    <a>Google Docs</a>     |           Todo o projeto            | Utilizado para fazer o planejamento e elaboração de diversos documentos relacionados ao projeto. |
|       <img src="./../../assets/ferramentasLogo/chrome.svg" width="100" height="100"></img>       |   <a>Google Chrome</a>    |           Todo o projeto            |    Um dos navegadores utilizados para avaliar os sites e ter acesso às diversas ferramentas.     |
|       <img src="./../../assets/ferramentasLogo/github.svg" width="100" height="100"></img>       |       <a>GitHub</a>       |           Todo o projeto            |                      Utilizado para trabalhar com o projeto da disciplina.                       |
|  <img src="./../../assets/ferramentasLogo/microsoft-teams.svg" width="100" height="100"></img>   |  <a>Microsoft Teams</a>   |           Todo o projeto            |          Local de trabalho, usado principalmente para as reuniões síncronas da equipe.           |
|      <img src="./../../assets/ferramentasLogo/youtube.svg" width="100" height="100"></img>       |      <a>YouTube</a>       |           Todo o projeto            |     Utilizado para compartilhar apresentações e disponibilizar as reuniões para o professor.     |
| <img src="./../../assets/ferramentasLogo/visual-studio-code.svg" width="100" height="100"></img> | <a>Visual Studio Code</a> |           Todo o projeto            |                 Ferramenta de programação, utilizada para montar o github pages.                 |
|     <img src="./../../assets/ferramentasLogo/lucidchart.png" width="100" height="100"></img>     |    <a>Lucid Chart</a>     |         Análise de Tarefas          |                      Ferramenta utilizada para construir alguns diagramas.                       |
|       <img src="./../../assets/ferramentasLogo/figma.svg" width="100" height="100"></img>        |       <a>Figma</a>        | Design, Avaliação e Desenvolvimento |                   Utilizado para trabalhar com protótipos de alta fidelidade.                    |

*Tabela 16 - Lista de ferramentas utilizadas*
</center>

## <a>Técnicas</a>

### <a>Planejamento</a>
Dentro do planejamento o grupo seguiu alguns passos para iniciarmos os trabalhos com relação ao Simples Nacional, a primeira etapa foi analisar alguns Sites e definir algumas técnicas que seriam utilizadas ao longo do projeto e primeiras técnicas definidas pela equipe foram o [Scrum](../Planejamento/Metodologia/#sprints) e seguir o ciclo de vida da [Mayhew](../Planejamento/ModeloDesign/#modelo-de-design_1). Nesse primeiro momento foi feito alguns documentos que auxiliam o trabalho, como, por exemplo, [Heatmap](../Planejamento/Heatmap.md), [Roadmap](../Planejamento/Roadmap.md) e [Políticas de Trabalho](../planejamento/../Planejamento/Politicas/CodigoDeConduta.md).<br></br>
Os participantes do Planejamento foram: [Ana Luiza](https://github.com/AnHoff), [Pedro Lucas](https://github.com/PedroLSF), [João Lucas](https://github.com/HacKairos), [Thiago Oliveira](https://github.com/Thiab394), [Eduardo](https://github.com/edudsan) e [Arthur Taylor](https://github.com/Eruel6).


### <a>Análise de Requisitos</a>

Na etapa de análise de requisitos o grupo aplicou diversas técnicas para conseguir se aproximar o máximo possível das necessidades real do usuário, entre as principais técnicas utilizadas que podem ser citadas estão o [HTA](../Tarefas/Analise/#hta) e o [GOMS](/Tarefas/Analise/#goms) dentro da [Análise de tarefas](../Tarefas/Analise), [Cenários](../Tarefas/Cenario.md), [Perfil de Usuários](../Tarefas/perfilUsuario.md) e [Personas](../Tarefas/personas.md).<br></br>
Os participantes do Planejamento foram: [Ana Luiza](https://github.com/AnHoff), [Pedro Lucas](https://github.com/PedroLSF), [João Lucas](https://github.com/HacKairos), [Thiago Oliveira](https://github.com/Thiab394), [Eduardo](https://github.com/edudsan) e [Arthur Taylor](https://github.com/Eruel6).

### <a>Design, Avaliação e Desenvolvimento</a>

O trabalho de design começa assim que o perfil de requisitos é criado. Em geral, existem dois tipos de projeto: projeto conceitual e projeto físico. A primeira trata do desenvolvimento de um modelo conceitual que capte como o produto será reorientado e como ele funciona, e a segunda trata dos detalhes do projeto, como telas, estrutura do menu, ícones e gráficos. Os designs evoluem iterativamente por meio de ciclos repetidos de envolvimento do usuário. Portanto, nessa etapa foram utilizadas várias técnicas tais como a [Análise de Tarefas](../DesignAvaliacaoDesen/Nivel1/AnaliseDeTarefas/PlanejamentoAvAnaliseDeTarefas.md), [Storyboard](../DesignAvaliacaoDesen/Nivel1/Storyboard/PlanejamentoAvStoryboard.md), [Protótipo de Papel](../DesignAvaliacaoDesen/Nivel2/ProtPapel/PlanejamentoProtPapel.md),[ Protótipo de Alta fidelidade](../DesignAvaliacaoDesen/Nivel3/ProtAltaFidelidade/index.md) e [Testes Pilotos](../DesignAvaliacaoDesen/TestesPiloto/TestepilotoAnaliTarefas.md).<br></br>
Os participantes do Planejamento foram: [Ana Luiza](https://github.com/AnHoff), [Pedro Lucas](https://github.com/PedroLSF), [João Lucas](https://github.com/HacKairos), [Thiago Oliveira](https://github.com/Thiab394), [Eduardo](https://github.com/edudsan) e [Arthur Taylor](https://github.com/Eruel6).

### <a>Verificação</a>

Aqui vamos comentar um pouco da escolha do nosso método de Verificação e Validação, a fim de obter um melhor padronização e organização, foi dividido em pastas que representam as mesmas contidas no projeto. E a técnica utilizada foi de [Inspeção](../Verificacao/index/#inspecao).<br></br>
Os participantes do Planejamento foram: [Ana Luiza](https://github.com/AnHoff), [Pedro Lucas](https://github.com/PedroLSF), [João Lucas](https://github.com/HacKairos), [Thiago Oliveira](https://github.com/Thiab394), [Eduardo](https://github.com/edudsan) e [Arthur Taylor](https://github.com/Eruel6).



## <a>Artefatos</a>
A seguir estão apresentadas as tabelas referentes a cada etapa do projeto. Vale destacar que a **Etapa 6: Verificação dos Artefatos** está apresentada no tópico [V&V](#vv).

### <a>Etapa 1</a>
A tabela 17 abaixo apresenta os artefatos criados durante o projeto na **Etapa 1: Planejamento**, com o nome de seus respectivos criadores e revisores.

<center>

| Artefato                                                                                         | Criador                                                                                                                                | Revisor                                                                                                                            | Data de Finalização |
| ------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- | ------------------- |
| [Página inicial do projeto](../index.md)                                                         | [João Lucas](https://github.com/HacKairos)                                                                                             | [Thiago Oliveira](https://github.com/Thiab394)                                                                                     | 20/11/2022          |
| [Sites Analisados](../Planejamento/SitesAnalisados.md)                                           | [Ana Luiza](https://github.com/AnHoff)<br>[Pedro Lucas](https://github.com/PedroLSF)<br>[Eduardo](https://github.com/edudsan)          | [Ana Luiza](https://github.com/AnHoff)<br>[Pedro Lucas](https://github.com/PedroLSF)<br>[João Lucas](https://github.com/HacKairos) | 25/01/2023          |
| [Metodologia e Processos](../Planejamento/Metodologia.md)                                        | [Arthur Taylor](https://github.com/Eruel6)<br>[Thiago Oliveira](https://github.com/Thiab394)                                           | [Arthur Taylor](https://github.com/Eruel6)<br>[Thiago Oliveira](https://github.com/Thiab394)                                       | 25/01/2023          |
| [Modelo de Design](../Planejamento/ModeloDesign.md)                                              | [Pedro Lucas](https://github.com/PedroLSF)                                                                                             | [João Lucas](https://github.com/HacKairos)                                                                                         | 25/01/2023          |
| [Ferramentas](../Planejamento/Ferramentas.md)                                                    | [Ana Luiza](https://github.com/AnHoff)<br>[João Lucas](https://github.com/HacKairos)                                                   | [Ana Luiza](https://github.com/AnHoff)<br>[Thiago Oliveira](https://github.com/Thiab394)                                           | 25/01/2023          |
| [Heatmap](../Planejamento/Heatmap.md)                                                            | [Eduardo](https://github.com/edudsan)                                                                                                  | [Ana Luiza](https://github.com/AnHoff)                                                                                             | 25/01/2023          |
| [Roadmap](../Planejamento/Roadmap.md)                                                            | [Arthur Taylor](https://github.com/Eruel6)<br>[Thiago Oliveira](https://github.com/Thiab394)<br>[Ana Luiza](https://github.com/AnHoff) | [Arthur Taylor](https://github.com/Eruel6)<br>[Thiago Oliveira](https://github.com/Thiab394)                                       | 25/01/2023          |
| Políticas - [Código de Conduta para Colaboradores](../Planejamento/Politicas/CodigoDeConduta.md) | [João Lucas](https://github.com/HacKairos)                                                                                             | [Ana Luiza](https://github.com/AnHoff)                                                                                             | 11/11/2022          |
| Políticas - [Política de Contribuição](../Planejamento/Politicas/PolitcaDeContribuicao.md)       | [João Lucas](https://github.com/HacKairos)                                                                                             | [Ana Luiza](https://github.com/AnHoff)                                                                                             | 11/11/2022          |
| Políticas - [Política de Issue](../Planejamento/Politicas/PolitcaDeIssue.md)                     | [João Lucas](https://github.com/HacKairos)                                                                                             | [Ana Luiza](https://github.com/AnHoff)                                                                                             | 11/11/2022          |
| Políticas - [Política de Branch](../Planejamento/Politicas/PolitcaDeBranch.md)                   | [João Lucas](https://github.com/HacKairos)                                                                                             | [Pedro Lucas](https://github.com/PedroLSF)                                                                                         | 11/11/2022          |
| Políticas - [Política de Commit](../Planejamento/Politicas/PolitcaDeCommit.md)                   | [João Lucas](https://github.com/HacKairos)<br>[Ana Luiza](https://github.com/AnHoff)                                                   | [João Lucas](https://github.com/HacKairos)<br>[Ana Luiza](https://github.com/AnHoff)                                               | 23/11/2022          |
| Políticas - [Política de Pull Request](../Planejamento/Politicas/PolitcaDePR.md)                 | [João Lucas](https://github.com/HacKairos)                                                                                             | [Ana Luiza](https://github.com/AnHoff)                                                                                             | 11/11/2022          |
| Políticas - [Política de Segurança](../Planejamento/Politicas/PolitcaDeSeguranca.md)             | [João Lucas](https://github.com/HacKairos)                                                                                             | [Ana Luiza](https://github.com/AnHoff)                                                                                             | 11/11/2022          |

*Tabela 17 - Artefatos realizados durante a etapa 1*
<br><br>

</center>

### <a>Etapas 2 e 3</a>
A tabela 18 abaixo apresenta os artefatos criados durante o projeto durante a **Etapa 2: Perfil do usuário, Aspectos Éticos de Pesquisas Envolvendo Pessoas, Personas e Análise de tarefas** e a **Etapa 3: Princípios Gerais de Projeto, Metas de usabilidade, Guia de Estilo**, com o nome de seus respectivos criadores e revisores.

<center>

| Artefato                                                                 | Criador                                                                                       | Revisor                                                                                      | Data de Finalização |
| ------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | ------------------- |
| [Termo de Consentimento](../Planejamento/ModeloTermoConsentimento.md)    | [Thiago Oliveira](https://github.com/Thiab394)                                                | [João Lucas](https://github.com/HacKairos)<br>[Ana Luiza](https://github.com/AnHoff)         | 25/01/2023          |
| [Aspectos Éticos](../Planejamento/AspectosEticos.md)                     | [Thiago Oliveira](https://github.com/Thiab394)<br> [Arthur Taylor](https://github.com/Eruel6) | [Arthur Taylor](https://github.com/Eruel6)                                                   | 25/01/2023          |
| [Análise de Tarefas](../Tarefas/Analise.md)                              | [Ana Luiza](https://github.com/AnHoff)<br>[Pedro Lucas](https://github.com/PedroLSF)          | [João Lucas](https://github.com/HacKairos)<br>[Pedro Lucas](https://github.com/PedroLSF)     | 25/01/2023          |
| [Perfil de Usuários](../Tarefas/perfilUsuario.md)                        | [Pedro Lucas](https://github.com/PedroLSF)<br>[Eduardo](https://github.com/edudsan)           | [Pedro Lucas](https://github.com/PedroLSF)<br>[João Lucas](https://github.com/HacKairos)     | 25/01/2023          |
| [Personas](../Tarefas/personas.md)                                       | [João Lucas](https://github.com/HacKairos)                                                    | [Eduardo](https://github.com/edudsan)                                                        | 25/01/2023          |
| [Cenários](../Tarefas/Cenario.md)                                        | [João Lucas](https://github.com/HacKairos)<br>[Pedro Lucas](https://github.com/PedroLSF)      | [Thiago Oliveira](https://github.com/Thiab394)<br>[Pedro Lucas](https://github.com/PedroLSF) | 25/01/2023          |
| [Metas de Usabilidade](../Tarefas/MetasUsabilidade.md)                   | [João Lucas](https://github.com/HacKairos)                                                    | [Eduardo](https://github.com/edudsan)                                                        | 25/01/2023          |
| [Características da Plataforma](../Tarefas/CaracteristicasPlataforma.md) | [João Lucas](https://github.com/HacKairos)                                                    | [Eduardo](https://github.com/edudsan)                                                        | 25/01/2023          |
| [Princípios Gerais](../Tarefas/PrincipiosGerais.md)                      | [Pedro Lucas](https://github.com/PedroLSF)<br>[Eduardo](https://github.com/edudsan)           | [Ana Luiza](https://github.com/AnHoff)<br>[Arthur Taylor](https://github.com/Eruel6)         | 25/01/2023          |
| [Guia de Estilo](../Tarefas/GuiaDeEstilo.md)                             | [Ana Luiza](https://github.com/AnHoff)<br>[Arthur Taylor](https://github.com/Eruel6)          | [Eduardo](https://github.com/edudsan)<br>[Thiago Oliveira](https://github.com/Thiab394)      | 25/01/2023          |

*Tabela 18 - Artefatos realizados durante as etapas 2 e 3*
<br><br>

</center>

### <a>Etapa 4</a>
A tabela 19 abaixo apresenta os artefatos criados durante o projeto durante a **Etapa 4: Planejamento da Avaliação do Storyboard e Análise de tarefas, planejamento do relato dos resultados da avaliação do Storyboard e o planejamento do relato dos resultados da avaliação do Análise de tarefas**, com o nome de seus respectivos criadores e revisores.

<center>

| Artefato                                                                                                                                       | Criador                                                                                                                               | Revisor                                                                                                                           | Data de Finalização |
| ---------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- | ------------------- |
| [Planejamento da Avaliação da Análise de Tarefas](../DesignAvaliacaoDesen/Nivel1/AnaliseDeTarefas/PlanejamentoAvAnaliseDeTarefas.md)           | [Arthur Taylor](https://github.com/Eruel6)<br>[Pedro Lucas](https://github.com/PedroLSF)                                              | [Arthur Taylor](https://github.com/Eruel6)<br>[Thiago Oliveira](https://github.com/Thiab394)                                      | 25/01/2023          |
| [Planejamento do Relato do Resultados da Análise de Tarefas](../DesignAvaliacaoDesen/Nivel1/AnaliseDeTarefas/PlanejamentoResAnaliseTarefas.md) | [Thiago Oliveira](https://github.com/Thiab394)                                                                                        | [João Lucas](https://github.com/HacKairos)                                                                                        | 25/01/2023          |
| [Planejamento da Avaliação do Storyboard](../DesignAvaliacaoDesen/Nivel1/Storyboard/PlanejamentoAvStoryboard.md)                               | [Ana Luiza](https://github.com/AnHoff)<br>[Eduardo](https://github.com/edudsan)                                                       | [João Lucas](https://github.com/HacKairos)<br>[Eduardo](https://github.com/edudsan)<br>[Arthur Taylor](https://github.com/Eruel6) | 25/01/2023          |
| [Planejamento do Relato do Resultados do Storyboard](../DesignAvaliacaoDesen/Nivel1/Storyboard/PlanejamentoRelatoResuStoryboard.md)            | [João Lucas](https://github.com/HacKairos)<br>[Ana Luiza](https://github.com/AnHoff)                                                  | [Ana Luiza](https://github.com/AnHoff)<br>[Eduardo](https://github.com/edudsan)                                                   | 25/01/2023          |
| [Teste Piloto - Análise de Tarefas](../DesignAvaliacaoDesen/TestesPiloto/TestepilotoAnaliTarefas.md)                                           | [Pedro Lucas](https://github.com/PedroLSF)<br>[Thiago Oliveira](https://github.com/Thiab394)<br>[Eduardo](https://github.com/edudsan) | [João Lucas](https://github.com/HacKairos)                                                                                        | 25/01/2023          |
| [Teste Piloto - Storyboard](../DesignAvaliacaoDesen/TestesPiloto/TestePilotoStoryboard.md)                                                     | [Pedro Lucas](https://github.com/PedroLSF)<br>[Thiago Oliveira](https://github.com/Thiab394)<br>[Eduardo](https://github.com/edudsan) | [João Lucas](https://github.com/HacKairos)                                                                                        | 25/01/2023          |

*Tabela 19 - Artefatos realizados durante a etapa 4*
<br><br>

</center>

### <a>Etapa 5</a>
A tabela 20 abaixo apresenta os artefatos criados durante o projeto durante a **Etapa 5: Relato dos resultados do Story Board e da Análise de tarefas, o Planejamento da Avaliação do Protótipo de Papel e do planejamento do relato dos resultados da avaliação do Protótipo de Papel**, com o nome de seus respectivos criadores e revisores.

<center>

| Artefato                                                                                                                                  | Criador                                                                                                                       | Revisor                                                                              | Data de Finalização |
| ----------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ | ------------------- |
| [Planejamento da Avaliação do Protótipo de Papel](../DesignAvaliacaoDesen/Nivel2/ProtPapel/PlanejamentoProtPapel.md)                      | [Ana Luiza](https://github.com/AnHoff)                                                                                        | [Thiago Oliveira](https://github.com/Thiab394)                                       | 25/01/2023          |
| [Planejamento do Relato do Resultados do Protótipo de Papel](../DesignAvaliacaoDesen/Nivel2/ProtPapel/PlanejamentoRelatoResuProtPapel.md) | [João Lucas](https://github.com/HacKairos)<br>[Ana Luiza](https://github.com/AnHoff)<br>[Eduardo](https://github.com/edudsan) | [Thiago Oliveira](https://github.com/Thiab394)                                       | 25/01/2023          |
| [Resultados da Análise de Tarefas](../DesignAvaliacaoDesen/Nivel1/AnaliseDeTarefas/RelatoResultadosAnaliseTarefas.md)                     | [Pedro Lucas](https://github.com/PedroLSF)<br>[Thiago Oliveira](https://github.com/Thiab394)                                  | [João Lucas](https://github.com/HacKairos)                                           | 25/01/2023          |
| [Resultados do Storyboard](../DesignAvaliacaoDesen/Nivel1/Storyboard/RelatoResultadosStoryboard.md)                                       | [Pedro Lucas](https://github.com/PedroLSF)<br>[Thiago Oliveira](https://github.com/Thiab394)                                  | [Ana Luiza](https://github.com/AnHoff)<br>[João Lucas](https://github.com/HacKairos) | 25/01/2023          |
| [Termo de Consentimento - Análise de Tarefas](../DesignAvaliacaoDesen/TermosConsentimento/TermoConsentimentoAnaliseTarefas.md)            | [Thiago Oliveira](https://github.com/Thiab394)                                                                                | [João Lucas](https://github.com/HacKairos)                                           | 25/01/2023          |
| [Termo de Consentimento - Storyboard](../DesignAvaliacaoDesen/TermosConsentimento/TermoConsentimentoStoryboard.md)                        | [Thiago Oliveira](https://github.com/Thiab394)                                                                                | [João Lucas](https://github.com/HacKairos)                                           | 25/01/2023          |
| [Verificação da 1ª Etapa](../DesignAvaliacaoDesen/Nivel1/VerificacaoEtapa1.md)                                                            | [Pedro Lucas](https://github.com/PedroLSF)<br>[Thiago Oliveira](https://github.com/Thiab394)                                  | [Ana Luiza](https://github.com/AnHoff)<br>[João Lucas](https://github.com/HacKairos) | 25/01/2023          |
| [Teste Piloto - Protótipo de Papel](../DesignAvaliacaoDesen/TestesPiloto/TestePilotoProtPapel.md)                                         | [Thiago Oliveira](https://github.com/Thiab394)<br>[Eduardo](https://github.com/edudsan)                                       | [João Lucas](https://github.com/HacKairos)                                           | 25/01/2023          |

*Tabela 20 - Artefatos realizados durante a etapa 5*
<br><br>

</center>

### <a>Etapa 7</a>
A tabela 21 abaixo apresenta os artefatos criados durante o projeto durante a **Etapa 7: Relato dos resultados do Protótipo de Papel, o Planejamento da Avaliação do protótipo de alta fidelidade e o Planejamento do relato dos resultados da avaliação do protótipo de alta fidelidade**, com o nome de seus respectivos criadores e revisores.

<center>

| Artefato                                                                                                                                                    | Criador                                                                                                                                    | Revisor                                        | Data de Finalização |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------- | ------------------- |
| [Planejamento da Avaliação do Protótipo de Alta Fidelidade](../DesignAvaliacaoDesen/Nivel3/ProtAltaFidelidade/PlanejamentoProtAlta.md)                      | [Ana Luiza](https://github.com/AnHoff)                                                                                                     | [Eduardo](https://github.com/edudsan)          | 25/01/2023          |
| [Planejamento do Relato do Resultados do Protótipo de Alta Fidelidade](../DesignAvaliacaoDesen/Nivel3/ProtAltaFidelidade/PlanejamentoRelatoResuProtAlta.md) | [João Lucas](https://github.com/HacKairos)                                                                                                 | [Thiago Oliveira](https://github.com/Thiab394) | 25/01/2023          |
| [Teste Piloto - Protótipo de Alta Fidelidade](../DesignAvaliacaoDesen/TestesPiloto/TestePilotoProtAltaFidelidade.md)                                        | [Eduardo](https://github.com/edudsan)                                                                                                      | [João Lucas](https://github.com/HacKairos)     | 25/01/2023          |
| [Resultados do Protótipo de Papel](../DesignAvaliacaoDesen/Nivel2/ProtPapel/RelatoResultadosProtPapel.md)                                                   | [Pedro Lucas](https://github.com/PedroLSF)<br>[João Lucas](https://github.com/HacKairos)<br>[Thiago Oliveira](https://github.com/Thiab394) | [Arthur Taylor](https://github.com/Eruel6)     | 11/01/2023          |
| [Termo de Consentimento - Protótipo de Papel](../DesignAvaliacaoDesen/TermosConsentimento/TermoConsentimentoProtPapel.md)                                   | [Thiago Oliveira](https://github.com/Thiab394)                                                                                             | [João Lucas](https://github.com/HacKairos)     | 25/01/2023          |

*Tabela 21 - Artefatos realizados durante a etapa 7*
<br><br>

</center>

### <a>Etapa 8</a>
A tabela 22 abaixo apresenta os artefatos criados durante o projeto durante a **Etapa 8: Relato dos resultados da avaliação do protótipo de alta fidelidade**, com o nome de seus respectivos criadores e revisores.

<center>

| Artefato                                                                                                              | Criador                                                                                                                                                                              | Revisor                                    | Data de Finalização |
| --------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------ | ------------------- |
| [Protótipo de Alta Fidelidade](../DesignAvaliacaoDesen/Nivel3/ProtAltaFidelidade/index.md)                            | [Ana Luiza](https://github.com/AnHoff)                                                                                                                                               | [João Lucas](https://github.com/HacKairos) | 25/01/2023          |
| [Resultados do Protótipo de Alta Fidelidade](../DesignAvaliacaoDesen/Nivel3/ProtAltaFidelidade/RelatoResProtAlta.md)  | [Pedro Lucas](https://github.com/PedroLSF)<br>[Arthur Taylor](https://github.com/Eruel6)<br>[Thiago Oliveira](https://github.com/Thiab394)<br>[Ana Luiza](https://github.com/AnHoff) | [Eduardo](https://github.com/edudsan)      | 25/01/2023          |
| [Termo de Consentimento - Alta Fidelidade](../DesignAvaliacaoDesen/TermosConsentimento/TermoConsentimentoProtAlta.md) | [Thiago Oliveira](https://github.com/Thiab394)                                                                                                                                       | [João Lucas](https://github.com/HacKairos) | 25/01/2023          |

*Tabela 22 - Artefatos realizados durante a etapa 8*
<br><br>

**Total de artefatos:** 68*.

*Os artefatos [V&V](#vv) estão inclusos na contagem.

</center>

### <a>Revisão Final</a>
A revisão final visa corrigir ocasionais erros em legendas e imagens, erros de ortografia e afins. Ela foi realizada por [João Lucas](https://github.com/HacKairos) e revisada por [Thiago Oliveira](https://github.com/Thiab394), [Ana Luiza](https://github.com/AnHoff) e [Pedro Lucas](https://github.com/PedroLSF) no dia 25/01/2023.

### <a>Contagem Individual</a>
A tabela 23 abaixo apresenta a quantidade total de artefatos criados e revisados por cada integrante.

<center>

| Integrante                                     | Criados | Revisados |
| ---------------------------------------------- | ------- | --------- |
| [Ana Luiza](https://github.com/AnHoff)         | 17      | 17        |
| [Arthur Taylor](https://github.com/Eruel6)     | 11      | 9         |
| [Eduardo](https://github.com/edudsan)          | 12      | 10        |
| [João Lucas](https://github.com/HacKairos)     | 22      | 26        |
| [Pedro Lucas](https://github.com/PedroLSF)     | 18      | 8         |
| [Thiago Oliveira](https://github.com/Thiab394) | 18      | 12        |

*Tabela 23 - Artefatos por integrante*
<br><br>

</center>

### <a>Comentários</a>

* O número total de artefatos criados é inferior à soma dos artefatos criados por cada integrante. Isso se deve ao fato de que diversos integrantes participaram da criação de um mesmo artefato;
* Os integrantes [Pedro Lucas](https://github.com/PedroLSF) e [Arthur Taylor](https://github.com/Eruel6) foram responsáveis por realizar as gravações com os usuários;
* O integrante [Arthur Taylor](https://github.com/Eruel6) foi o responsável por criar as atas de reunião e apresentações;
* O questionário sobre o perfil do usuário foi criado e divulgado pelo integrante [Eduardo](https://github.com/edudsan).

## <a>Protótipos</a>
### <a>Nível 1</a>

#### <a>Análise de Tarefas</a>
A Análise de tarefa se divide em 3 documentos principais, sendo eles:

* [Planejamento da Avaliação](https://interacao-humano-computador.github.io/2022.2-SimplesNacional/DesignAvaliacaoDesen/Nivel1/Storyboard/PlanejamentoAvStoryboard/)
* [Planejamento dos Resultados](https://interacao-humano-computador.github.io/2022.2-SimplesNacional/DesignAvaliacaoDesen/Nivel1/AnaliseDeTarefas/PlanejamentoResAnaliseTarefas/)
* [Relato dos Resultados](https://interacao-humano-computador.github.io/2022.2-SimplesNacional/DesignAvaliacaoDesen/Nivel1/AnaliseDeTarefas/RelatoResultadosAnaliseTarefas/)

#### <a>Storyboard</a>
Assim como a Análise de tarefa, o storyboard se divide em 3 documentos principais, sendo eles:

* [Planejamento da Avaliação](https://interacao-humano-computador.github.io/2022.2-SimplesNacional/DesignAvaliacaoDesen/Nivel1/AnaliseDeTarefas/PlanejamentoAvAnaliseDeTarefas/)
* [Planejamento dos Resultados](https://interacao-humano-computador.github.io/2022.2-SimplesNacional/DesignAvaliacaoDesen/Nivel1/Storyboard/PlanejamentoRelatoResuStoryboard/)
* [Relato dos Resultados](https://interacao-humano-computador.github.io/2022.2-SimplesNacional/DesignAvaliacaoDesen/Nivel1/Storyboard/RelatoResultadosStoryboard/)


Depois de identificar os usuários do Simples Nacional, o grupo foi atrás de desenvolver a Análise de Tarefa para verificarmos se atendia com o planejado. Com isso, criamos a uma sequência de atividades que representa o caminho do nosso usuário nativo digital e não nativo digital. Por fim, tivemos as entrevistas que desenvolveram um debates e questionários a fim de entender o quão próximo da realidade nosso storyboard está e se ele condiz com o que deve ser feito.

### <a>Nível 2</a>
#### <a>Protótipo de Papel</a>
Agora temos outros 3 documentos similares:

* [Planejamento da Avaliação](https://interacao-humano-computador.github.io/2022.2-SimplesNacional/DesignAvaliacaoDesen/Nivel2/ProtPapel/PlanejamentoProtPapel/)
* [Planejamento dos Resultados](https://interacao-humano-computador.github.io/2022.2-SimplesNacional/DesignAvaliacaoDesen/Nivel2/ProtPapel/PlanejamentoRelatoResuProtPapel/)
* [Relato dos Resultados](https://interacao-humano-computador.github.io/2022.2-SimplesNacional/DesignAvaliacaoDesen/Nivel2/ProtPapel/RelatoResultadosProtPapel/)

Depois de algumas entrevistas, finalmente podemos entender o que difere do caminho ideal para o real. Sabemos quais são as dores dos nosso usuários e precisamos descobrir como resolver, por isso vamos fazer um primeiro protótipo resolvendo essas dores e depois corrigir alguns pontos, aproximando o máximo do ideal solicitado.

### <a>Nível 3</a>
#### <a>Protótipo de Alta Fidelidade</a>
Os últimos 3 documentos:

* [Planejamento da Avaliação](https://interacao-humano-computador.github.io/2022.2-SimplesNacional/DesignAvaliacaoDesen/Nivel3/ProtAltaFidelidade/PlanejamentoProtAlta/)
* [Planejamento dos Resultados](https://interacao-humano-computador.github.io/2022.2-SimplesNacional/DesignAvaliacaoDesen/Nivel3/ProtAltaFidelidade/PlanejamentoRelatoResuProtAlta/)
* [Relato dos Resultados](https://interacao-humano-computador.github.io/2022.2-SimplesNacional/DesignAvaliacaoDesen/Nivel3/ProtAltaFidelidade/RelatoResProtAlta/)

Por fim, podemos mostrar a ideia final para nossos usuários, deixar que eles executem as nossas telas e compare com o atual. Portanto, eles podem avaliar se tudo que foi solicitado consta. E assim como todos os outros documentos, temos o relato dos resultados que demonstra o que irá entrar no site oficial como alteração.

## <a>Resultados</a>
Acreditamos que o objetivo primordial desse projeto, aplicar na prática o que foi aprendido em sala de aula, foi alcançado de diferentes formas. No início, os resultados não foram satisfatórios, deixando muito a desejar. As técnicas e conceitos foram aplicados de forma incorreta e, com isso, o trabalho iniciou "com o pé esquerdo". Apesar desse fato, o grupo conseguiu se reorganizar e melhorar muito a qualidade dos artefatos que estavam sendo elaborados a partir das [Etapas 3 e 4](#etapas-3-e-4-modelagem), sem deixar de lado as melhorias a serem realizadas nos artefatos iniciais. Com isso em mente, pode-se afirmar que a aplicação de técnicas e conceitos aprendidos em sala foi realizada com sucesso durante o projeto.

O outro objetivo do projeto, não menos importante que o primeiro apresentado, era analisar um aplicativo. O MEI foi escolhido após a elaboração e análise dos diferentes [Rich Pictures](../Planejamento/SitesAnalisados.md) elaborados pelos integrantes do grupo. Após a escolha do aplicativo, foi possível iniciar a aplicação dos conceitos e ténicas aprendidos, por meio da realização das fases do projeto.

Todos os integrantes presentes nas tabelas de [Artefatos](#artefatos) participaram ativamente do projeto. Seja por meio da elaboração direta de artefatos ou da realização de pesquisas e entrevistas com os usuários, todos participaram dando o melhor de si. Todos concordam: houve grande desenvolvimento de softskills. As mais notáveis foram:

* Organização;
* Planejamento;
* Resiliência.

A seguir, confira um resumo dos resultados mais notáveis do projeto.

### <a>Perfil do Usuário</a>
O [Perfil do Usuário](../Tarefas/perfilUsuario.md) identificado pelo grupo é semelhante ao perfil encontrado em estudos realizados por outros pesquisadores [2]. Esse fato dá suporte aos dados obtidos pelo grupo, que são compatíveis com os obtidos por meio de pesquisas oficiais de grandes empresas.

### <a>Protótipo de Alta Fidelidade</a>
O [Protótipo de Alta Fidelidade](../DesignAvaliacaoDesen/Nivel3/ProtAltaFidelidade/index.md) foi elaborado pelo integrante [João Lucas](https://github.com/HacKairos), em colaboração com [Arthur Taylor](https://github.com/Eruel6), e aprovado por todo o grupo (Ana, Pedro, Thiago e Eduardo). Sua criação visava melhorar pontos críticos, como a segurança do aplicativo, a partir do resultado da análise e modelagem de requisitos. Confira aqui o [Protótipo]([https://www.figma.com/proto/YVsTmRLQiocQb1d258RRZE/MEI?node-id=1%3A11&starting-point-node-id=1%3A9](https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Fproto%2F9MHpLCsADuC4ZvVwzR6Dbj%2FUntitled%3Fnode-id%3D6%253A2%26scaling%3Dcontain%26page-id%3D0%253A1%26starting-point-node-id%3D6%253A2%26show-proto-sidebar%3D1)).

## <a>V&V</a>
### <a>Verificação</a>
Para realizar a verificação dos artefatos do projeto, foram escolhidas pessoas não envolvidas na criação de cada artefato. Com isso, buscava-se encontrar erros não percebidos pelo criador e/ou revisor do mesmo até então.

A metodologia adotada foi a [Inspeção](../Verificacao/#inspecao) com o auxílio de [Checklists](../Verificação/#metodo-de-avaliacao). Na tabela 24 abaixo, Autor representa o criador da checklist e Revisor o responsável por aplicar a inspeção.

<center>

| Artefato                                                                                                                                   | Autor                                          | Revisor                                                                                  | Data de Aplicação |
| ------------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------- | ---------------------------------------------------------------------------------------- | ----------------- |
| [Sites Analisados](../Verificacao/Planejamento/VerificacaoSitesAnalisados.md)                                                              | [Pedro Lucas](https://github.com/PedroLSF)     | [João Lucas](https://github.com/HacKairos)                                               | 25/01/2023        |
| [Termo de Consentimento](../Verificacao/Planejamento/termoConsentimento.md)                                                                | [Ana Luiza](https://github.com/AnHoff)         | [Pedro Lucas](https://github.com/PedroLSF)                                               | 25/01/2023        |
| [Modelo de Design](../Verificacao/Planejamento/modeloDesign.md)                                                                            | [Ana Luiza](https://github.com/AnHoff)         | [Pedro Lucas](https://github.com/PedroLSF)                                               | 25/01/2023        |
| [Aspectos Éticos](../Verificacao/Planejamento/aspectosEticos.md)                                                                           | [Ana Luiza](https://github.com/AnHoff)         | [João Lucas](https://github.com/HacKairos)<br>[Pedro Lucas](https://github.com/PedroLSF) | 25/01/2023        |
| [Princípios Gerais](../Verificacao/Tarefas/principiosGerais.md)                                                                            | [Ana Luiza](https://github.com/AnHoff)         | [Arthur Taylor](https://github.com/Eruel6)                                               | 25/01/2023        |
| [Perfil de Usuário](../Verificacao/Tarefas/VerificacaoPerfilUsuario.md)                                                                    | [Arthur Taylor](https://github.com/Eruel6)     | [João Lucas](https://github.com/HacKairos)                                               | 25/01/2023        |
| [Análise de Tarefas](../Verificacao/Tarefas/AnaliseDeTarefas.md)                                                                           | [João Lucas](https://github.com/HacKairos)     | [Ana Luiza](https://github.com/AnHoff)                                                   | 25/01/2023        |
| [Cenários](../Verificacao/Tarefas/VerificacaoCenarios.md)                                                                                  | [Thiago Oliveira](https://github.com/Thiab394) | [Ana Luiza](https://github.com/AnHoff)                                                   | 25/01/2023        |
| [Metas de Usabilidade](../Verificacao/Tarefas/verificacaoMetasDeUsabilidade.md)                                                            | [Eduardo](https://github.com/edudsan)          | [Arthur Taylor](https://github.com/Eruel6)                                               | 25/01/2023        |
| [Características da Plataforma](../Verificacao/Tarefas/VerificacaoCaracteristicasPlataforma.md)                                            | [Arthur Taylor](https://github.com/Eruel6)     | [Ana Luiza](https://github.com/AnHoff)                                                   | 25/01/2023        |
| [Guia de Estilo](../Verificacao/Tarefas/verificacaoGuiaDeEstilo.md)                                                                        | [Eduardo](https://github.com/edudsan)          | [João Lucas](https://github.com/HacKairos)                                               | 25/01/2023        |
| Análise de Tarefas - [Planejamento da Avaliação](../Verificacao/DesignAvaliacaoDesen/Nivel1/AnalisedeTarefa/VerificacaoPlanAval.md)        | [Pedro Lucas](https://github.com/PedroLSF)     | [Thiago Oliveira](https://github.com/Thiab394)                                           | 25/01/2023        |
| Análise de Tarefas - [Planejamento do Relato](../Verificacao/DesignAvaliacaoDesen/Nivel1/AnalisedeTarefa/VerificacaoPlanejamentoRelato.md) | [Pedro Lucas](https://github.com/PedroLSF)     | [Thiago Oliveira](https://github.com/Thiab394)                                           | 25/01/2023        |
| Análise de Tarefas - [Relato dos Resultados](../Verificacao/DesignAvaliacaoDesen/Nivel1/AnalisedeTarefa/VerificacaoRelato.md)              | [Pedro Lucas](https://github.com/PedroLSF)     | [Thiago Oliveira](https://github.com/Thiab394)                                           | 25/01/2023        |
| Storyboard - [Planejamento da Avaliação](../Verificacao/DesignAvaliacaoDesen/Nivel1/Storyboard/VerficacaoPlanejamentoAval.md)              | [João Lucas](https://github.com/HacKairos)     | [Pedro Lucas](https://github.com/PedroLSF)                                               | 25/01/2023        |
| Storyboard - [Planejamento do Relato](../Verificacao/DesignAvaliacaoDesen/Nivel1/Storyboard/VerificacaoPlanejamentoRelato.md)              | [João Lucas](https://github.com/HacKairos)     | [Eduardo](https://github.com/edudsan)                                                    | 25/01/2023        |
| Storyboard - [Relato dos Resultados](../Verificacao/DesignAvaliacaoDesen/Nivel1/Storyboard/VerificacaoRelato.md)                           | [João Lucas](https://github.com/HacKairos)     | [Pedro Lucas](https://github.com/PedroLSF)                                               | 25/01/2023        |
| Protótipo de Papel - [Planejamento da Avaliação](../Verificacao/DesignAvaliacaoDesen/Nivel2/VerficacaoPlanejamentoAval.md)                 | [Arthur Taylor](https://github.com/Eruel6)     | [João Lucas](https://github.com/HacKairos)                                               | 25/01/2023        |
| Protótipo de Papel - [Planejamento do Relato](../Verificacao/DesignAvaliacaoDesen/Nivel2/VerificacaoPlanejamentoRelato.md)                 | [Arthur Taylor](https://github.com/Eruel6)     | [João Lucas](https://github.com/HacKairos)                                               | 25/01/2023        |
| Protótipo de Papel - [Relato dos Resultados](../Verificacao/DesignAvaliacaoDesen/Nivel2/VerificacaoRelato.md)                              | [Arthur Taylor](https://github.com/Eruel6)     | [João Lucas](https://github.com/HacKairos)                                               | 25/01/2023        |
| Protótipo de Alta Fidelidade - [Planejamento da Avaliação](../Verificacao/DesignAvaliacaoDesen/Nivel3/VerificacaoPlanejamentoAvaliacao.md) | [João Lucas](https://github.com/HacKairos)     | [Eduardo](https://github.com/edudsan)                                                    | 25/01/2023        |
| Protótipo de Alta Fidelidade - [Planejamento do Relato](../Verificacao/DesignAvaliacaoDesen/Nivel3/VerificacaoPlanejamentoRelato.md)       | [João Lucas](https://github.com/HacKairos)     | [Eduardo](https://github.com/edudsan)                                                    | 25/01/2023        |

*Tabela 24 - Artefatos de verificação*
<br><br>

</center>

### <a>Validação</a>
A validação foi realizada por diversos usuários durante o desenvolvimento do projeto. Conforme o grupo desenvolvia artefatos, havia a realização de entrevistas com o usuário, visando saber se o trabalho produzido correspondia com a expectativa do usuário e/ou realidade.

## <a>Facilidades e Dificuldades</a>
### <a>Ana</a>
"Acredito que a maior dificuldade do projeto tenha sido entrar em contato com os usuários e engajar comunidades do Facebook com o preenchimento de um questionário sobre o perfil dos usuários. Lidar com a equipe em certos momentos também é difícil, mas no final acaba sendo recompensador! Gostei de trabalhar neste projeto e acredito que aplicarei o que aprendi em futuros projetos."

### <a>Arthur</a>
"Positivos: A oportunidade de aprender a matéria de forma pratica durante a execução do projeto, a grande quantidade de apresentações que propiciava vários fedbacks para a melhora do projeto e nos possibilitou uma melhora contínua do projeto.Negativos: Devido ao semestre reduzido as entregas acabaram ficando um pouco corridas algumas vezes."

### <a>Eduardo</a>
"A experiência que tive sobre a disciplina foi o trabalho em grupo, onde todos se ajudavam e a metodologia de ensino ministrada pelo professor. Pois ele auxiliava após cada apresentação todos os grupos com comentários do que achou mais interessante em cada grupo e que os demais grupos poderiam seguir. A dificultade encontrada foi com o cronograma, pois acredito que o tempo disponível no semestre não colaborou para que conseguimos desenvolver com mais calma"

### <a>João</a>
"Plano de ensino bem elicitado, muitas listas de exercicios, materiais de apoio bons para consulta e estudo foram essenciais para a realização do projeto."

### <a>Pedro</a>
"Pontos Positivos: Acredito que foi um projeto que demonstrou de forma fiel todo trabalho de documentação e levantamentos de requisitos. Demonstrou a importância desse contato.O Grupo foi bem importante para o desenvolvimento do trabalho.Pontos Negativos:Acredito que seja uma quantidade desnecessária de atividades.Apesar de ser para aprendermos acredito que possamos usar menos técnicas para um mesmo objetivo"

### <a>Thiago</a>
Facilidade:
Ter uma série de projetos anteoriores, sendo deles alguns bons que serviram de exemplo,
um dos monitores bem presente e explicando bem a disciplina. Dificulade:
Poucos projetos anteriores bons, fazendo com que tenha uma certa dificuldade de se basear
nos mesmos,alta quantidade de conteudo e tarefas no começo pro meio do semestre, confusão
em muitas entregas por não ter explicitado tudo necessario para a mesma, fazendo com que
não entregassemos o "esperado" pelo professor, entregas seguidas com prazo extremamente
curto entre elas. porem apesar de tudo achei uma boa disciplina, deu para aprender realmente algumas das
mecanicas de IHC(Trocar pro req aqui), e é isso que realmente importa.

## <a>BIbliografia</a>
[1] 2022.1-YouTube. Disponível em: https://requisitos-de-software.github.io/2022.1-Youtube/apresentacao-final/. Acesso em: 27 de Janeiro de 2023.
