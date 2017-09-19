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

* TR-CSU1: Selecionar local de destino em uma lista;
* TR-CSU2: Visualizar Rota;
* TR-CSU3: Ver linhas e horários dos pontos dos campus;
* TR-CSU4: Visualizar pontos mais próximos da origem/destino;


#### 3.1.2 Descrição de Casos de Uso

**TR-CSU1**- Selecionar local de origem/destino em uma lista
  * Identificador: TR-CSU1

  * Atores envolvidos: Usuário

  * Pré-condições: Usuário deve estar conectado à internet. Habilitar o GPS (opcional)

  * Pós-condições: O aplicativo seleciona corretamente os pontos de origem e destino do usuário, mostrando uma lista dos pontos disponíveis no campus da UFG para auxiliar o usuário.

  * Cenário principal:
      * Usuário abre o aplicativo.
      * Usuário seleciona aba de transportes.
      * Usuário define o ponto de origem, caso seja na UFG, mostrar lista dos pontos disponíveis mais próximos da posição     atual do usuário.
      * Usuário define o ponto de destino, caso seja na UFG, mostrar lista dos pontos disponíveis no campus.

  * Cenários secundários:
      * Usuário não possui internet e o sistema mostra que não é possível realizar a busca.
      * Usuário não está na grande Goiânia e o sistema mostra que o usuário está fora da área de alcance.


  * Protótipos de tela: Protótipos de tela (interface homem-computador) relacionados ao caso de uso.

| Ref.     |                          Descrição                       	| Categoria | Prioridade |
|----------|------------------------------------------------------------|-----------|------------|
| TR-RFUN 1.1 | Mostrar lista de pontos disponíveis no campus Samambaia e Universitário | Evidente |Alta |
| TR-RFUN 1.2 | Mostrar pontos mais próximos do local atual do usuário (caso GPS esteja ativado) | Evidente |Média |
| TR-RFUN 1.3 |  Definir automaticamente um dos locais (origem ou destino) sendo somente pontos disponíveis nos câmpus da UFG | Evidente |Alta |

**TR-CSU2**- Visualizar Rota
  * Identificador: TR-CSU2

  * Atores envolvidos: Usuário

  * Pré-condições: Usuário deve ter selecionado o destino da lista bem como confirmado sua posição de origem.

  * Pós-condições: O aplicativo sugere rotas para o usuário seguir e chegar ao destino.

  * Cenário principal:
      * Usuário confirma local de partida.
      * Usuário seleciona local de destino.
      * Aplicativo sugere rotas a serem seguidas pelo usuário.

  * Cenários secundários:
      * Usuário não possui internet e o sistema mostra que não é possível realizar a busca.
      * Usuário não está na grande Goiânia e o sistema mostra que o usuário está fora da área de alcance.


  * Protótipos de tela: Protótipos de tela (interface homem-computador) relacionados ao caso de uso.

| Ref.     |                          Descrição                       	| Categoria | Prioridade |
|----------|------------------------------------------------------------|-----------|------------|
| TR-RFUN 2.1 | Validar posição de GPS do usuário | Oculta |Média |
| TR-RFUN 2.2 | Validar local de destino | Oculta |Média |
| TR-RFUN 2.3 |  Buscar rota de acordo com ponto de origem e destino | Oculta |Alta |
| TR-RFUN 2.4 |  Mostrar uma ou mais rotas possíveis | Evidente |Alta |

**TR-CSU3**- Visualizar Linhas e Horários
  * Identificador: TR-CSU3

  * Atores envolvidos: Usuário, Sistema.

  * Pré-condições: Usuário deve ter selecionado o ponto de ônibus em questão.

  * Pós-condições: O sistema retorna uma lista contendo as linhas de ônibus bem como os horários referentes ao ponto selecionado.

  * Cenário principal:
      * Usuário abre o aplicativo.
      * Usuário seleciona aba de transportes.
      * Usuário seleciona o número do ponto desejado.
      * Sistema lista as rotas e os horários referentes ao ponto definido pelo usuário.

  * Cenários secundários:
      * Usuário não possui internet e o sistema mostra que não é possível realizar a busca.

  * Protótipos de tela: Protótipos de tela (interface homem-computador) relacionados ao caso de uso.

| Ref.     |                          Descrição                       	| Categoria | Prioridade |
|----------|------------------------------------------------------------|-----------|------------|
| TR-RFUN 3.1 | Buscar informações de rotas de determinado ponto de ônibus | Oculta |Alta |
| TR-RFUN 3.2 | Exibir informações de rotas de determinado ponto de ônibus | Evidente |Alta |
| TR-RFUN 3.3 | Buscar informações de horários de determinado ponto de ônibus | Oculta |Alta |
| TR-RFUN 3.4 | Exibir informações de horários de determinado ponto de ônibus | Evidente |Alta |

**TR-CSU4**- Visualizar ponto mais próximo da origem
  * Identificador: TR-CSU4

  * Atores envolvidos: Usuário, Sistema.

  * Pré-condições: Usuário deve ter selecionado a origem.

  * Pós-condições: O sistema retorna a localização do ponto de ônibus mais próximo.

  * Cenário principal:
      * Usuário abre o aplicativo.
      * Usuário seleciona a origem.
      * Sistema verifica pontos ao redor.
      * Usuário visualiza o ponto de ônibus mais próximo.

  * Cenários secundários:
      * Usuário não possui internet e o sistema mostra que não é possível realizar a busca.
      * Usuário não seta a origem ou destino como locais válidos.

  * Protótipos de tela: Protótipos de tela (interface homem-computador) relacionados ao caso de uso.

