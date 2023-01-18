# Cenários

## <a>Histórico de Versão</a>
|Data|Data Prevista de Revisão|Versão|Descrição|Autor|Revisor|
| :----------: |:-----------:| :------: | :-----------: | :---------: |:---------: |
|09/12/2022|10/12/2022|1.0|Criação do documento| [João Lucas](https://github.com/HacKairos) | [Pedro Lucas](https://github.com/PedroLSF) |
|18/01/2023|20/12/2022|1.1|Adição dos Cenários que estavam com erros| [Pedro Lucas](https://github.com/PedroLSF) | |

## <a>Introdução</a>
Cenários são representações do contexto do sistema por meio de histórias de pessoas realizando atividades e são específicos e ricos em detalhes de contexto de uso do aplicativo, incluindo usuários, processos e dados reais ou potenciais. , texto ou narrativa visual. Os cenários não são apenas poderosos, mas também são uma ferramenta importante no processo geral de design de HCI porque representam um investimento de custo e tempo menor em comparação com os protótipos.

## <a>Metodologia</a>
Este projeto utiliza personas para representar situações em que a plataforma pode ser utilizada e para representar problemas enfrentados tanto pela plataforma quanto pelos usuários.

## <a>Representação dos Cenários</a>
A seguir na Tabela 1 a forma a qual sera representada os cenários.

<center style="max-width: 500px; margin: auto; align-items: center;">

| **Cenário**a     | **Número do Cenário** |
| :--------------:| :-------------- |
| **Titulo**      | _Nome do Cenário._ |
| **Objetivo**    | _Objetivo do Cenário._ |
| **Contexto**    | Local: _Local onde acontece o Cenário._<br>Tempo: _Tempo do Cenário._<br>Pré-condição: _Condição para que o Cenário aconteça._ |
| **Atores**      | _Ator(es) do Cenário._ |
| **Recursos**    | _Recursos do Cenário._ |
| **Episódios**   | _Episódios do Cenário da aplicação._ |
| **Restrição**   | _Restrição do Cenário._ |
| **Exceção**     | _Exceção do Cenário._ |

Tabela 1 - Representação dos cenários
</center>

## <a>Cenários</a>

Nas tabelas a seguir estão representados alguns cenários.<br></br><br>
<center style="max-width: 500px; margin: auto; align-items: center;">

| **Cenário**     | **001** |
| :--------------:| :-------------- |
| **Titulo**      | _Emissão de DAS em aberto, do ano atual._ |
| **Objetivo**    | _Emitir boleto  em aberto do DAS recente._ |
| **Contexto**    | **Local**: _Tela de Emitir DAS.(PGMEI)_<br>**Tempo**: _Indeterminado._<br>**Pré-condição**: _Acesso a internet._ |
| **Atores**      | _Usuário com CNPJ ativo._ |
| **Recursos**    | _Internet<br>Computador ou Smartphone com acesso ao Google ou Safari_ |
| **Episódios**   | _Usário acessa a opção PGMEI<br>Usúario acessa o site com o CNPJ<br>Usuário escolhe o mês em aberto para realizar o pagamento<br>Usuário tem acesso ao boleto_ |
| **Restrição**   | _Internet indisponível<br>Todos os DAS pagos_ |
| **Exceção**     | _CNPJ invalido<br>Não ter acesso ao smartphone/computador<br>Internet indisponivel._ |

Tabela 2 - Cenário 001<br></br><br>

| **Cenário**     | **002** |
| :--------------:| :-------------- |
| **Titulo**      | _Perguntas e Respostas._ |
| **Objetivo**    | _Ter acesso as perguntas e respostas do site._ |
| **Contexto**    | **Local**: _Tela inicial, a opção Perguntas e respostas na coluna da esquerda._<br>**Tempo**: _Indeterminado._<br>**Pré-condição**: _Acesso a internet._ |
| **Atores**      | _Usuário com CNPJ ativo._ |
| **Recursos**    | _Internet<br>Smartphone/Computador com acesso a internet._ |
| **Episódios**   | _Usúario acessa o site<br>Usuário acessa a opção Perguntas e Respostas<br>O site abre uma página com escolhas e logo em seguida baixa um pdf no dispositivo do usuario mostrando as perguntas mais frequentes e suas respostas_ |
| **Restrição**   | _Internet indisponível._ |
| **Exceção**     | _CNPJ invalido<br>Não ter acesso ao smartphone/computador<br>Internet indisponivel_ |

Tabela 3 - Cenário 002<br></br><br>

| **Cenário**     | **003** |
| :--------------:| :-------------- |
| **Titulo**      | _Exibir Manuais._ |
| **Objetivo**    | _Exibir Manuais sobre as legendas._ |
| **Contexto**    | **Local**: _Tela inicial._<br>**Tempo**: _Indeterminado._<br>**Pré-condição**: _Acesso a internet._ |
| **Atores**      | _Usuário com CNPJ ativo._ |
| **Recursos**    | _Internet<br>Smartphone/Computador com acesso a internet._ |
| **Episódios**   | _Usúario acessa o site com o CNPJ<br>Usuário acessa a opção Manuais na coluna a esquerda<br>Usuário clica na opção desejada_ |
| **Restrição**   | _Internet indisponível._ |
| **Exceção**     | _CNPJ invalido<br>Não ter acesso ao smartphone/computador<br>Internet indisponivel_ |

Tabela 4 - Cenário 003<br></br><br>

| **Cenário**     | **004** |
| :--------------:| :-------------- |
| **Titulo**      | _Gerar estado do DAS._ |
| **Objetivo**    | _Compartilhar imagem contendo a informação de quais DAS foram liquidados._ |
| **Contexto**    | **Local**: _Tela do PGMEI._<br>**Tempo**: _Indeterminado._<br>**Pré-condição**: _Acesso a internet._ |
| **Atores**      | _Usuário com CNPJ ativo._ |
| **Recursos**    | _Internet<br>Smartphone/Computador com o acesso a internet._ |
| **Episódios**   | _Usuário acessa a opção PGMEI<br>Usúario acessa o site com o CNPJ<br>Usuário clica no botão de Gerar PDF._ |
| **Restrição**   | _Internet indisponível._ |
| **Exceção**     | _CNPJ invalido<br>Não ter acesso ao smartphone/computador<br>Internet indisponivel._ |
Tabela 5 - Cenário 004<br></br><br>

| **Cenário**     | **005** |
| :--------------:| :-------------- |
| **Titulo**      | _Consultar CNPJ._ |
| **Objetivo**    | _Realizar uma consulta sobre o status do próprio CNPJ._ |
| **Contexto**    | **Local**: _Tela de Consulta Optantes._<br>**Tempo**: _Indeterminado._<br>**Pré-condição**: _Acesso a internet._ |
| **Atores**      | _Usuário com CNPJ ativo._ |
| **Recursos**    | _Internet<br>Smartphone/Computador com acesso a internet._ |
| **Episódios**   | _Usuário acessa a tela de Consulta Optantes<br>Usuário acessa o app com o CNPJ._ |
| **Restrição**   | _Internet indisponível._ |
| **Exceção**     | _CNPJ invalido<br>Não ter acesso ao smartphone/computador<br>Internet indisponivel._ |

Tabela 6 - Cenário 005<br></br><br>

| **Cenário**     | **006** |
| :--------------:| :-------------- |
| **Titulo**      | _Gerar relatório da consultar CNPJ._ |
| **Objetivo**    | _Realizar uma consulta sobre o status do próprio CNPJ._ |
| **Contexto**    | **Local**: _Tela de Consulta Optantes._<br>**Tempo**: _Indeterminado._<br>**Pré-condição**: _Acesso a internet._ |
| **Atores**      | _Usuário com CNPJ ativo._ |
| **Recursos**    | _Internet<br>Smartphone/Computador com acesso a internet._ |
| **Episódios**   | _Usuário acessa a tela de Consulta Optantes<br>Usuário acessa o app com o CNPJ<br>Usuário clica em Gerar PDF._ |
| **Restrição**   | _Internet indisponível._ |
| **Exceção**     | _CNPJ invalido<br>Não ter acesso ao smartphone/computador<br>Internet indisponivel._ |
Tabela 7 - Cenário 006<br></br><br>

| **Cenário**     | **007** |
| :--------------:| :-------------- |
| **Titulo**      | _Pedido de Restituição._ |
| **Objetivo**    | _Solicitar a restituição de um pagamento realizado indevidamente._ |
| **Contexto**    | **Local**: _Tela de Restituição._<br>**Tempo**: _Indeterminado._<br>**Pré-condição**: _Acesso a internet._ |
| **Atores**      | _Usuário com CNPJ ativo._ |
| **Recursos**    | _Internet<br>Smartphon/computador com acesso a internet_ |
| **Episódios**   | _Usuário clica na opção Restituição<br>Usuário acessa o site com o CNPJ, CPF e Código de Acesso<br> Usuário clica em "Solicitar Restituição"<br>Usuário informa o período desejado<br>Usuário clica no DAS que for exibido<br>Usuário solicita restituição_ |
| **Restrição**   | _Internet indisponivel_ |
| **Exceção**     | _CNPJ invalido<br>Não ter acesso ao smartphone/computador<br>Internet indisponivel<br>Data não estar mais disponível para restituição._ |

Tabela 8 - Cenário 007<br></br><br>

| **Cenário**     | **008** |
| :--------------:| :-------------- |
| **Titulo**      | _Ativar Débito Automático._ |
| **Objetivo**    | _Cadastrar o banco a fim de automatizar o pagamento do DAS._ |
| **Contexto**    |  **Local**: _Tela de Débito Automático._<br>**Tempo**: _Indeterminado._<br>**Pré-condição**: _Acesso a internet._ |
| **Atores**      | _Usuário com CNPJ ativo._|
| **Recursos**    |_Internet<br>Smartphon/computador com acesso a internet_|
| **Episódios**   |_Usuário clica na opção Débito Automático<br>Usuário acessa o site com o CNPJ, CPF e Código de Acesso<br> Usuário clica em "Débito Automático"<br>Usuário seleciona "Inclusão"<br>Usuário informa os dados do banco e pessoais_|
| **Restrição**   | _Internet indisponivel_ |
| **Exceção**     | _CNPJ invalido<br>Não ter acesso ao smartphone/computador<br>Internet indisponivel<br>Não ter cadastro em banco._ |

Tabela 9 - Cenário 008<br></br><br>

| **Cenário**     | **009** |
| :--------------:| :-------------- |
| **Titulo**      | _Desativar Débito Automático._ |
| **Objetivo**    | _Descadastrar o banco._ |
| **Contexto**    |  **Local**: _Tela de Débito Automático._<br>**Tempo**: _Indeterminado._<br>**Pré-condição**: _Acesso a internet._ |
| **Atores**      | _Usuário com CNPJ ativo._|
| **Recursos**    |_Internet<br>Smartphon/computador com acesso a internet_|
| **Episódios**   |_Usuário clica na opção Débito Automático<br>Usuário acessa o site com o CNPJ, CPF e Código de Acesso<br> Usuário clica em "Débito Automático"<br>Usuário seleciona "Desativação"<br>Usuário seleciona a opção cadastrada que deseja desativar_|
| **Restrição**   | _Internet indisponivel_ |
| **Exceção**     | _CNPJ invalido<br>Não ter acesso ao smartphone/computador<br>Internet indisponivel<br>Não ter cadastrado o banco no Simples Nacional._ |

Tabela 10 - Cenário 009<br></br><br>
| **Cenário**     | **010** |
| :--------------:| :-------------- |
| **Titulo**      | _Gerar Relatório sobre as Declarações._ |
| **Objetivo**    | _Descadastrar o banco._ |
| **Contexto**    |  **Local**: _Tela de Cálculo e Declarações._<br>**Tempo**: _Indeterminado._<br>**Pré-condição**: _Acesso a internet._ |
| **Atores**      | _Usuário com CNPJ ativo._|
| **Recursos**    |_Internet<br>Smartphon/computador com acesso a internet_|
| **Episódios**   |_Usuário clica na opção Cálculo e Declarações<br>Usuário acessa o site com o CNPJ, CPF e Código de Acesso<br> Usuário clica no icone de uma impressora<br>|
| **Restrição**   | _Internet indisponivel_ |
| **Exceção**     | _CNPJ invalido<br>Não ter acesso ao smartphone/computador<br>Internet indisponivel<br> |

Tabela 11 - Cenário 010

</center>

## <a>Bibliografia</a>
Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) _Interação Humano-Computador e Experiência do usuário_. Autopublicação. ISBN: 978-65-00-19677-1.
