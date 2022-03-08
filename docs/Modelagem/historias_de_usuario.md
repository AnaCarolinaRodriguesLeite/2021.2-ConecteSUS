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

| Épicos |    Nome        |    Descrição |
| :----: | :--------:     | :---------:  |
|  EP01  |    Conta       |  Esse épico está relacionado ao usuário e o escopo de suas limitações como "conta" durante o sistema, como login, cadastro, logout e outros. |
|  EP02  |    Históricos   | Esse épico está interligado ao RichPicture, em que o usuário consegue acessar o histórico de atendimentos, internações, vacinas, exames e medicamentos.  |           
|  EP03  |    Registros    | Esse épico está interligado ao RichPicture, em que o usuário consegue acessar o registro de atendimentos, internações, vacinas, exames e medicamentos.  |         
|  EP04  |    Geral       |  Esse épico corresponde a todas as outras funcionalidades que não se encaixaram a nenhum outro épico, podendo ser definidos por funcionalidades que fazem parte do sistema como forma de melhoria, praticidade e outros  |  

</center>

### 3.1 EP01: Conta

| História de Usuário | Rastreabilidade | Eu, como usuário gostaria de... |               Para poder...               | Prioridade |
| :-----------------: | :-------------: | :-----------------------------: | :---------------------------------------: | :--------: |
| US01 | RF 01 | vizualiar sem efetuar o login | visualizar informações gerais sem efetuar o login                               | Could  |
| US02 | RF 02 | efetuar o login no gov.br com o cpf | efetuar o login no gov.br com o cpf                                              |  Must  |
| US03 | RF 03 | ter outras opções de identificação para login | escolher outras opções de identificação para login                              | Could  |
| US04 | RF 04 | ver a senha inserida | ter certeza da senha que digitei                                                            | Should |
| US05 | RF 05 | recuperar senha caso tenha esquecido | ter uma alternativa de recuperação de senha caso esqueça                      |  Must  |
| US06 | RF 06 | navegar entre todas as abas | utilizar todo o app                                                     |  Must  |
| US07 | RF 36 | adicionar uma foto de perfil | melhorar meu perfil                                                    | Would  |
| US08 | RF 37 | gerenciar as contas | melhorar o meu uso do app                                                           | Could  |
| US09 | RF 38 | visualizar os dados cadastrados | verificar os dados da minha conta                                                 | Could  |
| US10 | RF 39 | visualizar as notícias relacionadas à saúde | me interar das notícias mais recentes                                     | Would  |
| US11 | RF 40 | entrar em contato com o ConecteSUS | esclarecer dúvidas e problemas          | Could  |
| US12 | RF 41 | verificar quais são os demais aplicativos do Ministério da Saúde | utilizar melhor dos serviços oferecidos                | Would  |
| US13 | RF 42 | consultar as duvidas frequentes relacionadas ao aplicativo | solucionar minha dúvida                      | Could  |
| US14 | RF 43 | consultar ao termo de utilização e política de privacidade | saber se as políticas e termos me agradam                      |  Must  |
| US15 | RF 44 |  avaliar o aplicativo | mostrar minha satisfação                                                            | Would  |
| US16 | RF 45 | fazer logout | me sentir seguro ao largar meu celular                                                                    |  Must  |
| US17 |  RF 46 | ser redirecionado para o site de cadastro | me despreocupar em procurar o site de cadastro                                              |  Must  |


### 3.2 EP02: Históricos

| História de Usuário | Rastreabilidade | Eu, como usuário gostaria de... |                    Para poder...                    | Prioridade |
| :-----------------: | :-------------: | :-----------------------------: | :-------------------------------------------------: | :--------: |
| US | RF 10 | acessar o certificado de vacinação da COVID-19       | ir em locais publicos e apresentar meu certificado |  Could  |
| US 18 | RF 11 | alterar o idioma do certificado de vacina COVID-19      | ir em locais publicos no exterior e apresentar meu certificado |  Could  | 
| US 19 | RF 12 | gerar um pdf do certificado de vacina COVID-19      | apresentar em locais públicos |  Should  | 
| US 20 | RF 13 | visualizar um QR Code para autenticar o certificado de vacina COVID-19       | ter uma forma diferente de validar meu certificado |   Should  |
| US 21 | RF 18 | ver as vacinas tomadas       | ver os dados das vacinas  |  Must  |
| US 22 | RF 19 | informar se há algum problema com minhas vacinas |  corrigir as informações erradas  |  Should  |
| US 23 | RF 20 | consultar meus exames de COVID-19 |  ver os dados das vacinas  |  Must  |
| US 24 | RF 21 | consultar meus medicamentos autodeclarados e recebidos |  ver as informações dos medicamentos  |  Must  |
| US 25 | RF 22 | adicionar um medicamento autodeclarado |  consultar as informações deste medicamento no futuro  |  Must  |
| US 26 | RF 23 | consultar os dados de atendimentos e internações realizadas no SUS |  ver as informações dos atendimentos e internações  |  Must  |


