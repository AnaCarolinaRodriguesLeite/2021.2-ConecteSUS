## Cenários

## 1. Introdução
<p align = "justify">
Um cenário nada mais é do que uma história curta ou uma descrição de um evento impactando as operações de um aplicativo. 
Os cenários são úteis para adicionar detalhes a um requisito. Trata-se de descrições de iterações do usuário com o sistema cobrindo um pequeno número de interações possíveis.
Diferentes cenários são desenvolvidos e oferecem diversos tipos de informação em variados níveis do sistema.
</p>

## 2. Metodologia
<p align = "justify">
Cenários são formas reconhecidas afim de compreender as interações entre ambientes e sistemas, para definir fluxos na parte comportamental do software. No nosso cenário, fizemos, os objetivos descreve a meta para o cenário, contexto são condições e pré condições para o cenário ter êxito, atores são os próprios Usuários, excessão são situações que os usuários não irão conseguir reproduzir os cenários e os epsódios são o detalhamento do cenário para o funcionamento do mesmo.
</p>

## 3. Cenários

###C01 - Fazer login usando CPF

| Objetivo  | Usuário fazer login usando CPF                                                                                                              |
|-----------|---------------------------------------------------------------------------------------------------------------------------------------------|
| Contexto  | Local: Tela do aplicativo<br> Tempo: 1 minuto <br>Pré-condição: Conhecer as credencias da sua conta e possuir acesso a internet                     |
| Atores    | Usuário                                                                                                                                     |
| Recursos  | Smartphone<br>Desktop<br>Tablet<br>Acesso a internet<br>Conta no gov.com.br                                                                             |
| Excessão  | Falta de energia<br> Smartphone ou Tablet descarregado <br>Perda de conexão com a internet <br>Não possuir conta no gov.com.br<br> Usuário esqueceu a senha |
| Episódios | Usuário abre o aplicativo<br> Usuário clica em entrar com a conta gov.com.br<br> Usuário digita o CPF<br> Usuário digita a senha<br> Usuário clica em entrar        |

###C02 - Fazendo login com o seu banco

| Objetivo  | Usuário fazer login usando o banco                                                                                                             |
|-----------|---------------------------------------------------------------------------------------------------------------------------------------------|
| Contexto  | Local: Tela do aplicativo<br> Tempo: 1 minuto <br>Pré-condição: Conhecer as credencias da sua conta e possuir acesso a internet                     |
| Atores    | Usuário                                                                                                                                     |
| Recursos  | Smartphone<br>Desktop<br>Tablet<br>Acesso a internet<br>Conta no gov.com.br                                                                             |
| Excessão  | Falta de energia<br> Smartphone ou Tablet descarregado <br>Perda de conexão com a internet <br>Não possuir conta no gov.com.br<br> Usuário esqueceu a senha |
| Episódios | Usuário abre o aplicativo<br> Usuário clica em login com o seu banco<br> Usuário seleciona o seu banco<br> Usuário digita sua agência<br> Usuário digita sua conta<br> Usuário digita senha<br> Usuário clica em entrar       |

###C03 - Emititir carteira nacional de vacinação

| Objetivo  | Usuário gerar carteira nacional de vacinação                                                                                                             |
|-----------|---------------------------------------------------------------------------------------------------------------------------------------------|
| Contexto  | Local: Tela do aplicativo<br> Tempo: 1 minuto <br>Pré-condição: Conhecer as credencias da sua conta e possuir acesso a internet                     |
| Atores    | Usuário                                                                                                                                     |
| Recursos  | Smartphone<br>Desktop<br>Tablet<br>Acesso a internet<br>Conta no gov.com.br                                                                             |
| Excessão  | Falta de energia<br> Smartphone ou Tablet descarregado <br>Perda de conexão com a internet <br>Usuário não estiver logado<br> Usuário não estar vacinado com pelo menos duas doses |
| Episódio 1 | Usuário clica no icone de carteira no centro inferior da tela<br> Usuário clica na opção Carteira Nacional de Vacinação que irá aparecer  |
| Episódio 2 | Usuário clica no opção de vacinas no canto esquerdo da tela<br> Usuário clica em cima das doses <br> Usuário clica na opção Carteira Nacional de Vacinação que irá aparecer  |

###C04 - Emitir cartão do SUS

| Objetivo  | Usuário emitir cartão do SUS                                                                                                              |
|-----------|---------------------------------------------------------------------------------------------------------------------------------------------|
| Contexto  | Local: Tela do aplicativo<br> Tempo: 1 minuto <br>Pré-condição: Conhecer as credencias da sua conta e possuir acesso a internet                     |
| Atores    | Usuário                                                                                                                                     |
| Recursos  | Smartphone<br>Desktop<br>Tablet<br>Acesso a internet<br>Conta no gov.com.br                                                                             |
| Excessão  | Falta de energia<br> Smartphone ou Tablet descarregado <br>Perda de conexão com a internet <br>Usuário não estiver logado<br>  |
| Episódio  | Usuário clica no icone de carteira no centro inferior da tela<br> Usuário clica na opção Cartão do SUS |

###C05 - Realizar Logout

| Objetivo  | Usuário fazer logout                                                                                                             |
|-----------|---------------------------------------------------------------------------------------------------------------------------------------------|
| Contexto  | Local: Tela do aplicativo<br> Tempo: 30 segundos <br>Pré-condição: Conhecer as credencias da sua conta e possuir acesso a internet                     |
| Atores    | Usuário                                                                                                                                     |
| Recursos  | Smartphone<br>Desktop<br>Tablet<br>Acesso a internet<br>Conta no gov.com.br                                                                             |
| Excessão  | Falta de energia<br> Smartphone ou Tablet descarregado <br>Perda de conexão com a internet <br>Usuário não estiver logado<br>|
| Episódio  | Usuário clica na opção de "mais" no canto inferior direito<br> Usuário clica em Sair |

