# Viagens a Negócios

<details>
  <summary><strong><h2>Dados obrigatórios para cálculo</strong></summary>

### Viagens em Aeronaves

#### Calculo de emissões por viagem a negócios em aeronaves de acordo aeroportos de origem e destino realizadas no ano

Campo no Supabase|Valores GHG|
|---|---|
`categoria_de_emissoes`|_VIAGENS A NEGÓCIOS - AEROPORTO - DISTANCIA_
`cnpj_usuario`|CNPJ da empresa|
`dist_percorrida`|Tipo de Viagem Aérea _(km)_|
`consumo_mensal`|Quilometragem do Passageiro _(km)_|

#### Calculo de emissões por viagem a negócios em aeronaves de acordo com quilômetros percorridos no ano

Campo no Supabase|Valores GHG|
|---|---|
`categoria_de_emissoes`|_VIAGENS A NEGÓCIOS - AEROPORTO_
[id_aeroporto_saida](https://github.com/ZNIT-Tech/documentation/blob/main/Aeroportos.md)|Partida|
[id_aeroporto_chegada](https://github.com/ZNIT-Tech/documentation/blob/main/Aeroportos.md)|Chegada|

### Transporte Público
Campo no Supabase|Valores GHG|
|---|---|
`categoria_de_emissoes`|_VIAGENS A NEGOCIOS_
`date`|Data da referência
[id_veiculo_viagem](https://github.com/ZNIT-Tech/documentation/blob/main/Transportes%20Publicos.md)|Tipo de transporte público|
`nro_passageiros`|Quantidade de Passageiros|
`dist_percorrida`|Distância Percorrida _(km)_|

### Viagens em automóveis

#### Cálculo de emissões de viagens a negócios realizadas em automóveis, por tipo e ano de fabricação da frota de veículos

Campo no Supabase|Valores GHG|
|---|---|
`categoria_de_emissoes`|_VIAGENS A NEGÓCIOS - AUTOMÓVEIS 1_
`date`|Data da referência _(yyyy-mm-dd hh:mm:ss)_|
[tipo_veiculo_frota](https://github.com/ZNIT-Tech/documentation/blob/main/Veiculos%20da%20Frota.md)|Tipo da frota de veículos|
`ano_frota`|Ano da frota|
`consumo_anual`|Consumo anual de combustível _(litros)_|
`consumo_mensal`|Consumo mensal de combustível _(litros)_|

<sub><em>Obs.: Inserir apenas consumo mensal ou consumo anual</em></sub>

---
#### Cálculo de emissões de viagens a negócios realizadas em automóveis por tipo de combustível no ano

Campo no Supabase|Valores GHG
|---|---|
`categoria_de_emissoes`|_VIAGENS A NEGÓCIOS - AUTOMÓVEIS 2_
`date`|Data da referência _(yyyy-mm-dd hh:mm:ss)_|
[combustivel](https://github.com/ZNIT-Tech/documentation/blob/main/Combustiveis.md)|Tipo de combustível|
`consumo_anual`|Consumo anual _(litros, km ou m³)_|
`consumo_mensal`|Consumo referente ao mês de date _(litros, km ou m³)_|

<sub><em>Obs.: Inserir apenas consumo mensal ou consumo anual</em></sub>

---
#### Cálculo de emissões de viagens a negócios realizadas em automóveis por distância percorrida no ano

Campo no Supabase|Valores GHG|
|---|---|
`categoria_de_emissoes`|_VIAGENS A NEGÓCIOS - AUTOMÓVEIS 3_
`date`|Data da referência _(yyyy-mm-dd hh:mm:ss)_|
[tipo_veiculo_frota](https://github.com/ZNIT-Tech/documentation/blob/main/Veiculos%20da%20Frota.md)|Tipo da frota de veículos|
`ano_frota`|Ano da frota|
`ano_do_veculo`|Ano do veículo|
`consumo_anual`|Distância percorrida / ano _(km)_|
`consumo_mensal`|Distância percorrida / mês referente a date _(km)_|

<sub><em>Obs.: Inserir apenas consumo mensal ou consumo anual. Quant só é usado quando consumo_mensal e consumo_anual não forem preenchidos. Ano_do_veculo só utiliza quando ano_frota não for preenchido</em></sub>

#### Cálculo de emissões de pernoite em viagens a negócios

Campo no Supabase|Valores GHG|
|---|---|
`categoria_de_emissoes`|_VIAGENS A NEGOCIO - PERNOITE_
`dias_trabalhados`|Número de noites|
`consumo_mensal`|Número de quartos|

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
