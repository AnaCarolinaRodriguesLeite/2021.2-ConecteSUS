# Requisitos Elicitados

<div align="justify">


## 1. Introdução
O presente documento reúne todos os requisitos levantados ao longo do projeto utilizando técnicas de elicitação, totalizando 46 requisitos funcionais e 5 requisitos não-funcionais.



## 2. Metodologia
A equipe utilizou diferentes técnicas de elicitação para levantar e concluir, finalmente, a lista de requisitos do projeto. As técnicas utilizadas foram:
* Brainstorm;
* Observação;
* Storyboard;
* Observação Participativa;
* Introspecção.

Os requisitos levantados em tais técnicas foram compilados e cada um deles é identificado por um ID, que possui o prefixo RF para requisitos funcionais e RNF para requisitos não-funcionais, juntamente com sua numeração. Para melhor rastreabilidade, as técnicas em que cada requisito se originou serão identificadas com a sigla da técnica juntamente com o número do requisito no devido documento. As técnicas serão referenciadas pelas seguintes siglas:

<center>

| Técnica | Sigla |
|:-:|:-:|
| Brainstorm   | BT |
| Observação   | OBS |
| Storyboard | SB |
| Observação Participativa  | OB  |
| Introspecção | ITP |

</center>


## 3. Resultado



### 3.1. Requisitos Funcionais

