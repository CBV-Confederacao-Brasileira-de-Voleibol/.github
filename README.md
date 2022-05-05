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
<table border="1">
<tr>
  <th>Descrição</th>
  <th>Data</th>
</tr>
<tr>
  <td>Reunião de planejamento de estimativas</td>
  <td>27/04/2022</td>
<tr>
  <tr>
  <td>Reunião de planejamento de sprint</td>
  <td>28/04/2022</td>
<tr>
  <tr>
  <tr>
  <td>Daily scrum</td>
  <td>Todas segundas e quintas no máximo 15 minutos</td>
<tr>
  <tr>
  <tr>
  <td>Reunião de revisão da Sprint realizada</td>
  <td> </td>
<tr>
</table>

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

- Épico (EP 1)- Sprint 1 : Modelagem de banco de dados e Registros de Competições , Equipes e Membros da equipe.

		
    - User Estória (US 1) - Dev teams precisa modelar o Diagrama de entidade-relacionamento para criação do banco de dados. 
      
        - Tasks (T1) - Criar entidade-relacionamento.
        - Tasks (T2) - Gerar tabelas no banco de dados.

		
    - User Estória (US 2) - Usuário administrador precisa acessar os sistemas para realizar as suas atividades de cadastro.   
    
        - Tasks (T1) - Criar a Interface de login do administrador.
        - Tasks (T2) - Criar a rota de login.
        
    - User Estória (US 2) - Usuário administrador precisa cadastrar uma competição para que as equipes possam participar, a competição pode ser definida como masculina ou feminina.
    
        - Tasks (T1) - Criar Interface de cadastro de Competições.
        - Tasks (T2) - Criar rota de cadastro  de Competições.
        - Tasks (T3) - Criar interface de competições cadastradas.
        - Tasks (T4) - Criar rota de competições cadastradas.

     

    - User Estória (US 4 ) - Usuário administrador precisa cadastrar as equipes para que as   mesmas possam participar da competição. 
      
         - Tasks (T1) - Criar Interface de cadastro de equipes.
         - Tasks (T2) - Criar rota de cadastro  de equipes.
         - Tasks (T3) - Criar interface de equipes cadastradas.
         - Tasks (T4) - Criar rota de equipes cadastradas.
         
         
    - User Estória (US 5) - Usuário administrador precisa cadastrar membros da equipe para que os mesmos possam participar da competição, os membros são classificados com Atletas, Técnicos  e Auxiliares.   
   
        - Tasks (T1) - Criar Interface de cadastro de membros.
        - Tasks (T2) - Criar rota de cadastro  de membros.
        - Tasks (T3) - Criar Interface de membros castrados de uma equipe.
        - Tasks (T4) - Criar rota de membros castrados de uma equipe.

- Épico (EP 2)- Sprint 2  : Iniciar um Competição,  Cadastro dos Resultados  das Partidas E Relatórios  estatísticas

    - User Estória (US 6) - O usuário administrador precisar iniciar uma competição  precisa gerar as partidas para que os times possam saber data e hora das suas partidas durante a competição.
    
        - Tasks (T1) - Criar Interface com tabela(partidas) dos jogos.
        - Tasks (T2) - Criar rota que geras as partidas das equipes participantes.
        - Tasks (T2) - Criar rota de partidas cadastradas de uma competição.

    - User Estória (US 7)-  Usuário administrador precisa cadastrar os resultados das partidas para que os demais usuários possam consultar os resultados.
      
        - Tasks (T1) - Criar Interface de cadastro de resultados de jogos.
        - Tasks (T2) - Criar rota de cadastro de resultados de jogos.

    - User Estória (US 8) - Usuário administrador precisa cadastrar as estáticas que cada  jogador  obteve durante uma partida para que possa gerar os relatórios estáticos dos jogadores. 
    
        - Tasks (T1) - Criar Interface de cadastro de estatísticas.
        - Tasks (T2) - Criar rota de cadastro de estatísticas.


    - User Estória (US 9) - O  usuários administrador precisa finalizar a fase classificatória e o  sistema precisa gerar o chaveamento da fase mata-mata para que as equipes possam saber os seus adversários 
    
        - Tasks (T1) - Criar Interface para finalizar a parte Classificatória de uma competição.
        - Tasks (T2) - Criar Interface De chaveamento do mata-mata.
        - Tasks (T3) - Criar rota que finaliza uma fase classificatória.
        - Tasks (T4) - Criar rota que gera o Chaveamento do mata-mata.


 - User Estória (US 10) - os usuários comuns precisam  verificar os desempenhas dos principais jogadores da competição.
 	
      - Tasks (T1) - Criar tela de relatórios.
      - Tasks (T2) - Criar rota que gera relatórios.


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


Estimativas
================

<table border="1"> 
  <th> (US 1)- Dev teams precisa modelar o Diagrama de entidade-relacionamento para criação do banco de dados.  </th>
<tr>
  <th>Código</th>
  <th>Descrição</th>
  <th>Responsável</th>
  <th>Estimativa de tempo</th>
  <th>Temporeal</th>
</tr>
<tr>
    <td>T1</td>
    <td>Criar entidade-relacionamento. </td>
    <td></td>
    <td> 1 hora </td>
    <td></td>
</tr>
<tr>
    <td>T2</td>
    <td>Gerar tabelas no banco de dados</td>
    <td></td>
    <td> 10 minutos </td>
    <td></td>
</tr>

</table>


