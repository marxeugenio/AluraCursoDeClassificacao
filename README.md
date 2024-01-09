# Classificação: aprendendo a classificar dados com Machine Learning

### Modulo 1 : Análise Exploratória

Começamos com a biblioteca pandas para ler um arquivo CSV chamado "marketing_investimento.csv" de uma base de dados fornecida pela Alura. Ele carrega esses dados em uma estrutura chamada DataFrame, nomeada de 'dados', permitindo que sejam explorados, analisados e manipulados para realizar diversas operações de análise e processamento de dados.

![image](https://github.com/marxeugenio/AluraCursoDeClassificacao/assets/78555292/f266e7ae-1332-4e50-9bb4-4f6c225c152f)

Logo apos o carregamento dos dados, é nós apresentados as 5 primeiras e as 5 ultimas linhas do DataFrame, mas só com isso não seria o suficiente para termos a certeza se estava tudo ok com os dados. No entanto, para obter informações mais detalhadas sobre o DataFrame, o comando dados.info() ajuda muito, pois o dados.info() fornece uma visão mais abrangente, mostrando informações 

![image](https://github.com/marxeugenio/AluraCursoDeClassificacao/assets/78555292/357697b1-2128-436e-ad02-ce1732d5cf90)

como o número total de entradas, os tipos de dados em cada coluna e se há valores nulos.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Anotações :

"""Como funciona o Machine Learning
O funcionamento do Machine Learning tem 3 etapas principais:

1 - Coleta dos dados

A primeira etapa de um projeto de ML é a extração ou coleta de dados. Os dados são essenciais e podem ser considerados a matéria-prima dos algoritmos. A quantidade e qualidade desses dados têm um impacto muito grande no aprendizado dos modelos. Com poucos dados, o modelo pode não ter informações suficientes para aprender. Com dados de pouca qualidade, o modelo pode não conseguir diferenciar bem o padrão dos dados ou compreender o padrão de forma diferente do que ocorre com os dados do mundo real.

2 - Treinamento dos modelos

Após coletar dados e assegurar que estão com qualidade, chega à etapa de treinar os modelos. O treinamento consiste no algoritmo procurar o padrão presente nos dados e construir uma regra para tomar decisões posteriormente em novos dados.

3 - Avaliação

Com o modelo treinado, chega a etapa de avaliar o desempenho do modelo, para identificar se realmente aprendeu o padrão dos dados e se é capaz de aplicar de forma satisfatória a regra gerada pelo algoritmo em dados novos, que não foram utilizados durante o momento do treinamento.

Apesar de serem as etapas principais, essas não são as únicas tarefas presentes em projetos de Machine Learning. Cada projeto tem suas próprias características, seja pelo formato e natureza dos dados, ao tipo de aplicação ou aos desafios encontrados ao longo do processo."""

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Graficos :

Esse código utiliza a biblioteca Plotly Express para criar um histograma a partir dos dados contidos no DataFrame "dados". O histograma é constuido com base na coluna "aderencia_investimento" e mostra a distribuição dos dados dessa coluna, o parâmetro text_auto=True permite exibir automaticamente rótulos nos gráficos, fornecendo informações adicionais sobre os dados






