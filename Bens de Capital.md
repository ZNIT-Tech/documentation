# Bens de capital

<details>
  <summary><strong><h2>Dados obrigatórios para cálculo</strong></summary>

|Campo no Supabase	|Valores GHG|
|---|---|
`categoria_de_emissoes`|_BENS DE CAPITAL_|
|`date`|Data|
|`escopo`|Escopo|
|[id_bens_capital](https://github.com/ZNIT-Tech/documentation/blob/main/Lista%20de%20Bens%20de%20Capital.md)|ID da tabela de bens de capital|
|`quant`|Peso do produto _(t ou kg)_|
|`un`|Unidade de medida do peso _(t ou kg)_|
|`*fator_de_emisso_bruto`|*Fator de emissão bruto|
|`*fator_correcao_do_fator_emissao`|*Fator de correção de fator de emissao|
|`*fator_conv_un_medida`|*Fator de conversar de unidade de medida|

<sub><em>Obs.: *Valor não obrigatório, inserir apenas caso possua</em></sub>

|Campo no Supabase	|Valores GHG|
|---|---|
`categoria_de_emissoes`|_BENS DE CAPITAL - ECO_|
|`date`|Data|
|`escopo`|Escopo|
|`eco_product`|Activity_id|
|`quant`|Quantidade comprada|
|`un`|Unidade da compra|
|`*fator_de_emisso_bruto`|Fator bruto de emissão|
|`*fator_correcao_do_fator_emissao`|Fator de correção do fator de emissão|
|`*fator_conv_un_medida`|Fator de conversão da unidade de medida|

<sub><em>Obs.: *Valor não obrigatório, inserir apenas caso possua</em></sub>

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
`peso_nf`|Peso|
`endereco_do_experdidor`|Endereço do remetente|
`endereco_do_destinatrio`|Endereço do destinatário|


</details>
