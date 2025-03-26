# Combustão Móvel

<details>
  <summary><strong><h2>Dados obrigatórios para cálculo</strong></summary>

#### Cálculo de emissões por tipo e ano de fabricação da frota de veículos no ano

Campo no Supabase|Valores GHG|
|---|---|
`categoria_de_emissoes`|"COMBUSTÃO MÓVEL 1"
`date`|Data da referência _(yyyy-mm-dd hh:mm:ss)_|
[tipo_veiculo_frota](https://github.com/ZNIT-Tech/documentation/blob/main/Veiculos%20da%20Frota.md)|Tipo da frota de veículos|
`ano_frota`|Ano da frota|
`consumo_anual`|Consumo anual de combustível|
`consumo_mensal`|Consumo mensal de combustível|

<sub><em>Obs.: Inserir apenas consumo mensal ou consumo anual</em></sub>

---
#### Cálculo de emissões por tipo de combustível no ano

Campo no Supabase|Valores GHG
|---|---|
`categoria_de_emissoes`|"COMBUSTÃO MÓVEL 2"
`date`|Data da referência _(yyyy-mm-dd hh:mm:ss)_|
[combustivel](https://github.com/ZNIT-Tech/documentation/blob/main/Combustiveis.md)|Tipo de combustível|
`consumo_anual`|Consumo anual|
`consumo_mensal`|Consumo referente ao mês de date|

<sub><em>Obs.: Inserir apenas consumo mensal ou consumo anual</em></sub>

---
#### Cálculo de emissões por distância percorrida no ano

Campo no Supabase|Valores GHG|
|---|---|
`categoria_de_emissoes`|"COMBUSTÃO MÓVEL 3"
`date`|Data da referência _(yyyy-mm-dd hh:mm:ss)_|
[tipo_veiculo_frota](https://github.com/ZNIT-Tech/documentation/blob/main/Veiculos%20da%20Frota.md)|Tipo da frota de veículos|
`ano_frota`|Ano da frota|
`ano_do_veculo`|Ano do veículo|
`consumo_anual`|Dias trabalhos no ano|
`consumo_mensal`|Distância percorrida / mês referente a date|
`quant`|Consumo Usado (mensal/anual)

<sub><em>Obs.: Inserir apenas consumo mensal ou consumo anual. Quant só é usado quando consumo_mensal e consumo_anual não forem preenchidos. Ano_do_veculo só utiliza quando ano_frota não for preenchido</em></sub>

</details>

---

<details>
  <summary><h2><strong>Dados complementares</strong></summary>

|Campo no Supabase|Valor|
|---|---|
|cnpj_fornecedor|CNPJ Fornecedor|
|nome_fornecedor|Nome Fornecedor|
numero_do_documento|Chave da NFe|
natureza_da_operao|Natureza da operação|
cdigo_do_produto|Codigo produto|
ncm|NCM|
un|Unidade de medida|
quant|Quantidade|
peso_nf|Peso|
endereco_do_experdidor|Endereço do remetente|
endereco_do_destinatrio|Endereço do destinatário|


</details>
