# 1.0.10 - 15-Mai-2020

## Novas funcionalidades
- Não há

## Correções
 - #257 Erro ao fechar caixa

## Melhorias
 - Ajustando label do relatório

## Incompatibilidades (Breaking Changes)
- Não há


# 1.0.9 - 07-Mai-2020

## Novas funcionalidades
- #252 Criando funções SQL para recuperar a semana


## Correções
- Não há

## Melhorias
- Não há

## Incompatibilidades (Breaking Changes)
- Não há


# 1.0.8 - 05-Mai-2020

## Novas funcionalidades
- #251 Não permitir Cadastrar Nenhuma Ocorrência com o Campo Observação em Branco. (caso configurado)
- #250 Preenchendo campo observação com os campos dinâmicos do documento

## Correções
- #249 Ajustando filtros de função

## Melhorias
- Removendo classe "text-small" para não ficar tão pequeno no PDF

## Incompatibilidades (Breaking Changes)
- Não há


Versões 1.0.6, 1.0.7 foram apenas configurações do novo serviço de PDF (DinkToPDF)

# 1.0.5 - 24-Abr-2020

## Novas funcionalidades
- Nova opção para gerar pdf (DinkToPDF) (configuração interna)
- Removendo link do UserReport
- Salvando ultimo filtro pesquisado em membros/ministros

## Correções
- Corrigindo criação de credencial pela operação


## Melhorias
- Não há

## Incompatibilidades (Breaking Changes)
- Não há

# 1.0.4 - 19-Abr-2020

## Novas funcionalidades
- Nova opção para gerar pdf (DinkToPDF) (configuração interna)
- Removendo link do UserReport
- Salvando ultimo filtro pesquisado em membros/ministros

## Correções
- Corrigindo criação de credencial pela operação


## Melhorias
- Não há

## Incompatibilidades (Breaking Changes)
- Serviço operacional

# 1.0.3 - 19-Abr-2020

## Novas funcionalidades
- Não há

## Correções
- Corrigindo combo de Cidade/Estado


## Melhorias
- Mudando o datacenter e voltando para windows (sem docker)

## Incompatibilidades (Breaking Changes)
- Não há

# 0.9.4 - 16-Abr-2020

## Novas funcionalidades
- Não há

## Correções
- commit 61a002c0: Corrigindo font-awsome
- commit 59231ecc: Corrigindo erro da combo

## Melhorias
- commit 471701fc: Editor de código para html e SQL

## Incompatibilidades (Breaking Changes)
- Não há

# 0.9.3 - 11-Abr-2020

## Novas funcionalidades
- Não há

## Correções
- Não há

## Melhorias
- Atualizando imagem docker

## Incompatibilidades (Breaking Changes)
- Não há

# 0.9.2 - 11-Abr-2020

## Novas funcionalidades
- Não há

## Correções
- Não há

## Melhorias
- Atualizando imagem docker

## Incompatibilidades (Breaking Changes)
- Não há

# 0.9.1 - 10-Abr-2020

## Novas funcionalidades
- Não há

## Correções
- Não há

## Melhorias
- Atualizando o angular para versão 9.1

## Incompatibilidades (Breaking Changes)
- Não há


# 0.8.7 - 04-Abr-2020

## Novas funcionalidades
- commit 3cc3256d: #244 Ajustando credenciais em Operações

## Correções
- Não há

## Melhorias
- Não há

## Incompatibilidades (Breaking Changes)
- Não há

# 0.8.6 - 03-Abr-2020

## Novas funcionalidades
- commit dd48e47c: #244 Verificar ao solicitar nova credencial, se existe credencial gerada com data de validade ativa, se sim, gerar um Alerta
- commit c74f7c27: #244 Alterar o Fluxo para liberar a impressão só após "confirmar" a solicitação


## Correções
- Não há

## Melhorias
- Não há

## Incompatibilidades (Breaking Changes)
- Não há

# 0.8.5 - 01-Abr-2020

## Novas funcionalidades
- commit 4fede60c: #205 Criando configuação para Natualidade como campo obrigatório


## Correções
- Não há

## Melhorias
- Não há

## Incompatibilidades (Breaking Changes)
- Não há


# 0.8.4 - 24-Mar-2020

## Novas funcionalidades
- Não há


