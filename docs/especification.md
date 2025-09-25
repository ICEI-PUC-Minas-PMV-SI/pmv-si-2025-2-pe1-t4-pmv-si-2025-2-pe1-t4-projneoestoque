# Especificações do Projeto
A presente seção tem como objetivo detalhar a definição do problema e a proposta de solução a partir da perspectiva do usuário. Para isso, foram utilizados métodos de levantamento de requisitos centrados no usuário, que permitem compreender suas necessidades e transformar essas demandas em funcionalidades claras para o sistema.

Primeiramente, elaborou-se o diagrama de personas, representando de forma simplificada os principais perfis de usuários do sistema, tais como estudantes de Medicina, médicos recém-formados e residentes. Em seguida, foram descritas as histórias de usuários, utilizando a técnica User Story no formato “Eu como [perfil] desejo [funcionalidade] para [benefício]”. Esse recurso possibilitou traduzir expectativas em cenários reais de uso, garantindo maior alinhamento entre a solução proposta e a rotina dos usuários.

Posteriormente, foram definidos os requisitos funcionais e não funcionais, responsáveis por estabelecer tanto as funcionalidades que o sistema deve oferecer quanto as características de qualidade que devem ser atendidas. Para essa etapa, foi empregada a técnica de levantamento e classificação de requisitos, atribuindo-se prioridades que orientam o desenvolvimento.
## Personas
| ![Foto da Persona](./img/persona2.jpg) | *Rafaela Mattos<br><br>Idade:* 19 anos<br>*Profissão:* Estudante de Medicina <br>*Localização:* Brasil<br>*Objetivo:* Organizar seus estudos e gerenciar melhor o tempo |
|--------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|

| *Descrição* | *Dores* | *Expectativas* |
|---------------|-----------|------------------|
| Rafaela é uma estudante de medicina que se sente desanimada e perdida com a quantidade de matérias e tarefas. Ela gostaria de se organizar melhor nos estudos, mas sente dificuldade por não ter uma visão clara do que precisa fazer. | - Não sabe como organizar todos os estudos e tarefas<br>- Considera a gestão do tempo complicada e cansativa<br>- Acha difícil encontrar um método claro e eficiente de estudo<br>- Sente ansiedade por perder prazos ou conteúdos importantes | - Conseguir organizar melhor todos os estudos e tarefas<br>- Ter um método claro e fácil de acompanhar para estudar<br>- Encontrar uma forma prática de gerenciar o tempo e atividades |

| ![Foto da Persona](./img/persona1.jpg) | *Pietra Silva<br><br>Idade:* 25 anos<br>*Profissão:* Médica recém-formada<br>*Localização:* Brasil<br>*Objetivo:* Organizar agenda |
|--------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|

| *Descrição* | *Dores* | *Expectativas* |
|---------------|-----------|------------------|
| Pietra é uma médica recém-formada que precisa organizar plantões e compromissos. Ela quer gerenciar melhor sua agenda, mas sente dificuldade em controlar horários e tarefas. | - Não consegue organizar plantões e compromissos<br>- Acha difícil visualizar toda a rotina de forma clara<br>- Considera a gestão da agenda complicada e cansativa<br>- Dificuldade em priorizar compromissos importantes | - Conseguir organizar plantões e compromissos de forma prática<br>- Ter uma visão clara de toda a rotina diária e semanal<br>- Reduzir a sobrecarga e tornar a gestão da agenda mais eficiente|

| ![Foto da Persona](./img/persona3.jpg) | *Ana Clara<br><br>Idade:* 35 anos<br>*Profissão:* Residente de Medicina<br>*Localização:* Brasil<br>*Objetivo:* Acesso rápido a protocolos clínicos e guias de conduta |
|--------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|

| *Descrição* | *Dores* | *Expectativas* |
|---------------|-----------|------------------|
| Ana é uma residente de medicina que precisa consultar protocolos de emergência rapidamente durante plantões. Ele quer se sentir seguro ao tomar decisões críticas, mas sente dificuldade em acessar informações de forma prática. | - Não consegue acessar protocolos de emergência de forma rápida<br>- Acha difícil ter todas as informações organizadas e acessíveis<br>- Tem medo de cometer erros por falta de referência clara<br>- Sente insegurança na hora de tomar decisões críticas | - Conseguir consultar protocolos de forma ágil e prática<br>- Ter todas as informações organizadas em um só lugar<br>- eduzir o risco de erros durante atendimentos emergenciais |
## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Usuário do sistema  | Registrar minhas tarefas           | Não esquecer de fazê-las               |
|Administrador       | Alterar permissões                 | Permitir que possam administrar contas |

Apresente aqui as histórias de usuário que são relevantes para o projeto de sua solução. As Histórias de Usuário consistem em uma ferramenta poderosa para a compreensão e elicitação dos requisitos funcionais e não funcionais da sua aplicação. Se possível, agrupe as histórias de usuário por contexto, para facilitar consultas recorrentes à essa parte do documento.

> **Links Úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)
> - [User Stories: requisitos que humanos entendem](https://www.luiztools.com.br/post/user-stories-descricao-de-requisitos-que-humanos-entendem/)
> - [Histórias de Usuários: mais exemplos](https://www.reqview.com/doc/user-stories-example.html)
> - [9 Common User Story Mistakes](https://airfocus.com/blog/user-story-mistakes/)

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade | 
|------|-----------------------------------------|----| 
|RF-001| A aplicação deve permitir que o usuário gerencie suas tarefas | ALTA |  
|RF-002| A aplicação deve permitir a emissão de um relatório de tarefas realizadas no mês   | MÉDIA | 


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| A aplicação deve ser responsiva | MÉDIA | 
|RNF-002| A aplicação deve processar requisições do usuário em no máximo 3s |  BAIXA | 

Com base nas Histórias de Usuário, enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:

- [Requisitos Funcionais
 (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
 correspondem a uma funcionalidade que deve estar presente na
  plataforma (ex: cadastro de usuário).
- [Requisitos Não Funcionais
  (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
  correspondem a uma característica técnica, seja de usabilidade,
  desempenho, confiabilidade, segurança ou outro (ex: suporte a
  dispositivos iOS e Android).
Lembre-se que cada requisito deve corresponder à uma e somente uma
característica alvo da sua solução. Além disso, certifique-se de que
todos os aspectos capturados nas Histórias de Usuário foram cobertos.

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |


Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.

> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)
