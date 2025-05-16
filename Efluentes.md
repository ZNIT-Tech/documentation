# Efluentes

<details>
  <summary><strong><h2>Dados obrigatórios para cálculo</strong></summary>

### Efluentes - IPCC (Sem quantidade de funcionários)

|Campos no Supabase|Valores GHG|
|---|---|
`categoria_de_emissoes`|_EFLUENTES - IPCC - DBO_|
`quant`|MFC
`fator_metano_dbo_final`|DBO Forte
`ch4_recuperado`|Maximo CH4
`consumo_anual`|Voluma Anual _([m³/ano])_

### Efluentes - IPCC (Com quantidade de funcionários)

|Campos no Supabase|Valores GHG|
|---|---|
`categoria_de_emissoes`|_EFLUENTES - IPCC - FUNCIONARIOS_|
`consumo_mensal`|MFC
`fator_metano_dbo_final`|DBO Forte
`ch4_recuperado`|CH4 Recuperado
`horas_trabalhadas`|Horas trabalhados _(padrão: 0.018)_
`dias_trabalhados`|Dias trabalhados _(padrão: 21)_
`meses_trabalhados`|Meses trabalhados _(padrão: 12)_
`fator_correcao_do_fator_emissao`|Fator de correção do fator de emissão
`quant`|Quantidade de Colaboradores

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
