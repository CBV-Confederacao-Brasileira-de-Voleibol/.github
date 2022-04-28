<h1 align="center">Projeto : CBV-Confederacao-Brasileira-de-Voleibol</h1>



<p>Projeto da disciplina  Tópicos Especiais em Engenharia de Software, compreende um sistema web para gerenciamento e controle da SUPERLIGA BRASILEIRA DE VÔLEI, sobre a Orietação do professor Alexandre Rafael Lenz</p>


Menu
=================
<!--ts-->
   * [Definition of Done](#Definition-of-Done)
      * [Estória](#Estória)
      * [Sprint](#Sprint)
      * [Release](#Release)
      * [Em Caso de Mudanças de Requisitos](#Em-Caso-de-Mudanças-de-Requisitos)
   * [Reuniões](#tabela-de-conteudo)
   * [Dev Team](#Dev-Team)
   * [Arquitetura](#Arquitetura)
   * [Tecnologias e Ferramentas](#Tecnologias-e-Ferramentas)
   * [User Stories](#User-Stories)
   * [Requisitos Não Funcionais](#Requisitos-Não-Funcionais)
   * [Riscos](#Riscos)
<!--te-->

Definition of Done
=================

Estória
-----------------
 <p align="center" >📀 Estória descrita de maneira clara e incluída no Product Backlog no Trello deve apresentar os seguintes pontos.</p>

👉 Deve ser independente.

👉 Deve ser flexível.

👉 Deve agregar valor ao usuário.

👉 Deve ser estimável.

👉 Deve ser realizável em uma Sprint.

👉 Deve ser testável.

<p align="center"> 📀 Estória implementada por completo quando a mesma segue e satisfaz os seguintes critérios.</p>

👉 Reunião de planejamento de estimativas, para estimar o esforço para desenvolver cada estória.

👉 Código implementado e  armazenado e versionado no gitHub.

👉 Deve ser criado um branch no git  para o desenvolvimento de cada estória.

👉 Realizado Teste funcional de cada serviço da Api através da ferramenta jest utilizando TDD,que deve ser armazenado em uma pasta “test” de cada serviço.

👉 Os erros encontrados em cada teste precisam ser informados em cada estórias no trello,  a mesma deve ser movida para lista de Bugs no trello.

👉 Todos os defeitos encontrados nos testes foram  corrigidos.

👉 Documentação atualizada: Diagrama de entidade-relacionamento e  documentação das rotas da API com Swagger.

👉 Todas as Documentações devem ser armazenadas no Trello na lista de Documentação.

👉 Merge realizado na branch developer do projeto no github.

👉 Movida para lista de concluídos no trello em seu determinado agrupamento (Back-End  e Front-End) 


Sprint
-----------------

<p align="center"> 📀 Uma sprint  está pronta para ser iniciada quando apresentar os seguintes pontos:</p>

👉 Reunião de planejamento de sprint.

👉 Realizado a priorização  das estorias que serão implementadas na sprint. 

👉 Realizar a priorização das estorias que precisar ter revisão de código, deve ser destacado na descrição da tarefa do trello.

👉 Definindo o tempo de duração da sprint.

👉 Aprovação da Dev teams.

👉 Aprovação do Product Owner. 

<p align="center"> 📀 Uma sprint implementada por completo quando a mesma satisfazer os seguintes critérios:</p>  

👉 Daily scrum (reuniões de cerca 15 minutos realizadas nas segundas e quintas).

👉 Todas as estórias de usuário priorizadas para a Sprint foram concluídas.

👉 Código das estória de usuário foi revisado por pelo menos um integrante do dev team (apenas para as que necessita de revisão). Informações de revisão foram armazenadas no trello em cada card de estória.

👉 Teste de integração Front-End com Back-End realizado e armazenado no git.

👉 Todos os defeitos encontrados nos testes foram corrigidos.

👉 Back-End e Front-End integrado. 

👉 Reunião de revisão da Sprint realizada.

Release
-----------------
<p align="center"> 📀 A release estará  implementada por completo quando a mesma satisfazer os seguintes critérios:</p>


👉 Código Completo (todas as metas da sprint foram cumpridas).

👉 Todos os defeitos encontrados no release foram corrigidos.

👉 Merge realizado na branch master do projeto no github.

👉 Todas as documentações atualizadas e finalizadas.

👉 Deploy da API back-end no heroku.

👉 Deploy front-end no vercel.

👉 Documento de entrega de qualidade de testes(apenas na última release).

👉 Release aprovado pelo Product Owner.

Em caso de mudanças de requisitos
-----------------

<p align="center"> 📀 Detalha  quais passos devem ser seguidos em caso de mudanças de requisitos durante o desenvolvimento do projeto:</p>

👉 Deve ser realizada uma reunião com Dev Team e Product Owner.

👉 Deve ser analisado os impactos  das mudanças. 

👉 Deve ser analisado se a mudança entra na sprint atual ou na próxima.

👉 Caso a mudança tenha  necessidade de entrar no sprint atual deve ser analisado se existe a necessidade de aumentar o tempo da sprint ou não. 

👉 Aprovação do Dev Team e Product Owner. 

Reuniões
=================


Dev Team
=================

<table border="1">
<tr>
  <th>Nome</th>
  <th>Cargo</th>
</tr>
<tr>
  <td>Matheus souza</td>
  <td>Scrum Master</td>
<tr>
  <tr>
  <td>Luana Gomes</td>
  <td>Especialista em testes QA</td>
<tr>
  <tr>
  <tr>
  <td>Yan e Wesley</td>
  <td>Implementador Front-En</td>
<tr>
  <tr>
  <tr>
  <td>Murilo Andrade e  Matheus Souza</td>
  <td>Implementador Back-End </td>
<tr>
</table>



Arquitetura
=================

![Arquitetura](https://drive.google.com/file/d/1GKb-tg8nxm7tCXvGZi6-v7uPonkDcDUf/view?usp=sharing)


Tecnologias e Ferramentas
=================

<p>As seguintes ferramentas foram usadas na construção do projeto:</p>

- [Docker](https://www.docker.com/)
- [NodeJS](https://nodejs.org/en/)
- [Next JS](https://nextjs.org/)
- [TypeOrm](https://typeorm.io/)
- [Jest](https://jestjs.io/pt-BR/)
- [Swagger](https://swagger.io/)
- [Trello](https://trello.com/pt-BR)
- [PostgresSQL](https://www.postgresql.org/)
- [Heroku](https://www.heroku.com/)
- [Vercel:](https://vercel.com/)

User Stories
=================

Requisitos Não Funcionais
=================

<table border="1">
<tr>
  <th>Código</th>
  <th>Descrição</th>
</tr>
<tr>
    <td>RNFx 1</td>
    <td>Permitir acesso via a qualquer browser</td>
</tr>
<tr>
    <td>RNFx 2</td>
    <td>O sistema deve apresentar o mínimo possível de falhas, mas não garante que o mesmo não esteja livre de erros ou interrupções</td>
</tr>
<tr>
    <td>RNFx 3</td>
    <td>Qualquer funcionalidade de cadastros, devem ser realizadas por usuários autenticados</td>
</tr>
<tr>
    <td>RNFx 4</td>
    <td>O sistema deve facilitar a utilização e compreensão de sua interface por parte dos usuários, além de buscar facilitar que o utilizador tenha em alcançar os seus objetivos</td>
</tr>
<tr>
    <td>RNFx 5</td>
    <td>O sistema deve estar disponível 24 horas por dia em todos os dias, inclusive domingo e feriados</td>
</tr>
</table>


Riscos
=================

<table border="1">
<tr>
  <th>Código</th>
  <th>Descrição</th>
  <th>Impacto</th>
  <th>Ação</th>
  <th>Descrição da Ação</th>
</tr>
<tr>
  <td>Rx 1</td>
  <td>Não entregar o produto no prazo</td>
  <td>Insatisfação do cliente e aumento no orçamento previsto</td>
  <td>Mitigar</td>
  <td>Desenvolvimento de cronograma bem detalhado e viável, além de reduzir o tamanho do caminho crítico do projeto</td>
</tr>
<tr>
  <td>Rx 2</td>
  <td>Tecnologias não conhecidas por alguns membros da equipe</td>
  <td>Aumento no prazo de entrega do produto.</td>
  <td>Mitigar</td>
  <td>Os membros que possui mais conheciment com as tecnologia deve realizar suporte aos demais</td>
</tr>
<tr>
  <td>Rx 3</td>
  <td>Alterações no escopo do projeto</td>
  <td>Aumento no prazo de entrega do produto.</td>
  <td>Mitigar</td>
  <td>Validação do escopo do projeto com o cliente, deixando claro as consequências caso aconteça</td>
</tr>
<tr>
  <td>Rx 4</td>
  <td>Ausência de membros da equipe por problemas de saúde</td>
  <td>Atraso em cascata nas entregas do projet.</td>
  <td>Mitigar</td>
  <td>Distribuição das atividades do membro ausente para os demais do grupo</td>
</tr>
 <tr>
  <td>Rx 5</td>
  <td>Comunicação ruim com os envolvidos</td>
  <td>Atraso nas entregas do projeto.</td>
  <td>Mitigar</td>
  <td>Reuniões de acompanhamento semanalmente</td>
</tr>
</table>



