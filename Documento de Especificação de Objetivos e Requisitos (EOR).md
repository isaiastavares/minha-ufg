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
    * 4.2 [Requisitos e Restrições de Interface Homem-Computador (RHIC)](#42requisitos-e-restrições-de-interface-homem-computador-rhic)
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
    * 6.1 [Transporte](#61-transporte)

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

* **Equipe de desenvolvimento**: Este documento explicitará quais requisitos deverão ser desenvolvidos bem como as interações entre os próprios requisitos de forma a auxiliar na manutenção (inserção de novos requisitos e/ou manutenção dos atuais).

* **Usuário-Final**: Este documento explicitará quais requisitos deverão ser esperados, incluindo a instrução de como esses requisitos poderão ser acessados (por meio dos protótipos de tela).

### 1.3 Organização do documento

   1. **Introdução** – Breve citação dos tópicos presentes neste artefato e o intuito dos mesmos.
   2. **Descrição do problema e do sistema** – Explanação sucinta do domínio do problema e como o sistema se propõe a atender as necessidades levantadas por ele.
   3. **Casos de Uso e Requisitos Funcionais** – Detalhamento dos cenários de uso funcionais relacionados ao software, com descrição por extenso e formalização dos requisitos funcionais em identificador único, categoria e prioridade de implementação.
   4. **Requisitos e Restrições não funcionais** – Elucidação dos atributos de qualidade e regras de negócio fundamentais para o sistema que não fazem parte do domínio do problema.
   5. **Requisitos Futuros** – Citação dos requisitos planejados pra futuras versões do produto.
   6. **Referência Cruzadas Complementares** – Relação entre os requisitos funcionais e não funcionais e referenciação das origens destes e dos casos de uso.
   7. **Modelo de domínio** - Representação visual das classes conceituais ou objetos domundo real no domínio de problema, representando a compreensão da informação que o sistema vai gerenciar
   8. **Aprovação Formal** – Prova formalizada de verificação e validação do conteúdo e integridade deste documento perante os interessados.

### 1.4 Definição de Siglas e Nomenclaturas

* **TR**: Transporte
* **OP**: Oportunidade
* **CA**: Calendário
* **CSU**: Caso de Uso
* **RFUN**: Requisito Funcional
* **RUS**: Requisito de Usabilidade
* **RHIC**: Requisito de Interface Homem-Computador
* **RIEX**: Requisito de Interface Externa
* **RPHW**: Requisito de Plataforma de Hardware
* **RPSW**: Requisito de Plataforma de Software
* **RDES**: Requisito de Desempenho
* **RDIS**: Requisito de Dispponibilidade
* **RSEG**: Requisito de Segurança
* **RMAN**: Requisito de Manutenibilidade
* **RDOC**: Requisito de Documentação
* **RFUT**: Requisitos Futuros
* **Região metropolitana**: Conjunto de **[cidades](http://www.cidade-brasil.com.br/regiao-metropolitana-de-goiania.html)** do estado de goiás. 
* **UFG**: Universidade Federal de Goiás

## 2. Descrição do problema e do sistema
-----------------------------------------

### 2.1 Identificação e missão do Sistema

O aplicativo minha-ufg visa disponibilizar aos seus usuários acesso aos serviços online da Universidade Federal de Goiás.

### 2.2 Domínio do problema e contexto de sua aplicação

Tendo em vista a dificuldade de acesso aos serviços disponíveis na UFG, o aplicativo visa facilitar ao usuário os serviços mais básicos da universidade, dentro os quais estão: Segurança, Notícias, Rádio Universitária, Eventos, Restaurantes Universitários, Guia estudantil (estes já implementados). Como também os novos serviços discutidos neste documento: Oportunidades, Calendário e Transportes.

### 2.3 Descrição dos interessados do sistema

| Interessado(s) 	| Descrição 	|
|----------------|---------	|
| Usuário-Final | Utilizará das facilidades que o sistema propõe, tais como, obter rotas e horários de pontos específicos nos campus, visualizar datas letivas e possiveis oportunidades.|

## 3. Casos de Uso e Requisitos Funcionais
---------------------------------

### 3.1 Transporte

#### 3.1.1 Diagramas de Caso de Uso e Lista de casos de uso

![](https://user-images.githubusercontent.com/9218555/30995360-04533f50-a490-11e7-9515-3f0eab591ff4.png)

* **TR-CSU1**: Selecionar local de origem e local de destino com base em uma lista;
* **TR-CSU2**: Visualizar rota entre a origem e o destino definidos pelo usuário;
* **TR-CSU3**: Modificar destino durante a rota;
* **TR-CSU4**: Visualizar linhas e horários;
* **TR-CSU5**: Visualizar locais Pré-definidos;
* **TR-CSU6**: Criar local Pré-definido;
* **TR-CSU7**: Modificar local Pré-definido;
* **TR-CSU8**: Remover local Pré-definido;

#### 3.1.2 Descrição de Casos de Uso

**TR-CSU1**- Selecionar local de origem e local de destino.
 * Identificador: TR-CSU1

 * Atores envolvidos: Usuário(Fernanda) e Sistema

  * Pré-condições:
    * Usuário deverá estar localizado na região Metropolitana de Goiânia.
    * Usuário deverá estar conectado à internet.
    * Usuário deverá estar com o GPS habilitado (opcional).

  * Pós-condições: 
    * O aplicativo seleciona corretamente local de origem e destino.

  * Cenário:
    1. Usuário seleciona Transporte na tela principal do app.
        * Se o usuário estiver fora da região metropoliana de Goiâna:
            * Sistema exibe ao usuário uma tela de erro explicando que o mesmo não se encontra dentro da área de atuação do Aplicativo.
        * Se o usuário não possuir acesso a internet:
            * Sistema exibe ao usuário uma tela de erro explicando que o mesmo não possui acesso a internet no momento.  
    2. Usuário aperta no campo de origem.
    3. Sistema exibe uma lista contendo os possiveis locais de origem conforme as regras definidas (RINF3, RINF4, RINF5 e RINF6).
    4. Usuário seleciona o local de origem desejado com base na lista disponível ou no próprio mapa.
    5. Usuário aperta no campo de destino.
    6. Sistema exibe uma lista contendo os possiveis locais de destino conforme as regras definidas (RINF3, RINF4, RINF5 e RINF6).
    7. Usuário seleciona o local de destino desejado com base na lista disponível ou no próprio mapa.

  * Protótipos de tela:
   <img src="https://user-images.githubusercontent.com/11222413/31588100-bcb0f23e-b1cb-11e7-8ece-7e158e3bc9ad.png" width="700" height="700"/>

| Ref. | Descrição | Categoria | Prioridade |
|----------|------------------------------------------------------------|-----------|------------|
| TR-RFUN 1 | Mostrar lista de possiveis locais de origem disponíveis cadastrados | Evidente |Alta |
| TR-RFUN 2 | Mostrar lista de possiveis locais de destino disponíveis cadastrados | Evidente |Alta |
| TR-RFUN 3 | Validar local de origem | Oculta |Média |
| TR-RFUN 4 | Validar local de destino | Oculta |Média |

**TR-CSU2**- Visualizar rota entre a origem e o destino definidos pelo usuário
 * Identificador: TR-CSU2

 * Atores envolvidos: Usuário(Fernanda) e Sistema

  * Pré-condições: 
    * TR-CSU1 deve ter sido executado.

  * Pós-condições:
    * O aplicativo mostra as opções de rotas entre os locais definidos pelo usuário.

  * Cenário:
    1. Usuário executa TR-CSU1.
    2. Usuário visualiza as possíveis rotas, no mapa e na parte inferior da tela.
    3. Usuário arrasta a parte inferior para cima a fim de visualizar todas as opções de rotas e selecionar uma.
    4. Sistema exibe apenas a rota selecionada pelo usuário.

  * Protótipos de tela:
   <img src="https://user-images.githubusercontent.com/11222413/31588101-bced72fe-b1cb-11e7-8396-8ff7a5c49ab9.png" height="350"/>

| Ref. | Descrição | Categoria | Prioridade |
|----------|------------------------------------------------------------|-----------|------------|
| TR-RFUN 5 | Validar posição de GPS do usuário | Oculta |Média |
| TR-RFUN 6 | Buscar rota de acordo com os pontos de origem e de destino definidos pelo usuário | Oculta |Alta |

**TR-CSU3**- Modificar destino durante a rota
 * Identificador: TR-CSU3

 * Atores envolvidos: Usuário(Fernanda), Sistema

  * Pré-condições: 
    * TR-CSU1 e TR-CSU2 devem ter sido executados.

  * Pós-condições:
    * O aplicativo mostra as novas opções de rotas entre os locais definidos pelo usuário.

  * Cenário:
    1. Usuário executa TR-CSU2.
    2. Usuário aperta no campo destino para mudar o local.
    3. Sistema exibe um popup para validar a modificação do destino da rota.
    4. Sistema exibe uma lista de lugares conforme as regras definidas (RINF3, RINF4, RINF5 e RINF6).
    5. Usuário seleciona um novo local.
    6. Usuário confirma a modificação do destino da rota.
    7. Sistema exibe uma nova rota partindo do ponto de transporte coletivo mais proximo do usuário até o novo destino definido pelo usuário.

  * Protótipos de tela: 
   <img src="https://user-images.githubusercontent.com/11222413/31588103-bd25686c-b1cb-11e7-8ff5-6365ecb5dc32.png" width="900" height="350"/>
  
| Ref.     |                          Descrição                       	| Categoria | Prioridade |
|----------|------------------------------------------------------------|-----------|------------|
| TR-RFUN 4 | Validar local de destino | Oculta |Média |
| TR-RFUN 6 | Buscar rota de acordo com os pontos de origem e de destino definidos pelo usuário | Oculta |Alta |
| TR-RFUN 7 | Validar com o usuário a mudança do local de destino | Evidente |Média |

**TR-CSU4**- Visualizar linhas e horários
 * Identificador: TR-CSU4

 * Atores envolvidos: Usuário(Fernanda), Sistema.

  * Pré-condição:
    * As mesmas definidas em TR-CSU1.
  
  * Pós-condições:
    * O aplicativo mostra as linhas e horários de acordo com o ponto selecionado pelo usuário.

  * Cenário:
    1. Usuário seleciona Transporte na tela principal do app.
        *  Se o usuário estiver fora da região metropoliana de Goiâna.
            *  Sistema exibe ao usuário uma tela de Erro explicando que o mesmo não se encontra dentro da área de atuação do Aplicativo.
        * Se o usuário não possuir acesso a internet.
            * Sistema exibe ao usuário uma tela de Erro explicando que o mesmo não possui acesso a internet no momento.
    2. Usuário seleciona no mapa o ponto de ônibus desejado.
    3. Sistema exibe uma tela contendo as informações a respeito das linhas e horários dos ônibus que passam no ponto selecionado.

 * Protótipos de tela:
 ![](https://user-images.githubusercontent.com/11222413/31261363-219e5c80-aa2a-11e7-946e-250062dea481.png)

| Ref. | Descrição | Categoria | Prioridade |
|----------|------------------------------------------------------------|-----------|------------|
| TR-RFUN 8 | Buscar informações de rotas de determinado ponto de ônibus | Oculta |Alta |
| TR-RFUN 9 | Exibir informações de rotas de determinado ponto de ônibus | Evidente |Alta |
| TR-RFUN 10 | Buscar informações de horários de determinado ponto de ônibus | Oculta |Alta |
| TR-RFUN 11 | Exibir informações de horários de determinado ponto de ônibus | Evidente |Alta |

**TR-CSU5**- Visualizar locais pré-definidos
 * Identificador: TR-CSU5

 * Atores envolvidos: Usuário(Fernanda), Sistema.

 * Pré-condição:
 * O banco de dados deverá estar disponível e funcional.

 * Pós-condições:
    * O aplicativo mostra os locais pré-definidos cadastrados.

 * Cenário:
 1. Usuário seleciona o botão "Meus locais".
 2. Sistema exibe uma tela contendo os locais pré-definidos cadastrados.
 * Se não houver nenhum local cadastrado:
 * O sistema exibe uma tela "vazia".

 * Protótipos de tela:
 ![](https://user-images.githubusercontent.com/11222413/31261364-21a19760-aa2a-11e7-95f5-7934386e8fbc.png)

| Ref. | Descrição | Categoria | Prioridade |
|----------|------------------------------------------------------------|-----------|------------|
| TR-RFUN 12 | Exibir lista de locais pré-definidos do usuário | Evidente |Média |

**TR-CSU6**- Criar local pré-definido
 * Identificador: TR-CSU6

 * Atores envolvidos: Usuário(Fernanda), Sistema

 * Pré-condições:
 * As mesmas definidas em TR-CSU5.

 * Pós-condições:
 * As mesmas definidas em TR-CSU5.

 * Cenário:
 1. Usuário executa TR-CSU5.
 2. Usuário seleciona o botão de adicionar novo local.
 3. Usuário seleciona um ponto no mapa, podendo selecionar sua própria posição segundo o GPS, referente ao novo local.
 4. Usuário nomeia o novo local.
 5. Usuário confirma os dados da nova localização.
 6. Sistema retorna para a tela de locais pré-definidos cadastrados.

 * Protótipos de tela:
 ![](https://user-images.githubusercontent.com/11222413/31261365-21a34e16-aa2a-11e7-9b6a-b4c7337a63bd.png)

| Ref. | Descrição | Categoria | Prioridade |
|----------|------------------------------------------------------------|-----------|------------|
| TR-RFUN 13 | Validar posição de "Meus locais" selecionada pelo usuário | Oculta |Média |
| TR-RFUN 14 | Gravar no banco a posição e nome do local | Oculta |Média

**TR-CSU7**- Modificar local pré-definido
 * Identificador: TR-CSU7

 * Atores envolvidos: Usuário(Fernanda), Sistema

 * Pré-condições:
 * As mesmas definidas em TR-CSU5.
 * Deverá existir um local pré-definido cadastrado no banco de dados.

 * Pós-condições:
 * O local selecionado deve ter sido modificado com sucesso.

 * Cenário:
 1. Usuário executa TR-CSU5.
 2. Usuário seleciona o botão de editar no local.
 3. Sistema exibe uma tela contendo um mapa com o local selecionado.
 4. Usuário seleciona um ponto no mapa (podendo selecionar sua própria posição segundo o GPS) referente á atualização do local.
 5. Usuário renomeia o local.
 6. Usuário confirma os dados da localização atualizada.
 7. Sistema atualiza o local pré-definido selecionado no banco de dados.
 8. Sistema retorna para a tela de locais pré-definidos cadastrados.

 * Protótipos de tela:
 ![](https://user-images.githubusercontent.com/11222413/31261366-21c06578-aa2a-11e7-8fdb-ae754e320f3a.png)

| Ref. | Descrição | Categoria | Prioridade |
|----------|------------------------------------------------------------|-----------|------------|
| TR-RFUN 15 | Atualizar no banco a posição e nome do local | Oculta |Média

**TR-CSU8**- Remover local pré-definido
 * Identificador: TR-CSU8

 * Atores envolvidos: Usuário(Fernanda), Sistema

 * Pré-condições:
 * As mesmas definidas em TR-CSU5.
 * Deverá existir um local pré-definido cadastrado no banco de dados.

 * Pós-condições:
 * O local selecionado deve ter sido removido da lista de meus locais.

 * Cenário:
 1. Usuário executa TR-CSU5.
 2. Usuário seleciona o botão de remover no local que deseja remover.
    3. Usuário confirma o local a ser removido.
    4. Sistema remove o local pré-definido selecionado do banco de dados.
 5. Sistema retorna para a tela de locais pré-definidos cadastrados.

 * Protótipos de tela:
 ![](https://user-images.githubusercontent.com/11222413/31261367-21c3fce2-aa2a-11e7-833c-f3250612effb.png)

| Ref. | Descrição | Categoria | Prioridade |
|----------|------------------------------------------------------------|-----------|------------|
| TR-RFUN 15 | Remover do banco a posição e nome do local | Oculta |Média

### 3.2 Oportunidades

#### 3.2.1 Diagramas de Caso de Uso e Lista de casos de uso

![](https://github.com/isaiastavares/minha-ufg/blob/master/assets/oportunidades/%5BOP%5DUseCases.png)

* **OP-CSU1**: Listar Oportunidades (Web)
* **OP-CSU2**: Filtrar Oportunidades (Web)
* **OP-CSU3**: Cadastrar Oportunidade (Web)
* **OP-CSU4**: Editar Oportunidade (Web)
* **OP-CSU5**: Excluir Oportunidade (Web)
* **OP-CSU6**: Listar Oportunidades - Usuário Deslogado (App)
* **OP-CSU7**: Listar Oportunidades - Usuário Logado (App)
* **OP-CSU8**: Filtrar Oportunidades (App)

 ![](https://github.com/isaiastavares/minha-ufg/blob/master/assets/oportunidades/OP-CSU%20-%20Tela%20inicial%20com%20todos%20os%20M%C3%B3dulos.png)

#### 3.2.2 Descrição de Casos de Uso

**OP-CSU1**- Listar Oportunidades (Web)

 * Identificador: OP-CSU1

 * Atores envolvidos: Usuário com permissão 'Oportunidade'

 * Pré-condições:
    * Usuário deve estar conectado à internet.

 * Pós-condições:
    * Não possui pós-condições.

 * Cenário principal:
    1. Usuário seleciona o menu oportunidades, Lista de Oportunidades.
    2. Exibir oportunidades cadastradas com Título, Descrição e Categoria.
    3. Exibir campo de busca.
    4. Exibir opção de cadastro de nova oportunidade.

 * Cenários secundários:
    1. Usuário filtra oportunidades exibidas através do campo de busca.
    2. Usuário adiciona nova oportunidade (OP-CSU3).

 * Protótipos de tela:

 ![](https://github.com/isaiastavares/minha-ufg/blob/master/assets/oportunidades/OP-CSU1%20-%20Listar%20Oportunidades%20(Web).png)

| Ref. | Descrição | Categoria | Prioridade |
|----------|------------------------------------------------------------|-----------|------------|
| OP-RFUN 2.1 | O menu de Oportunidades só deve ser exibido para o usuário que tiver permissão 'Oportunidades' | Oculta | Alta |
| OP-RFUN 2.2 | Listar as primeiras oportunidades em uma lista "infinita", que carrega outras oportunidades de acordo com a busca, ao "descer" na página. | Evidente | Média|
| OP-RFUN 2.3 | Exibir Título, Categoria e 100 caracteres da descrição de cada oportunidade. | Evidente | Alta |
| OP-RFUN 2.4 | Filtrar de acordo com o campo de busca do(s) curso(s) relacionado(s) de cada oportunidade (Título, Categoria e Descrição). | Evidente | Alta |
| OP-RFUN 2.5 | Chamar tela de cadastro de uma nova oportunidade. | Evidente | Alta |
| OP-RFUN 2.6 | Chamar tela de edição da oportunidade, ao clicar em alguma da lista. | Evidente | Alta |

**OP-CSU2**- Filtrar Oportunidades (Web)

 * Identificador: OP-CSU2

 * Atores envolvidos: Usuário com permissão 'Oportunidade'

 * Pré-condições:
    * Usuário deve estar conectado à internet.

 * Pós-condições:
    * O usuário abre o sistema Web.

 * Cenário principal:
    1. Usuário abre o sistema Web.
    2. Usuário clica no menu Oportunidades -> Listar Oportunidades.
    3. Usuário pode filtrar as oportunidades por título.

 * Protótipos de tela:

 ![](https://github.com/isaiastavares/minha-ufg/blob/master/assets/oportunidades/OP-CSU7.png)

**OP-CSU3**- Cadastrar Oportunidade (Web)

 * Identificador: OP-CSU3

 * Atores envolvidos: Usuário com permissão 'Oportunidade'

 * Pré-condições:
    * Usuário deve estar conectado à internet.

 * Pós-condições: 
    * Os campos Título, Descrição, Cursos, Categoria, Contratante e Contrato devem ser obrigatórios.

 * Cenário principal:
    1. Usuário acessa o sistema.
    2. Usuário clica no menu Oportunidades -> Listar Oportunidades.
    3. Usuário clica no botão com o sinal de + para cadastrar uma oportunidade.
    4. Usuário preenche as informações necessárias no formulário.
    5. Usuário clica em Salvar.

 * Cenários secundários:
    1. Usuário não possui permissão 'Oportunidade', então o menu Oportunidades não é exibido para ele.

 * Protótipos de tela:

 ![](https://github.com/isaiastavares/minha-ufg/blob/master/assets/oportunidades/OP-CSU3%20-%20Cadastrar%20Oportunidade%20(Web).png)

| Ref. | Descrição | Categoria | Prioridade |
|----------|------------------------------------------------------------|-----------|------------|
| OP-RFUN 1.1 | O menu de Oportunidades só deve ser exibido para o usuário que tiver permissão 'Oportunidades' | Oculta | Alta |

**OP-CSU4**- Editar Oportunidade (Web)

 * Identificador: OP-CSU4

 * Atores envolvidos: Usuário com permissão 'Oportunidade'

 * Pré-condições: 
    * Usuário deve estar conectado à internet.

 * Pós-condições: 
    * Os campos cadastrados inicialmente (Título, Descrição, Cursos, Categoria, Contratante e Contato) devem ser obrigatórios.

 * Cenário principal:
    1. Usuário acessa o sistema.
    2. Usuário clica no menu Oportunidades -> Listar Oportunidades.
    3. Usuário clica na oportunidade cadastrada que deseja editar.
    4. Usuário edita as informações que deseja e clica em Salvar.

 * Cenários secundários:
    1. Usuário não possui permissão 'Oportunidade', então o menu Oportunidades não é exibido para ele.

* Protótipos de tela:

 ![](https://github.com/isaiastavares/minha-ufg/blob/master/assets/oportunidades/OP-CSU4%20-%20Editar%20Oportunidade%20(Web).png)

**OP-CSU5**- Excluir Oportunidade (Web)

 * Identificador: OP-CSU5

 * Atores envolvidos: Usuário com permissão 'Oportunidade'

 * Pré-condições:
    * Usuário deve estar conectado à internet.

 * Pós-condições: 
    * Não possui pós condições.

 * Cenário principal:
    1. Usuário acessa o sistema.
    2. Usuário clica no menu Oportunidades -> Listar Oportunidades.
    3. Usuário clica na oportunidade cadastrada que deseja deletar.
    4. Usuário clica no botão excluir no final da página.
    5. Usuário confirma o desejo de excluir a oportunidade.

 * Cenários secundários:
    1. Usuário não possui permissão 'Oportunidade', então o menu Oportunidades não é exibido para ele.

* Protótipos de tela:

 ![](https://github.com/isaiastavares/minha-ufg/blob/master/assets/oportunidades/OP-CSU5%20-%20Excluir%20Oportunidade%20(Web).png)

**OP-CSU6**- Listar Oportunidades - Usuário Deslogado (App)

 * Identificador: OP-CSU6

 * Atores envolvidos: Usuários App

 * Pré-condições:
    * Usuário deve estar conectado à internet.
    * O usuário não deve estar logado no aplicativo.

 * Pós-condições:
    * O usuário abre o aplicativo.

 * Cenário principal:
    1. Usuário abre o aplicativo.
    2. Usuário clica no menu Oportunidades.
    3. Usuário visualiza as oportunidades cadastradas.

 * Cenários secundários:
     1. Usuário utiliza o filtro para visualizar as oportunidades de seu interesse.

 * Protótipos de tela:

 ![](https://github.com/isaiastavares/minha-ufg/blob/master/assets/oportunidades/Oportunidades.png)

| Ref. | Descrição | Categoria | Prioridade |
|----------|------------------------------------------------------------|-----------|------------|
| OP-RFUN 3.1 | Listar todas oportunidades por ordem decrescente de data de inserção e sem filtro. | Evidente | Alta |
| OP-RFUN 3.2 | Ir para tela detalhada da oportunidade ao clicar em uma oportunidade. | Evidente | Alta |

**OP-CSU7**- Listar Oportunidades - Usuário Logado (App)

 * Identificador: OP-CSU7

 * Atores envolvidos: Usuários App

 * Pré-condições:
    * Usuário deve estar conectado à internet.
    * Usuário deve estar logado no app

 * Pós-condições:
    * O usuário abre o aplicativo.

 * Cenário principal:
    1. Usuário abre o aplicativo.
    2. Usuário clica no menu Oportunidades.
    3. Usuário visualiza as oportunidades cadastradas de acordo com seu perfil.

 * Cenários secundários:
    1. Usuário utiliza o filtro para visualizar outras oportunidades.

 * Protótipos de tela:

 ![](https://github.com/isaiastavares/minha-ufg/blob/master/assets/oportunidades/Oportunidades_2.png)

| Ref. | Descrição | Categoria | Prioridade |
|----------|------------------------------------------------------------|-----------|------------|
| OP-RFUN 4.1 | Listar oportunidades por ordem decrescente de data de inserção de acordo com perfil do usuário. | Evidente | Alta |
| OP-RFUN 4.2 | Ir para tela detalhada da oportunidade ao clicar em uma oportunidade. | Evidente | Alta |

**OP-CSU8**- Filtrar Oportunidades (App)

 * Identificador: OP-CSU8

 * Atores envolvidos: Usuários App

 * Pré-condições: 
    * Usuário deve estar conectado à internet.

 * Pós-condições: 
    * O usuário abre o aplicativo.

 * Cenário principal:
    1. Usuário abre o aplicativo.
    2. Usuário clica no menu Oportunidades.
    3. Usuário pode filtrar as oportunidades por curso.

 * Protótipos de tela:

 ![](https://github.com/isaiastavares/minha-ufg/blob/master/assets/oportunidades/OP-CSU8.png)

### 3.3 Calendário

#### 3.3.1 Diagramas de Caso de Uso e Lista de casos de uso

<img src="https://raw.githubusercontent.com/isaiastavares/minha-ufg/Calendar/assets/calendario/%5BCA%5DUseCases%20UPDATE.png"/>


* CA-CSU1: Visualizar Regionais 
* CA-CSU2: Criar Eventos
* CA-CSU3: Editar Eventos
* CA-CSU4: Ver Notificação
* CA-CSU5: Pesquisar Eventos 


#### 3.3.2 Descrição de Casos de Uso


**CA-CSU1**- Visualizar Regionais
 * Identificador: CA-CSU1

 * Atores envolvidos: Consulentes.

 * Pré-condições: Os consulentes devem visualizar os calendário de acordo com a regional de escolha. Cada consulente tem sua regional favorita, mas também pode mudar para qualquer outra.

 * Pós-condições: O consulente escolhe sua regional e realiza qualquer busca desejada no calendário acadêmico.

 * Cenário principal:
1. Consulente acessa o aplicativo Minha UFG;
2. Consulente seleciona a opção Calendário;
3. Consulente entra no Calendário e escolhe sua regional de interesse.
4. Consulente seleciona a data que deseja consultar.

 * Cenários secundários:
1. O consulente pode acessar as funções do calendário offline.

  * Protótipos de tela: 
  
  <img src="https://raw.githubusercontent.com/isaiastavares/minha-ufg/Calendar/assets/calendario/%5BCA%5DCSU1-UPDATE-1.1-Escolher%20Regionais%201.png" width="550" height="500"/>
  
  <img src="https://raw.githubusercontent.com/isaiastavares/minha-ufg/Calendar/assets/calendario/%5BCA%5DCSU1-UPDATE-1.2-Escolher%20Regionais%202.png" width="550" height="500"/>

 
| Ref. | Descrição | Categoria | Prioridade |
|-------|----------------------------------------------------------|---------------|---------------|
| CA-RFUN 1.1 | O Calendário deve ser dividida em 4 Regionais: Goiânia, Jataí, Catalão e Cidade de Goiás. | Evidente |Alta |
| CA-RFUN 1.2 | Cada regional possui sua própria resolução e datas, já que cada regional segue um calendário diferente por conta de greves e suas particularidades.| Evidente |Alta |

**CA-CSU2**- Criar Eventos
 * Identificador: CA-CSU2

  * Atores envolvidos: Administrador.
  
  * Pré-condições: O Administrador deve conseguir criar um novo Evento para ser inserido no calendário acadêmico. O administrador deve acessar a parte web do Minha UFG e realizar o login. Depois que acessa a opção de Criar Evento, deve ter a possibilidade de inserir os dados pedidos e depois criar o novo evento.
 Além disso, o administrador tem a possibilidade de ver a Lista de Eventos selecionando o calendário desejado.

 * Pré-condições: O Administrador deve conseguir criar um novo Evento para ser inserido no calendário acadêmico. O administrador deve acessar a parte web do Minha UFG e realizar o login. Depois que acessa a opção de Criar Evento, deve ter a possibilidade de inserir os dados pedidos e depois criar o novo evento.

 * Pós-condições: Se você não estiver conectado à internet, não consegue acessar a parte do Administrador do Minha UFG.

 * Cenário principal:
1. O Administrador acessa a parte web com seu login e senha.
2. O Administrador seleciona a opção Calendário.
3. O Administrador seleciona a opção Eventos.
4. O Administrador seleciona a opção de Criar um novo evento.
   * a. O Administrador deve selecionar alguma Regional, onde o evento vai ser cadastrado;
   * b. O Administrador deve inserir o nome do evento;
   * c. O Administrador deve inserir o local onde será realizado;
   * d. O Administrador deve selecionar o período que vai ser o evento;
   * e. O Administrador tem a possibilidade de inserir observações sobre o evento;
   * f. O Administrador pode cancelar o cadastro e começar do zero inserindo novos dados, apertando o botão cancelar;
   * g. O Administrador, após inserir todos os dados, deve clicar em Salvar para salvar os dados e, consequentemente, criar um novo evento;
   * h. Se o Administrador não preencheu ou deixou algum campo obrigatório sem preencher, o cadastro não vai ser possível até que todos estejam preenchidos.
5. Após criar um novo evento, o Administrador volta para a página anterior com um retorno de que o cadastro de um novo evento.

 * Cenários secundários:
1. Após criar um novo evento, o Administrador volta para a página anterior com um retorno de que o cadastro de um novo evento realizado com sucesso.
2. Após criar um novo evento, o Administrador volta para a página anterior, mas por algum motivo (banco de dados, código...), ocorreu um erro e o evento não foi cadastrado. Dessa forma, vai retornar uma mensagem de que ocorreu um erro ao criar novo evento. Contate o suporte técnico ou tenta criar um novo evento.

  * Protótipos de tela: Criando um Novo Evento
  
  <img src="https://raw.githubusercontent.com/isaiastavares/minha-ufg/Calendar/assets/calendario/%5BCA%5DCSU2-UPDATE-2.1-Tela%20inical.png" />
  
  <img src="https://raw.githubusercontent.com/isaiastavares/minha-ufg/Calendar/assets/calendario/%5BCA%5DCSU2-UPDATE-2.2-Lista%20de%20Calend%C3%A1rios.png" />
  
  <img src="https://raw.githubusercontent.com/isaiastavares/minha-ufg/Calendar/assets/calendario/%5BCA%5DCSU2-UPDATE-2.3-Todos%20os%20Eventos.png" />
  
  <img src="https://raw.githubusercontent.com/isaiastavares/minha-ufg/Calendar/assets/calendario/%5BCA%5DCSU2-UPDATE-2.4-Informa%C3%A7%C3%B5es.png" />
  
  <img src="https://raw.githubusercontent.com/isaiastavares/minha-ufg/Calendar/assets/calendario/%5BCA%5DCSU2-UPDATE-2.5-Criar%20Evento.png" />
  
  <img src="https://raw.githubusercontent.com/isaiastavares/minha-ufg/Calendar/assets/calendario/%5BCA%5DCSU2-UPDATE-2.6-Preencher%20todos%20os%20campos%20do%20Evento.png" />
  
  <img src="https://raw.githubusercontent.com/isaiastavares/minha-ufg/Calendar/assets/calendario/%5BCA%5DCSU2-UPDATE-2.7-Evento%20salvo%20com%20sucesso.png" />
  
  <img src="https://raw.githubusercontent.com/isaiastavares/minha-ufg/Calendar/assets/calendario/%5BCA%5DCSU2-UPDATE-2.8-Erro%20ao%20Salvar%20evento.png" />
    
 
| Ref.     |                          Descrição                         | Categoria | Prioridade |
|-------|----------------------------------------------------------|---------------|---------------|
| CA-RFUN 2.1 | Criar um novo evento no Calendário Acadêmico. | Evidente |Alta |
| CA-RFUN 2.2 | Devem existir os seguintes campos: Selecionar regional do evento; Nome do evento; Local do evento; Data do evento; Observações gerais. Além disso, deter ter dois botões, um para Limpar todo o cadastro e outro para Criar Evento.| Evidente |Alta |
| CA-RNFUN 2.3 | Administrador deve conseguir acessar o sistema web. | Evidente |Alta |
| CA-RNFUN 2.4 | Administrador deve conseguir inserir todos os dados para realizar o cadastro. Obs: Somente o campo Observações gerais não é obrigatório o preenchimento.| Evidente |Alta |

**CA-CSU3**- Editar Eventos
 * Identificador: CA-CSU3

 * Atores envolvidos: Administrador.

 * Pré-condições: O Administrador deve conseguir editar um Evento para ser atualizado no calendário acadêmico. O administrador deve acessar o sistema web do Minha UFG e realizar o login. Depois acessar a opção de Editar Evento, deve escolher o evento para ter a possibilidade de alterar os dados e depois salvar as alterações do evento.

 * Pós-condições: O Administrador consegue alterar o evento desejado.

 * Cenário principal:
1. O Administrador acessa a parte web com seu login e senha.
2. O Administrador seleciona a opção Calendário.
3. O Administrador seleciona a opção Eventos.
4. O Administrador lista o dia que vai ser alterado e entra dentro da edição.
   * a. O Administrador pode selecionar outra Regional, onde o evento vai acontecer;
   * b. O Administrador pode alterar o nome do evento;
   * c. O Administrador pode alterar o local do onde será realizado;
   * d. O Administrador pode alterar o período que vai ser o evento;
   * e. O Administrador tem a possibilidade de alterar as observações sobre o evento;
   * f. O Administrador pode cancelar as alterações, apertando o botão Cancelar, voltando para a página anterior;
   * g. O Administrador, após alterar todos os dados, deve clicar em Salvar  para salvar os dados e, consequentemente, editar o evento que foi selecionado;
   * h. Se o Administrador não preencher ou deixar algum campo obrigatório sem preencher, a alteração não vai ser possível até que todos os campos estejam preenchidos.
6. Após editar um evento, o Administrador volta para a página anterior com um retorno de que as alterações sobre o evento foram salvas com sucesso.
7. O Administrador tem a possibilidade de excluir o evento na página onde está editando. Abaixo tem um botão chamado EXCLUIR, onde pode eliminar aquele evento.

  * Cenários secundários: 
1. O Administrador seleciona o botão de Pesquisar para localizar o evento que deseja alterar:
    * O Administrador seleciona o filtro de pesquisa de evento. Exemplo: Pesquisar por Regional;
2. Após Salvar Alterções do evento, o sistema notifica que o Administrador esqueceu de preencher e/ou selecionar algum campo obrigatório. Solicitando para verificar os dados e depois clicar novamente em Salvar Alterações.
3. Após editar um evento, o Administrador volta para a página anterior, mas por algum motivo (banco de dados, código…), ocorreu um erro e o evento não foi cadastrado. Dessa forma, vai retornar uma mensagem de que ocorreu um erro ao editar evento. Contate o suporte técnico ou tenta editar outro evento.

 * Protótipos de tela: Protótipos de tela (interface homem-computador) relacionados ao caso de uso.

<img src="https://raw.githubusercontent.com/isaiastavares/minha-ufg/Calendar/assets/calendario/%5BCA%5DCSU3-UPDATE-3.1-Editar%20Evento.png" />

<img src="https://raw.githubusercontent.com/isaiastavares/minha-ufg/Calendar/assets/calendario/%5BCA%5DCSU3-UPDATE-3.2-Selecionar%20Evento%20para%20Editar.png" />

<img src="https://raw.githubusercontent.com/isaiastavares/minha-ufg/Calendar/assets/calendario/%5BCA%5DCSU3-UPDATE-3.3-Editar_Excluir%20Evento.png" />

<img src="https://raw.githubusercontent.com/isaiastavares/minha-ufg/Calendar/assets/calendario/%5BCA%5DCSU3-UPDATE-3.4-Evento%20alterado%20com%20sucesso.png" />

<img src="https://raw.githubusercontent.com/isaiastavares/minha-ufg/Calendar/assets/calendario/%5BCA%5DCSU3-UPDATE-3.5-Evento%20Exclu%C3%ADdo%20com%20sucesso.png" />

<img src="https://raw.githubusercontent.com/isaiastavares/minha-ufg/Calendar/assets/calendario/%5BCA%5DCSU3-UPDATE-3.6-Erro%20ao%20Editar%20evento.png" />

 
| Ref.     |                          Descrição                       	| Categoria | Prioridade |
|-------|----------------------------------------------------------|---------------|---------------|
| CA-RFUN 3.1 | Editar um evento no Calendário Acadêmico. | Evidente |Alta |
| CA-RFUN 3.2 | Devem existir os seguintes campos: Selecionar regional do evento; Nome do evento; Local do evento; Data do evento; Observações gerais. Além disso, deter ter dois botões, um para Candelar as alterações e outro para Salvar Alterações.| Evidente |Alta |
| CA-RNFUN 3.3 | Administrador deve conseguir acessar o sistema web. | Evidente |Alta |
| CA-RNFUN 3.4 | Administrador deve conseguir inserir todos os dados para realizar o cadastro. Obs: Somente o campo Observações gerais não é obrigatório o preenchimento.| Evidente |Alta |

**CA-CSU4**- Notificar Eventos
 * Identificador: CA-CSU4.

 * Atores envolvidos: Consulente.

 * Pré-condições: Os consulentes devem estar inscritos para receberem as notificações.

 * Pós-condições: Essas notificações disparadas não serão mais enviadas aos consulentes.

 * Cenário principal:
 1. É cadastrado um evento exceptional, não previsto no calendário acadêmico, para uma regional ou para toda a UFG.
 2. O sistema empacota essa informação e envia para todos os inscritos nessas regionais.
 3. Ao chegar a notificação no dispositivo a mesma fica visível na caixa de notificações do dispositivo.
 4. Ao selecionar a notificação, o aplicativo é invocado e a tela de descrição do evento é exibida ao consulente.

 * Cenários secundários:
 1. Duas ou mais notificações foram recebidas pelo consulente e não foram visualizadas
 2. Ao selecionar a notificação é exibida a lista de notificações pendentes recebidas, o consulente seleciona a que deseja abrir.
 * Protótipos de tela:

 ![](https://raw.githubusercontent.com/isaiastavares/minha-ufg/Calendar/assets/calendario/%5BCA%5DCSU04%20.1-%20Notificar%20Eventos.png)

 ![](https://raw.githubusercontent.com/isaiastavares/minha-ufg/Calendar/assets/calendario/%5BCA%5DCSU04.2%20-%20Notificar%20Eventos.png)

| Ref. | Descrição | Categoria | Prioridade |
|-------|----------------------------------------------------------|---------------|---------------|
| CA-RFUN 4.1 | A postagem são eventos extraordinários em que o calendário acadêmico não estava prevendo. | Evidente |Alta |

  
**CA-CSU5**- Pesquisar eventos

   * Identificador:CA-CSU5

   * Atores envolvidos: Consulente

   * Pré-condições: 
       * O usuário está no contexto de Eventos do calendário. 
       * O usuário clica no botão de pesquisa de eventos
     
   * Pós-condições:
       * O Sistema apresenta os eventos
       * O usuário seleciona o evento que estava procurando

   * Fluxo principal:
       * Usuário clica no botão pesquisar       
       * Usuário digita o texto da pesquisa no campo de texto
       * A pesquisa é executada assim que o usuário parar de digitar
       * O Resultado da pesquisa é apresentado

   * Fluxo alternativo
       * Usuário clica em uma data em destaque do calendário
       * Os eventos da data selecionada são apresentados ao usuário
   
   * Fluxo alternativo 
       * Usuário clica no botão de pesquisar
       * O usuário digita o texto da pesquisa no campo de texto
       * A pesquisa é executada assim que o usuário parar de digitar
       * Nenhum resultado é encontrado
       * Uma mensagem é mostrada para o usuário dizendo que não há nenhum resultado com o termo da pesquisa
  
   * Protótipos de tela

  <img src="https://github.com/isaiastavares/minha-ufg/blob/Calendar/assets/calendario/%5BCA%5DCSU06%20-%20Pesquisa%20de%20eventos%20do%20canled%C3%A1rio%20-%20Tela%20de%20visualizar%20eventos%20do%20calend%C3%A1rio.png">
  <img src="https://github.com/isaiastavares/minha-ufg/blob/Calendar/assets/calendario/%5BCA%5DCSU06%20-%20Pesquisa%20de%20eventos%20do%20canled%C3%A1rio%20-%20Tela%20de%20pesquisar%20eventos%20do%20calend%C3%A1rio.png">
  <img src="https://github.com/isaiastavares/minha-ufg/blob/Calendar/assets/calendario/%5BCA%5DCSU06%20-%20Pesquisa%20de%20eventos%20do%20canled%C3%A1rio%20-%20Tela%20de%20Eventos%20n%C3%A3o%20encontrados.png">
   
       
## 4. Requisitos e restrições não funcionais
-----------------------------------------

### 4.1 Requisitos e Restrições de Usabilidade (RUS)

| Ref. 	|              Descrição                                               	| Caso de Uso     	|
|------	|-------------------------------------------------------------------	|-----------------	|
| RINF1 | O usuário deve estar localizado dentro da região metropolitana de goiânia  | Todos de transporte  |
| RINF2 | Obrigatóriamente um dos pontos de origem / destino deverá ser a UFG  | TR-CSU1  |
| RINF3 | Campo de pesquisa aparece no lugar da regional                       | CA-CSU5  |
| RINF4 | Calendário some enquanto o usuário está com campo de pesquisa aberto | CA-CSU5  |
| RINF5 | Pesquisa é executada quando detectado que o usuário parou de digitar, após 0.8 segundos | CA-CSU5  |



### 4.2	Requisitos e Restrições de Interface Homem Computador (RHIC)

| Ref. | Descrição | Caso de Uso |
|------- |---------------------------------------------------------- |---------------|
| RIHC1 | Deve ser utilizado "Google Material Design" para a interface. | Todos |
| RIHC2 | A área do mapa deverá ser restringida apenas para a região metropolitana de goiânia. | Todos de Transporte |

### 4.3 Requisitos e Restrições de Interface Externa (RIEX)

| Ref. | Descrição | Caso de Uso |
|------- |---------------------------------------------------------- |---------------|
| RIEX1 | O software realizará interação com o sistema Firebase. | TR-CSU1, TR-CSU6, TR-CSU7, TR-CSU8 |
| RIEX2 | O software realizará interação com o sistema Google Maps. | TR-CSU1, TR-CSU2, TR-CSU3, TR-CSU4, TR-CSU6, TR-CSU7 |

### 4.4 Requisitos e Restrições de Plataforma de Hardware (RPHW)

| Ref. | Descrição | Caso de Uso |
|------- |---------------------------------------------------------- |---------------|
| RPHW1 | Hardware de GPS integrado | Todos do Transporte |
| RPHW2 | Hardware para acesso á internet | Todos |
| RPHW3 | Processador mínimo de 2 GHz | Todos |

### 4.5 Requisitos e Restrições de Plataforma de Software (RPSW)

| Ref. | Descrição | Caso de Uso |
|------- |---------------------------------------------------------- |---------------|
| RPSW1 | Android versão 4.1 ou superior | Todos |
| RPSW2 | Deverá possuir uma aplicação externa de mapas | Todos do Transporte |
| RPSW3 | Uso do Firebase como serviço | Todos |

### 4.6 Requisitos e Restrições de Desempenho (RDES)

| Ref. | Descrição | Caso de Uso |
|------- |---------------------------------------------------------- |---------------|
| RDES1 | O aplicativo não pode travar/encerrar o processo com frequência. | Todos |

### 4.7 Requisitos e restrições de disponibilidade (RDIS).

| Ref. | Descrição | Caso de Uso |
|------- |---------------------------------------------------------- |---------------|
| RDIS1 | O aplicativo deve inicializar por completo em até 3 segundos. | Todos |
| RDIS2 | O aplicativo deve estar disponível e funcional 24/7. | Todos |

### 4.8 Requisitos e Restrições de Segurança (RSEG)

| Ref. | Descrição | Caso de Uso |
|------- |------------------------------------------ |------------- |
| RSEG1 | O aplicativo não deverá compartilhar a posição do usuário. | Todos de transporte |
| RSEG2 | O aplicativo deverá informar ao usuário que utilizará de sua localização. | Todos de transporte |
| RSEG3 | O aplicativo deverá informar ao usuário que utilizará dados de internet. | Todos |

### 4.9 Requisitos e Restrições de Manutenibilidade (RMAN)

| Ref. | Descrição | Caso de Uso |
|------- |---------------------------------------------------------- |---------------|
| RMAN1 | Será utilizado a ferramenta Javadoc para padronizar e facilitar o entendimento do código-fonte | Todos |
| RMAN2 | Todos os commits serão ser em inglês | Todos |

### 4.10 Requisitos e Restrições de Documentação (RDOC)

| Ref. | Descrição | Caso de Uso |
|------- |---------------------------------------------------------- |---------------|
| RDOC1 | Devem ser lançadas as notas de release a cada nova baseline. | Não se aplica |

## 5. Requisitos Futuros (RFUT)
---------------------------------

No momento não há requisitos futuros.

## 6. Referências cruzadas complementares
---------------------------------------------

### 6.1 Transporte

|Requisitos Funcionais | Requisitos Funcionais|
|---------------------|--------------------------|
|TR-CSU1|TR-CSU1, TR-CSU2, TR-CSU3|
|TR-CSU2|TR-CSU1, TR-CSU2, TR-CSU3|
|TR-CSU3|TR-CSU1, TR-CSU2, TR-CSU3|
|TR-CSU4|TR-CSU4|
|TR-CSU5|TR-CSU5, TR-CSU6, TR-CSU7, TR-CSU8|
|TR-CSU6|TR-CSU5, TR-CSU6, TR-CSU7, TR-CSU8|
|TR-CSU7|TR-CSU5, TR-CSU6, TR-CSU7, TR-CSU8|
|TR-CSU8|TR-CSU5, TR-CSU6, TR-CSU7, TR-CSU8|

## 7. Modelo de domínio

### 7.1 Modelo de domínio Transporte

<img src="https://github.com/isaiastavares/minha-ufg/blob/Transporte/assets/Transporte/Modelo-de-dominio-TR.png" width="700" height="350"/>

### 7.2 Modelo de domínio Oportunidades

![](https://github.com/isaiastavares/minha-ufg/blob/master/assets/oportunidades/%5BOP%5DOpportunities-ERD.png)

### 7.2 Modelo de domínio Calendário

<img src="https://github.com/isaiastavares/minha-ufg/blob/Calendar/assets/calendario/%5BMCD%5DModelo%20de%20classe%20de%20dom%C3%ADnio%20-%20Minha%20UFG.png"/>


## 8. Aprovação Formal
---------------------------------------------

Por meio deste documento, confirmo que os requisitos aqui presentes abordam todas as áreas do sistema a ser desenvolvido e de requisitos futuros (sejam elas melhorias ou novas funcionalidades), de forma a desenvolver um software com qualidade e segurança. Confirmo também que este documento aborda todos os requisitos e funcionalidades de forma correta e clara ao que foi solicitado e ao que foi dito e pedido nas entrevistas, etnografias e questionários. Confirmo também que não há requisitos extras neste documento, todos os requisitos aqui citados foram requeridos e atendem à alguma funcionalidade necessária.
    