# Análise de dados abertos com Python

Esse tem uma mostra do código feito no worksho análise de dados abertos no dia 6/03/2024 no evento de dados aberto no IFPA,  a base de dados foi valor dos preço de revenda de combustivel no 1ª semestre de 2023 (que pode ser encontrado [aqui](https://www.gov.br/anp/pt-br/centrais-de-conteudo/dados-abertos/serie-historica-de-precos-de-combustiveis))

Foi selecionado para a análise as seguintes colunas:

- **Regiao - Sigla**: Sigla da Região da
revenda pesquisada
- **Estado - Sigla**: Sigla da Unidade Federativa (UF) da revenda pesquisada
- **Municipio**: Nome do município da revenda pesquisada
- **Produto**: Nome do combustível pesquisado
- **Data da Coleta**: Data da coleta do(s) preço(s)
- **Valor de venda**: Preço de venda ao consumidor final praticado pelo
revendedor, na data da coleta
- **Unidade de Medida**
- **Bandeira**: Noma da Bandeira da revenda.
O Posto bandeirado é aquele que opta por exibir a marca comercial de um
distribuidor, o posto deverá vender somente combustíveis fornecidos pelo
distribuidor detentor da marca comercial exibida aos consumidores. Já o
Posto bandeira branca é o que opta por não exibir marca comercial de
nenhuma distribuidora.

Decidiu-se també excluir GNV pois estava uma medida diferente e era pouco se comparado aos outros
