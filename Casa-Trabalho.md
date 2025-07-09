# Emissões casa-trabalho

<details>
  <summary><strong><h2>Dados obrigatórios para cálculo</strong></summary>

#### Transporte Público

Campo no Supabase|Valor GHG|
|---|---|
`categoria_de_emissoes`|_TRABALHO-CASA_|
`date`|Data da referência _(yyyy-mm-dd hh:mm:ss)_|
[id_veiculo_viagem](https://github.com/ZNIT-Tech/documentation/blob/main/Transportes%20Publicos.md)|Tipo de transporte público|
`nro_passageiros`|Número de Passageiros|
`dist_percorrida`|Distância Percorrida _(km)_ por trecho|
`consumo_mensal`|Dias trabalhados / ano|
`fator_personalizado`|Ida e volta _(true/false)_|

---

Campo no Supabase|Valor GHG|
|---|---|
`categoria_de_emissoes`|_TRABALHO-CASA - ANUAL_|
`date`|Data da referência _(yyyy-mm-dd hh:mm:ss)_|
[id_veiculo_viagem](https://github.com/ZNIT-Tech/documentation/blob/main/Transportes%20Publicos.md)|Tipo de transporte público|
`nro_passageiros`|Número de Passageiros|
`dist_percorrida`|Distância Percorrida _(km)_ por trecho|
`dias_trabalhados`|Dias trabalhados|
`meses_trabalhados`|Meses trabalhados|
`fator_personalizado`|Ida e volta _(true/false)_|

---

#### Veiculos Particulares

Campos no Supabase|Valores GHG|
|---|---|
`categoria_de_emissoes`|_TRABALHO-CASA 1_|
`date`|Data da referência _(yyyy-mm-dd hh:mm:ss)_|
[tipo_veiculo_frota](https://github.com/ZNIT-Tech/documentation/blob/main/Veiculos%20da%20Frota.md)|Tipo da frota de veículos|
`ano_frota`|Ano da frota|
`consumo_anual`|Dias trabalhados no ano|
`consumo_mensal`|Dias trabalhados / mês |
`consumo_medio_dia`|Consumo médio de combustivel / dia _(litros ou m³)_|
`fator_personalizado`|Ida e volta _(true/false)_|

<sub><em>Obs.: Inserir apenas consumo mensal ou consumo anual</em></sub>

---

Campos no Supabase|Valores GHG|
|---|---|
`categoria_de_emissoes`|_TRABALHO-CASA 2_|
`date`|Data da referência _(yyyy-mm-dd hh:mm:ss)_|
[combustivel](https://github.com/ZNIT-Tech/documentation/blob/main/Combustiveis.md)|Tipo da frota de veículos|
`consumo_anual`|Dias trabalhados no ano|
`consumo_mensal`|Dias trabalhados / mês |
`consumo_medio_dia`|Consumo médio de combustivel / dia _(litros ou m³)_|
`fator_personalizado`|Ida e volta _(true/false)_|

<sub><em>Obs.: Inserir apenas consumo mensal ou consumo anual</em></sub>

---

Campo no Supabase|Valor GHG
|---|---|
`categoria_de_emissoes`|_TRABALHO-CASA 3_ |
`date`|Data da referência _(yyyy-mm-dd hh:mm:ss)_|
[tipo_veiculo_frota](https://github.com/ZNIT-Tech/documentation/blob/main/Veiculos%20da%20Frota.md)|Tipo da frota de veículos|
`ano_frota`|Ano da frota|
`consumo_anual`|Dias trabalhados no ano|
`consumo_mensal`|Dias trabalhados / mês |
`consumo_medio_dia`|Distância média / dia _(km)_|
`fator_personalizado`|Ida e volta _(true/false)_|

<sub><em>Obs.: Inserir apenas consumo mensal ou consumo anual</em></sub>

---

Campo no Supabase|Valor GHG
|---|---|
`categoria_de_emissoes`|_TRABALHO-CASA 3 - ANUAL_ |
`date`|Data da referência _(yyyy-mm-dd hh:mm:ss)_|
[tipo_veiculo_frota](https://github.com/ZNIT-Tech/documentation/blob/main/Veiculos%20da%20Frota.md)|Tipo da frota de veículos|
`ano_frota`|Ano da frota|
`dias_trabalhados`|Dias trabalhados na semana|
`meses_trabalhados`|Meses trabalhados no ano|
`consumo_medio_dia`|Distância média / dia _(km)_|
`fator_personalizado`|Ida e volta _(true/false)_|

<sub><em>Obs.: Inserir apenas consumo mensal ou consumo anual</em></sub>

---
Campo no Supabase|Valor GHG
|---|---|
`categoria_de_emissoes`|_TRABALHO-CASA - REMOTO_ |
`date`|Data da referência _(yyyy-mm-dd hh:mm:ss)_|
`nro_passageiros`|Numero de colaboradores em trabalho remoto|
`dias_trabalhados`|Dias trabalhados na semana em regime remoto|
`consumo_anual`|Dias trabalhados no ano*|

<sub><em>Obs.: *Caso _consumo_anual_ seja 0 ou _NULL_, valor padrão considerado é 230 </em></sub>

---

Campo no Supabase|Valor GHG
|---|---|
`categoria_de_emissoes`|_TRABALHO-CASA - REMOTO - ANUAL_ |
`date`|Data da referência _(yyyy-mm-dd hh:mm:ss)_|
`nro_passageiros`|Numero de colaboradores em trabalho remoto|
`dias_trabalhados`|Dias trabalhados na semana em regime remoto|
`meses_trabalhados`|Meses trabalhados em regime remoto|

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
