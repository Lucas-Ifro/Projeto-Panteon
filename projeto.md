<img src='/img/logo.png' alt='logo da empresa'/>

# *Panteon*

# PROJETO DE SOFTWARE

## *Stakeholders*
|NOME|CARGO|E-MAIL|
|:---|:---|:---|
|Altenir Modesto Gomes|Analista de software|altenirgomesmodesto@gmail.com|
|Adilson Junior Portilho Barbosa|Front-end|adilsonjuniorpb@gmail.com|
|Daniel Pereira Estevão|Designer UI UX|danielpereiraestevao6@gmail.com|
|Herick Bersch Magalhães|Full-Stack|herickbersch@gmail.com|
|Lucas Ferreira Rodrigues|Gerente|lucaslfr00@gmail.com|
|Vitor Gabriel da Silva Rocha|Back-end|Vitorgabrielvha3@gmail.com|


# Sumário

* [RESUMO DO PROJETO](#resumo-do-projeto)
* [INTRODUÇÃO](#introdução)
  * [PROPÓSITO DESTE DOCUMENTO](#propósito-deste-documento)
  * [ESCOPO DO PROJETO](#escopo-do-projeto)
  * [CONCEPÇÃO DO SISTEMA](#concepção-do-sistema)
  * [CONVENÇÕES, TERMOS E ABRIVEAÇÕES](#convenções-termos-e-abreviações)
* [DESCRIÇÃO GERAL](#descrição-geral)
  * [USUÁRIOS DO SISTEMA](#usuários-do-sistema)
  * [ABRANGÊNCIA E SISTEMAS SIMILARES](#abrangência-e-sistemas-similares)
  * [SUPOSIÇÕES E DEPENDÊNCIAS](#suposições-e-dependências)
* [ESTUDO DE VIABILIDADE](#estudo-de-viabilidade)
  * [VIABILIDADE TÉCNICA](#viabilidade-técnica)
  * [VIABILIDADE ECONÔMICA](#viabilidade-econômica)
  * [VIABILIDADE ORGANIZACIONAL](#viabilidade-organizacional)
* [METODOLOGIA ADOTADA NO DESENVOLVIMENTO](#metodologia-adotada-no-desenvolvimento)
* [REQUISITOS DO SOFTWARE](#requisitos-do-software)
  * [REQUISITOS FUNCIONAIS](#requisitos-funcionais)
  * [REQUISITOS NÃO FUNCIONAIS](#requisitos-não-funcionais)
* [PROTOTIPAGEM](#prototipagem)
* [DIAGRAMA DE CASOS DE USO](#diagrama-de-casos-de-uso)
  * [ESPECIFICAÇÃO DOS CASOS DE USO](#descrição--especificação-dos-casos-de-uso)
* [DIAGRAMA DE CLASSES](#diagrama-de-classes)
* [DIAGRAMA DE SEQUÊNCIAS](#diagrama-de-sequências)
* [ DIAGRAMA DE ATIVIDADES](#diagrama-de-atividades)
* [REFERÊNCIAS](#referências)


# RESUMO DO PROJETO




|Empresa| Empresa online e fisica|
|:---|:---|
|NOME|Panteon|
|Administrador Chefe| Cleidson Freitas|
|Administradora Chefe| Cleidson Freitas|
| PRINCIPAL OBJETIVO | Desenvolver as analises e diagramas do projeto na aulas de engenharia de software |
| BENEFÍCIOS ESPERADOS | Aumentar a produtividade da empresa |
| INÍCIO E TÉRMINO PREVISTOS | 01/06/2023 - 06/12/2023 |




# INTRODUÇÃO
  O projeto se destina a ajudar a empresa em questão na melhora da organização e comunicação com o cliente visto que existe uma deficiencia interna nesse process 


## PROPÓSITO DESTE DOCUMENTO

Este documento é destinado a avalição do professor sobre nossa evolução enquanto grupo. O propósito deste documento é apresentar a descrição dos serviços e funções que o sistema da Panteon contém.

## CONCEPÇÃO DO SISTEMA

Métodos utilizados para a obtenção dos requisitos do sistema:
  * Primeiramente foram realizadas reuniões com os cliente, na tentativa de entender a proposta do projeto.
  * Após conseguirmos identificar as principais funcionalidades começamos a trabalhar na prototipagem das telas.
  * Realizamos outra reunião com o cliente e validamos algumas telas e modificamos outras.
  * Realizamos muitas reuniões com a equipe e com os professores e continuamos trabalhando nas telas.
  * Após a criação das telas começamos a trabalhar nos diagramas UML, com a ajuda do professor.


## CONVENÇÕES, TERMOS E ABREVIAÇÕES

* Utilizamos o AVA Ambiente Virtual de Aprendizagem como instrutor de passos a serem seguidos na matéria de Fundamentos de  8 Ánalise;
* Moodle: Ambiente Virtual que hospedará os cursos oferecidos;
* Github: Utilizado para commit no nosso escop do nosso documento;
* Figma: Para a criação do prototipo do nosso site.

# DESCRIÇÃO GERAL

## ESCOPO DO PROJETO
<br>
### NO ESCOPO
<br>
A proposta de site da Panteon é aumentar a comunição com o cliente, demonstrando todos os processos para a criação de um desingn ou identidade visual de uma empresa, mostrando o que foi feito, o que está sendo feito, e o que falta fazer, mostrando a data aproximada de entrega.
 
<BR>
### FORA DO ESCOPO
Não fazem parte do escopo do projeto:

* Disponibilizar previas do projeto.

## Usuários do sistema
|USUÁRIO|DESCRIÇÃO|
|:---|:---|
|**Usuário Padrão:**|Clientes da Panteon|
|**Gerentes**|Carlos Ferreira e Cleidson Freitas|
|**Funcionários**|Designers e Marketing|



### Sistemas similares:

Como esse sistema tem uma proposta muito diferente do convencional, não ah muitos software de referências, podemos destacar os sistamas de rastreio de mercadoria, onde o clinete consegue acompanhar o transporte da sua mercadoria, o que se assemelhar ao nosso projeto, onde o cliente consegue acompanhar o desenvolvimento da sua identidade visual ou desingn de produto, sabendo a data de entrega e o que está sendo feito.

## Suposições e dependências

Os clientes devem utilizar um computador ou celular com acesso a internet para poder visualizar a Time-line.
Por ser uma aplicação web, não a uma configuração mínima para ter acesso.
Para o Funcionário é necessidade acessar por computador para poder realizar a criação dos projetos e gerenciamento dos mesmos.

# ESTUDO DE VIABILIDADE

Tendo em vista que a Panteon é uma empresa moderna, esse seria um grande diferencial em relação aos seus concorrentes, o que atrairia novos clientes e e mostraria todo o trabalho por de trás da criação dos Designers.

## Viabilidade Técnica

Devido ao escopo do projeto ser grande a uma necessidade de pelo memos 3 desenvolvedores, um bach-end, um frond-end e um full-stack para a criação do software. Como o sistema não terá inicialmente muitos acessos diarios não ultrapassando dos 200 acessos podemos ter apenas um funcionário para a manutenção do sistema. 

# Metodologia Adotada no Desenvolvimento


# Requisitos do Software

A especificação dos requisitos deste documento deve seguir as recomendações da norma IEEE Std-830-1998, levando em conta as recomentações do documento de [características dos requisitos](caracteristicas_requisitos.md).

## Requisitos Funcionais

A tabela a seguir contém a relação dos Requisitos Funcionais elicitados, com as colunas: identificador, nome, descrição e prioridade:

| IDENTIFICADOR | NOME | DESCRIÇÃO |
:---|:---|:---|
|RNF-001|Cadastrar funcionário|Essencial|
|RNF-002|Cadastrar cliente|Essencial|
|RNF-003|Cadastrar projeto|Essencial|
|RNF-004|Cliente fazer login|Essencial|
|RNF-005|Funcionário fazer login|Essencial|
|RNF-006|Adicionar Etapa|Essencial|
|RNF-007|Excluir etapa|Essencial|
|RNF-008|Atualizar cadastro do funcionário|Essencial|
|RNF-009|Atualizar cadastro do cliente|Essencial|
|RNF-010|Editar etapa|Essencial|
|RNF-011|Marcar etapa como concluída|Essencial|
|RNF-012|Remover funcionário do projeto|Essencial|
|RNF-013|Adicionar funcionário do projeto|Essencial|




## Requisitos Não Funcionais
A tabela a seguir contém a relação com os Requisitos Não Funcionais identificados, contendo identificador, nome, descrição e prioridade:


| Requisitos Não Funcionais do Sistema |Tipo|
:---|:---|
|Sistema deve ser bonito e fácil de utilizar|Usabilidade|
|O cliente deve conseguir compreender cada etapa do projeto|interpretação|
|Timeline deve conter efeitos visuais para mostrar o estado do projeto|visibilidade|



# Prototipagem

<img src='/img/prototipagem/tela1.png' alt='tela1'/>
<img src='/img/prototipagem/tela2.png' alt='tela2'/>
<img src='/img/prototipagem/tela3.png' alt='tela3'/>
<img src='/img/prototipagem/tela4.png' alt='tela4'/>
<img src='/img/prototipagem/tela5.png' alt='tela5'/>
<img src='/img/prototipagem/tela6.png' alt='tela6'/>
<img src='/img/prototipagem/tela7.png' alt='tela7'/>


# Diagrama de Casos de Uso

<img src='/img/Diagrama caso de uso/Diagrama_de_caso_de_uso_finalizado.png' alt='Diagrma de classe'/>

## Descrição / Especificação dos Casos de Uso

<br>


| UC-01 - Cadastrar Cliente |           
|:---|
| **Descrição/Objetivo:** Funcionário cadastra o cliente |
| **Atores:** Cliente |
| **Pré-condições:** Cliente informar os dados para o cadastro |
| **Pós-condições:** Cliente é incluído no projeto |
| **FLUXO PRINCIPAL / BÁSICO:** |
| 1. Funcionário vai à tela de criação de projeto |
| 2. Funcionário vai à tela de cadastrar cliente |
| 3. Funcionário insere as informações do cliente |
| 4. Sistema efetua o cadastro |
| **FLUXOS ALTERNATIVOS / EXCESSÕES:** |
| **2a: Dados dos clientes já cadastrados, informar cliente já cadastrado** |
| - Mensagem de cliente já cadastrado |
| **4a: Caso os dados estejam incorretos, editar os dados** |
| - Funcionário edita as informações do cliente |

<br>


| UC-02 - Cadastrar Funcionário |           
|:---|
| **Descrição/Objetivo:** Este caso de uso descreve o cadastro de um novo funcionário no site. |
| **Atores:** Gerente |
| **Pré-condições:** O funcionário tem que estar trabalhando na empresa. |
| **Pós-condições:** O funcionário pode criar projetos. |
| **FLUXO PRINCIPAL / BÁSICO:** |
| 1. O gerente acessa a opção de cadastro de funcionário. |
| 2. Adicione os passos subsequentes conforme necessário. |
| 3. Adicione os passos subsequentes conforme necessário. |
| **FLUXOS ALTERNATIVOS / EXCESSÕES:** |

<br>


| UC-03 - Cadastrar Projeto |           
|:---|
| **Descrição/Objetivo:** Este caso de uso descreve as etapas de um funcionário cadastrar e criar um projeto. |
| **Atores:** Funcionário |
| **Pré-condições:** Confirmação do projeto e assinatura do contrato com o cliente |
| **Pós-condições:** Ser direcionado à área de gerenciamento do projeto |
| **FLUXO PRINCIPAL / BÁSICO:** |
| 1. Funcionário informa o nome do projeto |
| 2. Funcionário adiciona o cliente ao projeto |
| 3. Funcionário adiciona a si mesmo ao projeto |
| 4. Funcionário cria o projeto |
| 5. Funcionário é direcionado à tela de gerenciamento de projeto |
| **FLUXOS ALTERNATIVOS / EXCESSÕES:** |
| **2a: Se o cliente não tiver conta, o funcionário cria uma conta para o cliente** |
| - Funcionário cria uma conta para o cliente |
| **3a: Se o funcionário não tiver conta, o administrador cria conta para o funcionário** |
| - Administrador cria uma conta para o funcionário |

<br>


| UC-03 - Cadastrar Projeto |           
|:---|
| **Descrição/Objetivo:** Este caso de uso descreve as etapas de um funcionário cadastrar e criar um projeto. |
| **Atores:** Funcionário |
| **Pré-condições:** Confirmação do projeto e assinatura do contrato com o cliente |
| **Pós-condições:** Ser direcionado à área de gerenciamento do projeto |
| **FLUXO PRINCIPAL / BÁSICO:** |
| 1. Funcionário informa o nome do projeto |
| 2. Funcionário adiciona o cliente ao projeto |
| 3. Funcionário adiciona a si mesmo ao projeto |
| 4. Funcionário cria o projeto |
| 5. Funcionário é direcionado à tela de gerenciamento de projeto |
| **FLUXOS ALTERNATIVOS / EXCESSÕES:** |
| **2a: Se o cliente não tiver conta, o funcionário cria uma conta para o cliente** |
| - Funcionário cria uma conta para o cliente |
| **3a: Se o funcionário não tiver conta, o administrador cria conta para o funcionário** |
| - Administrador cria uma conta para o funcionário |

<br>


| UC-04 - Cliente Fazer Login |           
|:---|
| **Descrição/Objetivo:** Este caso de uso descreve o cliente fazendo login no site. |
| **Atores:** Cliente |
| **Pré-condições:** O cliente deve ter uma conta ativa e estar cadastrado em um projeto. |
| **Pós-condições:** Visualizar a timeline. |
| **FLUXO PRINCIPAL / BÁSICO:** |
| 1. Autenticar Cliente. |
| 2. Cliente visualiza a timeline. |
| **FLUXOS ALTERNATIVOS / EXCESSÕES:** |
| **1a: Se conta e agência incorretas, solicitar novamente a conta** |
| - Sistema solicita ao cliente as informações de conta e agência novamente. |

<br>


| UC-05 - Funcionário Faz Login |           
|:---|
| **Descrição/Objetivo:** Este caso de uso descreve as etapas de login de um funcionário. |
| **Atores:** Funcionário |
| **Pré-condições:** O funcionário já deve estar cadastrado. |
| **Pós-condições:** O funcionário tem acesso ao site. |
| **FLUXO PRINCIPAL / BÁSICO:** |
| 1. Funcionário vai à tela de login. |
| 2. Funcionário informa as credenciais. |
| 3. Funcionário confirma. |
| 4. Funcionário é direcionado à tela de "Meus Projetos". |
| 5. Funcionário tem acesso ao sistema. |
| **FLUXOS ALTERNATIVOS / EXCESSÕES:** |
| **2a: Funcionário informa credenciais incorretas, requisitar credenciais corretas.** |
| - Sistema solicita ao funcionário as credenciais corretas. |


<br>

| UC-06 - Adicionar Etapa |           
|:---|
| **Descrição/Objetivo:** Neste caso de uso, o funcionário adiciona uma etapa. |
| **Atores:** Funcionário |
| **Pré-condições:** Ter um projeto criado. |
| **Pós-condição:** [Adicione a pós-condição conforme necessário.] |
| **FLUXO PRINCIPAL / BÁSICO:** |
| 1. Funcionário faz login. |
| 2. Acesse a tela de gerenciamento de projeto. |
| 3. Cria uma nova etapa. |
| 4. Adiciona data de entrega. |
| 5. Confirma a criação. |
| **FLUXOS ALTERNATIVOS / EXCESSÕES:** |
| **3a: Funcionário escolhe etapa já salva no sistema.** |
| - Funcionário seleciona uma etapa já existente no sistema. |


<br>

| UC-07 - Excluir Etapa |           
|:---|
| **Descrição/Objetivo:** Neste caso de uso, o funcionário exclui uma etapa. |
| **Atores:** Funcionário |
| **Pré-condições:** Possuir um projeto cadastrado. |
| **Pós-condição:** Etapa é excluída do projeto. |
| **FLUXO PRINCIPAL / BÁSICO:** |
| 1. Funcionário faz login. |
| 2. Acessa a tela de gerenciamento de projeto. |
| 3. Funcionário seleciona a etapa. |
| 4. Funcionário clica em excluir etapa. |
| 5. Funcionário confirma a exclusão. |
| 6. Sistema exclui a etapa. |
| **FLUXOS ALTERNATIVOS / EXCESSÕES:** |
| **6a: Funcionário exclui a etapa errada, então adiciona a etapa novamente.** |
| - Funcionário adiciona a etapa novamente no sistema. |

<br>


| UC-08 - Atualizar Cadastro do Funcionário |           
|:---|
| **Descrição/Objetivo:** Etapas para atualizar as informações do funcionário. |
| **Atores:** Gerente |
| **Pré-condições:** Funcionário já ter cadastro. |
| **Pós-condição:** Funcionário tem suas informações de cadastro atualizadas. |
| **FLUXO PRINCIPAL / BÁSICO:** |
| 1. Gerente faz login. |
| 2. Acessa a tela de gerenciamento de contas. |
| 3. Gerente seleciona a conta do funcionário. |
| 4. Gerente informa os novos dados. |
| 5. Gerente confirma. |
| 6. Sistema atualiza as credenciais. |
| **FLUXOS ALTERNATIVOS / EXCESSÕES:** |
| **4a: Gerente informa credenciais erradas, atualiza novamente as informações.** |
| - Gerente informa as credenciais corretas para atualizar as informações. |


<br>

| UC-09 - Atualizar Cadastro do Cliente |           
|:---|
| **Descrição/Objetivo:** Etapas para atualizar as informações do cliente. |
| **Atores:** Funcionário |
| **Pré-condições:** Cliente já ter cadastro. |
| **Pós-condição:** Cliente tem suas informações de cadastro atualizadas. |
| **FLUXO PRINCIPAL / BÁSICO:** |
| 1. Funcionário faz login. |
| 2. Acessa a tela de gerenciamento de contas. |
| 3. Funcionário seleciona a conta do cliente. |
| 4. Funcionário informa os novos dados. |
| 5. Funcionário confirma. |
| 6. Sistema atualiza as credenciais. |
| **FLUXOS ALTERNATIVOS / EXCESSÕES:** |
| **4a: Funcionário informa credenciais erradas, atualiza novamente as informações.** |
| - Funcionário informa as credenciais corretas para atualizar as informações. |

<br>


| UC-10 - Editar Etapa |           
|:---|
| **Descrição/Objetivo:** Este caso de uso descreve o funcionário editando uma etapa. |
| **Atores:** Funcionário |
| **Pré-condições:** Ter um projeto criado. |
| **Pós-condição:** Ter etapas criadas. |
| **FLUXO PRINCIPAL / BÁSICO:** |
| 1. Funcionário faz login. |
| 2. Acessa a tela de gerenciamento de projeto. |
| 3. Altera informações da etapa. |
| 4. Confirma. |
| **FLUXOS ALTERNATIVOS / EXCESSÕES:** |
| **3a: Funcionário adiciona informações erradas, então exclui e adiciona novamente.** |
| - Funcionário exclui a etapa com informações erradas e a adiciona novamente com as informações corretas. |
<br>



| UC-11 - Marcar Etapa como Concluída |           
|:---|
| **Descrição/Objetivo:** Este caso de uso descreve o funcionário marcando uma etapa como concluída. |
| **Atores:** Funcionário |
| **Pré-condições:** Possuir um projeto cadastrado. |
| **Pós-condição:** Possuir etapas cadastradas. |
| **FLUXO PRINCIPAL / BÁSICO:** |
| 1. Funcionário faz login. |
| 2. Acessa a tela de gerenciamento de projeto. |
| 3. Marca a etapa como concluída. |
| **FLUXOS ALTERNATIVOS / EXCESSÕES:** |
| **3a: O funcionário marca a etapa errada, então remarca a etapa novamente.** |
| - Funcionário desmarca a etapa incorreta e a marca novamente com a etapa correta. |

<br>

| UC-12 - Remover Funcionário do Projeto |           
|:---|
| **Descrição/Objetivo:** Este caso de uso descreve a remoção de um funcionário de um projeto. |
| **Atores:** Gerente |
| **Pré-condições:** O funcionário não é mais necessário no projeto. |
| **Pós-condição:** O funcionário não visualizará o projeto. |
| **FLUXO PRINCIPAL / BÁSICO:** |
| 1. O gerente acessa a tela de gerenciamento de projetos. |
| 2. O gerente visualiza os funcionários presentes nesse projeto. |
| 3. O gerente seleciona o funcionário que será excluído do projeto. |
| 4. O gerente seleciona a opção de excluir. |
| 5. O gerente finaliza a exclusão do funcionário. |
| 6. Sistema efetua a exclusão do funcionário. |
| **FLUXOS ALTERNATIVOS / EXCESSÕES:** |
| **8a: Caso o gerente exclua o funcionário errado, deve adicionar novamente o funcionário e excluir o funcionário certo.** |
| - Gerente adiciona novamente o funcionário correto e exclui o funcionário errado. |

<br>

| UC-13 - Adicionar Funcionário ao Projeto |           
|:---|
| **Descrição/Objetivo:** Este caso de uso descreve a adesão de um funcionário a um projeto. |
| **Atores:** Gerente |
| **Pré-condições:** O funcionário é necessário no projeto. |
| **Pós-condição:** O funcionário terá acesso ao projeto. |
| **FLUXO PRINCIPAL / BÁSICO:** |
| 1. O gerente acessa a tela de gerenciamento de projetos. |
| 2. O gerente visualiza os funcionários presentes nesse projeto. |
| 3. O gerente seleciona a opção de adicionar um novo funcionário. |
| 4. O gerente seleciona o funcionário que será adicionado. |
| 5. O gerente confirma a adesão do funcionário. |
| 6. O gerente finaliza a adesão do funcionário. |
| 7. Sistema efetua a adesão do funcionário. |
| **FLUXOS ALTERNATIVOS / EXCESSÕES:** |
| **9a: Caso o gerente adicione o funcionário errado, deve excluir esse funcionário e adicionar o funcionário certo.** |
| - Gerente exclui o funcionário errado e adiciona o funcionário certo. |

<br>

# Diagrama de Classes

<img src='/img/Diagrama de classe/Diagrama_de_classe.png' alt='Diagrma de classe'/>


# Diagrama de Sequências

<img src='/img/Diagrama de sequencia/Adicionar_etapa.png' alt='Diagrama de Sequência - Adicionar Etapa'/>
<img src='/img/Diagrama de sequencia/Atualizar_cliente.png' alt='Diagrama de Sequência - Atualizar Cliente'/>
<img src='/img/Diagrama de sequencia/atualizar_funcionario.png' alt='Diagrama de Sequência - Atualizar Funcionário'/>
<img src='/img/Diagrama de sequencia/Cadastro_cliente.png' alt='Diagrama de Sequência - Cadastro Cliente'/>
<img src='/img/Diagrama de sequencia/Cadastro_funcionario.png' alt='Diagrama de Sequência - Cadastro Funcionário'/>
<img src='/img/Diagrama de sequencia/Cliente_login.png' alt='Diagrama de Sequência - Cliente Login'/>
<img src='/img/Diagrama de sequencia/criacao_de_projeto.png' alt='Diagrama de Sequência - Criação de Projeto'/>
<img src='/img/Diagrama de sequencia/edicao_de_etapa.png' alt='Diagrama de Sequência - Edição de Etapa'/>
<img src='/img/Diagrama de sequencia/Excluir_etapa.png' alt='Diagrama de Sequência - Excluir Etapa'/>
<img src='/img/Diagrama de sequencia/Funcionario_login.png' alt='Diagrama de Sequência - Funcionário Login'/>
<img src='/img/Diagrama de sequencia/Funcionario_no_projeto.png' alt='Diagrama de Sequência - Funcionário no Projeto'/>
<img src='/img/Diagrama de sequencia/Marcar_etapa_como_concluida.png' alt='Diagrama de Sequência - Marcar Etapa como Concluída'/>
<img src='/img/Diagrama de sequencia/Remover_funcionario_do_projeto.png' alt='Diagrama de Sequência - Remover Funcionário do Projeto'/>


# Diagrama de Atividades

<img src='/img/Diagrama de atividade/Diagrama_de_atividade.png' alt='Diagrma de Atividade'/>
<img src='/img/Diagrama de atividade/Diagrama_de_atividade1.jpg' alt='Diagrma de Atividade'/>
<img src='/img/Diagrama de atividade/Diagrama_de_atividade2.png' alt='Diagrma de Atividade'/>


# REFERÊNCIAS

Esta subseção apresenta as referências aos documentos que utilizamos no auxílio à construção deste documento.
* [UML](https://www.omg.org/spec/UML/2.5/About-UML/)
* [Práticas para Especificação de Requisitos IEEE-830](https://ieeexplore.ieee.org/document/720574)