## Correções
- commit 7485a5d1: unable to load shared library 'libgdiplus'

## Melhorias
- Não há

## Incompatibilidades (Breaking Changes)
- Não há

# 0.8.3 - 23-Mar-2020

## Novas funcionalidades
- Não há


## Correções
- commit 7db0ae64: Corrigindo formatação de Reais no linux docker

## Melhorias
- Não há

## Incompatibilidades (Breaking Changes)
- Não há



# 0.8.2 - 22-Mar-2020

## Novas funcionalidades
- Não há


## Correções
- commit 8d70d5e7: Corrigindo filtro de receitas/despesas

## Melhorias
- Não há

## Incompatibilidades (Breaking Changes)
- Não há



# 0.8.1 - 22-Mar-2020

## Novas funcionalidades
- commit ccfbe84d: #197 Opção para alterar matrícula de ministro/membro


## Correções
- Não há

## Melhorias
- Mudança para container docker

## Incompatibilidades (Breaking Changes)
- Não há


# 0.7.9 - 18-Mar-2020

## Novas funcionalidades
- commit e7fdf646: #221 - Novo parametro para agrupar dinamicamente a lista geral simplificada
- commit e23c1de8: #146 - Configurações permissões de operações de dentro da edição do perfil
- commit c3030f8b: #146 - Nova aba de ocorrências na edição do perfil
- commit 8956c9f3: #227 - Novo filtro de multiplas contas nos relatórios da tesouraria
- commit c493551b: #146 - Aba de grupos de relatórios do perfil
- commit c7b1d427: #146 - Nova aba de títulos eclesiásticos no cadastro do perfil


## Correções
- commit 40dc1027: Ajustando Css do Grid
- commit 868c8cde: Corrigindo versão do Templater

## Melhorias
- commit f71670a8: Novo filtro para função
- commit ab8fe9c3: #222 - Combo de Igrejas - Mostrar o caminho completo da árvore
- commit a87f1c3c: #146 - Carregando árvore de permissões fechada por padrão
- commit 8d4222d3: #146 - Separando a aba de permissões da apa de dados principais do perfil
- commit 7fa25337: Melhorando tela de edição de perfil
- commit 4c6f9ee3: #231 - Credenciais - Filtrar por Tipo de solicitacao e por modelo

## Incompatibilidades (Breaking Changes)
- Não há

# 0.7.8 - 07-Mar-2020

## Novas funcionalidades
- commit f1c7bb97: #215 - Opção de filtrar débitos por lista de matrículas
- commit 7906382c: #220 Novos filtros na tela de lançamentos
- commit 61029013: Criando componente de combo multipla
- commit 093669bf: #219 - Novo tipo de paramtetro pra relatorios (MultipleCombo)
- commit 429adff5: #217 - Novos filtros para relação anual de dizimistas

## Correções
- commit f46d0d57: Corrigindo erro ao acessar abas de documentos
- commit 9081ffb5: Corrigindo consulta de Transferencias
- commit 61644184: #209 - Revisando naturalidade
- commit dc8b0234: Corrigindo atulização indevida da data de criação da pessoa
- commit 05b7d7a0: #218 - Corrigindo relatção de dizimistas anuais

## Melhorias
- 

## Incompatibilidades (Breaking Changes)
- Não há

# 0.7.7 - 01-Mar-2020

## Novas funcionalidades
- Não há

## Correções
- Não há

## Melhorias
- Imagem personalizada no campo de credencial
- Nova fonte para campos de credenciais "Old English Text MT"

## Incompatibilidades (Breaking Changes)
- Não há


# 0.7.6 - 28-Fev-2020

## Novas funcionalidades
- Não há

## Correções
- Corrigindo pre-deploy
- Corrigindo consultas SQL sem label de campo

## Melhorias
- Melhorando mapa de dashboard

## Incompatibilidades (Breaking Changes)
- Não há

# 0.7.5 - 24-Fev-2020

## Novas funcionalidades
- Não há

## Correções
- Ordem de visualização dos itens de dashboard
- Corrigindo abreviação de nome na credencial
- Corrigindo consulta de vigência de repasse

## Melhorias
- Não há

## Incompatibilidades (Breaking Changes)
- Não há


# 0.7.4 - 23-Fev-2020

