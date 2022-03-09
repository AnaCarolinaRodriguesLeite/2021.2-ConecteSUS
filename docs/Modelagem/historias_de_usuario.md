# Histórias de Usuário

## 1. Introdução

<p style="text-align: justify;"> O presente documento tem por objetivo apresentar as histórias de usuário do aplicativo ConecteSUS. Antes de introduzi-las, entende-se que histórias de usuário, ou user stories, são as sentenças ou frases que representam o domínio de negócio de uma aplicação. Ou seja, são criadas algumas frases que representam a ação de um usuário durante sua experiência durante a execução do aplicativo. Dessa forma, consegue-se mapear as funcionalidades de seu sistema através da suposição de seus desejos. Um exemplo de uma frase correspondente a uma história de usuário seria: "Eu, como usuário, desejo efetuar login para poder acessar minha conta".
 </p>

## 2. Metodologia

<p style="text-align: justify;">
A metodologia utilizada para a criação do documento de histórias de usuário foi de separar 3 integrantes da equipe para a produção do documento, foram necessários mais pessoas nessa atividade devido ao grau de importância requisitada, visto que esse levantamento servirá de consulta para a criação de outros documentos. Sob esse viés, foram mapeados e consultados os requisitos funcionais e não funcionais disponíveis no documento de pré-rastreabilidade Moscow. Ademais, foi criado uma tabela que representa as frases de ação do usuário que serão relacionadas com os requisitos e suas devidas tarefas. Dessa forma, foram utilizados épicos para refinar e subdividir todas as histórias de usuário de acordo com uma funcionalidade geral.
</p>

## 3. Épicos

<p style="text-align: justify;">
Os épicos são termos genéricos que buscam agrupar um conjunto de atividades e funcionalidades de um sistema. Definimos como épico um escopo que possa abrangir as mais diversas histórias de usuário. Através da consulta do Rich Picture, pode-se destacar os seguintes épicos refinados:</p>

<center>

| Épicos |    Nome    |                                                                                                       Descrição                                                                                                        |
| :----: | :--------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|  EP01  |   Conta    |                                      Esse épico está relacionado ao usuário e o escopo de suas limitações como "conta" durante o sistema, como login, cadastro, logout e outros.                                       |
|  EP02  | Históricos |                                Esse épico está interligado ao RichPicture, em que o usuário consegue acessar o histórico de atendimentos, internações, vacinas, exames e medicamentos.                                 |
|  EP03  | Registros  |                                 Esse épico está interligado ao RichPicture, em que o usuário consegue acessar o registro de atendimentos, internações, vacinas, exames e medicamentos.                                 |
|  EP04  |   Geral    | Esse épico corresponde a todas as outras funcionalidades que não se encaixaram a nenhum outro épico, podendo ser definidos por funcionalidades que fazem parte do sistema como forma de melhoria, praticidade e outros |

</center>

### 3.1 EP01: Conta

