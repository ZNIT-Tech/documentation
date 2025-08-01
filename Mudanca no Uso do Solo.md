# Mudança no Uso do Solo

<details>
  <summary><strong><h2>Dados obrigatórios para cálculo</strong></summary>

Campo no Supabase|Valor GHG|
|---|---|
`categoria_de_emissoes`|_MUDANCA USO SOLO_|
`date`|Data da referência _(yyyy-mm-dd hh:mm:ss)_|
|`escopo`|Escopo|
[id_estado](https://github.com/ZNIT-Tech/documentation/blob/main/Estados.md)|id_estado|
[id_uso_anterior_solo](https://github.com/ZNIT-Tech/documentation/blob/main/Lista%20de%20usos%20do%20solo.md)|id_uso_anterior_solo|
[id_uso_posterior_solo](https://github.com/ZNIT-Tech/documentation/blob/main/Lista%20de%20usos%20do%20solo.md)|id_uso_posterior_solo|
[id_bioma_anterior](https://github.com/ZNIT-Tech/documentation/blob/main/Lista%20de%20Biomas.md)|id_bioma_anterior|
`consumo_mensal* `|Área de MUS _(ha)_|
`classificacao_ano `|Tipo de vegetacao anterior _(Primaria / Secundaria)_|
`efluente_lancado_ambiente `|Fitonomia anterior _(True/False)_|
[id_bioma_posterior](https://github.com/ZNIT-Tech/documentation/blob/main/Lista%20de%20Biomas.md)|id_bioma_posterior|
`efluente_tratamento_aplicado`|Dados primarios sobre estoque de carbono|
`ch4_recuperado`|Estoque de carbono do solo _(tC/ha)_|
`fator_n2o_n`| Estoque de carbono da biomassa _(tC/ha)_|
[efluente_unidade](https://github.com/ZNIT-Tech/documentation/blob/main/Vegetacoes.md)|Detalhamento da Vegetacao|
|`fator_personalizado* `|Caso queira utilizar metodologia simples _(True/False)_|

<sub><em>Obs*.: Caso opte pelo calculo de metodologia simples, preencher apenas fator_personalizado com True e consumo_mensal com quantidade de árvores</em></sub>

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
