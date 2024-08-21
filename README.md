# Documentação da Tabela `Advertência`

Esta tabela armazena informações sobre advertências, com detalhes sobre o início, término e status, juntamente com vários valores relacionados.

| Coluna       | Descrição                              |
|--------------|----------------------------------------|
| id           | Identificador único da advertência.     |
| start        | Data/hora de início da advertência.    |
| end          | Data/hora de término da advertência.   |
| status_ticke | Status da advertência.                 |
| valor1       | Lista de dicionários com várias informações relacionadas à advertência. |
| valor2       | Lista de dicionários com várias informações relacionadas à advertência. |
| valor3       | Lista de dicionários com várias informações relacionadas à advertência. |
| valor4       | Lista de dicionários com várias informações relacionadas à advertência. |
| valor5       | Lista de dicionários com várias informações relacionadas à advertência. |
| valor6       | Lista de dicionários com várias informações relacionadas à advertência. |
| valor7       | Lista de dicionários com várias informações relacionadas à advertência. |
| valor8       | Lista de dicionários com várias informações relacionadas à advertência. |
| valor9       | Lista de dicionários com várias informações relacionadas à advertência. |
| valor10      | Lista de dicionários com várias informações relacionadas à advertência. |
| valor 11     | Lista de dicionários com várias informações relacionadas à advertência. |
| valor12      | Lista de dicionários com várias informações relacionadas à advertência. |
| valor13      | Lista de dicionários com várias informações relacionadas à advertência. |
| valor14      | Lista de dicionários com várias informações relacionadas à advertência. |
| nome         | Nome relacionado à advertência.       |

## Como encontrar a API para esta requisição