## Novas funcionalidades
- Não há

## Correções
- Não há

## Melhorias
 - Melhorando o mecanismo de dashboard

## Incompatibilidades (Breaking Changes)
- Não há

Obs: As verões 0.7.2 e 0.7.3 falharam




# 0.7.1 - 23-Fev-2020

## Novas funcionalidades
  - commit 6e36a962: #202 - Opção de Tamanho máximo para campo da credencial com abreviação
   - commit fb060fb4: #207 - No cadastro de novo membro, quando houver ocorrencia, informar país, cidade e observação
   - commit 515a1396: #214 - Opção para desabilitar a geração de excel de alguns relatórios, ou só em pdf
   - commit 3e904ea5: #100 - Opção de alterar nível da igreja
   - commit d3a9f881: #209 #141 - Resumo de funções no cadastro de igrejas
   - commit 5071a587: #195 - Opção para gerar credencial/diploma apenas para ativos
   
## Correções
  - commit 22b7b4cc: Corrigindo orientação dos relatórios
  - commit 9cfc5ae5: #194 - Corrigindo filtro e ordenação da combo de ocorrências
  - commit a739b144: #203 - Erro ao cadastrar nova cidade
  - commit 0b92dc8c: #204 - Erro ao criar usuário
## Melhorias
  - commit 4c915e7c: Migrando para .net core 3.1
  - commit 93d600c2: Refatorando strategies das combos
  - commit 5b0de353: Refatorando para novo acesso ao usuário logado
  - commit fc4b56b3: Possibilidade de relatórios com multiplos resultados (query)
  - commit fca56c22: Ajustes para carregar automaticamente a cidade e pais da igreja do usuário
  
## Incompatibilidades (Breaking Changes)
- Não há



# 0.6.11 - 12-Fev-2020

## Novas funcionalidades
 - commit be3f761b: Novo Relatório de campos com presidentes (CONAMAD)
 - commit f46be158: Novo opção de quantidade máxima de registros para anuidades e credenciais

## Correções
 - commit 9084fba4: Corrigindo aprovação/cancelado de transferências
 
## Melhorias
 - commit 9e9944b7: Cadastro rápido de novo bairro pela tela de edição/criação de igrejas
 - commit 53b52dc7: Melhorando para não mostrar credenciais canceladas por padrão

## Incompatibilidades (Breaking Changes)
- Não há



# 0.6.10 - 11-Fev-2020

## Novas funcionalidades
- commit dabfba5e: #186 - Nova opção de estilo de fonte (negrito, itálico) ao imprimir credencial
- commit 2c8e98e6: #54 - Novo Relatório de resumo de repasse

## Correções
- commit 3d587dcf: #191 - Corrigindo combo de ocorrências (Case insensitive)
- commit 3985edd7: #190 - Corrigindo Filtro transferências pela igreja do usuário, ordenar transferências
- commit 9fd8da1c: Corrigindo reltorios com segunda página em branco

## Melhorias
 - commit ce263df2: #182 - Manter login na navegação entre abas do browser
 - commit 5cf477fe: #184 - Ordenando a impressão de credenciais conforme ordem do grid
 - commit 832ae3df: #193 - Na visualização da operação/lançamento já criado. Mostrar o nome do usuário que criou

## Incompatibilidades (Breaking Changes)
- Não há


# 0.6.9 - 07-Fev-2020

## Novas funcionalidades
- Não há

## Correções
- Não há

## Melhorias
 - commit 27725ea1: Aumentando o Take da lista de débitos/anuidades de 100 para 1000
 - commit 4f450f38: Aumentando o Take da combo de igrejas/convenções de 20 pra 300
 
## Incompatibilidades (Breaking Changes)
- Não há


# 0.6.8 - 06-Fev-2020

## Novas funcionalidades
- Não há

## Correções
- commit 8dead293: #185 - Exibindo erro quando acontece na combo
- commit eb7e107c: #188 Corrigindo impressão de recibos no IE

## Melhorias
 - commit d832e237: #183 Novo campo de Situação do minisro e Título do ministro na tela de anuidades
 - commit b7d44d91: #187 Ao criar ocorrência, já trazer pre-selecionado a cidade/país da igreja do ministro/membro
 - commit 0016a8db: #189 Filtrando para exibir apenas as igrejas da árvore na modal de pagamento de anuidade

