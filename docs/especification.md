# Especificações do Projeto

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto.

Caso deseje atribuir uma imagem a sua persona, utilize o site https://thispersondoesnotexist.com/

## Personas

Persona 1

Carlos tem 38 anos, é dono de uma pequena loja de eletrônicos em uma cidade do interior. Trabalha há mais de 10 anos no comércio e conhece muito bem seus clientes, mas sempre teve dificuldades em organizar o estoque. Ele ainda usa planilhas simples e, muitas vezes, acaba anotando em cadernos. Isso gera atrasos e até perda de mercadorias. Carlos procura uma solução prática e acessível que o ajude a controlar melhor a entrada e saída de produtos, sem precisar ser especialista em tecnologia.

Persona 2

Mariana tem 29 anos e é gerente de operações em uma rede de lojas de médio porte que também vende online. Ela lida diariamente com problemas de estoque duplicado e atrasos na reposição, o que afeta diretamente as vendas e a experiência do cliente. Mariana busca uma ferramenta que permita acompanhar o estoque em tempo real e gerar relatórios simples para agilizar suas decisões. Organizada e prática, ela valoriza sistemas claros e que possam ser acessados facilmente por toda a equipe.

Persona 3

Lucas tem 22 anos e está começando seu próprio negócio online de venda de acessórios eletrônicos. Ele é estudante de tecnologia e sonha em transformar sua loja em uma marca reconhecida. Por ser iniciante, ainda tem dificuldades em gerenciar os produtos que vende e em calcular o momento certo de repor o estoque. Lucas busca uma solução intuitiva e de baixo custo, que o ajude a se organizar desde o início e evitar erros que possam atrapalhar seu crescimento.

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Dono de loja        | Adicionar e remover produtos       | Ter controle do estoque                |
|Gerente de loja     | Historico de transações            | Agilizar as decisões                   |
|Vendedor            | Consultar rapidamente o preço e a quantidade de um produto | Agilizar o atendimento |
|Caixa               | Filtrar produtos por nome ou categoria |  Localizar itens rapidamente |
|Estoquista          | Dar baixa em produtos vendidos     | Manter o controle de saída correto e evitar erros |

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade | 
|------|-----------------------------------------|----| 
|RF-001| Permitir o cadastro de novos produtos no sistema  | ALTA |  
|RF-002| Registrar a entrada de produtos no estoque   | ALTA | 
|RF-003| Registrar a saída de produtos vendidos | ALTA |
|RF-004| Consultar estoque em tempo real | ALTA |
|RF-005| Emitir relatórios de estoque e vendas | MEDIA |
|RF-006| Gerar alertas de produtos com baixo estoque | ALTA |

### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser de fácil utilização, com interface simples e intuitiva | ALTA | 
|RNF-002| O sistema deve ser acessível via web e responsivo para dispositivos móveis |  MEDIA |
|RNF-003| O sistema deve garantir segurança dos dados de estoque e vendas            | ALTA |
|RNF-004| O tempo de resposta das consultas de estoque deve ser inferior a 2 segundos | ALTA |
|RNF-005| O sistema deve permitir múltiplos acessos simultâneos sem perda de desempenho | MEDIA |
|RNF-006| O sistema deve possibilitar backup das informações | BAIXA |


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
