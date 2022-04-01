# Foward-from

## 1. Introdução

<p style="text-align: justify;"> O presente documento tem por objetivo conectar os requisitos funcionais com os outros artefatos levantados durante todo o ciclo de desenvolvimento do projeto do ConecteSUS. Em resumo, a Foward-from (de frente-de) é a rastreabilidade de requisitos para especificações de um projeto.
</p>

## 2. Metodologia

<p style="text-align: justify;"> 
A metodologia utilizada para a produção do respectivo documento tem como base os meta-modelos de Toranzo e Gengivir. Toranzo dizia que a classificação do conjunto de informações que devem ser rastreadas para melhor entender a atividade de rastreamento dos requisitos seriam as seguintes:</p>

- Ambiental: contém informações derivadas do contexto ambiental em que a organização está inserida e que podem afetar o desenvolvimento do sistema;

- Organizacional: apresenta informações relacionadas à organização (missão, objetivos, metas e padrões) podendo impactar os requisitos do sistema;

- Gerencial: mostra informações que permitem a associação de tarefas até requisitos, além de que podem auxiliar a gerência do projeto;

- Desenvolvimento, Gerencial: abrange informações interligadas aos variados artefatos produzidos no processo de Desenvolvimento, Gerencial;

## 3. Mapeamento

<p style="text-align: justify;"> Serão apresentadas na tabela abaixo o mapeamento dos documentos e referência dos artefatos listados na tabela que será apresentada posteriormente.</p>

<center>