## Incompatibilidades (Breaking Changes)
- Não há


# 0.6.7 - 02-Fev-2020

## Novas funcionalidades
- Configuração para label de "Débitos" (configurado como Anuidades)
- Criando configuração para o CAIXA da tesouraria ficar sempre na igreja do cadastro do usuário, e não ser alterada ao alterar o contexto da sessão atual.

## Correções
- Corrigindo valor padrão nos parâmetros dos relatórios
- Filtrando a tela de eventos para exibir apenas eventos da arvore da igreja do usuário logado

## Melhorias
 - Movendo menu de "Débitos" para dentro do módulo tesouraria
 - Ordenando lista de operações (novo campo Ordem)

## Incompatibilidades (Breaking Changes)
- Não há


# 0.6.6 - 30-Jan-2020

## Novas funcionalidades
- Salvando histórico de acessos ao sistema (Registro de logins)
- Opção de gatilho de ocorrência para cancelar débitos/anuidades anteriores ao ano corrente

## Correções
- Não há

## Melhorias
 - Melhoando tela de solicitação de credencial

## Incompatibilidades (Breaking Changes)
- Não há

# 0.6.5 - 29-Jan-2020

## Novas funcionalidades
- Novo relatório de Lista geral de anuidades por campo/convenção
- Criação rápida de bairros no cadastro de endereços

## Correções
- Corrigindo impressão de credencial no Microsoft Edge
- Corrigindo igreja padrão ao criar novo membro/ministro

## Melhorias
- Filtro de igreja em credenciais, agora filtra membros/ministros dentro da árvore da igreja
- Melhoria na seleção de credenciais
- Removendo ano atual como filtro padrão dos débitos/anuidades

## Incompatibilidades (Breaking Changes)
- Não há

# 0.6.4 - 25-Jan-2020

## Novas funcionalidades
- Novo relatório de Ficha Cadastral

## Correções
- Não há

## Melhorias
- Não há

## Incompatibilidades (Breaking Changes)
- Não há


# 0.6.3 - 24-Jan-2020

## Novas funcionalidades
- Pagar débitos em lote (mais de uma pessoa)

## Correções
- Corrigindo atribuição de perfis a usuários, e a perfis

## Melhorias
- Melhoria na seleção de perfis e de usuários

## Incompatibilidades (Breaking Changes)
- Não há

# 0.6.2 - 22-Jan-2020

## Novas funcionalidades
- Não há

## Correções
- Não há 

## Melhorias
- Mostrar variavel com valor somente leitura na execução de operações
- Operação de débito, cria apenas o pagamento se o débito já existir
- Combo de igrejas agora pesquisa apenas com "Começa com"

## Incompatibilidades (Breaking Changes)
- Não há

# 0.6.1 - 19-Jan-2020

## Novas funcionalidades
- Recibo manual de anuidade
- Tela de visualização individual da anuidade com histórico


## Correções
- Correção da ordem da combo de igrejas

## Melhorias
- Melhorando visualização mobile para anuidades


## Incompatibilidades (Breaking Changes)
- Não há

# 0.5.12 - 18-Jan-2020

## Novas funcionalidades
- Nova tela de débitos, no menu, fora das abas do ministro
- Configuração para aba de redirecionamento na busca rápida de membros/ministros
- Novo relatório de lista de membros com endereços

## Correções
- Correção de Bug que aculmulava os débitos selecionados ao trocar o ministro 

## Melhorias
- Mudando ordem do resultado da combo de igrejas/convenções
- Criando serviço de Processamento de Specification (interno)

## Incompatibilidades (Breaking Changes)
- Não há


# 0.5.11 - 14-Jan-2020

## Novas funcionalidades
- Não há

## Correções
- Corrigindo estorno de débitos

## Melhorias
- Não há

## Incompatibilidades (Breaking Changes)
- Não há


# 0.5.10 - 10-Jan-2020

## Novas funcionalidades
- Não há

## Correções
- Corrigindo erro em esqueci minha senha

## Melhorias
- Não há

## Incompatibilidades (Breaking Changes)
- Não há


# 0.5.9 - 10-Jan-2020

## Novas funcionalidades
- Não há

