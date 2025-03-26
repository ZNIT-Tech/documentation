# Combustão Móvel

<details>
  <summary><strong>Dados obrigatórios para cálculo</strong></summary>

### Cálculo de emissões por tipo e ano de fabricação da frota de veículos no ano
Campos no Supabase|Valores GHG|
|---|---|
`categoria_de_emissoes`|"COMBUSTÃO MÓVEL 1"
`date`|Data da referência _(yyyy-mm-dd hh:mm:ss)_|
[tipo_veiculo_frota](https://github.com/ZNIT-Tech/documentation/blob/main/Veiculos%20da%20Frota.md)|Tipo da frota de veículos|
`ano_frota`|Ano da frota|
`consumo_anual`|Consumo anual de combustível|
`consumo_mensal`|Consumo mensal de combustível|

Obs.: Inserir apenas consumo mensal ou consumo anual

---
### Cálculo de emissões por tipo de combustível no ano
categoria_de_emissoes: ‘COMBUSTÃO MÓVEL 2’
Campos no Supabase|Valores GHG
|---|---|
`date`|Data da referência _(yyyy-mm-dd hh:mm:ss)_|
[combustivel](https://github.com/ZNIT-Tech/documentation/blob/main/Combustiveis.md)|Tipo de combustível|
`consumo_anual`|Consumo anual|
`consumo_mensal`|Consumo referente ao mês de date|

Obs.: Inserir apenas consumo mensal ou consumo anual

---
### Cálculo de emissões por distância percorrida no ano
categoria_de_emissoes: ‘COMBUSTÃO MÓVEL 3’
Campos no Supabase|Valores GHG|
|---|---|
`date`|Data da referência _(yyyy-mm-dd hh:mm:ss)_|
[tipo_veiculo_frota](https://github.com/ZNIT-Tech/documentation/blob/main/Veiculos%20da%20Frota.md)|Tipo da frota de veículos|
`ano_frota`|Ano da frota|
`ano_do_veculo`|Ano do veículo|
`consumo_anual`|Dias trabalhos no ano|
`consumo_mensal`|Distância percorrida / mês referente a date|
`quant`|Consumo Usado (mensal/anual)

Obs.: Inserir apenas consumo mensal ou consumo anual. Quant só é usado quando consumo_mensal e consumo_anual não forem preenchidos. Ano_do_veculo só utiliza quando ano_frota não for preenchido

</details>

---

<details>
  <summary><strong>Dados complementares</strong></summary>

|Campo no Supabase|Valor|
|---|---|
|cnpj_fornecedor|CNPJ Fornecedor|
|nome_fornecedor|Nome Fornecedor|

</details>