|          Artefato           |                                                        Documento                                                         |
| :-------------------------: | :----------------------------------------------------------------------------------------------------------------------: |
| Epicos, Historia de Usuario |    [Historia de Usuario](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Modelagem/historias_de_usuario/)     |
|         Requisitos          | [Moscow](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnica_de_priorizacao/Moscow/) |
|           Lexico            |    [Léxicos](https://requisitos-de-software.github.io/2021.2-ConecteSUS/An%C3%A1lise/Verifica%C3%A7%C3%A3o/Lexicos/)     |
|           Cenario           |   [Cenários](https://requisitos-de-software.github.io/2021.2-ConecteSUS/An%C3%A1lise/Verifica%C3%A7%C3%A3o/Cenarios/)    |
|          Categoria          |                 [Meta-modelo de Toranzo](https://labrasoft.ifba.edu.br/assets/files/pdf/Livro_AADSP.pdf)                 |

</center>

## 4. Tabela

| Épico                | Número | Requisitos                                                                                            | História de Usuário | Léxico                                             | Cenário                                              | Categoria                                  |
|:--------------------:|:------:|:-----------------------------------------------------------------------------------------------------:|:-------------------:|:--------------------------------------------------:|:----------------------------------------------------:|:------------------------------------------:|
| Épico 01: Conta      | RF01   | O usuário deve poder visualizar informações gerais sem efetuar o login.                               | US01                | -                                                  | -                                                    | Gerencial, Desenvolvimento                 |
| Épico 01: Conta      | RF02   | O usuário deve poder efetuar o login no gov.br com o CPF.                                             | US02                | L01: Entrar                                        | C01: Fazer login usando  o CPF                       | Gerencial, Desenvolvimento                 |
| Épico 01: Conta      | RF03   | O usuário deve poder escolher outras opções de identificação para login.                              | US03                | L01: Entrar                                        | C02: Fazer login com o seu banco                     | Gerencial, Desenvolvimento                 |
| Épico 01: Conta      | RF04   | O usuário deve poder ver a senha inserida.                                                            | US04                | L01: Entrar                                        | C01: Fazer login usando  o CPF                       | Gerencial, Desenvolvimento                 |
| Épico 01: Conta      | RF05   | O usuário deve ter uma alternativa de recuperação de senha caso tenha esquecido.                      | US05                | L01: Entrar                                        | C01: Fazer login usando  o CPF                       | Gerencial, Desenvolvimento                 |
| Épico 01: Conta      | RF06   | O usuário deve poder navegar entre todas as abas.                                                     | US06                | L01: Entrar                                        | -                                                    | Gerencial, Desenvolvimento                 |
| Épico 01: Conta      | RF36   | O usuário deve poder adicionar uma foto de perfil.                                                    | US07                | L15: Meu perfil                                    | C08: Mudar foto de perfil                            | Gerencial                                  |
| Épico 01: Conta      | RF37   | O usuário deve poder gerenciar suas contas.                                                           | US08                | L15: Meu perfil                                    | C08: Mudar foto de perfil                            | Gerencial                                  |
| Épico 01: Conta      | RF38   | O usuário deve poder visualizar os dados cadastrados.                                                 | US09                | L15: Meu perfil                                    | -                                                    | Gerencial                                  |
| Épico 01: Conta      | RF39   | O usuário deve poder visualizar as notícias relacionadas à saúde.                                     | US10                | L19: Noticias                                      | -                                                    | Organizacional, Ambiental                  |
| Épico 01: Conta      | RF40   | O usuário deve poder entrar em contato com o ConecteSUS para esclarecer dúvidas e problemas.          | US11                | L20: Fale com o ConecteSUS                         | -                                                    | Organizacional, Desenvolvimento            |
| Épico 01: Conta      | RF41   | O usuário deve poder verificar quais são os demais aplicativos do Ministério da Saúde.                | US12                | L21: Aplicativos MS                                | -                                                    | Organizacional, Desenvolvimento            |
| Épico 01: Conta      | RF42   | O usuário deve poder consultar as duvidas frequentes relacionadas ao aplicativo.                      | US13                | L22: Dúvidas frequentes                            | -                                                    | Organizacional, Desenvolvimento            |
| Épico 01: Conta      | RF43   | O usuário deve poder consultar ao termo de utilização e política de privacidade.                      | US14                | L23: Termo de utilização, L24: Termo de utilização | -                                                    | Ambiental                                  |
| Épico 01: Conta      | RF44   | O usuário deve poder avaliar o aplicativo.                                                            | US15                | L25: Avalie-nos                                    | -                                                    | Gerencial                                  |
| Épico 01: Conta      | RF45   | O usuário deve poder fazer logout.                                                                    | US16                | L26: Sair                                          | C05: Realizar Logout                                 | Gerencial, Desenvolvimento                 |
| Épico 01: Conta      | RF46   | O usuário deve ser redirecionado para o site de cadastro                                              | US17                | -                                                  |                                                      | Desenvolvimento                            |
| EP02: Históricos     | RF10   | O usuário deve poder acessar o certificado de vacinação da COVID-19 no menu rápido.                   | US18                | L17: Histórico, L02: Vacinas                       | C03: Emitir carteira nacional de vacinação           | Gerencial, Desenvolvimento                 |
| EP02: Históricos     | RF11   | O usuário deve poder alterar o idioma do certificado de vacina COVID-19.                              | US19                | L17: Histórico, L02: Vacinas                       | C03: Emitir carteira nacional de vacinação           | Gerencial, Desenvolvimento                 |
| EP02: Históricos     | RF12   | O usuário deve poder gerar um pdf do certificado de vacina COVID-19.                                  | US20                | L17: Histórico, L02: Vacinas                       | C03: Emitir carteira nacional de vacinação           | Gerencial, Desenvolvimento                 |
| EP02: Históricos     | RF13   | O usuário deve poder visualizar um QR Code para autenticar o certificado de vacina COVID-19.          | US21                | L17: Histórico, L05: Valida QRCode                 | C03: Emitir carteira nacional de vacinação           | Gerencial, Desenvolvimento                 |
| EP02: Históricos     | RF18   | O usuário deve poder ver as vacinas tomadas.                                                          | US22                | L17: Histórico, L02: Vacinas                       | -                                                    | Gerencial, Desenvolvimento                 |
| EP02: Históricos     | RF19   | O usuário deve poder informar se há algum problema com suas vacinas.                                  | US23                | L17: Histórico                                     | -                                                    | Gerencial, Desenvolvimento                 |
| EP02: Históricos     | RF20   | O usuário deve poder consultar seus exames de COVID-19.                                               | US24                | L17: Histórico, L03: Exames                        | C06: Ver resultados de exames                        | Gerencial, Desenvolvimento                 |
| EP02: Históricos     | RF21   | O usuário deve poder consultar seus medicamentos autodeclarados e recebidos.                          | US25                | L17: Histórico, L04: Medicamentos                  | C09: Consultar medicamento                           | Gerencial, Desenvolvimento                 |
| EP02: Históricos     | RF22   | O usuário deve poder adicionar um medicamento autodeclarado.                                          | US26                | L17: Histórico, L04: Medicamentos                  | C09: Consultar medicamento                           | Gerencial, Desenvolvimento                 |
| EP02: Históricos     | RF23   | O usuário deve poder consultar os dados de atendimentos e internações realizadas no SUS.              | US27                | L17: Histórico, L09: Atendimentos e internações    | C06: Ver resultados de exames                        | Gerencial, Desenvolvimento                 |
| Épico 03 - Registros | RF26   | O usuário deve poder adicionar e consultar contatos emergenciais.                                     | US28                | L18: Registro, L07: Contatos                       | C07: Adicionar contato de emergência                 | Gerencial, Desenvolvimento                 |
| Épico 03 - Registros | RF27   | O usuário deve poder adicionar e consultar seu registro de saúde.                                     | US29                | L18: Registro, L08: Minha saúde                    | -                                                    | Gerencial, Desenvolvimento                 |
| Épico 03 - Registros | RF28   | O usuário deve poder consultar as regras e doações de sangue já realizadas.                           | US30                | L18: Registro, L10: Doação de sangue               | C10: Acompanhar ou tirar dúvidas da doação de sangue | Gerencial, Desenvolvimento                 |
| Épico 03 - Registros | RF29   | O usuário deve poder adicionar e consultar seu registro de alergias.                                  | US31                | L18: Registro                                      | -                                                    | Gerencial, Desenvolvimento                 |
| EP04: Geral          | RF07   | O usuário deve poder acessar a carteira nacional de vacina no menu rápido.                            | US32                | L02: Vacinas                                       | C03: Emitir carteira nacional de vacinação           | Desenvolvimento, Organizacional            |
| EP04: Geral          | RF08   | 	O usuário deve poder alterar o idioma da carteira nacional de vacina.                                | US33                | L02: Vacinas                                       | C03: Emitir carteira nacional de vacinação           | Desenvolvimento, Organizacional            |
| EP04: Geral          | RF09   | O usuário deve poder gerar um pdf da carteira nacional de vacina.                                     | US44                | L02: Vacinas                                       | C03: Emitir carteira nacional de vacinação           | Desenvolvimento, Organizacional            |
| EP04: Geral          | RF14   | O usuário deve poder acessar o cartão do SUS no menu rápido.                                          | US45                | -                                                  | C04: Emitir cartão do SUS                            | Desenvolvimento, Organizacional            |
| EP04: Geral          | RF15   | O usuário deve poder compartilhar seu cartão do SUS.                                                  | US46                | -                                                  | C04: Emitir cartão do SUS                            | Desenvolvimento, Organizacional            |
| EP04: Geral          | RF16   | O usuário deve poder visualizar um QR Code para o cartão do SUS.                                      | US47                | L05: Valida QRCode                                 | C04: Emitir cartão do SUS                            | Desenvolvimento, Organizacional            |
| EP04: Geral          | RF17   | O usuário deve poder ver as informações principais no menu inicial.                                   | US48                | L16: Home                                          | -                                                    | Desenvolvimento, Organizacional            |
| EP04: Geral          | RF24   | O usuário deve poder validar um QR Code.                                                              | US49                | L05: Valida QRCode                                 | -                                                    | Gerencial, Desenvolvimento                 |
| EP04: Geral          | RF25   | O usuário deve poder consultar a localização dos estabelecimentos da rede de saúde.                   | US50                | L06: Rede de saúde                                 | -                                                    | Organizacional, Desenvolvimento, Ambiental |
| EP04: Geral          | RF30   | O usuário deve poder consultar informações sobre saúde alimentar.	                                    | US51                | L08: Minha saúde                                   | -                                                    | Desenvolvimento, Organizacional            |
| EP04: Geral          | RF31   | O usuário deve poder realizar um teste de alimentação.                                                | US52                | L08: Minha saúde                                   | -                                                    | Desenvolvimento, Organizacional            |
| EP04: Geral          | RF32   | O usuário deve poder ver consultas agendadas e a fila de espera.                                      | US53                | L13: Agendamento                                   | -                                                    | Desenvolvimento, Organizacional            |
| EP04: Geral          | RF33   | O usuário deve poder consultar informações sobre doações de órgãos.                                   | US54                | L14: Transplante                                   | -                                                    | Desenvolvimento, Organizacional            |
| EP04: Geral          | RF34   | O usuário deve poder acompanhar sua posição na fila do sistema nacional de transplantes.              | US55                | L14: Transplante                                   | -                                                    | Desenvolvimento, Organizacional            |
| EP04: Geral          | RF35   | O usuário deve poder ser redirecionado para a chamada telefônica da central nacional de transplantes. | US56                | L14: Transplante                                   | -                                                    | Desenvolvimento                            |



## 5. Bibliografia

> LEONHARDT, Rodrigo. 2019.
> SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 24. 2019.

## Histórico de Versão

| Versão |    Data    |       Descrição        |         Autor          |   Revisor    |
| :----: | :--------: | :--------------------: | :--------------------: | :----------: |
|  0.1   | 01/04/2022 |  Criação do documento  |        Gustave         | Ana Carolina |
|  0.2   | 01/04/2022 | Levantamento da tabela | Ricardo, Daniel, Erick | Ana Carolina |
