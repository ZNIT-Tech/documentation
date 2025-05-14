# Combustão Móvel

<details>
  <summary><strong><h2>Dados obrigatórios para cálculo</strong></summary>

#### Cálculo de emissões por tipo e ano de fabricação da frota de veículos no ano

Campo no Supabase|Valores GHG|
|---|---|
`categoria_de_emissoes`|_COMBUSTÃO MÓVEL 1_
`date`|Data da referência _(yyyy-mm-dd hh:mm:ss)_|
[tipo_veiculo_frota](https://github.com/ZNIT-Tech/documentation/blob/main/Veiculos%20da%20Frota.md)|Tipo da frota de veículos|
`ano_frota`|Ano da frota|
`consumo_anual`|Consumo anual de combustível _(litros)_|
`consumo_mensal`|Consumo mensal de combustível _(litros)_|

<sub><em>Obs.: Inserir apenas consumo mensal ou consumo anual</em></sub>

---
#### Cálculo de emissões por tipo de combustível no ano

Campo no Supabase|Valores GHG
|---|---|
`categoria_de_emissoes`|_COMBUSTÃO MÓVEL 2_
`date`|Data da referência _(yyyy-mm-dd hh:mm:ss)_|
[combustivel](https://github.com/ZNIT-Tech/documentation/blob/main/Combustiveis.md)|Tipo de combustível|
`consumo_anual`|Consumo anual _(litros/m³/kg)_|
`consumo_mensal`|Consumo referente ao mês de date _(litros/m³/kg)_|

<sub><em>Obs.: Inserir apenas consumo mensal ou consumo anual</em></sub>

---
#### Cálculo de emissões por distância percorrida no ano

Campo no Supabase|Valores GHG|
|---|---|
`categoria_de_emissoes`|_COMBUSTÃO MÓVEL 3_
`date`|Data da referência _(yyyy-mm-dd hh:mm:ss)_|
[tipo_veiculo_frota](https://github.com/ZNIT-Tech/documentation/blob/main/Veiculos%20da%20Frota.md)|Tipo da frota de veículos|
`ano_frota`|Ano da frota|
`ano_do_veculo`|Ano do veículo|
`consumo_anual`|Distância percorrida / ano  _(km)_|
`consumo_mensal`|Distância percorrida / mês referente a date _(km)_| 

<sub><em>Obs.: Inserir apenas consumo mensal ou consumo anual. Quant só é usado quando consumo_mensal e consumo_anual não forem preenchidos. Ano_do_veculo só utiliza quando ano_frota não for preenchido</em></sub>

#### Cálculo de emissões de gases de efeito estufa por transporte de carga por consumo de combustível no ano

Campo no Supabase|Valores GHG
|---|---|
`categoria_de_emissoes`|_COMBUSTÃO MÓVEL - HIDROVIARIO_
`date`|Data da referência _(yyyy-mm-dd hh:mm:ss)_|
[combustivel](https://github.com/ZNIT-Tech/documentation/blob/main/Combustiveis.md)|Tipo de combustível|
`consumo_anual`|Consumo anual _(litros)_|
`consumo_mensal`|Consumo referente ao mês de date _(litros)_|

<sub><em>Obs.: Inserir apenas consumo mensal ou consumo anual</em></sub>

#### Cálculo de emissões de gases de efeito estufa por transporte aéreo no ano

Campo no Supabase|Valores GHG
|---|---|
`categoria_de_emissoes`|_COMBUSTÃO MÓVEL - AEREO_
`date`|Data da referência _(yyyy-mm-dd hh:mm:ss)_|
[combustivel](https://github.com/ZNIT-Tech/documentation/blob/main/Combustiveis.md)|Tipo de combustível|
`consumo_anual`|Consumo anual _(litros)_|

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
