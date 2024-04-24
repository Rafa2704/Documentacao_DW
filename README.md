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





