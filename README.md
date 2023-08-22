# CREDIT SCORE EDA-ANALYSIS no SQL

___

## Objetivos
* Fornecer uma exploração dos dados via SQL
*  Analisar alguns dados para compreender como uma análise de crédito depende de determinadas variáveis
*  Apresentar insights que possam auxiliar na tomada de decisão da instituição financeira

---
## Dicionário de dados

| Variável                | Descrição                                           | Tipo         |
| ----------------------- |:---------------------------------------------------:| ------------:|
| idade | idade do cliente | inteiro|
| sexo | sexo do cliente (F ou M) | string|
| dependentes | número de dependentes do cliente | inteiro|
| escolaridade | nível de escolaridade do clientes | string|
| salario_anual | faixa salarial do cliente | string|
| tipo_cartao | tipo de cartao do cliente | string|
| qtd_produtos | quantidade de produtos comprados nos últimos 12 meses | bigint|
| iteracoes_12m | quantidade de iterações/transacoes nos ultimos 12 meses | inteiro|
| meses_inativo_12m | quantidade de meses que o cliente ficou inativo | inteiro|
| limite_credito | limite de credito do cliente | float|
|valor_transacoes_12m | valor das transações dos ultimos 12 meses |float|
|qtd_transacoes_12m  | quantidade de transacoes dos ultimos 12 meses | inteiro|

______
A tabela foi criada no **PostgreSQL** com uma versão dos dados disponibilizados em:
