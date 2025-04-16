# Residuos Sólidos

<details>
  <summary><strong><h2>Dados obrigatórios para cálculo</strong></summary>

#### Resíduos Sólidos
|Campo no Supabase	|Valores GHG|
|---|---|
`categoria_de_emissoes`|_RESÍDUOS SÓLIDOS_|
[id_uf](https://github.com/ZNIT-Tech/documentation/blob/main/Municipios.md)|
|`residuos_aterro`|Quantidade de Resíduos|
|`composicao_papelao`|Composição em decimal (ex: 0.5)|
|`composicao_textil`|Composição em decimal (1.0 = 100%)|
|`composicao_alimentar`|Composição em decimal (1.0 = 100%)|
|`composicao_madeira`|Composição em decimal (1.0 = 100%)|
|`composicao_jardim`|Composição em decimal (1.0 = 100%)|
|`composicao_fraldas`|Composição em decimal (1.0 = 100%)|
|`composicao_borracha`|Composição em decimal (1.0 = 100%)|
|`composicao_lodo_domestico`|Composição em decimal (1.0 = 100%)|
|`composicao_lodo_industrial`|Composição em decimal (1.0 = 100%)|
|`classificacao_ano`|A, B, C, D, E, F, G, H|
|`fracao_ch4_biogas`|Entre com o dado, entre 0 e 1 (Padrão = 0.5)|
|`recuperacao_metano`|sim ou nao|
|`eficiencia_recuperacao`||


#### Resíduos - IPCC
|Campo no Supabase	|Valores GHG|
|---|---|
`categoria_de_emissoes`|_RESIDUOS - IPCC_|
|`consumo_mensal`|Quantidade de Resíduos|
|[destino_residuo_ipcc](https://github.com/ZNIT-Tech/documentation/blob/main/Destino%20Residuos.md)|Destino de Residuos|
|[residuo_ipcc](https://github.com/ZNIT-Tech/documentation/blob/main/Residuos.md)|Tipo de Resíduo|
|`un`|Unidade de medida (_t_ ou _kg_)|

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