| Ref.     |                          Descrição                       	| Categoria | Prioridade |
|----------|------------------------------------------------------------|-----------|------------|
| TR-RFUN 4.1 | Validar ponto de origem selecionado | Oculta |Alta |
| TR-RFUN 4.2 | Verificar distância de pontos a partir do selecionado | Oculta |Alta |
| TR-RFUN 4.3 | Mostrar localização do ponto mais próximo | Evidente |Alta |

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

* CA-CSU1: Escolher Regionais - Consulente(Usuário app)
* CA-CSU2: Criar Eventos - Administrador(WEB)
* CA-CSU3: Editar Eventos - Administrador(WEB)
* CA-CSU4: Ver Notificação - Consulente(Usuário app) *Prototipo
* CA-CSU5: Excluir Eventos - Administrador(WEB)
* CA-CSU6: Pesquisar Eventos - Consulente(Usuário app) - Listar Campos de Pesquisa
* CA-CSU7: Filtrar Eventos - Administrador(WEB)
* CA-CSU8: 

**CA-CSU1**- Visualizar Regionais
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

**CA-CSU5**- Postar Eventos
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
  
**CA-CSU6**- Notificar Eventos
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

**CA-CSU7**- Inserir Informação no Calendário
  * Identificador: CA-CSU7

  * Atores envolvidos: Administrador.
  
  * Pré-condições: 
  1. O usuário (Administrador) está no contexto de configuração do calendário
  2. O sistema exibe uma tela com as opções de configurações  
  3. O usuário (Administrador) seleciona a opção “Inserir Informação” 
  4. O sistema exibe uma tela com um formulário para inserção 
  5. O usuário (Administrador) seleciona a data (dia/mês/ano) desejada para inserir a informação 
  6. O usuário (Administrador) seleciona a regional para que adicione a informação
  7. O usuário (Administrador) descreve a informação a ser inserida (opção de inserir imagem)

  * Pós-condições: O Sistema apresenta os resultados.

  * Cenário principal: 
  1. O sistema exibe uma mensagem “Informação adicionada com sucesso”
  2. O usuário acessa a informação com a data e regional selecionada
  3. O sistema exibe as informações inseridas por um administrador

  * Cenários secundários: 
  1. Não exibe botão para configuração 
  1.1 O usuário tenta acessar botão de configuração
  1.2 O sistema sempre verifica privilégios de categoria por usuário
  1.3 Cada categoria de usuário possui tipos de privilégios distintos
  2. Ação de inserção não permitida
  2.1 O usuário (administrador) tenta inserir informação no calendário
  2.2 O sistema bloqueia ação:
  2.2.1 O sistema exibe uma mensagem, “Informações inseridas incorretas” (data e/ou regional)
  2.2.2 O sistema exibe uma mensagem, “Campos não foram preenchidos” (data e/ou regional e/ou informações)
  2.2.3 O sistema exibe uma mensagem “Não existe essa regional”
  2.2.4 O sistema exibe uma mensagem “Temporariamente fora do ar”

  * Protótipos de tela: Protótipos de tela (interface homem-computador) relacionados ao caso de uso.


| Ref.     |                          Descrição                       	| Categoria | Prioridade |
|-------|----------------------------------------------------------|---------------|---------------|
| CA-RFUN 7.1 | Somente quem tem o perfil de administrador pode inserir ou retirar informações do calendário. | Evidente |Alta  |

**CA-CSU8**- Excluir Informação no Calendário
  * Identificador: CA-CSU8
  
  * Atores envolvidos: Administrador.
  
  * Pré-condições: 
  1. O usuário (Administrador) está no contexto de configuração do calendário
  2. O sistema exibe uma tela com as opções de configurações  
  3. O usuário (Administrador) seleciona a opção “Excluir Informação”
  4. O sistema exibe uma tela com um campo de pesquisa (data, regional e informação)
  5. O usuário (Administrador) faz a pesquisa (de acordo com os campos fornecidos) de onde está a informação que deseja excluir

  * Pós-condições: O Sistema apresenta os resultados.

  * Cenário principal: 
  1. O sistema exibe uma mensagem “Informação excluída com sucesso”
  2. O usuário acessa a informação com a data e regional selecionada
  3. O sistema não exibe mais as informações 

  * Cenários secundários: 
  1. Não exibe botão para configuração 
    1.1 O usuário tenta acessar botão de configuração
    1.2 O sistema sempre verifica privilégios de categoria por usuário
    1.3 Cada categoria de usuário possui tipos de privilégios distintos
  2. Ação de exclusão não permitida
    2.1 O usuário (administrador) tenta excluir informação no calendário
    2.2 O sistema bloqueia ação:
    2.3 O sistema exibe uma mensagem “Temporariamente fora do ar”

  * Protótipos de tela: Protótipos de tela (interface homem-computador) relacionados ao caso de uso.


| Ref.     |                          Descrição                       	| Categoria | Prioridade |
|-------|----------------------------------------------------------|---------------|---------------|
| CA-RFUN 8.1 | Somente quem tem o perfil de administrador pode inserir ou retirar informações do calendário. | Evidente |Alta  |

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
