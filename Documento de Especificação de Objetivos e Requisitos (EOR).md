Minha UFG
===================

Índice Analítico
-----------------

Incluir índice de conteúdo do documento que estiver sendo elaborado
* 1. [Introdução](#1-introdução)	
    * 1.1 [Objetivos](#11-objetivos)	
    * 1.2 [Público Alvo](#12-público-alvo)	
    * 1.3 [Organização do documento](#13-organização-do-documento)	
    * 1.4 [Definição de Siglas e Nomenclaturas](#14-definição-de-siglas-e-nomenclaturas)	
* 2. [Descrição do problema e do sistema](#2-descrição-do-problema-e-do-sistema)
    * 2.1 [Identificação e missão do Sistema](#21-identificação-e-missão-do-sistema)	
    * 2.2 [Domínio do problema e contexto de sua aplicação](#22-domínio-do-problema-e-contexto-de-sua-aplicação)	
    * 2.3 [Descrição dos interessados do sistema](#23-descrição-dos-interessados-do-sistema)
* 3. [Casos de Uso e Requisitos Funcionais](#3-casos-de-uso-e-requisitos-funcionais)
    * 3.1 [Transporte](#31-transporte)
    * 3.1.1 [Diagramas de Caso de Uso e Lista de casos de uso](#311-diagramas-de-caso-de-uso-e-lista-de-casos-de-uso)
    * 3.1.2 [Descrição de Casos de Uso](#312-descrição-de-casos-de-uso)
    * 3.2 [Oportunidades](#32-oportunidades)
    * 3.2.1 [Diagramas de Caso de Uso e Lista de casos de uso](#321-diagramas-de-caso-de-uso-e-lista-de-casos-de-uso)
    * 3.2.2 [Descrição de Casos de Uso](#322-descrição-de-casos-de-uso)
    * 3.3 [Calendário](#33-calendário)  
    * 3.3.1 [Diagramas de Caso de Uso e Lista de casos de uso](#331-diagramas-de-caso-de-uso-e-lista-de-casos-de-uso)
    * 3.3.2 [Descrição de Casos de Uso](#332-descrição-de-casos-de-uso)
* 4. [Requisitos e restrições não funcionais](#4-requisitos-e-restrições-não-funcionais)
    * 4.1 [Requisitos e Restrições de Usabilidade (RUS)](#41-requisitos-e-restrições-de-usabilidade-rus)
    * 4.2 [Requisitos e Restrições de Interface Homem Computador (RHIC)](#42-requisitos-e-restrições-de-interface-homem-computador-rhic)  
    * 4.3 [Requisitos e Restrições de Interface Externa (RIEX)](#43-requisitos-e-restrições-de-interface-externa-riex)	
    * 4.4 [Requisitos e Restrições de Plataforma de Hardware (RPHW)](#44-requisitos-e-restrições-de-plataforma-de-hardware-rphw)	
    * 4.5 [Requisitos e Restrições de Plataforma de Software (RPSW)](#45-requisitos-e-restrições-de-plataforma-de-software-rpsw)	
    * 4.6 [Requisitos e Restrições de Desempenho (RDES)](#46-requisitos-e-restrições-de-desempenho-rdes)	
    * 4.7 [Requisitos e restrições de disponibilidade (RDIS)](#47-requisitos-e-restrições-de-disponibilidade-rdis)	
    * 4.8 [Requisitos e Restrições de Segurança (RSEG)](#48-requisitos-e-restrições-de-segurança-rseg)	
    * 4.9 [Requisitos e Restrições de Manutenibilidade (RMAN)](#49-requisitos-e-restrições-de-manutenibilidade-rman)	
    * 4.10 [Requisitos e Restrições de Documentação (RDOC)](#410-requisitos-e-restrições-de-documentação-rdoc)	
* 5. [Requisitos Futuros (RFUT)](#5-requisitos-futuros-rfut)	
* 6. [Referências cruzadas complementares](#6-referências-cruzadas-complementares)
* 7. [Modelo de domínio](#7-modelo-de-dominio)
* 8. [Aprovação Formal](#8-aprovação-formal)	

## 1. Introdução

Esta seção deverá apresentar o documento ao leitor. O objetivo principal da introdução é descrever o documento e não o sistema, embora deva ser mencionado qual é o sistema e para qual empresa ou mercado ele será construído. O conteúdo a ser coberto na introdução está descrito nas subseções seguintes.	

### 1.1 Objetivos

Definir os objetivos do documento.	
Exemplo:	
Este documento tem os seguintes objetivos:	
•	Definir os interessados no sistema e as suas necessidades que devem ser satisfeitas pelo sistema a ser desenvolvido;	
•	Derivar os casos de uso e requisitos do sistema de forma a orientar a equipe de que será responsável pelo seu desenvolvimento;	
•	Estabelecer um contrato para negociação e concordância entre todos os interessados;	
•	Reduzir retrabalho com projeto, codificação e teste através da especificação rigorosa e completa dos requisitos;	
•	Prover uma base para avaliação de prazos e custos de desenvolvimento;	
•	Facilitar a transferência dos produtos do desenvolvimento para novos usuários, novos clientes, novos ambientes operacionais e novas equipes de desenvolvimento e manutenção;	
•	Prover uma base para a evolução futura do sistema a partir de uma versão aprovada (linha de base) deste documento.	

### 1.2 Público Alvo

Identificar o público alvo do documento, isto é, todos os perfis de pessoas que terão interesse na sua leitura. Os interesses de cada perfil na leitura do documento também devem ser descritos.

### 1.3 Organização do documento

Descrever suscintamente a organização do documento em seções e o conteúdo de cada seção. Não há necessidade de descer ao nível de subseções.

### 1.4 Definição de Siglas e Nomenclaturas

Definir e explicar sucintamente siglas e nomencalturas utilizadas neste documento.

* TR: Transporte
* OP: Oportunidade
* CA: Calendário

## 2. Descrição do problema e do sistema
-----------------------------------------

Nesta seção o sistema objeto da especificação de requisitos deve ser descrito. O domínio do problema que deverá ser resolvido pelo sistema deve ser explicado e também as características específicas do problema no contexto da empresa em que o sistema deverá ser utilizado. As subseções seguintes podem ser colocadas no documento EOR para separar cada conteúdo específico, mas também pode ser usado um estilo de texto sem separação de subseções desde que todo o conteúdo seja coberto.

### 2.1 Identificação e missão do Sistema

Identificar o sistema objeto da especificação de requisitos e definir em poucas palavras qual é a missão do sistema que está sendo considerado neste documento.

### 2.2 Domínio do problema e contexto de sua aplicação

A descrição do domínio do problema deve complementar e detalhar a visão geral do domínio do problema identificando o contexto deste problema no ambiente alvo (ambiente do cliente alvo).
Exemplo:
Suponha que o domínio do problema seja a venda de produtos em um comércio varejista. Esta seção deverá explicar em que consiste o problema de vender produtos em uma empresa que atua no comércio varejista, ou seja, descrever genericamente quais são os processos de negócio envolvidos e seus objetivos. Além disso, o problema deve ser contextualizado mostrando as características específicas do problema na empresa alvo.

### 2.3 Descrição dos interessados do sistema

Descrever os perfis de cada interessado envolvido com o sistema.

| Interessado(s) 	| Descrição 	|
|:----------------:	|---------	|
| Nome do perfil do interessado. Por exemplo: (cliente, atendente, vendedor, gerente comercial, etc.) | Descrever o perfil do interessado e como se espera que seja sua interação com o sistema direta ou indiretamente. Por exemplo, o vendedor da loja é a pessoa que atende os clientes e registra as vendas que são feitas. |



## 3. Casos de Uso e Requisitos Funcionais
---------------------------------

### 3.1 Transporte

#### 3.1.1 Diagramas de Caso de Uso e Lista de casos de uso

![](http://postimg.org/image/skrz04i6x/)

#### 3.1.2 Descrição de Casos de Uso

**TR-CSU1**- Título do caso de uso
  * Identificador: Um identificador único.

  * Atores envolvidos: Nome dos atores que estejam envolvidos neste caso de uso.
  
  * Pré-condições: O que deve ser verdade antes que o procedimento seja chamado.

  * Pós-condições: O que deve ser verdade depois que o procedimento seja chamado.

  * Cenário principal: Lista/fluxo de atividades que devem ser realizadas pelos atores durante o caso de uso.

  * Cenários secundários: Lista/fluxo de atividades que devem ser realizadas pelos atores durante o caso de uso no caso de exceções às atividades do cenário principal.

  * Protótipos de tela: Protótipos de tela (interface homem-computador) relacionados ao caso de uso.

| Ref.     |                          Descrição                       	| Categoria | Prioridade |
|-------|----------------------------------------------------------|---------------|---------------|
| TR-RFUN 1.1 | descricao | Evidente |Alta  |

### 3.2 Oportunidades

#### 3.2.1 Diagramas de Caso de Uso e Lista de casos de uso

![](http://postimg.org/image/skrz04i6x/)

#### 3.2.2 Descrição de Casos de Uso

**OP-CSU1**- Título do caso de uso
  * Identificador: Um identificador único.

  * Atores envolvidos: Nome dos atores que estejam envolvidos neste caso de uso.
  
  * Pré-condições: O que deve ser verdade antes que o procedimento seja chamado.

  * Pós-condições: O que deve ser verdade depois que o procedimento seja chamado.

  * Cenário principal: Lista/fluxo de atividades que devem ser realizadas pelos atores durante o caso de uso.

  * Cenários secundários: Lista/fluxo de atividades que devem ser realizadas pelos atores durante o caso de uso no caso de exceções às atividades do cenário principal.

  * Protótipos de tela: Protótipos de tela (interface homem-computador) relacionados ao caso de uso.

| Ref.     |                          Descrição                       	| Categoria | Prioridade |
|-------|----------------------------------------------------------|---------------|---------------|
| OP-RFUN 1.1 | descricao | Evidente |Alta  |


### 3.3 Calendário

#### 3.3.1 Diagramas de Caso de Uso e Lista de casos de uso

![](http://postimg.org/image/skrz04i6x/)

#### 3.3.2 Descrição de Casos de Uso


**CA-CSU1**- Título do caso de uso
  * Identificador: Um identificador único.

  * Atores envolvidos: Nome dos atores que estejam envolvidos neste caso de uso.
  
  * Pré-condições: O que deve ser verdade antes que o procedimento seja chamado.

  * Pós-condições: O que deve ser verdade depois que o procedimento seja chamado.

  * Cenário principal: Lista/fluxo de atividades que devem ser realizadas pelos atores durante o caso de uso.

  * Cenários secundários: Lista/fluxo de atividades que devem ser realizadas pelos atores durante o caso de uso no caso de exceções às atividades do cenário principal.

  * Protótipos de tela: Protótipos de tela (interface homem-computador) relacionados ao caso de uso.
  
  **CA-CSU1**- Regionais
  * Identificador: CA-CSU1

  * Atores envolvidos: Administrador, alunos, servidores e comunidade em geral.
  
  * Pré-condições: Os usuários devem visualizar os calendário de acordo com a regional de escolha. Cada usuário tem sua regional favorita, mas também pode mudar para qualquer outra.

  * Pós-condições: O usuário escolhe sua regional e realiza qualquer busca desejada.

  * Cenário principal: 
  1. Usuário acessa ao sistema com seu login e senha;
  2. Usuário seleciona a opção Calendário;
  3. Usuário entra no Calendário em sua regional de escolha.
  4. Usuário pode alterar regional e acessar informações.

  * Cenários secundários: 
  1. Administrador pode inserir novas notícias que correspodem ao calendário.

  * Protótipos de tela: Protótipos de tela (interface homem-computador) relacionados ao caso de uso.


| Ref.     |                          Descrição                       	| Categoria | Prioridade |
|-------|----------------------------------------------------------|---------------|---------------|
| CA-RFUN 1.1 | O Calendário deve ser dividida em 4 Regionais: Goiânia, Jataí, Catalão e Cidade de Goiás. | Evidente |Alta  |
| CA-RFUN 1.2 | Cada regional possui sua própria resolução e datas, já que cada regional segue um calendário diferente por conta de greves e suas particularidades. | Evidente |Alta  |

**CA-CSU2**- Visualizar Calendário offline
  * Identificador: CA-CSU2

  * Atores envolvidos: Administrador, Usuário
  
  * Pré-condições: O usuário deve estar logado no Minha UFG para acessar a função Calendário.

  * Pós-condições: O Sistema apresenta o calendário offline.

  * Cenário principal: 
  1. O usuário está sem acesso à internet.
  2. O Usuário já está logado no aplicativo Minha UFG.
  3. O Usuário acessa a função Calendário.
  4. O Usuário consegue acessar o calendário offline.

  * Cenários secundários: 
  1. O administrador pode inserir uma nova informação no calendário, no entanto não pode alterar datas fixas estipuladas pela Pró-reitoria de Graduação.
  2.O administrador, após realizar alguma alteração, deve alterar os dados e atualizar para que os usuários consigam acessar o Calendário offline.

  * Protótipos de tela: Protótipos de tela (interface homem-computador) relacionados ao caso de uso.
  
 
| Ref.     |                          Descrição                       	| Categoria | Prioridade |
|-------|----------------------------------------------------------|---------------|---------------|
| CA-RFUN 2.1 | O Calendário deve ser acessado offline por seus usuários. | Evidente |Alta  |

**TR-CSU3**- Fazer consulta de evento

* Identificador:CL-CSU3
* Atores envolvidos: Usuário	
* Pré-condições: 
  	
1. O usuário está no contexto de pesquisa de eventos do calendário
2. O usuário seleciona a regional que deseja fazer a pesquisa
3. O sistema sincroniza o calendário

* Pós-condições: O Sistema apresenta os eventos
* Cenário principal:O resultado é retornado
  		
1. O usuário abre a tela de pesquisa de eventos		
2. Usuário seleciona a regional		
3. O usuário digita o texto da pesquisa	
4. A pesquisa é executada quando o usuário para de digitar
5. O resultado da consulta é retornada para o usuário
		
* Cenários secundários: Nenhum resultado encontrado	     
	
1. O usuário abre a tela de filtro de eventos
2. Usuário seleciona a regional
3. O usuário digita o texto da pesquisa
4. A pesquisa é executada quando o usuário para de digitar
5. Nenhum resultado é retornado
6. Uma mensagem é mostrada para o usuário mostrando que não há nenhum resultado com o termo da pesquisa		
        
Erro ao fazer pesquisa
	
1. O usuário abre a tela de filtro de eventos
2. O usuário digita o texto da pesquisa
3. Usuário seleciona a regional
4. A pesquisa é executada quando o usuário para de digitar
5. A pesquisa retorna um erro inesperado 
6. Uma mensagem é mostrada para o usuário mostrando que um erro ocorreu

  * Protótipos de tela: Protótipos de tela (interface homem-computador) relacionados ao caso de uso.

| Ref.     |                          Descrição                       	| Categoria | Prioridade |
|-------|----------------------------------------------------------|---------------|---------------|
| TR-CSU3 | descricao | Evidente |Alta  |

## 4. Requisitos e restrições não funcionais 
--------------------------------------------

Elaborar uma lista de todos os requisitos não funcionais. Considerar requisitos de informação, de interface, de projeto, de arquitetura de software, de plataforma de hardware, de plataforma de software, de plataforma de comunicação, de desempenho, de disponibilidade, de segurança, de manutenibilidade, de portabilidade e de documentação. A lista poderá ser dividida por tipo de requisito, mas é importante que os requisitos tenham uma identificação única para que possam ser referenciados sem ambigüidades no futuro.

### 4.1 Requisitos e Restrições de Usabilidade (RUS)

Elaborar uma lista de todas as necessidades de informação que o software não pode deixar de atender. Esta lista deverá ser classificada em informações cadastrais e informações gerenciais. Por exemplo, para um software de vendas existem, entre outras, as seguintes necessidades de informação:
Exemplo:

| Ref. 	|              Descrição                                               	| Caso de Uso     	|
|------	|-------------------------------------------------------------------	|-----------------	|
| RINFx | Descrição do requisito RINFx  | CSUy, CSUm ...  |

Estes requisitos de informação são importantes para verificar a qualidade da modelagem de dados que for feita.       

### 4.2	Requisitos e Restrições de Interface Homem Computador (RHIC)

Definir os aspectos de Interface Homem Computador (IHC) como: conteúdo de informações, fatores ergonômicos, dispositivos de interação, formato de apresentação, tipo de diálogo, e mecanismos de ajuda alocados a cada perfil/grupo/tarefa de usuário. Descrever, em particular, os requisitos de usabilidade para cada perfil/grupo/tarefa de usuário. Por exemplo, pode-se definir como requisito que as opções de menu do sistema tenham teclas de atalho associadas. 
Exemplo:

| Ref.  	|                          Descrição                       	| Caso de Uso |
|-------	|----------------------------------------------------------	|---------------|
| RIHCx 	| Descrição do requisito RIHCx | CSUy, CSUm ... |

### 4.3 Requisitos e Restrições de Interface Externa (RIEX)

Identificar e descrever as interfaces com outros softwares/sistemas que o software deverá prover. Por exemplo, um software comercial deve gerar informações para o Sistema de Arrecadação da Secretaria da Fazenda Estadual. O formato dessas informações e o protocolo de envio são definidos pela própria secretaria, e atender essas definições é um requisito do software.
Exemplo:

| Ref.  	|                          Descrição                       	| Caso de Uso |
|-------	|----------------------------------------------------------	|---------------|
| RIEXx 	| Descrição do requisito RIEXx | CSUy, CSUm ...	|

### 4.4 Requisitos e Restrições de Plataforma de Hardware (RPHW)

Identificar e descrever requisitos e restrições relacionadas com a plataforma de hardware que será utilizada pelo software:
Exemplo:

| Ref.  	|                          Descrição                       	| Caso de Uso |
|-------	|----------------------------------------------------------	|---------------|
| RPHWx	| Descrição do requisito RPHWx | CSUy, CSUm ... |

### 4.5 Requisitos e Restrições de Plataforma de Software (RPSW)

Se o software tiver que ser executado em plataformas de software específicas, essas plataformas de software deverão ser definidas:
1. Sistema Operacional: identificar e descrever o sistema operacional em que o software deverá ser executado;
2. Softwares Básicos: identificar SGBD, linguagem de programação, ferramentas CASE e outros.
Se houver mais de uma plataforma de software, deve-se especificar qual a plataforma principal e em que situações as outras plataformas podem ser utilizadas.
Exemplo:

| Ref.  	|                          Descrição                       	| Caso de Uso |
|-------	|----------------------------------------------------------	|---------------|
| RPSWx | Descrição do requisito RSPWx | CSUy, CSUm ... |

### 4.6 Requisitos e Restrições de Desempenho (RDES)

Identificar e descrever os requisitos e restrições de desempenho do software.
Exemplo:

| Ref.  	|                          Descrição                       	| Caso de Uso |
|-------	|----------------------------------------------------------	|---------------|
| RDESx | Descrição do requisito RDESx | CSUy, CSUm ... |

### 4.7 Requisitos e restrições de disponibilidade (RDIS).

Especificar os requisitos de disponibilidade necessários para o software de uma forma global:
1. Período de disponibilidade: horário comercial, 24 horas por dia, etc.
2. Período máximo para recuperação do software em caso de falha.
Devem ser definidos os tipos de falha e a tolerância aceitável para cada tipo de falha. Os tipos de falha podem ser definidos em função dos requisitos funcionais e de dados, mas não se restringem a estes. Por exemplo: a função “Registrar Venda” deve ter um tempo para recuperação de falha de no máximo uma hora (o que significa que esta função não poderá ficar mais do que uma hora indisponível para o usuário em nenhuma circunstância). 
Exemplo:

| Ref.  	|                          Descrição                       	| Caso de Uso |
|-------	|----------------------------------------------------------	|---------------|
| RDISx	| Descrição do requisito RDISx | CSUy, CSUm ... |

### 4.8 Requisitos e Restrições de Segurança (RSEG)

Especificar os requisitos de segurança necessários para controle de acesso ao software. Definir a necessidade, por exemplo, de:
1. Verificação de senha;
2. Criptografia de dados;
3. Registro das operações efetuadas;
4. Habilitação de funções por perfil de usuário;
5. Acesso seletivo aos dados e funções.
Exemplo:

| Ref.  	|              Descrição                      	| Caso de Uso 	|
|-------	|------------------------------------------	|-------------	|
| RSEGx | Descrição do requisito RSEGx | CSUy, CSUm ... |

### 4.9 Requisitos e Restrições de Manutenibilidade (RMAN)

Especificar os requisitos que visam facilitar a manutenção posterior do software, tais como:
1. Requisitos de reutilização (exemplo: uso de implementação orientada a objetos; bibliotecas de classes e padrões de projeto);
2. Requisitos de modularização (exemplo: valores para métricas de acoplamento entre módulos; máximo de pontos de função por módulo);
3. Requisitos de configuração (exemplo: regras para controle de versões);
4. Requisitos de documentação (exemplo: documentação de programa)
Exemplo:

| Ref.  	|                          Descrição                       	| Caso de Uso |
|-------	|----------------------------------------------------------	|---------------|
| RMANx	| Descrição do requisito RMANx | CSUy, CSUm ... |

### 4.10 Requisitos e Restrições de Documentação (RDOC)

Especificar os requisitos de documentação do produto de software que será desenvolvido. 
Exemplo:

| Ref.  	|                          Descrição                       	| Caso de Uso |
|-------	|----------------------------------------------------------	|---------------|
| RDOCx | Descrição do requisito RDOCx | CSUy, CSUm ... |



## 5. Requisitos Futuros (RFUT)
---------------------------------

Este espaço é reservado para o surgimento de futuros requisitos.

| Ref.|   Descrição | Caso de Uso |
|-------|------------|---------------|
|  | |   |

## 6. Referências cruzadas complementares 
---------------------------------------------

Nesta seção são colocadas algumas referências cruzadas que podem ajudar o rastreamento futuro dos requisitos. Estes mapeamentos podem ser feitos em forma de matrizes de rastreabilidade como mostram os exemplos a seguir:

|Requisitos Funcionais | Requisitos Funcionais|
|---------------------|--------------------------|
|Colocar identificação do requisito funcional|Colocar a identificação do requisito funcional vinculado|

## 7. Modelo de dominio

## 8. Aprovação Formal 
---------------------------------------------

Por meio deste documento, confirmo que os requisitos aqui presentes abordam todas as áreas do sistema a ser desenvolvido e de requisitos futuros (sejam elas melhorias ou novas funcionalidades), de forma a desenvolver um software com qualidade e segurança. Confirmo também que este documento aborda todos os requisitos e funcionalidades de forma correta e clara ao que foi solicitado e ao que foi dito e pedido nas entrevistas, etnografias e questionários. Confirmo também que não há requisitos extras neste documento, todos os requisitos aqui citados foram requeridos e atendem à alguma funcionalidade necessária.