## Correções
- Não há

## Melhorias
- Não mostrar débitos cancelados, nova opção de filtro "Mostrar cancelados"
- Ao exibir a igreja do membro/ministro, exibe o nome de toda a árvore hierárquica

## Incompatibilidades (Breaking Changes)
- Não há


# 0.5.8 - 08-Jan-2020

## Novas funcionalidades
- Não há

## Correções
- Não há

## Melhorias
- Melhorando visualização pelo Celular
- Melhorando comportando de combos da tela de receita/despesa
- Melhorando identação do menu


## Incompatibilidades (Breaking Changes)
- Não há

# 0.5.7 - 07-Jan-2020

## Novas funcionalidades
- Opção de recibo ao pagar um débito
- Novo Recibo de receita
- Nova função de banco de dados para exibir o nome de toda a árvore de igrejas

## Correções
- Bug de Conta não carrega as vezes na modal de pagamento

## Melhorias
- Não há


## Incompatibilidades (Breaking Changes)
- Não há

# 0.5.6 - 03-Jan-2020

## Novas funcionalidades
- Não há

## Correções
- Não há

## Melhorias
- Melhorando busca rápida de membros


## Incompatibilidades (Breaking Changes)
- Não há

# 0.5.5 - 03-Jan-2020

## Novas funcionalidades
- Novos relatórios de débitos (anuidades)
- Novos relatórios de eventos
 
## Correções
- Corrigindo navegação
- Corrigindo filtro da compo de eventos 

## Melhorias
- Melhorando visualização da foto do membro


## Incompatibilidades (Breaking Changes)
- Não há

# 0.5.4 - 31-Dez-2019

## Novas funcionalidades
- Não há
 
## Correções
- Não há

## Melhorias
- Corrigindo sistema de build


## Incompatibilidades (Breaking Changes)
- Não há


# 0.5.3 - 31-Dez-2019

## Novas funcionalidades
- Não há
 
## Correções
- Não há

## Melhorias
- Corrigindo sistema de build


## Incompatibilidades (Breaking Changes)
- Não há


# 0.5.2 - 31-Dez-2019

## Novas funcionalidades
- Busca rápida de membros/ministgros 
 
## Correções
- Não há

## Melhorias
- Atualizando componentes e Angular para versão 8


## Incompatibilidades (Breaking Changes)
- Não há


# 0.5.1 - 29-Dez-2019

## Novas funcionalidades
 - Não há
 
## Correções
-  Não há

## Melhorias
- novo mecanismo de build automatizado (yaml)


## Incompatibilidades (Breaking Changes)
- Não há


# 0.4.10 - 28-Dez-2019

## Novas funcionalidades
 - Configuração para "label" no singular e plural para "Igrejas"
 - Configuração para "label" no singular e plural para "Membros"
 
## Correções
- Corrigindo arredondamento ao fechar caixa

## Melhorias
- Não há


## Incompatibilidades (Breaking Changes)
- Não há


# 0.4.9 - 28-Dez-2019

## Novas funcionalidades
 - Opção para "Permitir membros de fora da igreja realizadora" em inscrição de eventos 
 
## Correções
- Corrigindo scroll-bar congelada

## Melhorias
- Não há


## Incompatibilidades (Breaking Changes)
- Não há

# 0.4.8 - 28-Dez-2019

## Novas funcionalidades
 - Variáveis de operações
 - Nova aba de "Operações" no cadastro do membro
 - Inscrição avulsa de pesssoas físicas em eventos
 - Criação rápida de pessoas físicas pela tela de inscrição de eventos 
 - Criação rápida de pessoas físicas/jurídicas pela tela de lançamento de receita/despesa
 
## Correções
- Corrigindo configurações de transferências

## Melhorias
- Não há


## Incompatibilidades (Breaking Changes)
- Não há

# 0.4.7 - 11-Dez-2019

## Novas funcionalidades
 - Não há
 
## Correções
- Corrigindo bug de cache nos dashboards

## Melhorias
- Não há


## Incompatibilidades (Breaking Changes)
- Não há


# 0.4.6 - 11-Dez-2019

## Novas funcionalidades
 - Motivo de isenção de débitos
 
## Correções
- Edição de usuários, seleção de perfis.

## Melhorias
- Relatório de débitos


