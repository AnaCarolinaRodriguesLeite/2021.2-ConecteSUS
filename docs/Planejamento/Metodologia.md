# Metodologia

## 1. Métodos ágeis

<p style="text-align: justify;">Os métodos ágeis são projetados para produzir software útil rapidamente. Eles são baseados no desenvolvimento incremental. Os incrementos são pequenos e uma nova versão do sistema geralmente é criada e fornecida aos clientes a cada duas ou três semanas, para que seja possível obter um feedback rapidamente sobre as mudanças nos requisitos. Além disso, esses métodos minimizam a documentação usando comunicação informal no lugar de reuniões formais com documentos escritos.
</p>

<p style="text-align: justify;">Os métodos ágeis consideram o design e a implementação como atividades centrais no processo de software. Eles incorporam outras tarefas a essas atividades, como a elicitação dos requisitos e os testes. Apesar de existirem diversos processos ágeis, todos compartilham um conjunto de princípios com base no manifesto ágil e foi descrito por Sommerville, Ian (2019, p. 61):
</p>

<center>

| Princípio               | Descrição                                                                                                                                                                                                                            |
| ----------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Envolvimento do cliente | Os clientes devem ser envolvidos em todo o processo de desenvolvimento. Seu papel é fornecer e priorizar novos requisitos de sistema e avaliar as iterações do sistema.                                                              |
| Acolher as mudanças     | Tenha em mente que os requisitos do sistema mudam e, portanto, deve-se projetar o sistema para acomodar essas mudanças.                                                                                                              |
| Entrega incremental     | O software é desenvolvido em incrementos e o cliente especifica os requisitos incluídos em cada um deles.                                                                                                                            |
| Manter a simplicidade   | Deve-se ter como foco a simplicidade, tanto do software que está sendo desenvolvido quanto do processo de desenvolvimento. Sempre que possível, trabalhe ativamente para eliminar a complexidade do sistema.                         |
| Pessoas, não processos  | As habilidades do time de desenvolvimento devem ser reconhecidas e aproveitadas da melhor maneira possível. Seus membros devem ter liberdade para desenvolver seu modo próprio de trabalhar sem se prender a processos determinados. |

<figcaption>Tabela 1: Princípios dos métodos ágeis.</figcaption>

</center>

## 2. Extreme Programming (XP)

<p style="text-align: justify;">Extreme Programming, mais conhecido como XP, é uma metodologia ágil de desenvolvimento de software que tem como objetivo produzir software de alta qualidade e, também, melhor qualidade de vida para a equipe de desenvolvimento. A metodologia XP capacita seus desenvolvedores a lidarem com confiança às mudanças nos requisitos do cliente, mesmo no final do ciclo de vida. Além disso, Don Wells (1999) diz que a XP é configurada para pequenos grupos de programadores. A equipe XP inclui não apenas os desenvolvedores, mas também os gerentes e clientes, todos trabalhando juntos.
</p>

<p style="text-align: justify;">Os requisitos se baseiam em histórias simples dos clientes (histórias de usuário) e são utilizados como base para decidir qual funcionalidade deve ser incluída em um determinado incremento. Os programadores trabalham em pares (pair programming) e desenvolvem testes para cada tarefa antes de escreverem o código. Todos os testes devem ser executados com sucesso quando o novo código é integrado ao sistema, já que há um curto intervalo de tempo entre as releases do sistema.
</p>

<center>

