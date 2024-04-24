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

Esta tabela contém informações sobre clientes no contexto de publicidade, incluindo detalhes como identificação, situação, nome, informações de contato e endereço.

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

Esta tabela contém informações sobre fornecedores no contexto de publicidade, incluindo detalhes como identificação, situação, nome, informações de contato e endereço.

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

Esta tabela contém informações sobre empresas públicas, incluindo detalhes como código, razão social, nome e número de inscrição.

| Coluna       | Descrição                              |
|--------------|----------------------------------------|
| codigo       | Código único da empresa.               |
| razao_soc    | Razão social da empresa.               |
| nome         | Nome da empresa.                       |
| inscricao    | Número de inscrição da empresa.        |


# Documentação da Tabela `fato_pedidos_cap_publi`

Esta tabela contém informações sobre contas a pagar do nosso erp publi

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


