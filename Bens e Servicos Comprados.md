# Bens e Serviços Comprados

<details>
  <summary><strong><h2>Dados obrigatórios para cálculo</strong></summary>

|Campo no Supabase	|Valores GHG|
|---|---|
`categoria_de_emissoes`|_BENS E SERVIÇOS COMPRADOS_|
|[id_compra_produto](https://github.com/ZNIT-Tech/documentation/blob/main/Produtos%20e%20Servi%C3%A7os.md)*|Id do produto/serviço|
|`quant`|Quantidade comprada|
|`un`|Unidade da compra|
|`fator_de_emisso_bruto**`|Fator bruto de emissão|
|`fator_correcao_do_fator_emissao**`|Fator de correção do fator de emissão|
|`fator_conv_un_medida**`|Fator de conversão da unidade de medida|

<sub><em>Obs.: * Se CNPJ for 07882930000165, procurar em [Tabela de Produtos - Mitre](https://github.com/ZNIT-Tech/documentation/blob/main/Tabela%20de%20Produtos%20-%20Mitre.md) </em></sub>

<sub><em>Obs.: ** Valores não obrigatórios</em></sub>

Campo no Supabase|Valores GHG
|---|---|
`categoria_de_emissoes`|_BENS E SERVICOS COMPRADOS - COMBUSTAO MOVEL 2_
`date`|Data da referência _(yyyy-mm-dd hh:mm:ss)_|
[combustivel](https://github.com/ZNIT-Tech/documentation/blob/main/Combustiveis.md)|Tipo de combustível|
`consumo_anual`|Consumo anual _(litros/m³/kg)_|
`consumo_mensal`|Consumo referente ao mês de date _(litros, m³ ou kg)_|

<sub><em>Obs.: Inserir apenas consumo mensal ou consumo anual</em></sub>

</details>

---

<details>
  <summary><h2><strong>Dados complementares</strong></summary>

|Campo no Supabase|Valor|
|---|---|
|`cnpj_fornecedor`|CNPJ Fornecedor|
|`nome_fornecedor`|Nome Fornecedor|
`numero_do_documento`|Chave da NFe|
`natureza_da_operao`|Natureza da operação|
`cdigo_do_produto`|Codigo produto|
`ncm`|NCM|
`un`|Unidade de medida|
`quant`|Quantidade|
`peso_nf`|Peso|
`endereco_do_experdidor`|Endereço do remetente|
`endereco_do_destinatrio`|Endereço do destinatário|


</details>
