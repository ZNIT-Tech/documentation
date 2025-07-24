# Transporte e Distribuição (Upstream)

<details>
  <summary><strong><h2>Dados obrigatórios para cálculo</strong></summary>

#### Cálculo de emissões por tipo e ano de fabricação da frota de veículos no ano

Campo no Supabase|Valores GHG|
|---|---|
`categoria_de_emissoes`|_TRANSPORTE E DISTRIBUIÇÃO (UPSTREAM) 1_
`date`|Data da referência _(yyyy-mm-dd hh:mm:ss)_|
|`escopo`|Escopo|
[tipo_veiculo_frota](https://github.com/ZNIT-Tech/documentation/blob/main/Veiculos%20da%20Frota.md)|Tipo da frota de veículos|
`ano_frota`|Ano da frota|
`consumo_anual`|Consumo anual de combustível _(litros)_|
`consumo_mensal`|Consumo mensal de combustível _(litros)_|

<sub><em>Obs.: Inserir apenas consumo mensal ou consumo anual</em></sub>

---
#### Cálculo de emissões por tipo de combustível no ano

Campo no Supabase|Valores GHG
|---|---|
`categoria_de_emissoes`|_TRANSPORTE E DISTRIBUIÇÃO (UPSTREAM) 2_
`date`|Data da referência _(yyyy-mm-dd hh:mm:ss)_|
|`escopo`|Escopo|
[combustivel](https://github.com/ZNIT-Tech/documentation/blob/main/Combustiveis.md)|Tipo de combustível|
`consumo_anual`|Consumo anual _(litros, m³ ou kg)_|
`consumo_mensal`|Consumo referente ao mês de date _(litros, m³ ou kg)_|

<sub><em>Obs.: Inserir apenas consumo mensal ou consumo anual</em></sub>

---
#### Cálculo de emissões por distância percorrida e peso da carga fracionada transportada (caminhões e veículos de carga) no ano

Campos no Supabase|Valores GHG|
|---|---|
`categoria_de_emissoes`|_TRANSPORTE E DISTRIBUIÇÃO (UPSTREAM) 3_|
|`date`|Data|
|`escopo`|Escopo|
[Id_caminhao](https://github.com/ZNIT-Tech/documentation/blob/main/Caminhoes.md)|Tipo de veículo|
`carga_transportada`|Carga Transportada _(t)_|
`consumo_anual`|Distância Percorrida _(km)_|


---
#### Cálculo de emissões por distância percorrida e idade da frota no ano

Campo no Supabase|Valores GHG|
|---|---|
`categoria_de_emissoes`|_TRANSPORTE E DISTRIBUIÇÃO (UPSTREAM) 4_
`date`|Data da referência _(yyyy-mm-dd hh:mm:ss)_|
|`escopo`|Escopo|
[tipo_veiculo_frota](https://github.com/ZNIT-Tech/documentation/blob/main/Veiculos%20da%20Frota.md)|Tipo da frota de veículos|
`ano_frota`|Ano da frota|
`ano_do_veculo`|Ano do veículo|
`consumo_anual`|Distância percorrida anual _(km)_|
`consumo_mensal`|Distância percorrida / mês referente a date _(km)_|

<sub><em>Obs.: Inserir apenas consumo mensal ou consumo anual. Quant só é usado quando consumo_mensal e consumo_anual não forem preenchidos. Ano_do_veculo só utiliza quando ano_frota não for preenchido</em></sub>

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