### 3.3 EP03: Registros

| História de Usuário | Rastreabilidade |    Eu, como usuário gostaria de...    |                                  Para poder...                                   | Prioridade |
| :-----------------: | :-------------: | :-----------------------------------: | :------------------------------------------------------------------------------: | :--------: |
| US27 | RF 26 | adicionar e consultar contatos emergenciais | me sentir seguro ao passar mal fora de casa                                     |  Must  |
| US28 | RF 27 | adicionar e consultar meu registro de saúde | ter um controle melhor da minha saúde                                     |  Must  |
| US29 | RF 28 | consultar as regras e doações de sangue | realizar uma doação                        |  Must  |
| US30 | RF 29 | adicionar e consultar seu registro de alergias | ter um controle melhor da minha saúde                                    |  Must  |


### 3.4 EP04: Geral

| História de Usuário | Rastreabilidade |    Eu, como usuário gostaria de...    |                                  Para poder...                                   | Prioridade |
| :-----------------: | :-------------: | :-----------------------------------: | :------------------------------------------------------------------------------: | :--------: |
| US31 | RF 07 | acessar a carteira nacional de vacina no menu rápido | gerar a carteira de maneira rápida                          | Could  |
| US32 | RF 08 | alterar o idioma da carteira nacional de vacina | utilizar a carteira no exterior                             | Could  |
| US33 | RF 09 |  gerar um pdf da carteira nacional de vacina | apresentar minha cateira                                  | Should |
| US34 | RF 14 |  acessar o cartão do SUS no menu rápido | apresentar meu cartão                                  | Could  |
| US35 | RF 15 |  compartilhar seu cartão do SUS | permitir que alguem apresente meu cartão                                         | Could  |
| US36 | RF 16 |  visualizar um QR Code para o cartão do SUS | permitir que alguem verifique meu cartão                              | Would  |
| US37 | RF 17 |  ver as informações principais no menu inicial | conhecer minhas opções                                |  Must  |
| US38 | RF 24 |  validar um QR Code | confirmar a autenticidade do documento                                                      | Should |
| US39 | RF 25 |  consultar a localização dos estabelecimentos da rede de saúde | ser atendido                |  Must  |
| US40 | RF 30 |  consultar informações sobre saúde alimentar | melhorar minha alimentação                                  |  Must  |
| US41 | RF 31 |  realizar um teste de alimentação | saber se estou me alimentando bem                                           | Could  |
| US42 | RF 32 |  ver consultas agendadas e a fila de espera | ser atendido no dia                                    |  Must  |
| US43 | RF 33 |  consultar informações sobre doações de órgãos | realizar uma doação                             | Could  |
| US44 | RF 34 |  acompanhar sua posição na fila do sistema nacional de transplantes | saber quando realizarei meu trasplante         |  Must  |
| US45 | RF 35 | ser redirecionado para a chamada telefônica da central nacional de transplantes | fazer a chamada de maneira rápida | Would  |


## 4. Bibliografia

>- WIEGERS, Karl; BEATTY, Joy. "Software Requirements". Microsoft Press, 2013.
>- Artefato: Backlog do Produto. TRT9. Disponível em: https://www.trt9.jus.br/pds/Scrum/workproducts/product_backlog_68345C16.html. Acesso em: 10 de Setembro de 2021.
>- FERREIRA, Avelino. Product Backlog: Épico, História de Usuário e Tarefas. K21, 2020. Disponível em: https://k21.global/blog/product-backlog-epico-historia-tarefas. Acesso em: 10 de Setembro de 2021.
>- RADIGAN, Dan. O backlog do produto: sua lista de tarefas definitiva.  Atlassian. Disponível em: https://www.atlassian.com/br/agile/scrum/backlogs. Acesso em: 10 de Setembro de 2021.

## Histórico de Versão

| Versão |    Data    |               Descrição                |    Autor     | Revisor |
| :----: | :--------: | :------------------------------------: | :----------: | :-----: |
|  0.1   | 07/03/2022 | Criação do documento | Gustave, Daniel e Erick | Ana Carolina |