![ciclo_de_vida_XP](https://user-images.githubusercontent.com/49570180/152994415-c9265c11-c7d7-49ca-9bc5-62422dd20ddc.png)

 <figcaption>
      <b>Imagem 1: Ciclo de release da XP.</b>
    <br><small>Fonte: forbes</small>
  </figcaption>

</center>

## 3. Scrum

<p style="text-align: justify;"> Scrum é um método ágil, iterativo e incremental para gerenciamento de projetos, que não necessariamente precisam ser projetos de desenvolvimento de software. Dentre os métodos ágeis, Scrum é o mais conhecido e usado. Por meio da organização das tarefas e prioridades que o Scrum estabelece, passa a ser possível garantir o cumprimento de prazos e um maior foco nas diretrizes estabelecidas pelo planejamento. Sabendo quais são as atividades que possuem mais importância, as equipes consegue organizar melhor o fluxo de uma para a outra.
</p>

<p style="text-align: justify;"> O Scrum utiliza o product backlog que é um registro que contém as áreas do produto que devem ser desenvolvidas. De acordo com a prioridade de cada produto, cria-se uma lista de tarefas de liberação a partir da lista de tarefas de produtos, que é o ponto de conexão para que as necessidades da lista de tarefas de produtos sejam processadas. Publicar uma tarefa é um ponto na criação de uma tarefa do sprint e representa o período de tempo para a conclusão de uma tarefa (chamada de história de usuário).
</p>

<center>

![scrum](https://user-images.githubusercontent.com/49570180/152995506-4d54c8a7-bf17-4d7b-84da-f388dd922200.png)

  <figcaption>
      <b>Imagem 2: Ciclo de sprint do Scrum.</b>
    <br><small>Fonte: caetreinamentos</small>
  </figcaption>

</center>

## 4. Kanban

<p style="text-align: justify;"> O método Kanban é projetado para causar mudanças evolutivas em seu gerenciamento de maneira não disruptiva. Implementando pequenas mudanças em vez de grandes mudanças, o risco de resistência de sua equipe é reduzido. A abordagem incremental a esta abordagem tem pouca ou nenhuma resistência de sua equipe ou partes interessadas. A primeira etapa é criar um Kanban para visualizar o fluxo de trabalho. O Quadro Kanban é dividido em colunas, da seguinte forma:
</p>
<p style="text-align: justify;"> A primeira coluna é o backlog do produto. Como em Scrum, usuários escrevem as histórias, que vão para o Backlog. </p>

<p style="text-align: justify;"> As demais colunas são os passos que devem ser seguidos para transformar uma história do usuário em uma funcionalidade executável. A ideia, portanto, é que as histórias sejam processadas passo a passo, da esquerda para a direita, como em uma linha de montagem. Além disso, cada coluna é dividida em duas sub-colunas: em execução e concluídas. As tarefas concluídas em um passo estão aguardando serem puxadas, por um membro do time, para o próximo passo. Por isso, Kanban é chamado de um sistema pull.
</p>

<center>
 
![kanbam](https://user-images.githubusercontent.com/49570180/152995674-42fbcb34-85f2-408a-a62d-125d0e086531.jpg)

  <figcaption>
      <b>Imagem 3: Exemplo de quadro Kanban.</b>
    <br><small>Fonte: UFMG</small>
  </figcaption>

</center>

## Bibliografia

>SOMMERVILLE, Ian. 2011. Engenharia de software. 10. ed. São Paulo: Pearson Addison Wesley, 2019.

>Metodologia Ágil: O que é Kanban. Programadores Brasil, 2020. Disponível em: https://programadoresbrasil.com.br/2020/02/metodologia-agil-o-que-e-kanban/ . Acesso: 08/02/2022.

>Extreme Programming. Agile Alliance. Disponível em: https://www.agilealliance.org/glossary/xp/#.YRnn2znQQyc . Acesso: 08/02/2022.

>Metodologia Ágil: O que é Scrum. Programadores Brasil, 2020. Disponível em: https://programadoresbrasil.com.br/2020/02/o-que-e-scrum-metodologia-agil/ . Acesso: 08/02/2022.


## Histórico de versão

| Versão | Data       | Descrição                                 | Autor        | Revisor        |
| ------ | ---------- | ----------------------------------------- | ------------ | ------------ |
| 0.1    | 08/02/2022 | Criação da primeira versão metodologia    | Ana Carolina | Ricardo Loureiro |
| 0.2    | 08/02/2022 | Correção das imagens                      | Ana Carolina | Ricardo Loureiro |
|    0.3   | 20/02/2022 |  Revisão  da v0.1 e v0.2 | Ricardo Loureiro  | - |
