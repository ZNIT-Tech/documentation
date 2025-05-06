# Emissões Fugitivas

<details>
  <summary><strong><h2>Dados obrigatórios para cálculo</strong></summary>

### Gases não quioto

|Campos no Supabase|Valores GHG|
|---|---|
`categoria_de_emissoes`|_EMISSOES FUGITIVAS - NAO QUIOTO_|
`escopo`|4| 
[gwp_id](https://github.com/ZNIT-Tech/documentation/blob/main/Gases.md)|Gás ou composto|
`uni_novas_carga`|Unidades Novas Carga _(kg)_
`uni_novas_capacidade`|Unidades Novas Capacidade _(kg)_
`uni_exist_recarga`|Unidade Existentes Recarga _(kg)_
`uni_disp_capacidade`|Unidades Dispensadas Capacidade _(kg)_
`uni_disp_recup`|Unidades Dispensadas Recuperada _(kg)_

### Abordagem por estágio do ciclo de vida

|Campos no Supabase|Valores GHG|
|---|---|
`categoria_de_emissoes`|_EMISSOES FUGITIVAS 1_|
[gwp_id](https://github.com/ZNIT-Tech/documentation/blob/main/Gases.md)|Gás ou composto|
`uni_novas_carga`|Unidades Novas Carga _(kg)_
`uni_novas_capacidade`|Unidades Novas Capacidade _(kg)_
`uni_exist_recarga`|Unidade Existentes Recarga _(kg)_
`uni_disp_capacidade`|Unidades Dispensadas Capacidade _(kg)_
`uni_disp_recup`|Unidades Dispensadas Recuperada _(kg)_


### Abordagem por Balanço de Massa (Compra)

Campos no Supabase|Valores GHG|
|---|---|
`categoria_de_emissoes`|_EMISSOES FUGITIVAS 2_|
[gwp_id](https://github.com/ZNIT-Tech/documentation/blob/main/Gases.md)|Gás ou composto|
`uni_novas_capacidade`|VE = Variação no estoque|
`uni_exist_recarga`|T = Quantidade transferida|
`uni_disp_capacidade`|MC = Mudança de capacidade _(kg)_ |


### Triagem

Campos no Supabase|Valores GHG|
|---|---|
`categoria_de_emissoes`|_EMISSOES FUGITIVAS 3_|
[gwp_id](https://github.com/ZNIT-Tech/documentation/blob/main/Gases.md)|Gás ou composto|
[id_equip_refrigerador](https://github.com/ZNIT-Tech/documentation/blob/main/Equipamento%20de%20Refrigeracao.md)| Tipo de Equipamento|
`uni_novas_capacidade`|Carga das Unidades Novas _(kg)_|
`uni_exist_recarga`|Capacidade Unidades em Operação _(kg)_|
`uni_disp_capacidade`|Capacidade Unidades Dispensadas _(kg)_|

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
