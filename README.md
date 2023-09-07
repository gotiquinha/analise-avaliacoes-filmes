# analise-avaliacoes-filmes
Análise exploratória de avaliações de filmes utilizando as bibliotecas pandas e seaborn em Python. Este repositório abrange desde a leitura dos dados até a visualização e obtenção de insights sobre as avaliações e detalhes dos filmes.

# Análise de Dados com Pandas: Avaliações de Filmes
Neste repositório, realizo uma análise exploratória de um conjunto de dados contendo avaliações de filmes usando as bibliotecas pandas e seaborn em Python. A análise abrange desde a leitura e limpeza dos dados até a visualização e obtenção de insights.

### Sobre as bibliotecas:
**Pandas:** Uma ferramenta poderosa e flexível para análise de dados em Python. Com ela, podemos manipular, analisar e visualizar dados de maneira eficiente.

**Seaborn:** Uma biblioteca de visualização de dados Python baseada no Matplotlib. Ela fornece uma interface de alto nível para criar gráficos estatísticos atraentes.

### Conjunto de Dados:
Estamos trabalhando com dois conjuntos de dados:

**Avaliações de Filmes:** Cada linha representa uma avaliação dada por um usuário a um filme em particular e inclui informações como o ID do usuário, o ID do filme, a nota dada e o momento da avaliação.  
**Informações de Filmes:** Cada linha representa um filme e inclui detalhes como o ID do filme, o título e o gênero.

### Etapas da Análise:
**Leitura dos Dados:** Utilizamos `pd.read_csv()` para ler os arquivos CSV contendo os dados das avaliações e informações dos filmes.  
**Exploração Inicial:** Examino as primeiras linhas dos DataFrames, verifico os tipos de dados e obtenho informações básicas.  
**Manipulação de Colunas:** Redefino os nomes das colunas para facilitar a referência durante a análise.  
**Análise Descritiva:** Obtenho medidas estatísticas básicas, como média, mediana, valores únicos e contagem de valores.  
**Visualização com Pandas:** Uso a funcionalidade `.plot()` do pandas para gerar um histograma das avaliações.  
**Visualização com Seaborn:** Uso o `sns.boxplot()` para visualizar a distribuição das avaliações. O gráfico mostra que metade das notas está entre 3 e 4, enquanto a outra metade está entre 3 e 2.  
**Consulta e Agrupamento:** Realizo consultas específicas para obter informações sobre avaliações de filmes específicos e agrupo os dados por filme para obter a média das avaliações.
 
### Conclusões:
Com esta análise, foi possível obter uma compreensão básica das avaliações de filmes e detalhes dos filmes presentes nos conjuntos de dados. As bibliotecas pandas e seaborn provaram ser ferramentas valiosas para essa tarefa, permitindo uma análise eficiente, visualizações claras e insights rápidos.
