# Energia Elétrica (Escolha de Compra)

<details>
  <summary><strong><h2>Dados obrigatórios para cálculo</strong></summary>

Campos no Supabase|Valores GHG|
|---|---|
`categoria_de_emissoes`|_ENERGIA ELETRICA (ESCOLHA DE COMPRA)_|
`date`|Data da referência _(yyyy-mm-dd hh:mm:ss)_|
`consumo_anual`|Eletricidade comprada anual _(MWh)_|
`consumo_mensal`|Eletricidade comprada / mês referente a date _(MWh)_|
[id_fonte_geracao_energia](https://github.com/ZNIT-Tech/documentation/blob/main/Fonte%20de%20Geracao%20de%20Energia.md)|Fonte de Geração de Energia|
[id_combustivel_termoeletrico](https://github.com/ZNIT-Tech/documentation/blob/main/Combustiveis%20Termoeletricos.md)|Combustível (caso fonte seja termoelétrica)|
`fator_co2`|Fator de CO2 fornecido pelo gerador _(tCO2 / MWh)_|
`fator_ch4`|Fator de CH4 fornecido pelo gerador _(tCH4 / MWh)_|
`fator_n2o`|Fator de N2O fornecido pelo gerador _(tN2O / MWh)_|
`fator_co2_bio`|Fator de CO2 biogênico|
`eficiencia_recuperacao`|Eficiência da planta geradora _(decimal <= 1.0)_|
`fator_personalizado`*|Utilizar fator provido _(true/false)_|

<sub><em>Obs.: Inserir apenas consumo mensal ou consumo anual. Eficiência padrão: 1.0 = 100%</em></sub>
<sub><em>Obs.: Colocar TRUE apenas quando tiver um valor inserido em fator de emissão de CO2, CH4 e N2O </em></sub>

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
