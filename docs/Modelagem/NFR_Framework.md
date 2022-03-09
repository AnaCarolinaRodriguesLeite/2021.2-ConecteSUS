# NFR Framework

## 1. Introdução
<p style="text-align: justify;">O NFR Framework é um método de expressar e analisar Requisitos Não-Funcionais que foi proposto por Chung na Universidade de Toronto, sendo esse método uma representação sistemática e global de NFRs, abordando de uma maneira qualitativa e orientada a processos. 
</p>

<p style="text-align: justify;">Seu objetivo é ajudar os desenvolvedores a implementar soluções customizadas, levando em consideração as características dos campos e sistemas relacionados. Essas características incluem requisitos não funcionais, requisitos funcionais, prioridades e cargas de trabalho. Essas condições determinam a escolha de alternativas de desenvolvimento para um determinado sistema.
</p>

<p style="text-align: justify;">É representado por meio de um grafo, chamado Softgoal Interdependency Graph (SIG), que registra as considerações do desenvolvedor sobre os softgoals e mostra suas interdependências, oferece técnicas de operacionalização e fornece catálogos para inferir possíveis interações.
</p>

<p style="text-align: justify;"> Os softgoals podem ser separados em 3 tipos: </p>

- <p style="text-align: justify;">NFR Softgoal: Característica abstrata, a qual se deseja considerar na análise, visando saber se a mesma será cumprida ou não cumprida, ou seja, escolhida ou não escolhida para ser implementada. São requisitos não funcionais, vistos como critérios/atributos de qualidade.</p>

- <p style="text-align: justify;">Operationalizing Softgoal: Forma concreta de viabilizar ou não as características abstratas. São funcionalidades.</p>

- <p style="text-align: justify;">Claim Softgoal(Argumentation): A notação que pode ser acrescentada ao modelo, argumentando algo sobre um ponto específico da modelagem. Escrita em linguagem natural.</p>

<p style="text-align: justify;"> Cada um desses Softgoals podem ser decompostos, e os tipos de decomposição são: </p>

- <p style="text-align: justify;">Decomposição de Softgoal NFR: refina ou subdivide um um softgoal NFR em outros específicos. Isso pode ajudar a dividir grandes problemas em problemas menores e oferece um aspecto útil para lidar com ambiguidades e prioridades.</p>

- <p style="text-align: justify;">Decomposição de Operacionalização: subdivide um softgoal de operacionalização em outros softgoals de operacionalização mais específicos. Operacionalizações são úteis para definir uma solução geral e refiná-la em soluções mais específicas.</p>

- <p style="text-align: justify;">Decomposição de Afirmação (Claims): refina um softgoal de afirmação em outros softgoals de afirmação. Ela é importante para apoiar ou negar justificativas específicas de projeto.</p>

- <p style="text-align: justify;">Priorização: A priorização é um tipo especial de decomposição, onde ocorre o refinamento de um softgoal em outro softgoal com o mesmo tipo e tópicos, mas com uma prioridade associada.</p>


<p style="text-align: justify;">As decomposições são especificações dos softgoals, ou seja, alterações no estado de um softgoal filho geram alterações no softgoal pai, e essas alterações são chamadas de contribuições. Essas contribuições são:</p>

Contribuição | Descrição
-|-
AND | se os softgoals descendentes forem satisfeitos os softgoals ascendentes também são.
OR | se algum softgoal descendente for satisfeito, o ascendente é satisfeito.
MAKE(++) | se o softgoal descendente for satisfeito o softgoal pai também é.
BREAK(--) | se o softgoal descendente for suficientemente satisfeito, o softgoal pai é negado.
HELP(+) | se o softgoal descendente for parcialmente satisfeito, o softgoal ascendente será parcialmente satisfeito.
HURT(-) | se o softgoal descendente for satisfeito, o softgoal ascendente será parcialmente negado.
UNKNOWN(?) | fornece uma contribuição desconhecida entre um softgoal descendente e um ascendente, e pode ser tanto positiva quanto negativa.
EQUALS | o softgoal descendente só será satisfeito se o softgoal ascendente for satisfeito / o softgoal descendente será negado se o softgoal ascendente for negado.
SOME (+\|-) | usado se o sinal da contribuição é conhecido, mas a extensão(parcial ou total) não é. 

<center> <figcaption>Tabela 1: Contribuições.</figcaption> </center>


## 2. Metodologia

<p style="text-align: justify;">Através desse documento, buscamos definir as funcionalidades dos requisitos não-funcionais através da implementação de diagramas utilizando o NFR Framework, criando análises das possíveis situações.
</p>


## 3. Requisitos Funcionais

<p style="text-align: justify;"> Abaixo estão listados os requisitos não-funcionais levantados pelas das técnicas de elicitação utilizadas no projeto, que serão os mesmos utilizados no NFR Framework.
</p>