1. **User:** Acesse o site [Goepik.io](https://goepik.io/epik).
2. **Registro e Autenticação:** Vá para o seu perfil, clique na sua foto e acesse as configurações.
3. **Documentação da API:** Escolha a opção de API e selecione "Epick Advertencia".
4. **Explorar a API:** Selecione o processo "Envio de Advertência" e a atividade "Solicitação de Envio de Advertência".

# Documentação da Tabela `dim_clientes_publi`

Esta tabela contém informações sobre clientes do nosso ERP publi

| Coluna        | Descrição                              |
|---------------|----------------------------------------|
| cod_cliente   | Identificador único do cliente (Primary Key). |
| nome          | Nome do cliente.                       |
| situacao      | Situação do cliente (ativo, inativo, etc.). |
| razao_soc     | Razão social do cliente (se aplicável). |
| cgc           | CGC (Cadastro Geral de Contribuintes) do cliente. |
| municipio     | Município do cliente.                  |
| estado        | Estado do cliente.                     |
| cep           | CEP (Código de Endereçamento Postal) do cliente. |
| tipo          | Tipo de cliente (pessoa física, pessoa jurídica, etc.). |
| email         | Endereço de e-mail do cliente.         |
| dtinclusao    | Data de inclusão do cliente no sistema.|
| recno         | Número de registro do cliente.         |
| cnpj_cpf      | CNPJ (Cadastro Nacional da Pessoa Jurídica) ou CPF (Cadastro de Pessoa Física) do cliente. |

# Documentação da Tabela `dim_fornecedor_publi`

Esta tabela contém informações sobre fornecedores cadastrado no ERP publi

| Coluna            | Descrição                              |
|-------------------|----------------------------------------|
| cod_fornecedor    | Identificador único do fornecedor (Primary Key). |
| nome              | Nome do fornecedor.                    |
| situacao          | Situação do fornecedor (ativo, inativo, etc.). |
| razao_soc         | Razão social do fornecedor (se aplicável). |
| cgc               | CGC (Cadastro Geral de Contribuintes) do fornecedor. |
| municipio         | Município do fornecedor.               |
| estado            | Estado do fornecedor.                  |
| cep               | CEP (Código de Endereçamento Postal) do fornecedor. |
| tipo              | Tipo de fornecedor (pessoa física, pessoa jurídica, etc.). |
| email             | Endereço de e-mail do fornecedor.      |
| dtinclusao        | Data de inclusão do fornecedor no sistema.|
| recno             | Número de registro do fornecedor.      |
| cnpj_cpf          | CNPJ (Cadastro Nacional da Pessoa Jurídica) ou CPF (Cadastro de Pessoa Física) do fornecedor. |


# Documentação da Tabela `dim_empresas_publi`

Esta tabela contém informações sobre empresas no ERP publi, incluindo detalhes como código, razão social, nome e número de inscrição.

| Coluna       | Descrição                              |
|--------------|----------------------------------------|
| codigo       | Código único da empresa.               |
| razao_soc    | Razão social da empresa.               |
| nome         | Nome da empresa.                       |
| inscricao    | Número de inscrição da empresa.        |


# Documentação da Tabela `fato_pedidos_cap_publi`

Esta tabela contém informações sobre contas a pagar do nosso no ERP publi

| Coluna          | Descrição                              |
|-----------------|----------------------------------------|
| documento       | Documento relacionado ao pedido.       |
| cod_fornec      | Código do fornecedor relacionado ao pedido. |
| cod_client      | Código do cliente relacionado ao pedido. |
| descricao       | Descrição do pedido.                   |
| emissao         | Data de emissão do pedido.             |
| entrada         | Data de entrada do pedido.             |
| valor           | Valor do pedido.                       |
| vencimento      | Data de vencimento do pedido.          |
| banco           | Banco relacionado ao pagamento do pedido. |
| tipo_pedid      | Tipo de pedido.                        |
| datapagto       | Data de pagamento do pedido.           |
| valorpagto      | Valor pago do pedido.                  |
| contapagto      | Conta relacionada ao pagamento do pedido. |
| ccm_baixa       | CCM de baixa do pedido.                |
| chequepagt      | Cheque relacionado ao pagamento do pedido. |
| ctb_apropr      | Conta de apropriação do pedido.        |
| ctb_baixa       | Conta de baixa do pedido.              |
| conf_aprop      | Confirmação de apropriação do pedido.  |
| conf_baixa      | Confirmação de baixa do pedido.        |
| tag             | Tag relacionada ao pedido.             |
| opmanu          | Operação de manutenção do pedido.      |
| dtmanu          | Data de manutenção do pedido.          |
| usmanu          | Usuário responsável pela manutenção do pedido. |
| tipo_doc        | Tipo de documento do pedido.           |
| juros           | Juros do pedido.                       |
| multa           | Multa do pedido.                       |
| vencto_org      | Vencimento original do pedido.         |
| fatura          | Fatura relacionada ao pedido.          |
| chave_parc      | Chave da parcela do pedido.            |
| bv_perc         | Percentual BV do pedido.               |
| empresa         | Empresa relacionada ao pedido.         |
| dtinclusao      | Data de inclusão do pedido no sistema. |
| hrmanu          | Hora de manutenção do pedido.          |
| valor_brut      | Valor bruto do pedido.                 |
| lib_lote        | Lote de liberação do pedido.           |
| lib_data        | Data de liberação do pedido.           |
| lib_usuari      | Usuário responsável pela liberação do pedido. |
| num_serie       | Número de série do pedido.             |
| usinclusao      | Usuário responsável pela inclusão do pedido. |
| situacao        | Situação do pedido.                    |
| data_sit        | Data da situação do pedido.            |
| cod_ir          | Código IR do pedido.                   |
| recno           | Número de registro do pedido.          |
| sit_descri      | Descrição da situação do pedido.       |
| lote_data       | Data do lote do pedido.                |
| lote_usuar      | Usuário responsável pelo lote do pedido. |
| envbcodata      | Dados de envio do pedido.              |
| tipo_despe      | Tipo de despesa do pedido.             |
| idfat           | ID da fatura relacionada ao pedido.    |
| spedfiscal      | Informações fiscais relacionadas ao pedido. |
| dtexecucao      | Data de execução do pedido.            |
| pag_e_lote      | Página e lote do pedido.               |
| cod_agenci      | Código da agência do pedido.           |
| part_scp        | Participante SCP do pedido.            |
| hrinclusao      | Hora de inclusão do pedido.            |
| documento_empresa | Documento da empresa relacionado ao pedido. |
| pit             | PIT relacionado ao pedido.             |


# Documentação do Fluxo de Férias

## Construção do Fluxo de Férias

O fluxo de férias é construído utilizando dados de três APIs do Goepick: solicitar férias, aprovar férias e pedido de férias.

### APIs do Goepick Utilizadas:

1. **Solicitar Férias API:**
   - Esta API é responsável por permitir que os usuários solicitem férias. Ela fornece informações detalhadas sobre as solicitações de férias, incluindo o ID do ticket, data de início e término das férias e status da solicitação.

2. **Aprovar Férias API:**
   - Esta API é utilizada para aprovar solicitações de férias. Fornece detalhes sobre as aprovações de férias, incluindo o ID do ticket a ser aprovado, datas de início e término da aprovação, o status do ticket e informações sobre o aprovador.

3. **Pedido de Férias API:**
   - Esta API lida com os pedidos de férias, incluindo informações sobre o ID do ticket, datas de início e término do pedido, status do ticket e valores associados ao pedido.

## Construção do Fluxo:

O fluxo de férias é construído em três etapas principais:

1. **Scripts em Python:**
   - São utilizados três scripts em Python para ler os dados das APIs do Goepick.
   - Cada script lê os dados de uma API específica e salva os resultados em arquivos CSV na pasta designada.

2. **Apache Hop ETL:**
   - O Apache Hop é utilizado para realizar o ETL (Extração, Transformação e Carregamento) dos dados.
   - Os dados salvos nos arquivos CSV são lidos pelo Apache Hop, onde são transformados e combinados com base no ID do ticket.
   - Este processo de ETL permite a junção dos dados das três fontes API em um único conjunto de dados.

3. **Armazenamento no Banco de Dados:**
   - Após a transformação e combinação dos dados pelo Apache Hop, o resultado é gravado no banco de dados.
   - Os dados combinados e processados agora estão prontos para análise e utilização posterior.

## Exemplo de Uso:

Para executar o fluxo de férias:

1. Execute os scripts em Python para obter os dados das APIs do Goepick e salvá-los nos arquivos CSV.
2. Utilize o Apache Hop para realizar o ETL dos dados, transformá-los e combiná-los conforme necessário.
3. Grave os dados resultantes no banco de dados para análise e utilização.

Este fluxo de trabalho permite a gestão eficiente das solicitações, aprovações e pedidos de férias, proporcionando uma visão abrangente do processo.

---

## Detalhes do Fluxo de Férias

Este documento descreve o fluxo de férias em detalhes, incluindo informações sobre status, colunas associadas, tickets, aprovações, datas e usuários.

| Coluna           | Descrição                                 |
|------------------|-------------------------------------------|
| status           | Status do fluxo de férias.                |
| coluna1 - coluna12 | Descrições das colunas associadas ao fluxo de férias. |
| ticket_id_aprovar | ID do ticket a ser aprovado.              |
| inicio_aprovar   | Data de início da aprovação.              |
| fim_aprovar      | Data de fim da aprovação.                 |
| ticket_status_aprovar | Status do ticket a ser aprovado.       |
| coluna1_aprovar  | Descrição da coluna associada à aprovação. |
| coluna2_aprovar  | Descrição da coluna associada à aprovação. |
| nome_aprovar     | Nome do aprovador.                        |
| ticket_id        | ID do ticket.                             |
| start_at         | Data/hora de início do fluxo de férias.  |
| end_at           | Data/hora de término do fluxo de férias. |
| ticket_status    | Status do ticket.                         |
| device           | Dispositivo utilizado no fluxo de férias.|
| user_name        | Nome do usuário associado ao fluxo de férias. |
| ticket_id_pedido | ID do ticket de pedido.                   |
| fim_pedido       | Data de término do pedido.                |
| inicio_pedido    | Data de início do pedido.                 |
| ticketd_status_pedido | Status do ticket de pedido.           |
| values_pedido    | Valores associados ao pedido.            |
| aprovador_dp     | Aprovador de departamento.               |


# Documentação das Contas a Receber do ERP Publi

Este documento descreve as informações relacionadas às contas a receber no contexto do ERP Publi, incluindo detalhes sobre pedidos, clientes, fornecedores, produtos, serviços, faturas, entre outros.

| Coluna           | Descrição                                       |
|------------------|-------------------------------------------------|
| pedido           | Número do pedido associado à conta a receber.   |
| tipo             | Tipo de transação (ex: venda, serviço, etc.).    |
| cod_client       | Código do cliente relacionado à transação.      |
| cod_fornec       | Código do fornecedor relacionado à transação.   |
| produto          | Produto associado à transação.                  |
| titulo           | Título da transação.                            |
| servico          | Serviço associado à transação.                  |
| emissao          | Data de emissão da transação.                   |
| valor            | Valor da transação.                             |
| prazopagto       | Prazo de pagamento da transação.                |
| descricao        | Descrição da transação.                         |
| prazoentre       | Prazo entre transações.                         |
| origem           | Origem da transação.                            |
| fatura           | Número da fatura associada à transação.         |
| tipofatura       | Tipo de fatura (ex: fatura, nota fiscal, etc.). |
| opmanu           | Operação de manutenção.                         |
| dtmanu           | Data de manutenção.                             |
| usmanu           | Usuário responsável pela manutenção.            |
| nf_fornece      | Nota fiscal fornecida.                          |
| vencimento      | Data de vencimento da transação.                |
| situacao        | Situação da transação.                          |
| empresa         | Empresa relacionada à transação.                |
| dtinclusao      | Data de inclusão da transação no sistema.      |
| hrmanu          | Hora de manutenção.                             |
| nf_numero       | Número da nota fiscal.                          |
| nf_valor        | Valor da nota fiscal.                           |
| nf_situaca      | Situação da nota fiscal.                        |
| historico       | Histórico da transação.                         |
| usinclusao      | Usuário responsável pela inclusão.              |
| nf_serie        | Série da nota fiscal.                           |
| nf_empresa      | Empresa relacionada à nota fiscal.              |
| recno           | Número de registro da transação.                |
| campanha        | Campanha relacionada à transação.               |
| idfat           | ID da fatura.                                   |
| cod_agenci      | Código da agência.                              |
| nfe             | Nota fiscal eletrônica.                         |
| orcx_recno      | Número de registro na caixa.                    |
| documento_empresa | Documento da empresa relacionado à transação. |

# Documentação da Tabela `fato_faturamento`

Esta tabela armazena informações relacionadas ao faturamentodo nosso ERP publi

| Coluna          | Descrição                                  |
|-----------------|--------------------------------------------|
| fatura          | Número da fatura.                         |
| situacao        | Situação da fatura (ex: aberta, fechada). |
| cad_sacado      | Cadastro do sacado.                       |
| sacado          | Nome do sacado.                           |
| pit             | PIT (Período de Apuração e Pagamento).    |
| produto         | Produto associado à fatura.               |
| emissao         | Data de emissão da fatura.                |
| vencimento      | Data de vencimento da fatura.             |
| subtipo         | Subtipo da fatura.                        |
| iss_rf          | Valor do ISS retido na fonte.             |
| irrf            | Valor do IRRF (Imposto de Renda Retido na Fonte). |
| indicador       | Indicador.                                |
| opmanu          | Operação de manutenção.                   |
| dtmanu          | Data de manutenção.                       |
| usmanu          | Usuário responsável pela manutenção.      |
| darf            | DARF (Documento de Arrecadação de Receitas Federais). |
| data_sit        | Data de situação.                         |
| ctb_chave       | Chave contábil.                           |
| ctb_estorn      | Estorno contábil.                         |
| referencia      | Referência.                               |
| ccusto          | Centro de custo.                          |
| dtinclusao      | Data de inclusão.                         |
| hrmanu          | Hora de manutenção.                       |
| competenci      | Competência.                              |
| tipo_doc        | Tipo de documento.                        |
| documento       | Documento associado à fatura.            |
| recibo          | Recibo.                                   |
| cartacred       | Carta de crédito.                         |
| icsll           | Valor do ICSLL.                           |
| icofins         | Valor do COFINS.                          |
| ipis            | Valor do PIS.                             |
| usinclusao      | Usuário de inclusão.                      |
| campanha        | Campanha.                                 |
| iinss           | Valor do INSS.                            |
| nfe             | Nota Fiscal Eletrônica.                   |
| serie           | Série.                                    |
| idfat           | ID da fatura.                             |
| saac            | SAAC (Sistema de Arrecadação e Cobrança).|
| lote            | Lote.                                     |
| codativ         | Código de atividade.                      |
| vernfe          | Versão da NF-e.                           |
| spedfbcalc      | SPED Fiscal Base de Cálculo.              |
| nferetorno     | Retorno da NF-e.                          |
| iss_fm          | Valor do ISS.                             |
| horanfe         | Hora da NF-e.                             |
| sitrps          | Situação do RPS.                          |
| xmlnfe          | XML da NF-e.                              |
| cod_scp         | Código do SCP (Sistema de Controle de Pagamento). |
| nferecibo       | Recibo da NF-e.                           |
| t_reg_trib      | Tipo de registro tributário.              |
| hrinclusao      | Hora de inclusão.                         |
| codtribmun      | Código tributário municipal.              |
| natop           | Natureza da operação.                     |
| itservico       | Item de serviço.                          |
| cnae            | CNAE (Classificação Nacional de Atividades Econômicas). |
| sismanu         | Sistema de manutenção.                    |
| cst             | Código de Situação Tributária.            |
| ref_idfat       | Referência do ID da fatura.               |
| nfe_gmt         | Horário de Greenwich da NF-e.             |
| tiposervic      | Tipo de serviço.                          |
| reinflote       | Lote do REINF (eSocial).                  |
| reinfstatu      | Status do REINF (eSocial).                |
| reinfproc       | Processo do REINF (eSocial).              |
| reinftpev       | Tipo de evento do REINF (eSocial).        |
| reinfidev       | Identificador do evento do REINF (eSocial). |
| reinfhash       | Hash do REINF (eSocial).                  |
| reinfrecib      | Recibo do REINF (eSocial).                |
| reinferro       | Erro do REINF (eSocial).                  |
| reinfcoder      | Código do erro do REINF (eSocial).        |
| nfelink         | Link da NF-e.                             |
| reinfxml        | XML do REINF (eSocial).                   |
| cod_sacado      | Código do sacado.                         |
| cod_client      | Código do cliente.                        |
| tipo_rec        | Tipo de recibo.                           |
| desconto        | Valor do desconto.                        |
| controle        | Controle.                                 |
| encargos        | Encargos.                                 |
| empresa         | Empresa.                                  |
| cofins          | Valor do COFINS.                          |
| csll            | Valor da CSLL.                            |
| imp_manual      | Imposto manual.                           |
| inss            | Valor do INSS.                            |
| recno           | Número de registro.                       |
| datanfe         | Data da NF-e.                             |
| codigo_ex       | Código EX.                                |
| part_scp        | Part SCP (Sistema de Controle de Pagamento). |
| cod_agenci      | Código da agência.                        |
| m_reg_trib      | Modalidade de registro tributário.        |
| idctb           | ID do CTB (Controle de Contabilidade).    |
| idctb_esto      | ID do CTB de estorno.                     |
| spedreinf       | SPED do REINF (eSocial).                  |
| valor           | Valor.                                    |
| receita1        | Receita 1.                                |
| receita2        | Receita 2.                                |
| iss             | Valor do ISS.                             |
| ir              | Valor do IR.                              |
| total           | Valor total.                              |
| terceiros       | Terceiros.                                |
| pis             | Valor do PIS.                             |
| cofins_ktl      | COFINS KTL.                               |

# Documentação da Tabela `fato_orcamentos`

Esta tabela armazena informações relacionadas aos orçamentos do nosso ERP publi

| Coluna        | Descrição                                    |
|---------------|----------------------------------------------|
| orcamento     | Número do orçamento.                         |
| pit           | PIT (Período de Apuração e Pagamento).      |
| tipo          | Tipo do orçamento.                           |
| modelo        | Modelo do orçamento.                         |
| cod_client    | Código do cliente associado ao orçamento.   |
| produto       | Produto associado ao orçamento.             |
| emissao       | Data de emissão do orçamento.               |
| valor         | Valor do orçamento.                         |
| descricao     | Descrição do orçamento.                     |
| fatura        | Número da fatura associada ao orçamento.    |
| situacao      | Situação do orçamento.                      |
| data_aprov    | Data de aprovação do orçamento.             |
| campanha      | Campanha relacionada ao orçamento.          |
| empresa       | Empresa relacionada ao orçamento.           |
| vencimento    | Data de vencimento do orçamento.            |
| recno         | Número de registro do orçamento.            |
| idfat         | ID da fatura associada ao orçamento.        |



# Documentação da Tabela `fato_jobone_pendencia`

Esta tabela armazena informações relacionadas às pendências de atividades de alocação e apontamento de horas, considerando a estrutura organizacional e feriados. A `fato_jobone_pendencia` é essencial para análises detalhadas de pendências operacionais, permitindo a identificação de inconsistências e problemas relacionados à alocação de recursos e cumprimento de prazos.

## Fonte de Dados
A tabela é construída a partir de múltiplas fontes, incluindo:
- **APONTAM_DATA**
- **USUARIO**
- **EQUIPE_USUARIO**
- **AREA**
- **CARGO**
- **DIA_ALOCACAO**
- **TAB_FERIADO**
- **PESSOA**

## Joins Principais
- **APONTAM_DATA** com **USUARIO** e **EQUIPE_USUARIO** para associar dados de apontamento aos usuários e equipes.
- **AREA** e **CARGO** para relacionar cargos com suas respectivas áreas.
- **DIA_ALOCACAO** e **TAB_FERIADO** para identificar alocações em dias de feriado.
- Join final com **PESSOA** para integrar todas as informações relevantes na tabela final.

## Colunas da Tabela
| Coluna                 | Descrição                                                         |
|------------------------|-------------------------------------------------------------------|
| apontam_data_id        | Identificador da data de apontamento.                             |
| usuario_id             | Identificador do usuário.                                         |
| usuario_aprov_id       | Identificador do usuário que aprovou.                             |
| cargo_id               | Identificador do cargo.                                           |
| area_cargo_id          | Identificador da área do cargo.                                   |
| DATA                   | Data relacionada ao registro.                                     |
| num_horas_dia          | Número de horas alocadas no dia.                                  |
| status                 | Status da pendência.                                              |
| nivel                  | Nível da pendência.                                               |
| data_apont             | Data do apontamento.                                              |
| data_aprov             | Data da aprovação.                                                |
| tab_feriado_id         | Identificador da tabela de feriados.                              |
| LOGIN                  | Login do usuário.                                                 |
| flag_ativo             | Indicador se o registro está ativo.                               |
| tipo_relacao           | Tipo de relação do usuário com a organização.                     |
| equipe_id              | Identificador da equipe.                                          |
| area                   | Área do usuário.                                                  |
| area_id                | Identificador da área.                                            |
| empresa_id             | Identificador da empresa.                                         |
| cargo                  | Cargo do usuário.                                                 |
| chave_dia_alocacao     | Chave única de alocação do dia.                                   |
| dia_alocacao_id        | Identificador do dia de alocação.                                 |
| data_1                 | Data adicional relacionada ao registro.                           |
| horas_diarias          | Horas diárias alocadas.                                           |
| dia_semana             | Dia da semana.                                                    |
| feriado                | Indicador se o dia é feriado.                                     |
| flag_padrao            | Indicador de padrão.                                              |
| email                  | E-mail do usuário.                                                |
| pessoa_id              | Identificador da pessoa.                                          |
| flag_atiivo_pessoa     | Indicador se a pessoa está ativa.                                 |

## Uso
Essa tabela é essencial para conseguir cruzar dados de pêndencias de apontamentos com o dash de advêrtencias.

# Documentação da Tabela `dim_nucleo`

Esta tabela armazena informações sobre as unidades de negócio, incluindo detalhes como a empresa associada, o nome da unidade, códigos externos, usuários responsáveis e percentuais de rateio.

## Colunas da Tabela
| Coluna                | Descrição                                                      |
|-----------------------|----------------------------------------------------------------|
| unidade_negocio_id    | Identificador único da unidade de negócio.                     |
| empresa_id            | Identificador da empresa associada à unidade de negócio.       |
| nome                  | Nome da unidade de negócio.                                    |
| cod_ext_unid_neg      | Código externo da unidade de negócio.                          |
| usuario_id            | Identificador do usuário responsável pela unidade.             |
| perc_rateio           | Percentual de rateio associado à unidade de negócio.           |

## Uso
A tabela `dim_nucleo` é utilizada para gerenciar e analisar as diferentes unidades de negócio, facilitando a organização e o cálculo de rateios com base nas informações associadas.


# Documentação da Tabela: `fato_aprovacao_contratacao_goepick`

## Descrição
A tabela `fato_aprovacao_contratacao_goepick` armazena informações detalhadas sobre os processos de aprovação e contratação de pedidos de fornecedores dentro do sistema Goepick. Essa tabela é parte essencial do workflow de aprovação de contratos e gerenciamento de pedidos, permitindo o rastreamento das atividades realizadas, os responsáveis por cada etapa, e o status do processo.

## Estrutura da Tabela

| Nome da Coluna     | Tipo de Dados | Descrição                                                                                  |
|--------------------|---------------|--------------------------------------------------------------------------------------------|
| `ticket_id`        | INTEGER       | Identificador único do ticket.                                                             |
| `workflow_name`    | VARCHAR       | Nome do workflow associado ao ticket.                                                      |
| `workflow_version` | VARCHAR       | Versão do workflow utilizado no processo.                                                  |
| `schedule_title`   | VARCHAR       | Título do agendamento ou processo específico dentro do workflow.                           |
| `activity_id`      | INTEGER       | Identificador da atividade específica dentro do workflow.                                  |
| `start_at`         | TIMESTAMP     | Data e hora de início da atividade.                                                        |
| `end_at`           | TIMESTAMP     | Data e hora de término da atividade.                                                       |
| `status`           | VARCHAR       | Status atual da atividade (ex: em andamento, concluída, falhou).                           |
| `ticket_status`    | VARCHAR       | Status geral do ticket (ex: aberto, fechado, cancelado).                                   |
| `device`           | VARCHAR       | Dispositivo utilizado para realizar a atividade.                                           |
| `"values"`         | JSON          | Valores específicos relacionados à atividade ou ao ticket, armazenados em formato JSON.    |
| `user_name`        | VARCHAR       | Nome do usuário responsável pela execução da atividade ou aprovação.                       |

## Relacionamentos
- **`ticket_id`**: Chave primária que identifica de forma única cada registro dentro da tabela.
- A tabela pode ser referenciada por outras tabelas para rastrear o progresso dos tickets e atividades associadas dentro do workflow de aprovação e contratação.

## Exemplos de Uso
A tabela `fato_aprovacao_contratacao_goepick` é utilizada principalmente para:
- Monitorar o progresso das aprovações e contratações de fornecedores.
- Auditar as atividades realizadas no processo de contratação.
- Gerar relatórios de status e desempenho dos processos de aprovação.

## Considerações
- A coluna `"values"` armazena dados em formato JSON, que podem variar conforme a necessidade do workflow e da atividade específica. É importante garantir a consistência desses dados conforme a versão do workflow.

## Observações Adicionais
- A tabela é otimizada para consultas de auditoria e relatórios gerenciais, permitindo uma visão detalhada do processo de contratação desde a criação até a conclusão.

# Documentação da Tabela: `fato_cadastro_pedido_goepick`

## Descrição
A tabela `fato_cadastro_pedido_goepick` armazena os dados referentes ao cadastro de pedidos realizados por fornecedores no sistema Goepick. Esta tabela é essencial para o rastreamento dos pedidos desde a sua criação até a aprovação, permitindo o acompanhamento do fluxo de trabalho e das atividades relacionadas.

## Estrutura da Tabela

| Nome da Coluna     | Tipo de Dados | Descrição                                                                                  |
|--------------------|---------------|--------------------------------------------------------------------------------------------|
| `ticket_id`        | INTEGER       | Identificador único do ticket relacionado ao pedido.                                       |
| `comentarios`      | TEXT          | Comentários adicionais fornecidos pelo requisitante ou pelo sistema durante o cadastro.    |
| `codigo_fornecedor`| VARCHAR       | Código único que identifica o fornecedor responsável pelo pedido.                          |
| `nome_requisitante`| VARCHAR       | Nome do requisitante que realizou o pedido.                                                |
| `numero_pedido`    | VARCHAR       | Número de identificação do pedido no sistema.                                              |
| `workflow_name`    | VARCHAR       | Nome do workflow associado ao cadastro do pedido.                                          |
| `workflow_version` | VARCHAR       | Versão do workflow utilizado para o cadastro do pedido.                                    |
| `schedule_title`   | VARCHAR       | Título do agendamento ou processo específico dentro do workflow relacionado ao pedido.     |
| `activity_id`      | INTEGER       | Identificador da atividade específica dentro do workflow.                                  |
| `start_at`         | TIMESTAMP     | Data e hora de início da atividade de cadastro do pedido.                                  |
| `end_at`           | TIMESTAMP     | Data e hora de término da atividade de cadastro do pedido.                                 |
| `status`           | VARCHAR       | Status atual da atividade de cadastro (ex: em andamento, concluída, falhou).               |
| `ticket_status`    | VARCHAR       | Status geral do ticket (ex: aberto, fechado, cancelado).                                   |
| `device`           | VARCHAR       | Dispositivo utilizado para realizar a atividade de cadastro.                               |
| `"values"`         | JSON          | Valores específicos relacionados ao pedido, armazenados em formato JSON.                   |
| `user_name`        | VARCHAR       | Nome do usuário responsável pela execução da atividade de cadastro.                        |

## Relacionamentos
- **`ticket_id`**: Chave primária que identifica de forma única cada registro dentro da tabela.
- A tabela pode ser referenciada por outras tabelas para acompanhar o histórico e as alterações realizadas durante o cadastro do pedido.

## Exemplos de Uso
A tabela `fato_cadastro_pedido_goepick` é utilizada principalmente para:
- Rastrear a criação e cadastro de pedidos de fornecedores.
- Auditar o processo de cadastro para garantir conformidade e consistência.
- Gerar relatórios sobre o status e desempenho dos pedidos cadastrados no sistema.

## Considerações
- A coluna `"values"` armazena dados em formato JSON, que podem variar conforme o workflow e as características específicas de cada pedido. É importante validar esses dados para manter a consistência e integridade das informações.

## Observações Adicionais
- A tabela é otimizada para consultas e relatórios gerenciais, facilitando o acompanhamento dos pedidos e a análise do fluxo de trabalho relacionado ao cadastro de pedidos.

# Documentação da Tabela: `fato_pedidos_cancelados`

## Descrição
A tabela `fato_pedidos_cancelados` armazena informações detalhadas sobre os pedidos de fornecedores que foram cancelados dentro do sistema Goepick. Esta tabela permite o rastreamento dos motivos de cancelamento, o status do workflow associado, e as atividades realizadas até o cancelamento.

## Estrutura da Tabela

| Nome da Coluna     | Tipo de Dados | Descrição                                                                                  |
|--------------------|---------------|--------------------------------------------------------------------------------------------|
| `ticket_id`        | INTEGER       | Identificador único do ticket relacionado ao pedido cancelado.                             |
| `workflow_name`    | VARCHAR       | Nome do workflow associado ao pedido cancelado.                                            |
| `workflow_version` | VARCHAR       | Versão do workflow utilizado no processo de cancelamento.                                  |
| `schedule_title`   | VARCHAR       | Título do agendamento ou processo específico dentro do workflow relacionado ao cancelamento.|
| `activity_id`      | INTEGER       | Identificador da atividade específica dentro do workflow até o cancelamento.               |
| `start_at`         | TIMESTAMP     | Data e hora de início da atividade que resultou no cancelamento.                           |
| `end_at`           | TIMESTAMP     | Data e hora de término da atividade que resultou no cancelamento.                          |
| `status`           | VARCHAR       | Status atual da atividade de cancelamento (ex: em andamento, concluída, falhou).           |
| `ticket_status`    | VARCHAR       | Status geral do ticket (ex: cancelado, pendente).                                          |
| `device`           | VARCHAR       | Dispositivo utilizado para realizar a atividade de cancelamento.                           |
| `"values"`         | JSON          | Valores específicos relacionados ao cancelamento do pedido, armazenados em formato JSON.   |
| `user_name`        | VARCHAR       | Nome do usuário responsável pela execução da atividade de cancelamento.                    |

## Relacionamentos
- **`ticket_id`**: Chave primária que identifica de forma única cada registro dentro da tabela.
- A tabela pode ser referenciada por outras tabelas para auditorias e análises do motivo de cancelamento de pedidos.

## Exemplos de Uso
A tabela `fato_pedidos_cancelados` é utilizada principalmente para:
- Rastrear os motivos e processos que levaram ao cancelamento de pedidos de fornecedores.
- Auditar as atividades relacionadas ao cancelamento de pedidos para garantir conformidade.
- Gerar relatórios de análise sobre os cancelamentos, permitindo a identificação de padrões ou problemas recorrentes.

## Considerações
- A coluna `"values"` armazena dados em formato JSON, que podem variar conforme o workflow e as características específicas de cada pedido cancelado. É essencial validar esses dados para manter a consistência e integridade das informações.

## Observações Adicionais
- A tabela é otimizada para consultas e relatórios gerenciais, proporcionando uma visão detalhada do fluxo de trabalho até o cancelamento e ajudando a identificar áreas para melhorias no processo.


# Documentação da Tabela: `fato_requisicao_solicitacao`

## Descrição
A tabela `fato_requisicao_solicitacao` armazena informações detalhadas sobre as requisições e solicitações realizadas no sistema Goepick. Essa tabela abrange desde a descrição do pedido até os detalhes financeiros e logísticos, permitindo o acompanhamento completo das solicitações desde a criação até o seu fechamento.

## Estrutura da Tabela

| Nome da Coluna                | Tipo de Dados | Descrição                                                                                  |
|-------------------------------|---------------|--------------------------------------------------------------------------------------------|
| `ticket_id`                   | INTEGER       | Identificador único do ticket relacionado à requisição ou solicitação.                     |
| `descricao`                   | TEXT          | Descrição detalhada da solicitação ou requisição.                                          |
| `centro_custo`                | VARCHAR       | Código ou identificador do centro de custo associado à requisição.                         |
| `data_inicio`                 | DATE          | Data de início da solicitação ou requisição.                                               |
| `data_termino`                | DATE          | Data de término da solicitação ou requisição.                                              |
| `email_requisitante`          | VARCHAR       | E-mail do requisitante que realizou a solicitação.                                         |
| `empresa`                     | VARCHAR       | Nome da empresa relacionada à solicitação ou requisição.                                   |
| `"op/ct"`                     | VARCHAR       | Código de operação ou contrato relacionado à solicitação.                                  |
| `condicao_pagamento`          | VARCHAR       | Condição de pagamento acordada para a solicitação ou requisição.                           |
| `projeto`                     | VARCHAR       | Identificação do projeto ao qual a solicitação está vinculada.                             |
| `nome_projeto`                | VARCHAR       | Nome do projeto relacionado à solicitação.                                                 |
| `nucleo`                      | VARCHAR       | Núcleo responsável pela solicitação ou requisição.                                         |
| `tipo_contratacao_produto`    | VARCHAR       | Tipo de contratação ou produto envolvido na solicitação.                                   |
| `tipo_contratacao`            | VARCHAR       | Especificação do tipo de contratação realizada.                                            |
| `valor`                       | DECIMAL       | Valor total da solicitação ou requisição.                                                  |
| `valor_unitario`              | DECIMAL       | Valor unitário dos produtos ou serviços solicitados.                                       |
| `valor_influenciador`         | DECIMAL       | Valor relacionado ao influenciador, se aplicável.                                          |
| `user_name`                   | VARCHAR       | Nome do usuário responsável pela criação da solicitação ou requisição.                     |
| `razao_nome`                  | VARCHAR       | Razão social ou nome completo da entidade ou indivíduo relacionado à solicitação.          |
| `"Produto / Serviço"`         | VARCHAR       | Descrição do produto ou serviço solicitado.                                                |

## Relacionamentos
- **`ticket_id`**: Chave primária que identifica de forma única cada registro dentro da tabela.
- A tabela pode ser referenciada por outras tabelas e relatórios para obter informações detalhadas sobre as requisições e solicitações, incluindo aspectos financeiros e operacionais.

## Exemplos de Uso
A tabela `fato_requisicao_solicitacao` é utilizada principalmente para:
- Rastrear todas as solicitações e requisições realizadas dentro do sistema.
- Monitorar o desempenho e a conformidade das requisições em relação aos centros de custo e condições de pagamento.
- Gerar relatórios financeiros e operacionais detalhados sobre as solicitações realizadas.

## Considerações
- A tabela contém campos que capturam tanto informações financeiras quanto operacionais, sendo essencial para o acompanhamento completo do ciclo de vida das requisições.
- Os campos `valor`, `valor_unitario`, e `valor_influenciador` devem ser validados para garantir a precisão dos relatórios financeiros.

## Observações Adicionais
- A tabela é estruturada para suportar consultas complexas e relatórios detalhados, fornecendo uma visão abrangente das solicitações e permitindo a identificação de padrões ou áreas que necessitem de melhorias no processo de requisição.


# Documentação da Tabela: `fato_rateio_gipview`

## Descrição
A tabela `fato_rateio_gipview` é originada do sistema Gipview e é utilizada para determinar a porcentagem de alocação de recursos por agência e núcleos. Essa tabela é fundamental para o rastreamento e análise da distribuição de colaboradores e suas respectivas alocações dentro da empresa.

## Estrutura da Tabela

| Nome da Coluna            | Tipo de Dados | Descrição                                                                                  |
|---------------------------|---------------|--------------------------------------------------------------------------------------------|
| `nome`                    | VARCHAR       | Nome completo do colaborador alocado.                                                      |
| `cpf`                     | VARCHAR       | CPF do colaborador alocado.                                                                |
| `empresa`                 | VARCHAR       | Nome da empresa à qual o colaborador está vinculado.                                       |
| `cod_nucleo`              | VARCHAR       | Código do núcleo ao qual o colaborador está alocado.                                        |
| `nucleo`                  | VARCHAR       | Nome do núcleo ao qual o colaborador está alocado.                                         |
| `percentual`              | DECIMAL       | Percentual de alocação do colaborador no núcleo específico.                                |
| `email`                   | VARCHAR       | E-mail do colaborador alocado.                                                             |
| `relacao`                 | VARCHAR       | Relação do colaborador com a empresa (ex: CLT, PJ, estagiário).                            |
| `origem`                  | VARCHAR       | Origem das informações sobre a alocação do colaborador.                                    |
| `data_hora_sincronizacao` | TIMESTAMP     | Data e hora da última sincronização dos dados com o sistema Gipview.                       |
| `data_exportacao_select`  | TIMESTAMP     | Data e hora da exportação dos dados para o banco de dados atual.                           |

## Relacionamentos
- **`cpf`**: Chave primária que identifica de forma única cada colaborador dentro da tabela.
- A tabela pode ser referenciada por outras tabelas e relatórios para obter informações detalhadas sobre as alocações de recursos, facilitando a análise da distribuição por núcleos e agências.

## Exemplos de Uso
A tabela `fato_rateio_gipview` é utilizada principalmente para:
- Monitorar e analisar a distribuição de colaboradores por agências e núcleos, de acordo com a porcentagem de alocação.
- Gerar relatórios gerenciais que ajudam a entender a alocação de recursos e a eficiência operacional dos núcleos e agências.
- Verificar a conformidade das alocações em relação às metas e planos de alocação de recursos da empresa.

## Considerações
- A coluna `percentual` deve ser validada para garantir que os valores de alocação estejam corretos e somem 100% para cada colaborador onde aplicável.
- Os dados de sincronização e exportação (`data_hora_sincronizacao`, `data_exportacao_select`) são cruciais para garantir que os relatórios e análises estejam baseados nas informações mais recentes.

## Observações Adicionais
- A tabela é projetada para suportar análises detalhadas da alocação de recursos, ajudando a identificar áreas que necessitem de ajuste ou realocação de pessoal para otimização das operações.


# Documentação da Tabela: `fato_op`

## Descrição
A tabela `fato_op` armazena informações detalhadas sobre as oportunidades de negócios geradas no sistema JobOne a partir de 1º de janeiro de 2023. Esta tabela é essencial para o rastreamento das oportunidades desde a sua criação até o fechamento, permitindo a análise de desempenho, status, e probabilidade de sucesso das oportunidades de vendas.

## Estrutura da Tabela

| Nome da Coluna         | Tipo de Dados | Descrição                                                                                  |
|------------------------|---------------|--------------------------------------------------------------------------------------------|
| `oportunidade_id`      | INTEGER       | Identificador único da oportunidade no sistema.                                            |
| `empresa_id`           | INTEGER       | Identificador da empresa associada à oportunidade.                                         |
| `cliente_id`           | INTEGER       | Identificador do cliente relacionado à oportunidade.                                       |
| `cenario_escolhido_id` | INTEGER       | Identificador do cenário escolhido para a oportunidade.                                    |
| `numero`               | VARCHAR       | Número identificador da oportunidade.                                                      |
| `nome`                 | VARCHAR       | Nome da oportunidade ou descrição breve.                                                   |
| `data_entrada`         | DATE          | Data de entrada da oportunidade no sistema.                                                |
| `origem`               | VARCHAR       | Origem da oportunidade (ex: indicação, marketing, cold call).                              |
| `tipo_negocio`         | VARCHAR       | Tipo de negócio relacionado à oportunidade (ex: nova venda, upsell, renovação).            |
| `flag_conflito`        | BOOLEAN       | Indica se a oportunidade possui algum tipo de conflito (ex: conflito de interesse).         |
| `status`               | VARCHAR       | Status atual da oportunidade (ex: em andamento, concluída, perdida).                       |
| `data_status`          | DATE          | Data da última atualização do status da oportunidade.                                      |
| `tipo_conc`            | VARCHAR       | Tipo de concorrência envolvida na oportunidade (ex: direta, indireta).                     |
| `perda_para`           | VARCHAR       | Identificação do concorrente para o qual a oportunidade foi perdida, se aplicável.         |
| `motivo_status`        | VARCHAR       | Motivo associado ao status atual da oportunidade (ex: motivo de perda).                    |
| `valor_oportun`        | DECIMAL       | Valor financeiro estimado da oportunidade.                                                 |
| `perc_prob_fech`       | DECIMAL       | Percentual de probabilidade de fechamento da oportunidade.                                 |
| `data_prov_fech`       | DATE          | Data prevista para o fechamento da oportunidade.                                           |
| `data_prox_int`        | DATE          | Data da próxima interação ou contato relacionado à oportunidade.                           |
| `tipo_contrato_id`     | INTEGER       | Identificador do tipo de contrato associado à oportunidade.                                |
| `usuario_resp_id`      | INTEGER       | Identificador do usuário responsável pela oportunidade.                                    |
| `unid_negocio_resp_id` | INTEGER       | Identificador da unidade de negócio responsável pela oportunidade.                         |

## Relacionamentos
- **`oportunidade_id`**: Chave primária que identifica de forma única cada oportunidade dentro da tabela.
- A tabela pode ser referenciada por outras tabelas e relatórios para analisar o desempenho das oportunidades de vendas, o status, e a evolução ao longo do tempo.

## Exemplos de Uso
A tabela `fato_op` é utilizada principalmente para:
- Monitorar o pipeline de vendas e o status das oportunidades em aberto.
- Analisar as razões de perda ou ganho de oportunidades, permitindo ajustes nas estratégias comerciais.
- Gerar relatórios gerenciais sobre o desempenho de vendas, previsão de receita, e eficácia das equipes de vendas.

## Considerações
- A coluna `valor_oportun` deve ser validada para garantir a precisão dos relatórios financeiros e previsões de receita.
- Os campos `data_status`, `data_prov_fech`, e `data_prox_int` são cruciais para o gerenciamento do tempo e o acompanhamento das interações com o cliente.

## Observações Adicionais
- A tabela é otimizada para suportar consultas complexas e relatórios detalhados, ajudando na análise do ciclo de vida das oportunidades desde a sua criação até o fechamento ou perda.


# Documentação da Tabela: `historico_status_op`

## Descrição
A tabela `historico_status_op` armazena o histórico das mudanças de status das oportunidades registradas na tabela `fato_op`. Esta tabela é alimentada por uma trigger que captura qualquer alteração no status das oportunidades, registrando o início e o fim de cada status, bem como o responsável pela alteração e a unidade de negócio associada.

## Estrutura da Tabela

| Nome da Coluna         | Tipo de Dados | Descrição                                                                                  |
|------------------------|---------------|--------------------------------------------------------------------------------------------|
| `historico_id`         | SERIAL        | Identificador único do registro no histórico.                                              |
| `oportunidade_id`      | INTEGER       | Identificador da oportunidade cuja mudança de status está sendo registrada.                |
| `status`               | VARCHAR       | Status da oportunidade no momento da alteração.                                            |
| `data_inicio`          | TIMESTAMP     | Data e hora em que o status foi definido.                                                  |
| `data_fim`             | TIMESTAMP     | Data e hora em que o status foi alterado para um novo valor.                               |
| `usuario_resp_id`      | INTEGER       | Identificador do usuário responsável pela alteração do status.                             |
| `unid_negocio_resp_id` | INTEGER       | Identificador da unidade de negócio responsável pela oportunidade no momento da alteração. |

## Funcionamento da Trigger

### Trigger: `trigger_update_status_history`

- **Objetivo:** A trigger `trigger_update_status_history` é acionada após qualquer atualização na coluna `status` da tabela `fato_op`. 
- **Ação:** Quando o status de uma oportunidade é alterado:
  1. Um novo registro é inserido na tabela `historico_status_op`, contendo o `oportunidade_id`, o novo `status`, a `data_status` como `data_inicio`, o `usuario_resp_id`, e o `unid_negocio_resp_id`.
  2. O registro anterior para a mesma `oportunidade_id`, onde o `status` era diferente e a `data_fim` está em aberto (`NULL`), é atualizado com a `data_status` da nova alteração, encerrando o período daquele status.

### Função: `update_status_history()`
- **Função:** A função `update_status_history()` é responsável por executar a lógica descrita acima:
  1. Insere um novo registro no `historico_status_op`.
  2. Atualiza o registro anterior do mesmo `oportunidade_id` para definir a `data_fim` com a data do novo status.

## Exemplos de Uso
A tabela `historico_status_op` é utilizada para:
- Rastrear todas as mudanças de status das oportunidades ao longo do tempo.
- Fornecer uma visão detalhada da evolução das oportunidades, permitindo análise de duração de cada estágio.
- Auditar o processo de vendas e identificar pontos de ineficiência ou gargalos, analisando o tempo gasto em cada status.

## Considerações
- A coluna `data_fim` é atualizada pela trigger somente quando ocorre uma nova alteração de status. Portanto, registros com `data_fim` igual a `NULL` indicam que a oportunidade está atualmente naquele status.
- A precisão das datas e a consistência dos registros dependem da correta configuração da trigger e da função associada.

## Observações Adicionais
- A tabela `historico_status_op` é essencial para auditorias e relatórios de performance das equipes de vendas, permitindo uma análise profunda do ciclo de vida das oportunidades.

# Documentação da Tabela: `fato_horas_jobone`

## Descrição
A tabela `fato_horas_jobone` armazena dados detalhados sobre as horas trabalhadas pelos colaboradores, integrando informações das tabelas de `apontam_data`, `apontam_hora`, e `tipo_apontam` do sistema JobOne. Esta tabela é utilizada para monitorar e analisar o tempo dedicado a diferentes tarefas, projetos, e clientes, facilitando o controle de produtividade e alocação de recursos.

## Estrutura da Tabela

| Nome da Coluna         | Tipo de Dados | Descrição                                                                                  |
|------------------------|---------------|--------------------------------------------------------------------------------------------|
| `apontam_hora_id`      | INTEGER       | Identificador único da entrada de hora apontada.                                           |
| `apontam_data_id`      | INTEGER       | Identificador da data associada ao apontamento de horas.                                   |
| `tipo_apontam_id`      | INTEGER       | Identificador do tipo de apontamento (ex: horas extras, horas normais).                    |
| `job_id`               | INTEGER       | Identificador do job ou projeto relacionado ao apontamento de horas.                       |
| `cliente_id`           | INTEGER       | Identificador do cliente para o qual o job foi realizado.                                  |
| `papel_id`             | INTEGER       | Identificador do papel ou função desempenhada pelo colaborador.                            |
| `tarefa_id`            | INTEGER       | Identificador da tarefa específica associada ao apontamento de horas.                      |
| `horas`                | DECIMAL       | Quantidade de horas trabalhadas apontadas.                                                 |
| `obs`                  | TEXT          | Observações adicionais sobre o apontamento de horas.                                       |
| `status`               | VARCHAR       | Status do apontamento (ex: aprovado, pendente, rejeitado).                                 |
| `oportunidade_id`      | INTEGER       | Identificador da oportunidade relacionada ao job.                                          |
| `unid_neg_cli_id`      | INTEGER       | Identificador da unidade de negócio do cliente.                                            |
| `unid_neg_job_id`      | INTEGER       | Identificador da unidade de negócio do job.                                                |
| `unid_neg_usu_id`      | INTEGER       | Identificador da unidade de negócio do usuário (colaborador).                              |
| `contrato_id`          | INTEGER       | Identificador do contrato relacionado ao job ou oportunidade.                              |
| `usuario_id`           | INTEGER       | Identificador do usuário (colaborador) que realizou o apontamento de horas.                |
| `cargo_id`             | INTEGER       | Identificador do cargo do colaborador no momento do apontamento.                           |
| `"DATA"`               | DATE          | Data do apontamento de horas.                                                              |
| `codigo`               | VARCHAR       | Código associado ao apontamento, para referência interna ou relatórios.                    |
| `nome`                 | VARCHAR       | Nome do colaborador que realizou o apontamento.                                            |
| `flag_ativo`           | BOOLEAN       | Indica se o colaborador estava ativo no momento do apontamento de horas.                   |

## Relacionamentos
- **`apontam_hora_id`**: Chave primária que identifica de forma única cada entrada de hora apontada.
- A tabela pode ser referenciada para gerar relatórios detalhados sobre as horas trabalhadas, distribuídas por clientes, projetos, unidades de negócio e colaboradores.

## Exemplos de Uso
A tabela `fato_horas_jobone` é utilizada principalmente para:
- Monitorar o tempo gasto pelos colaboradores em diferentes projetos e tarefas.
- Analisar a eficiência e produtividade das equipes, bem como a utilização de recursos.
- Gerar relatórios financeiros sobre a alocação de horas trabalhadas para faturamento e controle de contratos.

## Considerações
- A coluna `horas` deve ser validada para garantir a precisão no cálculo do tempo trabalhado e evitar discrepâncias nos relatórios financeiros.
- O campo `status` é essencial para a aprovação e controle das horas apontadas, permitindo a gestão do fluxo de aprovação.

## Observações Adicionais
- A tabela é fundamental para a análise operacional e financeira dos projetos, permitindo uma visão detalhada do esforço dedicado a cada tarefa e cliente. Ela suporta consultas complexas para otimizar a gestão de recursos humanos e operacionais.