| ID    | Requisito                       | Técnica utilizada |
| ----- | ------------------------------------ | :---- |
| RF 01 | O usuário deve poder visualizar informações gerais sem efetuar o login. | [OB01](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/Observacao_participativa/)  |
| RF 02 | O usuário deve poder efetuar o login no gov.br com o cpf.  |  [OB02](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/Observacao_participativa/)  |
| RF 03 | O usuário deve poder escolher outras opções de identificação para login. | [OB03](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/Observacao_participativa/)  |
| RF 04 | O usuário deve poder ver a senha inserida.  | [0B04](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/Observacao_participativa/) |
| RF 05 | O usuário deve ter uma alternativa de recuperação de senha caso tenha esquecido.|  [OB05](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/Observacao_participativa/)  |
| RF 06 | O usuário deve poder navegar entre todas as abas.  |  [OB06](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/Observacao_participativa/)  |
| RF 07 | O usuário deve poder acessar a carteira nacional de vacina no menu rápido.  | [OB07](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/Observacao_participativa/), [ST11](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/storytelling/#4-requisitos-funcionais)  |
| RF 08 | O usuário deve poder alterar o idioma da carteira nacional de vacina. | [OB08](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/Observacao_participativa/)  |
| RF 09 | O usuário deve poder gerar um pdf da carteira nacional de vacina. | [OB09](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/Observacao_participativa/), [ITP19](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/introspeccao/#31-requisitos-funcionais), [SB11](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/storytelling/#4-requisitos-funcionais) |
| RF 10 | O usuário deve poder acessar o certificado de vacinação da COVID-19 no menu rápido. | [OB10](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/Observacao_participativa/), [ITP06](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/introspeccao/#31-requisitos-funcionais), [BT02](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/brainstorming/#5-levantamento-de-requisitos), [SB10](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/storytelling/#4-requisitos-funcionais) |
| RF 11 | O usuário deve poder alterar o idioma do certificado de vacina COVID-19. | [OB11](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/Observacao_participativa/)  |
| RF 12 | O usuário deve poder gerar um pdf do certificado de vacina COVID-19.  | [OB12](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/Observacao_participativa/) |
| RF 13 | O usuário deve poder visualizar um QR Code para autenticar o certificado de vacina COVID-19.  | [OB13](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/Observacao_participativa/) |
| RF 14 | O usuário deve poder acessar o cartão do SUS no menu rápido. | [OB14](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/Observacao_participativa/), [ITP20](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/introspeccao/#31-requisitos-funcionais)  |
| RF 15 | O usuário deve poder compartilhar seu cartão do SUS. | [OB15](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/Observacao_participativa/#3-resultados)  |
| RF 16 | O usuário deve poder visualizar um QR Code para o cartão do SUS. | [OB16](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/Observacao_participativa/#3-resultados)  |
| RF 17 | O usuário deve poder ver as informações principais no menu inicial. |  [OB17](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/Observacao_participativa/#3-resultados)  |
| RF 18 | O usuário deve poder ver as vacinas tomadas. |  [OB18](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/Observacao_participativa/#3-resultados), [SB03](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/storytelling/#4-requisitos-funcionais), [ITP05](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/introspeccao/#31-requisitos-funcionais)  |
| RF 19 | O usuário deve poder informar se há algum problema com suas vacinas. | [OB19](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/Observacao_participativa/#3-resultados) |
| RF 20 | O usuário deve poder consultar seus exames de COVID-19.|  [OB20](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/Observacao_participativa/#3-resultados), [ITP07](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/introspeccao/#31-requisitos-funcionais), [SB04](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/storytelling/#4-requisitos-funcionais), [BT03](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/brainstorming/#5-levantamento-de-requisitos)  |
| RF 21 | O usuário deve poder consultar seus medicamentos autodeclarados e recebidos. |  [SB05](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/storytelling/#4-requisitos-funcionais), [BT11](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/brainstorming/#5-levantamento-de-requisitos), [OB21](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/Observacao_participativa/#3-resultados)  |
| RF 22 | O usuário deve poder adicionar um medicamento autodeclarado. |  [OB22](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/Observacao_participativa/#3-resultados), [ITP11](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/introspeccao/#31-requisitos-funcionais)  |
| RF 23 | O usuário deve poder consultar os dados de atendimentos e internações realizadas no SUS. |  [OB23](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/Observacao_participativa/#3-resultados), [BT05](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/brainstorming/#5-levantamento-de-requisitos), [ITP09](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/introspeccao/#31-requisitos-funcionais), [SB06](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/storytelling/#4-requisitos-funcionais)  |
| RF 24 | O usuário deve poder validar um QR Code. | [OB24](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/Observacao_participativa/#3-resultados) |
| RF 25 | O usuário deve poder consultar a localização dos estabelecimentos da rede de saúde. |  [OB25](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/Observacao_participativa/#3-resultados), [BT07](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/brainstorming/#5-levantamento-de-requisitos)  |
| RF 26 | O usuário deve poder adicionar e consultar contatos emergenciais. |  [OB26](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/Observacao_participativa/#3-resultados), [SB07](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/storytelling/#4-requisitos-funcionais), [ITP15](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/introspeccao/#31-requisitos-funcionais), [ITP16](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/introspeccao/#31-requisitos-funcionais), [BT16](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/brainstorming/#5-levantamento-de-requisitos), [BT17](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/brainstorming/#5-levantamento-de-requisitos)  |
| RF 27 | O usuário deve poder adicionar e consultar seu registro de saúde. |  [OB27](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/Observacao_participativa/#3-resultados), [BT18](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/brainstorming/#5-levantamento-de-requisitos), [BT19](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/brainstorming/#5-levantamento-de-requisitos), [ITP17](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/introspeccao/#31-requisitos-funcionais), [ITP18](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/introspeccao/#31-requisitos-funcionais)  |
| RF 28 | O usuário deve poder consultar as regras e doações de sangue já realizadas. |  [OB28](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/Observacao_participativa/#3-resultados), [BT06](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/brainstorming/#5-levantamento-de-requisitos), [BT14](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/brainstorming/#5-levantamento-de-requisitos), [ITP12](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/introspeccao/#31-requisitos-funcionais), [SB08](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/storytelling/#4-requisitos-funcionais) |
| RF 29 | O usuário deve poder adicionar e consultar seu registro de alergias.  |  [OB29](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/Observacao_participativa/#3-resultados), [SB09](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/storytelling/#4-requisitos-funcionais), [ITP13](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/introspeccao/#31-requisitos-funcionais), [ITP14](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/introspeccao/#31-requisitos-funcionais), [BT15](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/brainstorming/#5-levantamento-de-requisitos)  |
| RF 30 | O usuário deve poder consultar informações sobre saúde alimentar. |  [OB30](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/Observacao_participativa/#3-resultados)  |
| RF 31 | O usuário deve poder realizar um teste de alimentação.  | [OB31](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/Observacao_participativa/#3-resultados)  |
| RF 32 | O usuário deve poder ver consultas agendadas e a fila de espera. |  [OB32](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/Observacao_participativa/#3-resultados)  |
| RF 33 | O usuário deve poder consultar informações sobre doações de órgãos. | [OB33](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/Observacao_participativa/#3-resultados)  |
| RF 34 | O usuário deve poder acompanhar sua posição na fila do sistema nacional de transplantes. |  [OB34](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/Observacao_participativa/#3-resultados)  |
| RF 35 | O usuário deve poder ser redirecionado para a chamada telefônica da central nacional de transplantes. | [OB35](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/Observacao_participativa/#3-resultados)  |
| RF 36 | O usuário deve poder adicionar uma foto de perfil. | [OB36](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/Observacao_participativa/#3-resultados)  |
| RF 37 | O usuário deve poder gerenciar suas contas. | [OB37](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/Observacao_participativa/#3-resultados)  |
| RF 38 | O usuário deve poder visualizar os dados cadastrados. | [OB38](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/Observacao_participativa/#3-resultados)  |
| RF 39 | O usuário deve poder visualizar as notícias relacionadas à saúde. | [OB39](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/Observacao_participativa/#3-resultados)  |
| RF 40 | O usuário deve poder entrar em contato com o ConecteSUS para esclarecer dúvidas e problemas.  | [OB40](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/Observacao_participativa/#3-resultados)  |
| RF 41 | O usuário deve poder verificar quais são os demais aplicativos do Ministério da Saúde. | [OB41](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/Observacao_participativa/#3-resultados)  |
| RF 42 | O usuário deve poder consultar as duvidas frequentes relacionadas ao aplicativo. | [OB42](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/Observacao_participativa/#3-resultados)  |
| RF 43 | O usuário deve poder consultar ao termo de utilização e política de privacidade. |  [OB43](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/Observacao_participativa/#3-resultados)  |
| RF 44 | O usuário deve poder avaliar o aplicativo. | [OB44](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/Observacao_participativa/#3-resultados)  |
| RF 45 | O usuário deve poder fazer logout.  |  [OB45](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/Observacao_participativa/#3-resultados), [ITP03](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/introspeccao/#31-requisitos-funcionais)  |
| RF 46 | O usuário deve ser redirecionado para o site de cadastro. |  [OB46](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/Observacao_participativa/#3-resultados), [SB02](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/storytelling/#4-requisitos-funcionais), [ITP01](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/introspeccao/#31-requisitos-funcionais)  |



### 3.2. Requisitos Não-Funcionais
| ID     | Requisito                                                                   | Técnica utilizada |
| ------ | --------------------------------------------------------------------------- | :----: |
| RNF 01 | O aplicativo não pode demorar muito para abrir. | [ITP21](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/introspeccao/#31-requisitos-funcionais), [SB12](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/storytelling/#5-requisitos-nao-funcionais) |
| RNF 02 | O aplicativo não pode ficar indisponível.  |  [ITP22](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/introspeccao/#31-requisitos-funcionais), [SB14](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/storytelling/#5-requisitos-nao-funcionais)  |
| RNF 03 | Os usuários devem conseguir encontrar a funcionalidade desejada rapidamente. | [ITP23](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/introspeccao/#31-requisitos-funcionais), [SB13](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/storytelling/#5-requisitos-nao-funcionais) |
| RNF 04 | O aplicativo deve proteger os dados dos usuários.  |  [ITP24](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/introspeccao/#31-requisitos-funcionais), [SB15](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/storytelling/#5-requisitos-nao-funcionais) |
| RNF 05 | O aplicativo deve apresentar persistência de login. | [BT20](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/brainstorming/#5-levantamento-de-requisitos)  |

## Bibliografia
> SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 07. 1º/2019. Slides apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.

> SOMMERVILLE, Ian. 2011. Engenharia de Software.


## Histórico de versão
| Versão | Data | Descrição | Autor | Revisor |
|:--:|:--:|:--:|:--:|:--:|
|0.1|05/03/2022|Criação do resultado dos requisitos obtidos através das técnicas de elicitação|Ana Carolina|Gustave|