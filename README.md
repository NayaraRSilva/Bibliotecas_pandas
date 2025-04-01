# Bibliotecas_pandas

# Análise de Dados de Vendas no Varejo

Este repositório apresenta um projeto de análise de dados de vendas no setor varejista. O objetivo é tratar, explorar e visualizar os dados utilizando Python e bibliotecas como Pandas, Matplotlib e Plotly.

# Tecnologias Utilizadas

#Python

Pandas (para manipulação e tratamento de dados)

Matplotlib (para visualização de dados estática)

Plotly (para visualização de dados interativa)

Estrutura do Projeto

/
|-- dados/                 # Pasta contendo os arquivos de entrada
|   |-- varejo.xlsx
|   |-- cliente_varejo.xlsx
|-- analise_vendas.py       # Script principal de análise e visualização de dados
|-- README.md               # Documentação do projeto

Como Executar o Projeto

Certifique-se de ter o Python instalado (versão 3.8 ou superior).

Instale as dependências necessárias utilizando o seguinte comando:

pip install pandas matplotlib plotly openpyxl

Execute o script Python:

python analise_vendas.py

Funcionalidades do Script

Carregamento de Dados: Importa os arquivos varejo.xlsx e cliente_varejo.xlsx.

Limpeza e Tratamento:

Substitui valores em colunas categóricas.

Trata valores nulos nas colunas estado e Preço.

Cria uma nova coluna mes a partir da data.

Junção de Tabelas: Mescla as tabelas de vendas e clientes.

Análises Realizadas:

Cálculo da média de renda por canal de venda.

Cálculo da média de idade por bandeira.

Contagem de vendas por data.

Preço médio por departamento.

Visualizações:

Gráfico de barras com Matplotlib (Idade média por bandeira).

Gráficos interativos com Plotly:

Idade média por bandeira

Evolução das vendas ao longo do tempo

Preço médio por departamento

Exemplos de Gráficos

Idade Média por Bandeira (Matplotlib):


Vendas por Data (Plotly):


Contribuição

Sinta-se à vontade para contribuir! Se desejar adicionar melhorias ou novas análises, abra uma issue ou envie um pull request.

Licença

Este projeto está licenciado sob a MIT License - veja o arquivo LICENSE para mais detalhes.