###C06 - Ver resultados de exames

| Objetivo  | Usuário deve poder gerar um PDF do resultado dos seus exames                                                             |
|-----------|---------------------------------------------------------------------------------------------------------------------------------------------|
| Contexto  | Local: Tela do aplicativo<br> Tempo: 30 segundos <br>Pré-condição: Conhecer as credencias da sua conta e possuir acesso a internet                     |
| Atores    | Usuário                                                                                                                                     |
| Recursos  | Smartphone<br>Desktop<br>Tablet<br>Acesso a internet<br>Conta no gov.com.br                                                                             |
| Excessão  | Falta de energia<br> Smartphone ou Tablet descarregado <br>Perda de conexão com a internet <br>Usuário não estiver logado<br> Não ter feito algum exame|
| Episódio  | Usuário clica na opção de "Exames" no centro da tela<br> Usuário clica no exame que deseja ver o resultado <br> Usuário clica no icone de documento, gerando o PDF com o resultado |

###C07 - Adicionar contato de emergência

| Objetivo  | Usuário tem que adicionar um contato de emergência na aba registros                                                            |
|-----------|---------------------------------------------------------------------------------------------------------------------------------------------|
| Contexto  | Local: Tela do aplicativo<br> Tempo: 45 segundos <br>Pré-condição: Conhecer as credencias da sua conta e possuir acesso a internet                     |
| Atores    | Usuário                                                                                                                                     |
| Recursos  | Smartphone<br>Desktop<br>Tablet<br>Acesso a internet<br>Conta no gov.com.br                                                                             |
| Excessão  | Falta de energia<br> Smartphone ou Tablet descarregado <br>Perda de conexão com a internet <br>Usuário não estiver logado<br>|
| Episódio  | Usuário clica na opção de "Registro" na parte inferior da tela<br> Usuário clica na opção de contatos no canto superior esquerdo <br> Usuário clica na opção adicionar contato <br> Usuário seleciona contato de emergência<br>Usuário clica em continuar<br>Usuário preenche o nome e telefone do contato de emergência<br>Usuário clica em adicionar|

###C08 - Mudar foto de perfil

| Objetivo  | Adicionar uma foto de perfil                                                            |
|-----------|---------------------------------------------------------------------------------------------------------------------------------------------|
| Contexto  | Local: Tela do aplicativo<br> Tempo: 45 segundos <br>Pré-condição: Conhecer as credencias da sua conta e possuir acesso a internet                     |
| Atores    | Usuário                                                                                                                                     |
| Recursos  | Smartphone<br>Desktop<br>Tablet<br>Acesso a internet<br>Conta no gov.com.br                                                                             |
| Excessão  | Falta de energia<br> Smartphone ou Tablet descarregado <br>Perda de conexão com a internet <br>Usuário não estiver logado<br>|
| Episódio  | Usuário clica no icone de perfil no canto superior direito<br> Usuário clica no ícone de lápis<br>Usuário seleciona uma foto pela camêra ou a galeria de fotos |

###C09 - Consultar medicamentos

| Objetivo  | Usuário pode ver detalhes dos seus medicamentos autodeclarados ou recebidos                                                         |
|-----------|---------------------------------------------------------------------------------------------------------------------------------------------|
| Contexto  | Local: Tela do aplicativo<br> Tempo: 1 minuto <br>Pré-condição: Conhecer as credencias da sua conta,possuir acesso a internet e receber medicamentos pelo governo                 |
| Atores    | Usuário                                                                                                                                     |
| Recursos  | Smartphone<br>Desktop<br>Tablet<br>Acesso a internet<br>Conta no gov.com.br                                                                             |
| Excessão  | Falta de energia<br> Smartphone ou Tablet descarregado <br>Perda de conexão com a internet <br>Usuário não estiver logado<br>|
| Episódio  | Usuário clica no icone medicamentos ao centro da tela <br> Usuário seleciona a opção de autodeclarado ou recebido<br>Usuário clica nos medicamentos que deseja adicionar em autodeclarados ou acompanhar nos recebidos |

###C10 - Acompanhar ou tirar dúvidas da doação de sangue

| Objetivo  | Usuário pode ver detalhes das suas doações passadas ou tirar dúvidas de como doar sangue                                                         |
|-----------|---------------------------------------------------------------------------------------------------------------------------------------------|
| Contexto  | Local: Tela do aplicativo<br> Tempo: 1 minuto <br>Pré-condição: Conhecer as credencias da sua conta, possuir acesso a internet e ter doado sangue                   |
| Atores    | Usuário                                                                                                                                     |
| Recursos  | Smartphone<br>Desktop<br>Tablet<br>Acesso a internet<br>Conta no gov.com.br                                                                             |
| Excessão  | Falta de energia<br> Smartphone ou Tablet descarregado <br>Perda de conexão com a internet <br>Usuário não estiver logado<br> |
| Episódio  | Usuário clica no icone de doações de sangue <br> Usuário clica na opção de minhas doações ou regras|

## Bibliografia 

> SERRANO, Maurício; SERRANO, Milene; Requisitos - Aula 10;

## Histórico de Versão

| Versão | Data       | Descrição                                 | Autor        | Revisor  |
| ------ | ---------- | ----------------------------------------- | ------------ | -------- |
| 0.1    | 03/03/2022 | Criação dos cenários                      | Ricardo e Daniel | Erick  |
| 0.2    | 04/03/2022 | Revisando e fazendo pequenas correções    |      Erick       |   -    |
