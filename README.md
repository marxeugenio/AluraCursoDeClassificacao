# Classificação: ofereça um pai clássico com Machine Learning

### Módulo 1: Análise Exploratória

Comentários com uma biblioteca de pandas para um arquiador CSV chamado "marketing_investimento.csv" de uma base de dados fornos pela Alura. Ele cria esses dados em uma estrutura chamada DataFrame, nomeada de 'dados', permite que você explore, analise e manipule para realizar diversas óperas de análise e processo de dados.

[imagemm!](https://github.com/marxeugenio/AluraCursoDeClassificacao/assets/78555292/f266e7ae-1332-4e50-9bb4-4f6c225c152f)

Logo após o registro dos dados, não é apresentado como 5 primeiras e como 5 ultimas linhas do DataFrame, mas também não é uma série ou um dispositivo para termos de uma certeza se está tudo bem com os pais. Não há informações adicionais sobre o DataFrame, ou como dados.info () ajuda muito, pois o dados.info () oferece uma visão mais abrangente, informações mais detalhadas 

[imagemm!](https://github.com/marxeugenio/AluraCursoDeClassificacao/assets/78555292/357697b1-2128-436e-ad02-ce1732d5cf90)

como o número total de entradas, os tipos de dados em cada coluna e seus valores nulos.

-------------------------------------------------- -------------------------------------------------- -------------------------------------------------- -------------------------

# Anotações:

"" "Como a música do Machine Learning
O funcionamento do Machine Learning tem 3 etapas principais :

1 - Coleta dos dados

Uma primeira versão de um projeto de ML é uma extração ou cola de dados. Os dados são essências e podem ser considerados como um algoritmo matéria-prima dos. Uma quantidade e qualidade de dados diz que os dados têm um impacto muito grande, sem acordo com os modelos. Com poucos dados, o modelo não pode ter informações suficientes para se render. Como dados de qualidade, o modelo não pode ser encontrado em um pai ou pai ou pai ou pai ou pai ou pai ou mãe do que os pais fazem.

2 - Treinamento dos modelos

Após coletar dados e assegurar que estão com qualidade, chega à etapa de treinar os modelos. O tratamento consiste em nenhum algoritmo de aquisição ou apresentação presente nos dados e na construção de uma regra para tomar decisões posteriores em novos pais.

3 - Avaliação

Como modelo treinado, como uma lista de avaliadores ou modelo de modelo, para identificar se o valor dos pais e se o limite de aplicação de forma satisfatória para o algoritmo de geração de dados em dados novos, que não são utilizados durante o momento do tratamento.

Apesar de serem como etapas principais, não é como as únicas tarefas presentes nos projetos de Machine Learning. Cada projeto tem suas características características, veja o formato e a natureza dos dados, o tipo de aplicação ou os desafios contidos no processo."""

-------------------------------------------------- -------------------------------------------------- -------------------------------------------------- -------------------------

# Graficos:

Esse código utiliza uma biblioteca Plotly Express para criar um histograma e partir de dados contidos no DataFrame "dados". O histórico é constante com base na coluna "aderencia_investimento" e a maioria das distribuições dos pais dessa coluna, ou parâmetro text_auto = Verdadeiro permissão para exibir automaticamente os itens nos gráficos, informações adicionais

Utilizando o seguinte comando :

importe plotly.express como px

px.histograma (dados, x = "aderencia_investimento", text_auto = True)

Você pode obter um gráfico de barras no total de anúncios nos investimentos, como uma coluna Sim e outros Não .

[!imagem](https://github.com/marxeugenio/AluraCursoDeClassificacao/assets/78555292/5cc7bfcf-0d3f-4da1-8271-4aace1f314ee)

A seguir, tarifa mais um teste utilizado ou seguir comando :

px.histograma (dados, x = "estado_civil", text_auto = True, color = "aderencia_investimento", barmode = "group")

Que pegam apenas uma coluna estada_civil da nossa base de dados e fazem comparação com pessoas que são solteiras, casas e divórcios, e a maioria é uma diferença de qualidade que é mais adepto de um produto ou investimento

[imagem!](https://github.com/marxeugenio/AluraCursoDeClassificacao/assets/78555292/b3ce32cc-5cd7-4e78-9b6b-4dff939b18cf)

-------------------------------------------------- -------------------------------------------------- -------------------------------------------------------------------------

E seguindo essa mesma analogia testamos todas as possibilidades / colunas da nossa base de dados :

px.histograma(dados, x = "escolaridade", text_auto = True, color = "aderencia_investimento", barmode = "group")

[imagemm!](https://github.com/marxeugenio/AluraCursoDeClassificacao/assets/78555292/95b96c95-82c6-4634-931a-ddd2335d34b3)

-------------------------------------------------- -------------------------------------------------- -------------------------------------------------------------------------

px.histograma (dados, x = "inadimplencia", text_auto = True, color = "aderencia_investimento", barmode = "group")

[imagemm!](https://github.com/marxeugenio/AluraCursoDeClassificacao/assets/78555292/1ac18258-41ff-4775-b59a-1984ca88d4c0)

-------------------------------------------------- -------------------------------------------------- ------------------------------------------------------------------









