# Descrição 📜

Esse projeto utiliza técnicas de Data Science para medir a performance de 4 lojas, e a partir disso, determinar qual loja é a melhor candidata para ser vendida.

1. Analisamos o faturamento líquido somando todas as vendas e subtraindo com a soma de todos os fretes. E visualizamos ele com um gráfico de barras verticais.

2. Analisamos as vendas por categoria fazendo uma soma das vendas de cada categoria por loja e visualizamos utilizando um gráfico de pizza ou 'pie chart'.

3. A média de avaliação é calculada usano média aritmética e apresentada como valores simples, sem gráficos.

4. Os produtos mais e menos vendidos são calculados somando cada venda dos produtos e selecionando os que possuem maior e menor frequência para cada loja. Visualizamos usando um gráfico de pontos.

5. O frete médio é calculado usando uma média aritmética e apresentado com valores simples, sem gráficos.

# Dependências 🔧

Utilizamos o Pandas para carregar os arquivos csv de cada loja e também para executar as operações necessárias para os cálculos. Usamos funções do Pandas e também do próprio Python. Para as visualizações foi usado o Matplotlib.

# Utilização 👷

Usamos um notebook que possui a seguinte estrutura:

Cada célula possui o código que executa os cálculos necessários, seguido por uma célula que gera a visualização gráfica, quando implementada.

Usamos funções que recebem uma lista de DataFrames, e a partir dela, criamos novos DataFrames com as informações específicas.

O código pode ser rodado simplesmente executando as células. Se quiser analisar outras lojas, será necessário um csv com a mesma estrutura, a partir dai basta usar as funções definidas nas células anteriores, eg.

'''python
nova_loja = [pd.read_csv(path), ...]
faturamento_novo = calculo_preco(nova_loja)
'''

As outras funções também tem a mesma regra de execução.

# Ajuda 🆘

Caso existam dúvidas sobre alguma funcionalidade é recomendado olhar as documentações das bibliotecas utilizadas:

1. https://pandas.pydata.org/docs
2. https://matplotlib.org/stable/
3. https://docs.python.org/3/library/functions.html

# Autores 📕

Esse projeto foi criado por Haydée Magriñá.