| ID     | Requisitos            | Técnica utilizada |
| ------ | --------------------- | :---------------: |
| RNF 01 | O aplicativo não pode demorar muito para abrir. | [ITP21](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/introspeccao/#31-requisitos-funcionais), [SB12](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/storytelling/#5-requisitos-nao-funcionais) |
| RNF 02 | O aplicativo não pode ficar indisponível.  |  [ITP22](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/introspeccao/#31-requisitos-funcionais), [SB14](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/storytelling/#5-requisitos-nao-funcionais)  |
| RNF 03 | Os usuários devem conseguir encontrar a funcionalidade desejada rapidamente. | [ITP23](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/introspeccao/#31-requisitos-funcionais), [SB13](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/storytelling/#5-requisitos-nao-funcionais) |
| RNF 04 | O aplicativo deve proteger os dados dos usuários.  |  [ITP24](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/introspeccao/#31-requisitos-funcionais), [SB15](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/storytelling/#5-requisitos-nao-funcionais) |
| RNF 05 | O aplicativo deve apresentar persistência de login. | [BT20](https://requisitos-de-software.github.io/2021.2-ConecteSUS/Elicita%C3%A7%C3%A3o/Tecnicas_de_elicitacao/brainstorming/#5-levantamento-de-requisitos)  |


<center> <figcaption>Tabela 2: Requisitos não funcionais.</figcaption> </center>




## 4. Legenda

<center>

![elementos_do_NFR_Framework](https://user-images.githubusercontent.com/49570180/157316868-0d2e5154-355f-490d-9696-7ac1c898d155.jpeg)

</center>

<center>

  <figcaption>
      <b>Imagem 1: Elementos de definição do NFR Framework.</b>
    <br><small>Fonte: própria</small>
  </figcaption>

</center>


<center>

![elementos_de_relacionamento](https://user-images.githubusercontent.com/49570180/157317602-00134891-0e25-4de3-8e14-d5983c8b7daf.jpeg)


</center>

<center>

  <figcaption>
      <b>Imagem 2: Elementos de relacionamento do NFR Framework.</b>
    <br><small>Fonte: própria</small>
  </figcaption>

</center>


## 5. Diagramas

### 5.1 Confiabilidade

<center>

![Confiabilidade_NFR](https://user-images.githubusercontent.com/49570180/157367881-d2edf258-6af0-4168-9a56-4afaef00b94a.jpeg)

</center>

<center>

  <figcaption>
      <b>Imagem 3: Diagrama NFR Framework de Confiabilidade.</b>
    <br><small>Fonte: própria</small>
  </figcaption>

</center>

#### 5.1.1 Com propagação

<center>

![Confiabilidade_satisfatorio](https://user-images.githubusercontent.com/49570180/157367890-9475074b-c003-4430-9471-c7627f92ac15.jpeg)

</center>

<center>

  <figcaption>
      <b>Imagem 4: Diagrama NFR Framework de Usabilidade com propagação.</b>
    <br><small>Fonte: própria</small>
  </figcaption>

</center>

### 5.2 Perfomance

<center>

![Perfomance_NFR](https://user-images.githubusercontent.com/49570180/157367908-0baa83d1-0427-4f8d-9599-d311c27ad8d1.jpeg)

</center>

<center>

  <figcaption>
      <b>Imagem 5: Diagrama NFR Framework de Perfomance.</b>
    <br><small>Fonte: própria</small>
  </figcaption>

</center>

#### 5.2.1 Com propagação

<center>

![Perfomance_satisfatorio](https://user-images.githubusercontent.com/49570180/157367956-c7ddce92-1d3a-4e17-92ca-7382dff86a91.jpeg)

</center>

<center>

  <figcaption>
      <b>Imagem 6: Diagrama NFR Framework de Perfomance com propagação.</b>
    <br><small>Fonte: própria</small>
  </figcaption>

</center>

### 5.3 Usabilidade

<center>

![Usabilidade_NFR](https://user-images.githubusercontent.com/49570180/157367975-8a7e9d96-eef9-41dd-b0d7-158bd04b8b2f.jpeg)

</center>

<center>

  <figcaption>
      <b>Imagem 7: Diagrama NFR Framework de Usabilidade.</b>
    <br><small>Fonte: própria</small>
  </figcaption>

</center>

#### 5.3.1Com propagação

<center>

![Usabilidade_satisfatorio](https://user-images.githubusercontent.com/49570180/157367983-8ff8c777-98d2-434b-b0f0-818789ebb2b1.jpeg)

</center>

<center>

  <figcaption>
      <b>Imagem 8: Diagrama NFR Framework de Usabilidade com propagação.</b>
    <br><small>Fonte: própria</small>
  </figcaption>

</center>


## Bibliografia

>Guardiões da Saúde. Disponível em: https://github.com/Requisitos-de-Software/2020.1-GuardioesdaSaude/blob/master/docs/modelagem/NFR.md . Acesso em: 08/03/2022.

>Disney Plus. Disponível em: https://requisitos-de-software.github.io/2021.1-DisneyPlus/modelagem/nfr_framework/#1-introducao. Acesso em: 08/03/2022.

>MetroDF. Disponível em: https://requisitos-de-software.github.io/2021.1-MetroDF/Modelagem/nfr/#com-propagacao_4 . Acesso em: 08/03/2022.



## Histórico de Versão

| Versão |    Data    |  Descrição | Autor | Revisor |
| :----: | :--------: | :--------: | :---: | :-----: |
|  0.1   | 08/03/2022 | Criação do documento: Introdução, Metodologia, Requisitos Funcionais, Legenda, Diagramas, Bibliografia | Ana Carolina | Erick |
|  0.2   | 09/03/2022 | Revisão do documento | Erick | - |