| História de Usuário |                                                                 Rastreabilidade                                                                 |                 Eu, como usuário gostaria de...                  |                          Para poder...                           | Prioridade |
| :-----------------: | :---------------------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------: | :--------------------------------------------------------------: | :--------: |
|        US01         | [RF01](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnica_de_priorizacao/Moscow/#41-requisitos-funcionais) |            vizualiar informações sem efetuar o login             | visualizar informações sem necessariamente entrar na minha conta |   Could    |
|        US02         | [RF02](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnica_de_priorizacao/Moscow/#41-requisitos-funcionais) |               efetuar o login no gov.br com o cpf                |               entrar na minha conta com o meu cpf                |    Must    |
|        US03         | [RF03](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnica_de_priorizacao/Moscow/#41-requisitos-funcionais) |          ter outras opções de identificação para login           |        escolher outras opções de identificação para login        |   Could    |
|        US04         | [RF04](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnica_de_priorizacao/Moscow/#41-requisitos-funcionais) |                       ver a senha inserida                       |                 ter certeza da senha que digitei                 |   Should   |
|        US05         | [RF05](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnica_de_priorizacao/Moscow/#41-requisitos-funcionais) |               recuperar senha caso tenha esquecido               |     ter uma alternativa de recuperação de senha caso esqueça     |    Must    |
|        US06         | [RF06](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnica_de_priorizacao/Moscow/#41-requisitos-funcionais) |                   navegar entre todas as abas                    |                       utilizar todo o app                        |    Must    |
|        US07         | [RF36](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnica_de_priorizacao/Moscow/#41-requisitos-funcionais) |                   adicionar uma foto de perfil                   |                       melhorar meu perfil                        |   Would    |
|        US08         | [RF37](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnica_de_priorizacao/Moscow/#41-requisitos-funcionais) |                       gerenciar as contas                        |                    melhorar o meu uso do app                     |   Could    |
|        US09         | [RF38](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnica_de_priorizacao/Moscow/#41-requisitos-funcionais) |                 visualizar os dados cadastrados                  |                verificar os dados da minha conta                 |   Could    |
|        US10         | [RF39](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnica_de_priorizacao/Moscow/#41-requisitos-funcionais) |           visualizar as notícias relacionadas à saúde            |              me interar das notícias mais recentes               |   Would    |
|        US11         | [RF40](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnica_de_priorizacao/Moscow/#41-requisitos-funcionais) |                entrar em contato com o ConecteSUS                |                  esclarecer dúvidas e problemas                  |   Could    |
|        US12         | [RF41](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnica_de_priorizacao/Moscow/#41-requisitos-funcionais) | verificar quais são os demais aplicativos do Ministério da Saúde |             utilizar melhor dos serviços oferecidos              |   Would    |
|        US13         | [RF42](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnica_de_priorizacao/Moscow/#41-requisitos-funcionais) |    consultar as duvidas frequentes relacionadas ao aplicativo    |                     solucionar minha dúvida                      |   Could    |
|        US14         | [RF43](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnica_de_priorizacao/Moscow/#41-requisitos-funcionais) |    consultar ao termo de utilização e política de privacidade    |            saber se as políticas e termos me agradam             |    Must    |
|        US15         | [RF44](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnica_de_priorizacao/Moscow/#41-requisitos-funcionais) |                       avaliar o aplicativo                       |                     mostrar minha satisfação                     |   Would    |
|        US16         | [RF45](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnica_de_priorizacao/Moscow/#41-requisitos-funcionais) |                           fazer logout                           |              me sentir seguro ao largar meu celular              |    Must    |
|        US17         | [RF46](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnica_de_priorizacao/Moscow/#41-requisitos-funcionais) |            ser redirecionado para o site de cadastro             |          me despreocupar em procurar o site de cadastro          |    Must    |

### 3.2 EP02: Históricos

| História de Usuário |                                                                 Rastreabilidade                                                                 |                    Eu, como usuário gostaria de...                     |                         Para poder...                          | Prioridade |
| :-----------------: | :---------------------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------: | :------------------------------------------------------------: | :--------: |
|        US18         | [RF10](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnica_de_priorizacao/Moscow/#41-requisitos-funcionais) |             acessar o certificado de vacinação da COVID-19             |       ir em locais publicos e apresentar meu certificado       |   Could    |
|        US19         | [RF11](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnica_de_priorizacao/Moscow/#41-requisitos-funcionais) |           alterar o idioma do certificado de vacina COVID-19           | ir em locais publicos no exterior e apresentar meu certificado |   Could    |
|        US20         | [RF12](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnica_de_priorizacao/Moscow/#41-requisitos-funcionais) |             gerar um pdf do certificado de vacina COVID-19             |                 apresentar em locais públicos                  |   Should   |
|        US21         | [RF13](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnica_de_priorizacao/Moscow/#41-requisitos-funcionais) | visualizar um QR Code para autenticar o certificado de vacina COVID-19 |       ter uma forma diferente de validar meu certificado       |   Should   |
|        US22         | [RF18](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnica_de_priorizacao/Moscow/#41-requisitos-funcionais) |                         ver as vacinas tomadas                         |                    ver os dados das vacinas                    |    Must    |
|        US23         | [RF19](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnica_de_priorizacao/Moscow/#41-requisitos-funcionais) |            informar se há algum problema com minhas vacinas            |                corrigir as informações erradas                 |   Should   |
|        US24         | [RF20](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnica_de_priorizacao/Moscow/#41-requisitos-funcionais) |                   consultar meus exames de COVID-19                    |                    ver os dados das vacinas                    |    Must    |
|        US25         | [RF21](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnica_de_priorizacao/Moscow/#41-requisitos-funcionais) |         consultar meus medicamentos autodeclarados e recebidos         |              ver as informações dos medicamentos               |    Must    |
|        US26         | [RF22](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnica_de_priorizacao/Moscow/#41-requisitos-funcionais) |                 adicionar um medicamento autodeclarado                 |      consultar as informações deste medicamento no futuro      |    Must    |
|        US27         | [RF23](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnica_de_priorizacao/Moscow/#41-requisitos-funcionais) |   consultar os dados de atendimentos e internações realizadas no SUS   |       ver as informações dos atendimentos e internações        |    Must    |

### 3.3 EP03: Registros

| História de Usuário |                                                                 Rastreabilidade                                                                 |        Eu, como usuário gostaria de...         |                Para poder...                | Prioridade |
| :-----------------: | :---------------------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------: | :-----------------------------------------: | :--------: |
|        US28         | [RF26](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnica_de_priorizacao/Moscow/#41-requisitos-funcionais) |  adicionar e consultar contatos emergenciais   | me sentir seguro ao passar mal fora de casa |    Must    |
|        US29         | [RF27](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnica_de_priorizacao/Moscow/#41-requisitos-funcionais) |  adicionar e consultar meu registro de saúde   |    ter um controle melhor da minha saúde    |    Must    |
|        US30         | [RF28](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnica_de_priorizacao/Moscow/#41-requisitos-funcionais) |    consultar as regras e doações de sangue     |             realizar uma doação             |    Must    |
|        US31         | [RF29](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnica_de_priorizacao/Moscow/#41-requisitos-funcionais) | adicionar e consultar seu registro de alergias |    ter um controle melhor da minha saúde    |    Must    |

### 3.4 EP04: Geral

| História de Usuário |                                                                 Rastreabilidade                                                                 |                         Eu, como usuário gostaria de...                         |              Para poder...               | Prioridade |
| :-----------------: | :---------------------------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------: | :--------------------------------------: | :--------: |
|        US32         | [RF07](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnica_de_priorizacao/Moscow/#41-requisitos-funcionais) |              acessar a carteira nacional de vacina no menu rápido               |    gerar a carteira de maneira rápida    |   Could    |
|        US33         | [RF08](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnica_de_priorizacao/Moscow/#41-requisitos-funcionais) |                 alterar o idioma da carteira nacional de vacina                 |     utilizar a carteira no exterior      |   Could    |
|        US34         | [RF09](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnica_de_priorizacao/Moscow/#41-requisitos-funcionais) |                   gerar um pdf da carteira nacional de vacina                   |         apresentar minha cateira         |   Should   |
|        US35         | [RF14](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnica_de_priorizacao/Moscow/#41-requisitos-funcionais) |                     acessar o cartão do SUS no menu rápido                      |          apresentar meu cartão           |   Could    |
|        US36         | [RF15](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnica_de_priorizacao/Moscow/#41-requisitos-funcionais) |                         compartilhar seu cartão do SUS                          | permitir que alguem apresente meu cartão |   Could    |
|        US37         | [RF16](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnica_de_priorizacao/Moscow/#41-requisitos-funcionais) |                   visualizar um QR Code para o cartão do SUS                    | permitir que alguem verifique meu cartão |   Would    |
|        US38         | [RF17](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnica_de_priorizacao/Moscow/#41-requisitos-funcionais) |                  ver as informações principais no menu inicial                  |          conhecer minhas opções          |    Must    |
|        US39         | [RF24](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnica_de_priorizacao/Moscow/#41-requisitos-funcionais) |                               validar um QR Code                                |  confirmar a autenticidade do documento  |   Should   |
|        US40         | [RF25](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnica_de_priorizacao/Moscow/#41-requisitos-funcionais) |          consultar a localização dos estabelecimentos da rede de saúde          |               ser atendido               |    Must    |
|        US41         | [RF30](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnica_de_priorizacao/Moscow/#41-requisitos-funcionais) |                   consultar informações sobre saúde alimentar                   |        melhorar minha alimentação        |    Must    |
|        US42         | [RF31](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnica_de_priorizacao/Moscow/#41-requisitos-funcionais) |                        realizar um teste de alimentação                         |    saber se estou me alimentando bem     |   Could    |
|        US43         | [RF32](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnica_de_priorizacao/Moscow/#41-requisitos-funcionais) |                   ver consultas agendadas e a fila de espera                    |           ser atendido no dia            |    Must    |
|        US44         | [RF33](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnica_de_priorizacao/Moscow/#41-requisitos-funcionais) |                  consultar informações sobre doações de órgãos                  |           realizar uma doação            |   Could    |
|        US45         | [RF34](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnica_de_priorizacao/Moscow/#41-requisitos-funcionais) |       acompanhar sua posição na fila do sistema nacional de transplantes        |  saber quando realizarei meu trasplante  |    Must    |
|        US46         | [RF35](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnica_de_priorizacao/Moscow/#41-requisitos-funcionais) | ser redirecionado para a chamada telefônica da central nacional de transplantes |    fazer a chamada de maneira rápida     |   Would    |

## 4. Bibliografia

> - WIEGERS, Karl; BEATTY, Joy. "Software Requirements". Microsoft Press, 2013.
> - Artefato: Backlog do Produto. TRT9. Disponível em: https://www.trt9.jus.br/pds/Scrum/workproducts/product_backlog_68345C16.html. Acesso em: 10 de Setembro de 2021.
> - FERREIRA, Avelino. Product Backlog: Épico, História de Usuário e Tarefas. K21, 2020. Disponível em: https://k21.global/blog/product-backlog-epico-historia-tarefas. Acesso em: 10 de Setembro de 2021.
> - RADIGAN, Dan. O backlog do produto: sua lista de tarefas definitiva. Atlassian. Disponível em: https://www.atlassian.com/br/agile/scrum/backlogs. Acesso em: 10 de Setembro de 2021.

## Histórico de Versão

| Versão |    Data    |             Descrição             |          Autor          |   Revisor    |
| :----: | :--------: | :-------------------------------: | :---------------------: | :----------: |
|  0.1   | 07/03/2022 |       Criação do documento        | Gustave, Daniel e Erick | Ana Carolina |
|  0.2   | 09/03/2022 |     Linkando rastreabilidade      |          Erick          | Ana Carolina |
|  0.3   | 09/03/2022 | Ajustando número de cada história |         Daniel          | Ana Carolina |
