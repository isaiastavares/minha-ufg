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
* 3. [Casos de Uso e Requisitos Funcionais](#4-casos-de-uso-e-requisitos-funcionais)
    * 3.1 [Transporte](#31)
    * 3.1.1 [Diagramas de Caso de Uso e Lista de casos de uso](#311-diagramas-de-caso-de-uso-e-lista-de-casos-de-uso)
    * 3.1.2 [Descrição de Casos de Uso](#312-descrição-de-casos-de-uso)
    * 3.2 [Oportunidades](#32)
    * 3.2.1 [Diagramas de Caso de Uso e Lista de casos de uso](#321-diagramas-de-caso-de-uso-e-lista-de-casos-de-uso)
    * 3.2.2 [Descrição de Casos de Uso](#322-descrição-de-casos-de-uso)
    * 3.3 [Calendário](#33)
    * 3.3.1 [Diagramas de Caso de Uso e Lista de casos de uso](#331-diagramas-de-caso-de-uso-e-lista-de-casos-de-uso)
    * 3.3.2 [Descrição de Casos de Uso](#332-descrição-de-casos-de-uso)
* 4. [Requisitos e restrições não funcionais](#4-requisitos-e-restrições-não-funcionais)
    * 4.1 [Requisitos e Restrições de Usabilidade (RUS)](#41-requisitos-e-restrições-de-usabilidade-rus)
    * 4.2 [Requisitos e Restrições de Interface Homem-Computador (RHIC)](#42-requisitos-e-restrições-de-interface-homem-computador-rhic)
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

### 1.1 Objetivos

Este documento tem os seguintes objetivos:
* Definir os interessados no sistema e as suas necessidades que devem ser satisfeitas pelo sistema a ser desenvolvido;
* Definir casos de uso, requisitos funcionais e não-funcionais do sistema e diagramas de caso de uso de forma a orientar a equipe de que será responsável pelo seu desenvolvimento;
* Estabelecer um contrato para negociação e concordância entre todos os interessados;
* Reduzir retrabalho com projeto, codificação e teste através da especificação completa dos requisitos;
* Facilitar a transferência dos produtos do desenvolvimento para novos usuários, novos clientes e novas equipes de desenvolvimento e manutenção;
* Prover uma base para a evolução futura do sistema a partir de uma versão aprovada (linha de base) deste documento.

### 1.2 Público Alvo

Este documento foi desenvolvido visando todos que utilizarão do sistema, tais como:

* Equipe de desenvolvimento: Este documento explicitará quais requisitos deverão ser desenvolvidos bem como as interações entre os próprios requisitos de forma a auxiliar na manutenção (inserção de novos requisitos e/ou manutenção dos atuais).

* Usuário-Final: Este documento explicitará quais requisitos deverão ser esperados, incluindo a instrução de como esses requisitos poderão ser acessados (por meio dos protótipos de tela).

### 1.3 Organização do documento

   1.	Introdução – Breve citação dos tópicos presentes neste artefato e o intuito dos mesmos.
   2.	Descrição do problema e do sistema – Explanação sucinta do domínio do problema e como o sistema se propõe a atender as necessidades levantadas por ele.
   3.	Casos de Uso e Requisitos Funcionais – Detalhamento dos cenários de uso funcionais relacionados ao software, com descrição por extenso e formalização dos requisitos funcionais em identificador único, categoria e prioridade de implementação.
   4.	Requisitos e Restrições não funcionais – Elucidação dos atributos de qualidade e regras de negócio fundamentais para o sistema que não fazem parte do domínio do problema.
   5.	Requisitos Futuros – Citação dos requisitos planejados pra futuras versões do produto.
   6.	Referência Cruzadas Complementares – Relação entre os requisitos funcionais e não funcionais e referenciação das origens destes e dos casos de uso.
   7. Modelo de domínio - Representação visual das classes conceituais ou objetos domundo real no domínio de problema, representando a compreensão da informação que o sistema vai gerenciar
   8.	Aprovação Formal – Prova formalizada de verificação e validação do conteúdo e integridade deste documento perante os interessados.


### 1.4 Definição de Siglas e Nomenclaturas

Definir e explicar sucintamente siglas e nomencalturas utilizadas neste documento.

* TR: Transporte
* OP: Oportunidade
* CA: Calendário
* CSU: Caso de Uso
* RFUN: Requisito Funcional
* RUS: Requisito de Usabilidade
* RHIC: Requisito de Interface Homem-Computador
* RIEX: Requisito de Interface Externa
* RPHW: Requisito de Plataforma de Hardware
* RPSW: Requisito de Plataforma de Software
* RDES: Requisito de Desempenho
* RDIS: Requisito de Dispponibilidade
* RSEG: Requisito de Segurança
* RMAN: Requisito de Manutenibilidade
* RDOC: Requisito de Documentação
* RFUT: Requisitos Futuros

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

| Interessado(s) 	| Descrição 	|
|:----------------:	|---------	|
| Usuário-Final | Utilizará das facilidades que o sistema propõe, tais como, obter rotas e horários de pontos específicos nos campus, visualizar datas letivas e possiveis oportunidades.|


## 3. Casos de Uso e Requisitos Funcionais
---------------------------------

### 3.1 Transporte

#### 3.1.1 Diagramas de Caso de Uso e Lista de casos de uso

<img src="https://user-images.githubusercontent.com/9218555/30995360-04533f50-a490-11e7-9515-3f0eab591ff4.png" width="550" height="500"/>

* TR-CSU1: Selecionar local de origem e local de destino com base em uma lista;
* TR-CSU2: Visualizar rota entre a origem e o destino definidos pelo usuário;
* TR-CSU3: Modificar destino durante a rota;
* TR-CSU4: Visualizar linhas e horários;
* TR-CSU5: Visualizar locais Pré-definidos;
* TR-CSU6: Criar local Pré-definido;
* TR-CSU7: Atualizar local Pré-definido;
* TR-CSU8: Remover local Pré-definido;

#### 3.1.2 Descrição de Casos de Uso

**TR-CSU1**- Selecionar local de origem e local de destino com base em uma lista
  * Identificador: TR-CSU1

  * Atores envolvidos: Usuário e Sistema

  * Pré-condições:
    * Usuário deverá estar localizado na região Metropolitana de Goiânia.
    * Usuário deverá estar conectado á internet.
    * Usuário deverá estar com o GPS habilitado (opcional).

  * Pós-condições: 
    * A lista com os lugares deverá estar disponível ao usuário.

  * Cenário:
    1. Usuário abre o aplicativo.
    2. Usuário seleciona aba de transportes.
        * Se o usuário estiver fora da região metropoliana de Goiâna.
            * Sistema exibe ao usuário uma tela de erro explicando que o mesmo não se encontra dentro da área de atuação do Aplicativo.
        * Se o usuário não possuir acesso a internet.
            * Sistema exibe ao usuário uma tela de erro explicando que o mesmo não possui acesso a internet no momento.  
    3. Usuário define o seu local de origem.
    4. Sistema exibe uma lista contendo os possiveis locais de origem conforme as regras definidas (RINF3, RINF4, RINF5 e RINF6).
    5. Usuário seleciona o local de origem desejado com base na lista disponível.
    6. Usuário define o seu local de destino.
    7. Sistema exibe uma lista contendo os possiveis locais de destino conforme as regras definidas (RINF3, RINF4, RINF5 e RINF6).
    8. Usuário seleciona o local de destino desejado com base na lista disponível.

  * Protótipos de tela:
   <img src="https://user-images.githubusercontent.com/11222413/31042741-13367a00-a585-11e7-937f-d26e01b46ded.png" width="700" height="350"/>


| Ref.     |                          Descrição                       	| Categoria | Prioridade |
|----------|------------------------------------------------------------|-----------|------------|
| TR-RFUN 1 | Mostrar lista de possiveis locais de origem disponíveis cadastrados | Evidente |Alta |
| TR-RFUN 2 | Mostrar lista de possiveis locais de destino disponíveis cadastrados | Evidente |Alta |
| TR-RFUN 3 | Validar local de origem | Oculta |Média |
| TR-RFUN 4 | Validar local de destino | Oculta |Média |

**TR-CSU2**- Visualizar rota entre a origem e o destino definidos pelo usuário
  * Identificador: TR-CSU2

  * Atores envolvidos: Usuário e Sistema

  * Pré-condições: 
    * As mesmas definidas em TR-CSU1.

  * Pós-condições:
    * As mesmas definidas em TR-CSU1.

  * Cenário:
    1. Usuário executa TR-CSU1.
    2. Usuário clica no botão para confirmar a origem e o destino selecionados.
    3. Sistema verifica o ponto mais próixmo do usuário.
    4. Sistema exibe uma rota para transporte coletivo partindo do ponto de origem do usuário até o destino definido pelo usuário.

  * Protótipos de tela:
   <img src="https://user-images.githubusercontent.com/11222413/31042546-1428ab6c-a581-11e7-88a1-a26317e1b186.png" width="200" height="350"/>

| Ref.     |                          Descrição                       	| Categoria | Prioridade |
|----------|------------------------------------------------------------|-----------|------------|
| TR-RFUN 5 | Validar posição de GPS do usuário | Oculta |Média |
| TR-RFUN 6 | Buscar rota de acordo com os pontos de origem e de destino definidos pelo usuário | Oculta |Alta |

**TR-CSU3**- Modificar destino durante a rota
  * Identificador: TR-CSU3

  * Atores envolvidos: Usuário, Sistema

  * Pré-condições: 
    * As mesmas definidas em TR-CSU1.

  * Pós-condições:
    * As mesmas definidas em TR-CSU1.

  * Cenário:
    1. Usuário executa TR-CSU2.
    2. Usuário define um novo destino com base durante a rota.
    3. Sistema exibe uma lista de lugares conforme as regras definidas (RINF3, RINF4, RINF5 e RINF6).
    4. Usuário seleciona um lugar.
    5. Sistema exibe um popup para validar a modificação do destino da rota.
    6. Usuário confirma a modificação do destino da rota.
    7. Sistema exibe uma nova rota partindo do ponto de transporte coletivo mais proximo do usuário até o destino definido pelo usuário.

  * Protótipos de tela: 
   <img src="https://user-images.githubusercontent.com/11222413/31101501-55573e76-a7a4-11e7-96b6-4f4554723b7f.png" width="700" height="350"/>
  
| Ref.     |                          Descrição                       	| Categoria | Prioridade |
|----------|------------------------------------------------------------|-----------|------------|
| TR-RFUN 4 | Validar local de destino | Oculta |Média |
| TR-RFUN 6 | Buscar rota de acordo com os pontos de origem e de destino definidos pelo usuário | Oculta |Alta |
| TR-RFUN 7 | Validar com o usuário a mudança do local de destino | Evidente |Média |

**TR-CSU4**- Visualizar linhas e horários
  * Identificador: TR-CSU4

  * Atores envolvidos: Usuário, Sistema.

  * Pré-condição:
    * Usuário deverá estar localizado na região metropolitana de Goiânia.
    * Usuário deverá estar conectado á internet.
    * Usuário deverá estar com o GPS habilitado (opcional).
  
  * Pós-condições:
    * Não há. 

  * Cenário:
    1. Usuário abre o aplicativo.
    2. Usuário seleciona aba de transportes.
        *  Se o usuário estiver fora da região metropoliana de Goiâna.
            *  Sistema exibe ao usuário uma tela de Erro explicando que o mesmo não se encontra dentro da área de atuação do Aplicativo.
        * Se o usuário não possuir acesso a internet.
            * Sistema exibe ao usuário uma tela de Erro explicando que o mesmo não possui acesso a internet no momento.
    3. Usuário seleciona o ponto de ônibus desejado.
    4. Sistema exibe uma tela contendo as informações a respeito das linhas que passam no ponto selecionado.


  * Protótipos de tela:
   <img src="https://user-images.githubusercontent.com/11222413/31042789-5874687e-a586-11e7-8244-e83a6e74d547.png" width="600" height="350"/>


| Ref.     |                          Descrição                       	| Categoria | Prioridade |
|----------|------------------------------------------------------------|-----------|------------|
| TR-RFUN 8 | Buscar informações de rotas de determinado ponto de ônibus | Oculta |Alta |
| TR-RFUN 9 | Exibir informações de rotas de determinado ponto de ônibus | Evidente |Alta |
| TR-RFUN 10 | Buscar informações de horários de determinado ponto de ônibus | Oculta |Alta |
| TR-RFUN 11 | Exibir informações de horários de determinado ponto de ônibus | Evidente |Alta |

**TR-CSU5**- Visualizar locais Pré-definidos
  * Identificador: TR-CSU5

  * Atores envolvidos: Usuário, Sistema.

  * Pré-condição: 
    * Usuário deverá estar localizado na região Metropolitana de Goiânia.
    * Usuário deverá estar com o GPS habilitado (opcional).

  * Pós-condições: 
    * O banco de dados deverá estar disponível e funcional.

  * Cenário:
    1. Usuário abre o aplicativo.
    2. Usuário seleciona aba de transportes.
        * Se o usuário estiver fora da região metropoliana de Goiâna.
            * Sistema exibe ao usuário uma tela de erro explicando que o mesmo não se encontra dentro da área de atuação do Aplicativo.
        * Se o usuário não possuir acesso a internet.
            * Sistema exibe ao usuário uma tela de erro explicando que o mesmo não possui acesso a internet no momento.
    3. Usuário seleciona o botão "Meus locais".
    4. Sistema exibe uma tela contendo os locais pré-definidos cadastrados.
        * Se o usuário não houver cadastrado local algum antes.
            * O sistema exibe uma tela "vazia", sem os locais cadastrados.

  * Protótipos de tela:
  <img src="https://user-images.githubusercontent.com/11222413/31042512-5dd01dfa-a580-11e7-804c-2180d1f00c60.png" width="200" height="350"/>


| Ref.     |                          Descrição                       	| Categoria | Prioridade |
|----------|------------------------------------------------------------|-----------|------------|
| TR-RFUN 12 | Exibir lista de locais pré-definidos do usuário | Evidente |Média |

**TR-CSU6**- Criar local Pré-definido
  * Identificador: TR-CSU6

  * Atores envolvidos: Usuário, Sistema

  * Pré-condições: 
    * As mesmas definidas em TR-CSU5.

  * Pós-condições:
    * As mesmas definidas em TR-CSU5.

  * Cenário:
    1. Usuário executa TR-CSU5.
    2. Usuário seleciona o botão de adicionar novo local.
    3. Sistema exibe uma tela contendo um mapa com os locais adicionados.
    4. Usuário seleciona um ponto no mapa, podendo selecionar sua própria posição segundo o GPS, referente ao novo local.
    5. Usuário nomeia o novo local.
    6. Usuário confirma os dados da nova localização.
    7. Sistema retorna para a tela de locais pré-definidos cadastrados.

  * Protótipos de tela:
  <img src="https://user-images.githubusercontent.com/11222413/31042715-920c30e6-a584-11e7-8d17-12ff5de34d0b.png" width="700" height="350"/>


| Ref.     |                          Descrição                       	| Categoria | Prioridade |
|----------|------------------------------------------------------------|-----------|------------|
| TR-RFUN 13 | Validar posição de "Meus locais" selecionada pelo usuário | Oculta |Média |
| TR-RFUN 14 | Gravar no banco a posição e nome do local | Oculta |Média 

**TR-CSU7**- Atualizar local Pré-definido
  * Identificador: TR-CSU7

  * Atores envolvidos: Usuário, Sistema

  * Pré-condições: 
    * As mesmas definidas em TR-CSU5.
    * Deverá existir um local Pré-definido cadastrado no banco de dados.

  * Pós-condições:
    * As mesmas definidas em TR-CSU5.

  * Cenário:
    1. Usuário executa TR-CSU5.
    2. Usuário seleciona o botão de editar novo local.
    3. Sistema exibe uma tela contendo um mapa com os locais adicionados.
    4. Usuário seleciona um ponto no mapa (podendo selecionar sua própria posição segundo o GPS) referente á atualização do local.
    5. Usuário renomeia o local.
    6. Usuário confirma os dados da localização atualizada.
    7. Sistema atualiza o local pré-definido selecionado no banco de dados.
    8. Sistema retorna para a tela de locais pré-definidos cadastrados.

  * Protótipos de tela:
  <img src="https://user-images.githubusercontent.com/11222413/31042717-94cd8e7e-a584-11e7-8756-d5666fad290b.png" width="550" height="350"/>


| Ref.     |                          Descrição                       	| Categoria | Prioridade |
|----------|------------------------------------------------------------|-----------|------------|
| TR-RFUN 15 | Atualizar no banco a posição e nome do local | Oculta |Média 

**TR-CSU8**- Remover local Pré-definido
  * Identificador: TR-CSU8

  * Atores envolvidos: Usuário, Sistema

  * Pré-condições: 
    * As mesmas definidas em TR-CSU5.
    * Deverá existir um local Pré-definido cadastrado no banco de dados.

  * Pós-condições:
    * As mesmas definidas em TR-CSU5.

  * Cenário:
    1. Usuário executa TR-CSU5.
    2. Usuário seleciona o botão de remover novo local.
    3. Sistema remove o local pré-definido selecionado do banco de dados.
    4. Sistema retorna para a tela de locais pré-definidos cadastrados.

  * Protótipos de tela:
  <img src="https://user-images.githubusercontent.com/11222413/31042718-9a73d108-a584-11e7-8ed0-5d59c8141502.png" width="550" height="350"/>

| Ref.     |                          Descrição                       	| Categoria | Prioridade |
|----------|------------------------------------------------------------|-----------|------------|
| TR-RFUN 15 | Remover do banco a posição e nome do local | Oculta |Média 

### 3.2 Oportunidades

#### 3.2.1 Diagramas de Caso de Uso e Lista de casos de uso

* OP-CSU1: Cadastrar Oportunidade

#### 3.2.2 Descrição de Casos de Uso

**OP-CSU1**- Cadastrar Oportunidade (Web)

  * Identificador: OP-CSU1

  * Atores envolvidos: Usuário com permissão 'Oportunidade'

  * Pré-condições: Usuário deve estar conectado à internet.

  * Pós-condições:
	  * Os campos Título, Descrição, Categoria, Contato e Cursos Relacionados devem ser obrigatórios.

  * Cenário principal:
      * Usuário acessa o sistema.
      * Usuário clica no menu Oportunidades.
      * Usuário clica no botão para cadastrar oportunidade.
      * Usuário informa as seguintes informações: Título, Empresa, Descrição, Horário / Carga Horária, Requisitos, Benefícios (Salário, Bolsa, Auxílio Transporte, Outros), Contato (Nome, Email e Telefone), Local, Cursos Relacionados, Categoria (CLT, PJ, Trainee, Estágio ou Freelancer).

  * Cenários secundários:
      * Usuário não possui permissão 'Oportunidade', então o menu Oportunidades não é exibido para ele.

  * Protótipos de tela: Protótipos de tela (interface homem-computador) relacionados ao caso de uso.

| Ref.     |                          Descrição                       	| Categoria | Prioridade |
|----------|------------------------------------------------------------|-----------|------------|
| OP-RFUN 1.1 | O menu de Oportunidades só deve ser exibido para o usuário que tiver permissão 'Oportunidades' | Oculta |Alta |

**OP-CSU2**- Listar Oportunidades (Web)

  * Identificador: OP-CSU2

  * Atores envolvidos: Usuário com permissão 'Oportunidade'

  * Pré-condições: Usuário deve estar conectado à internet.

  * Pós-condições: Não possui pós-condições.

  * Cenário principal:
      * Usuário acessa o sistema.
      * Usuário clica no menu Oportunidades.


  * Cenários secundários:
      * Usuário filtra oportunidades exibidas através do campo de busca.

  * Protótipos de tela: Protótipos de tela (interface homem-computador) relacionados ao caso de uso.

| Ref.     |                          Descrição                       	| Categoria | Prioridade |
|----------|------------------------------------------------------------|-----------|------------|
| OP-RFUN 2.1 | O menu de Oportunidades só deve ser exibido para o usuário que tiver permissão 'Oportunidades' | Oculta |Alta |
| OP-RFUN 2.2 | Listar as primeiras 10(dez) oportunidades.  | Evidente |Média|
| OP-RFUN 2.3 | Exibir 4 colunas na tabela de listagem das oportunidades, com o ID, o Título, a Categoria e também a coluna com ícones de ações (Alterar, Excluir) para cada oportunidade.  | Evidente |Alta |
| OP-RFUN 2.4 | Filtrar de acordo com o campo de busca tanto para o ID, Título ou Categoria de cada oportunidade.  | Evidente |Alta |

### 3.3 Calendário

#### 3.3.1 Diagramas de Caso de Uso e Lista de casos de uso

![](http://postimg.org/image/skrz04i6x/)

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
2. O administrador, após realizar alguma alteração, deve alterar os dados e atualizar para que os usuários consigam acessar o Calendário offline.

  * Protótipos de tela: Protótipos de tela (interface homem-computador) relacionados ao caso de uso.


| Ref.     |                          Descrição                       	| Categoria | Prioridade |
|-------|----------------------------------------------------------|---------------|---------------|
| CA-RFUN 2.1 | O Calendário deve ser acessado offline por seus usuários. | Evidente |Alta  |

**CA-CSU3**- Fazer consulta de evento

* Identificador:CA-CSU3
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
| CA-RFUN 3.1 | descricao | Evidente |Alta  |

**CA-CSU4**- Pesquisar eventos offline
  * Identificador: CA-CSU4.

  * Atores envolvidos: Administrador, Usuário.

  * Pré-condições:
	* Usuário não deve estar conectado à internet.
    * O usuário deve ter feito login no aplicativo pelo menos uma vez.

  * Pós-condições: O aplicativo apresenta o calendário.

  * Cenário principal:
    * O Usuário não possui internet.
    * O Usuário abre o aplicativo Minha UFG.
    * O Usuário seleciona o ícone do calendário.
    * O Usuário pesquisa o evento desejado.
    * O aplicativo lista os eventos sugeridos conforme a pesquisa feita.
  * Cenários secundários:
	* O aplicativo avisa que não tem nenhum evento disponível.
	* O aplicativo pede que para efetuar conexão com a internet para atualizar.

  * Protótipos de tela: Protótipos de tela (interface homem-computador) relacionados ao caso de uso.


| Ref.     |                          Descrição                       	| Categoria | Prioridade |
|-------|----------------------------------------------------------|---------------|---------------|
| CA-RFUN 4.1 | As pesquisas devem funcionar no modo offline | Evidente |Alta  |

**CA-CSU5**- Postagem de Eventos
  * Identificador: CA-CSU5

  * Atores envolvidos: Administrador

  * Pré-condições: O administrador deve acessar o modo administrador do aplicativo Minha UFG para realizar a postagem de eventos.

  * Pós-condições: O sistema apresenta as postagens realizadas pelo administrador.

  * Cenário principal:
  1. O administrador acessa o aplicativo minha UFG.
  2. O administrador entra dentro da função minha UFG.
  3. O administrador insere a postagem.
  4. Postagem realizada com sucesso.

  * Cenários secundários:
  1. As atualizações devem aparecer para o usuário após ter acesso à internet.
  2. O usuário pode ter acesso às postagens offline.
  3. A cada nova postagem, o usuário deve atualizar a função aplicativo.

  * Protótipos de tela: Protótipos de tela (interface homem-computador) relacionados ao caso de uso.

**CA-CSU6**- Notificações de eventos
  * Identificador: CA-CSU6.

  * Atores envolvidos: Usuários.

  * Pré-condições: Os usuários devem estar inscritos para receberem as notificações.

  * Pós-condições: Essas notificações disparadas não serão mais enviadas aos usuários.

  * Cenário principal:
  1. É cadastrado um evento exceptional, não previsto no calendário acadêmico, para uma regional ou para toda a UFG.
  2. O sistema empacota essa informação e envia para todos os inscritos nessas regionais.
  3. Ao chegar a notificação no dispositivo a mesma fica visível na caixa de notificações do dispositivo.
  4. Ao selecionar a notificação, o aplicativo é invocado e a tela de descrição do evento é exibida ao usuário.

  * Cenários secundários:
  1. Duas ou mais notificações foram recebidas pelo usuário e não foram visualizadas
  2. Ao selecionar a notificação é exibida a lista de notificações pendentes recebidas, o usuário seleciona a que deseja abrir.
  * Protótipos de tela: Protótipos de tela (interface homem-computador) relacionados ao caso de uso.


| Ref.     |                          Descrição                       	| Categoria | Prioridade |
|-------|----------------------------------------------------------|---------------|---------------|
| CA-RFUN 6.1 | A postagem são eventos extraordinários em que o calendário acadêmico não estava prevendo. | Evidente |Alta  |

## 4. Requisitos e restrições não funcionais
--------------------------------------------

Elaborar uma lista de todos os requisitos não funcionais. Considerar requisitos de informação, de interface, de projeto, de arquitetura de software, de plataforma de hardware, de plataforma de software, de plataforma de comunicação, de desempenho, de disponibilidade, de segurança, de manutenibilidade, de portabilidade e de documentação. A lista poderá ser dividida por tipo de requisito, mas é importante que os requisitos tenham uma identificação única para que possam ser referenciados sem ambigüidades no futuro.

### 4.1 Requisitos e Restrições de Usabilidade (RUS)

| Ref. 	|              Descrição                                               	| Caso de Uso     	|
|------	|-------------------------------------------------------------------	|-----------------	|
| RINF1 | O usuário deve estar localizado dentro da região metropolitana de goiânia  | Todos de transporte  |
| RINF2 | Obrigatóriamente um dos pontos de origem ou de destino deverá ser em um campus da UFG  | TR-CSU1 , TR-CSU3  |
| RINF3 | Se a rota do usuário possuir **origem de dentro da UFG**, a lista de locais  exibidos deverá conter: As preferências definidas previamente pelo usuário, uma lista com os locais do campus em que está presente e a posição atual do usuário com base no GPS (Se habilitado). | TR-CSU1 , TR-CSU3 |
| RINF4 | Se a rota do usuário possuir **origem de fora da UFG**, a lista de locais  exibidos deverá conter: As preferências definidas previamente pelo usuário, uma opção para inserir uma origem e a posição atual do usuário com base no GPS (Se habilitado). | TR-CSU1 , TR-CSU3 |
| RINF5 | Se a rota do usuário possuir **destino de dentro da UFG**, a lista de locais  exibidos deverá conter: As preferências definidas previamente pelo usuário e uma lista com os locais do campus em que está presente. | TR-CSU1 , TR-CSU3 |
| RINF6 | Se a rota do usuário possuir **destino de fora da UFG**, a lista de locais  exibidos deverá conter: As preferências definidas previamente pelo usuário e uma opção para inserir um destino. | TR-CSU1 , TR-CSU3 |

### 4.2	Requisitos e Restrições de Interface Homem Computador (RHIC)

| Ref.  	|                          Descrição                       	| Caso de Uso |
|-------	|----------------------------------------------------------	|---------------|
| RIHC1 	| Deve ser utilizado “Google Material Design” para a interface. | Todos |
| RIHC2 	| A área do mapa deverá ser restringida apenas para a região metropolitana de goiânia. | Todos de Transporte |

### 4.3 Requisitos e Restrições de Interface Externa (RIEX)

| Ref.  	|                          Descrição                       	| Caso de Uso |
|-------	|----------------------------------------------------------	|---------------|
| RIEX1 	| O software realizará interação com o sistema Firebase. | TR-CSU1, TR-CSU6, TR-CSU7, TR-CSU8	|
| RIEX2 	| O software realizará interação com o sistema Google Maps. | TR-CSU1, TR-CSU2, TR-CSU3, TR-CSU4, TR-CSU5	|

### 4.4 Requisitos e Restrições de Plataforma de Hardware (RPHW)

| Ref.  	|                          Descrição                       	| Caso de Uso |
|-------	|----------------------------------------------------------	|---------------|
| RPHW1	| Hardware de GPS integrado | Todos do Transporte |
| RPHW2	| Hardware para acesso á internet | Todos |
| RPHW3	| Processador mínimo de 1 GHz | Todos |

### 4.5 Requisitos e Restrições de Plataforma de Software (RPSW)

| Ref.  	|                          Descrição                       	| Caso de Uso |
|-------	|----------------------------------------------------------	|---------------|
| RPSW1 | Android versão 4.1 ou superior | Todos |
| RPSW2 | Deverá possuir uma aplicação externa de mapas | Todos do Transporte |
| RPSW3 | Uso do Firebase como serviço | Todos |

### 4.6 Requisitos e Restrições de Desempenho (RDES)

| Ref.  	|                          Descrição                       	| Caso de Uso |
|-------	|----------------------------------------------------------	|---------------|
| RDES1 | O aplicativo não pode travar/encerrar o processo com frequência. | Todos |

### 4.7 Requisitos e restrições de disponibilidade (RDIS).

| Ref.  	|                          Descrição                       	| Caso de Uso |
|-------	|----------------------------------------------------------	|---------------|
| RDIS1	| O aplicativo deve inicializar por completo em até 3 segundos. | Todos |
| RDIS2	| O aplicativo deve estar disponível e funcional 24/7.  | Todos |

### 4.8 Requisitos e Restrições de Segurança (RSEG)

| Ref.  	|              Descrição                      	| Caso de Uso 	|
|-------	|------------------------------------------	|-------------	|
| RSEG1 | O aplicativo não deverá compartilhar a posição do usuário. | Todos de transporte |
| RSEG2 | O aplicativo deverá informar ao usuário que utilizará de sua localização. | Todos de transporte |
| RSEG3 | O aplicativo deverá informar ao usuário que utilizará dados de internet. | Todos |

### 4.9 Requisitos e Restrições de Manutenibilidade (RMAN)

| Ref.  	|                          Descrição                       	| Caso de Uso |
|-------	|----------------------------------------------------------	|---------------|
| RMAN1	| Será utilizado a ferramenta Javadoc para padronizar e facilitar o entendimento do código-fonte | Todos |
| RMAN2	| Todos os commits serão ser em inglês | Todos |

### 4.10 Requisitos e Restrições de Documentação (RDOC)

| Ref.  	|                          Descrição                       	| Caso de Uso |
|-------	|----------------------------------------------------------	|---------------|
| RDOC1 | Devem ser lançadas as notas de release a cada nova baseline. | Não se aplica |

## 5. Requisitos Futuros (RFUT)
---------------------------------

No momento não há requisitos futuros.

## 6. Referências cruzadas complementares
---------------------------------------------

Nesta seção são colocadas algumas referências cruzadas que podem ajudar o rastreamento futuro dos requisitos. Estes mapeamentos podem ser feitos em forma de matrizes de rastreabilidade como mostram os exemplos a seguir:

|Requisitos Funcionais | Requisitos Funcionais|
|---------------------|--------------------------|
|Colocar identificação do requisito funcional|Colocar a identificação do requisito funcional vinculado|

## 7. Modelo de dominio

### 7.1 Modelo de domínio Transporte

<img src="https://user-images.githubusercontent.com/9218555/31204209-1ebc51a0-a941-11e7-9524-7f74ff76192a.png" width="700" height="450"/>

## 8. Aprovação Formal
---------------------------------------------

Por meio deste documento, confirmo que os requisitos aqui presentes abordam todas as áreas do sistema a ser desenvolvido e de requisitos futuros (sejam elas melhorias ou novas funcionalidades), de forma a desenvolver um software com qualidade e segurança. Confirmo também que este documento aborda todos os requisitos e funcionalidades de forma correta e clara ao que foi solicitado e ao que foi dito e pedido nas entrevistas, etnografias e questionários. Confirmo também que não há requisitos extras neste documento, todos os requisitos aqui citados foram requeridos e atendem à alguma funcionalidade necessária.