## Incompatibilidades (Breaking Changes)
- Não há

*As versões 0.4.4 e 0.4.5 falharam

# 0.4.3 - 08-Dez-2019

## Novas funcionalidades
- Criar ocorrência a partir da criação/aprovação/cancelamento de transferencias
- Duas novas configurações internas: "TransferenciasExibirMembrosForaArvoreIgrejas" e "TransferenciasExibirIgrejasForaArvore"
- Criar ou reativar débitos desde a criação da transferência até sua aprovação
- Bloquear o uso de plano de contas na tela de lançamentos manuais
- Exigir nível mínimo de título eclesiástico para ocorrêncais
- Configuração de ocorrencias como pré-requisito para ocorrencias (somente no úlitmo histórico ou em todo o histórico)
- Configuração de ocorrencias como impedimentos para ocorrencias (somente no úlitmo histórico ou em todo o histórico)

## Correções
- Não há

## Melhorias
- Cache para parâmetros iniciais do sistema
- Cache para fotos da combo de membros e para foto do usuário logado

## Incompatibilidades (Breaking Changes)
- Não há


# 0.4.2 - 04-Dez-2019

## Novas funcionalidades
- Não há

## Correções
- Corrigindo aritimética do javascript

## Melhorias
- Não há

## Incompatibilidades (Breaking Changes)
- Não há

# 0.4.1 - 03-Dez-2019

## Novas funcionalidades
- Cancelamento de débitos por ocorrência com desfazimento
- Ações de Isenção, Cancelamento, Criação e Reativação de débitos por ocorrência
- Criando tipo de solicitações de credenciais e configurações de geração de ocorrencia
- Criar ocorrencia ao criar soliciação de credencial e/ou ao confirmar impressão
- Criando nova solicitação de Credencial pela operação automática
- Nova configuração de conta de repasse: Baixar repasses quando receita de membro da devedora na credora

## Correções
- Corrigido Transferencia para nível hierárquico não permitido

## Melhorias
- Ajustando pagamento de débitos para vincular o lançamento à conta do tipo de débito
- Relatório estatístico por agrupador de título eclesiástico
- Melhorando mensagem de fechamento de caixa
- Cache para o conteúdo dos itens do Dashboard (padrão 30min)
- Exibir todas as igrejas na combo de destino da transfefencia

## Incompatibilidades (Breaking Changes)
- Configuração de geração de ocorrencia por modelo de credencial foi descontinuada
- Tipos de débitos sem conta financeira não existem mais 

# 0.3.4 - 29-Nov-2019

## Novas funcionalidades
- Bloqueio de cadastro de membros por nível hierárquico de igrejas
- Cancelamento de débitos por ocorrência
- Desfazimento de cancelamento de débitos por ocorrência
- Novo relatório de agrupador por título eclesiástico

## Correções
- Não há

## Melhorias
- Não há

## Incompatibilidades (Breaking Changes)
- Não há



# 0.3.3 - 26-Nov-2019

## Novas funcionalidades
- Geolocalização no cadastro de igrejas
- Novas situações para inscrições em eventos
- Nova tela de consulta de igrejas

## Correções
- Não há

## Melhorias
- Melhorias na aparência dos relatórios

## Incompatibilidades (Breaking Changes)
- Não há


# 0.3.2 - 19-Nov-2019

## Novas funcionalidades
- Geolocalização no cadastro de membros
- Cancelamento de inscrição de evento


## Correções
- Script de pre-deploy

## Melhorias
- Não há

## Incompatibilidades (Breaking Changes)
- Não há


# 0.3.1 - 16-Nov-2019

## Novas funcionalidades
- Recebimento de caixa de igreja afilhada
- Novo módulo de eventos


## Correções
- Permissões de menus

## Melhorias
- Não há

## Incompatibilidades (Breaking Changes)
- Não há

# 0.2.20

## Novas funcionalidades
- Possibilidade de Caixas quinzenais (por configuração interna)


## Correções
- Tela de edição de usuários, salvar perfis do usuário

## Melhorias
 - Algorítmo de pesqiusa das combos de Membros, Pessoas físicas, pessoas jurídicas e igrejas. Pesquisa utilizando %

## Incompatibilidades (Breaking Changes)
- Não há
