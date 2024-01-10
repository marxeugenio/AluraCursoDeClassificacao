# Classificação: ofereça um pai clássico com Machine Learning

### Módulo 1: Análise Exploratória

Comentários com uma biblioteca de pandas para um arquiador CSV chamado "marketing_investimento.csv" de uma base de dados fornos pela Alura. Ele cria esses dados em uma estrutura chamada DataFrame, nomeada de 'dados', permite que você explore, analise e manipule para realizar diversas épocas de análise e processo de dados.

![Captura de tela 2024-01-09 220546](https://github.com/marxeugenio/AluraCursoDeClassificacao/assets/78555292/6af0a37f-d42f-47e4-9549-1636f1f1805a)


Logo após o registro dos dados, não é apresentado como 5 itens e como 5 ultimas do DataFrame, mas não é uma série ou um dispositivo para termos de uma certeza se você está usando o pai. Não há informações adicionais sobre o DataFrame ou como dados.info () ajuda muito, pois o pai.info () oferece uma visão mais rápida, informações mais detalhadas 

![Captura de tela 2024-01-08 232840](https://github.com/marxeugenio/AluraCursoDeClassificacao/assets/78555292/85e7012c-1adf-4649-ad78-fccfa34ad729)


como o número total de entradas, os tipos de dados em cada coluna e seus valores nulos.

---------------------------------- ---------------------------------- ---------------------------------- ---------------------------------- ------------------ ------------------ ------------------ ----------------------

# Anotações:

"" "Como uma música do Machine Learning
O funcionamento do Machine Learning tem 3 etapas principais :

1 - Coleta dos dados

Uma versão versátil de um projeto de ML é uma extração ou cola de dados. Os dados são essências e podem ser considerados como um algoritmo matéria-prima dos. Uma quantidade e qualidade dos dados que os pais têm um impacto muito grande, sem acordo com os modelos. Com poucos dados, o modelo não pode ser informado sobre como informações necessárias para o tornado do tornado. Como pais de qualidade, o modelo não pode ser encontrado em um país ou pai ou pai ou mãe ou mãe ou mãe ou mãe ou mãe ou mãe ou mãe ou mãe ou mãe ou mãe ou mãe ou mãe ou mãe ou mãe ou mãe ou que os pais fazem.

2 - Treinamento dos modelos

Após coletar dados e assegurar que estão com qualidade, chega à etapa de treinar os modelos. O tratamento consiste em um algoritmo de aquisição ou apresentação presente nos pais e na construção de uma regra para tomar decisões posteriores em novos pais.

3 - Avaliação

Como modelo treinado, como uma lista de avaliadores ou modelo de modelo, para identificar o valor dos pais e se o limite de aplicação de forma satisfatória para o algoritmo de geração de dados em pais novos, que não são utilizados durante o momento do tratamento.

Apesar de serem como etapas principais, não é como as músicas étnicas presentes nos projetos de Machine Learning. Cada projeto tem suas características características, veja ou formate uma natureza dos dados, o tipo de aplicação ou os desafios contidos no processo."""

---------------------------------- ---------------------------------- ---------------------------------- ---------------------------------- ------------------ ------------------ ----------------------
# Graficos:

Esse código utiliza uma biblioteca Plotly Express para criar um histórico e partir de dados contidos no DataFrame "dados". O histórico é constante com base na coluna "aderencia_investimento" e uma maioria das distribuições dos pais dessa coluna, ou parâmetro text_auto = Verdadeiro permissão para exibir automaticamente os itens nos gráficos, informações adicionais

Utilizando o seguinte comando :

importe plotly.express como px

px.histograma (dados, x = "aderencia_investimento", text_auto = True)

Você pode obter um gráfico de barras no total de anúncios nos investimentos, como uma coluna Sim e outros Não .

![Captura de tela 2024-01-09 214652](https://github.com/marxeugenio/AluraCursoDeClassificacao/assets/78555292/38d0580c-ad81-4951-87c3-861fbe1f45bc)


A seguir, tarifa mais um teste utilizado ou seguir comando :

px.histograma (dados, x = "estado_civil", text_auto = True, color = "aderencia_investimento", barmode = "group")

Que pegam apenas uma coluna está sujeita a uma base de dados e comparação com pessoas que são solteiras, casas e divisões, e uma maioria é uma diferença de qualidade que é mais adepto de um produto ou investimento

![Captura de tela 2024-01-09 215517](https://github.com/marxeugenio/AluraCursoDeClassificacao/assets/78555292/d55983bf-71f9-4120-bbe1-3057e9c7c77b)


E seguindo essa mesma analogia testamos todas as possibilidades / colunas da nossa base de dados :

px.histograma (dados, x = "escolaridade", text_auto = True, color = "aderencia_investimento", barmode = "group")

![Captura de tela 2024-01-09 215638](https://github.com/marxeugenio/AluraCursoDeClassificacao/assets/78555292/f2630512-d089-41c3-9eac-ab0791d686d3)

px.histograma (dados, x = "inadimplencia", text_auto = True, color = "aderencia_investimento", barmode = "group")

![Captura de tela 2024-01-09 215708](https://github.com/marxeugenio/AluraCursoDeClassificacao/assets/78555292/844c1683-6db2-49d1-871c-6670540d717d)

px.histograma (dados, x = "fez_emprestimo", text_auto = True, color = "aderencia_investimento", barmode = "group")

![Captura de tela 2024-01-09 221218](https://github.com/marxeugenio/AluraCursoDeClassificacao/assets/78555292/3456aab1-8414-467b-b330-13200fa11e37)

---------------------------------- ---------------------------------- ---------------------------------- ---------------------------------- ------------------ ------------------ ------------------ ------------------ ----------------------

# Anotações

"" "Variáveis quantitativas ou numéricas
São características que podem ser medidas a partir de valores numéricos que são enviados e divididos entre diferentes discretas e contínuas.

Discretas variadas: características médicas apenas por um número finito ou condomínio de valores. Só fez sentido para valores inteiros. Por exemplo: número de arquivos, número de vendas.
Variáveis contidas: características médicas que assumem valores em escala contínua (na reta real), em que faz sentido valorres fracionários. Exemplo: peso, ritmo, alta.
Variáveis qualitativas ou categorias
São características que não possuem valores quantitativos e definidos por categorias ou classes. São divisões em nominais e ordinais.

Variáveis nominais: não existe ordenação entre categorias. Exemplo: sexo biológico, pais, rotatividade.
Variáveis ordinais: existe um ordem entre como categorias. Exemplo: escolaridade, mês."""

---------------------------------- ---------------------------------- ---------------------------------- ---------------------------------- ------------------ ------------------ ------------------ ----------------------

# Continuação dos Gráficos:

O grafico a seguir mais uma distribuição das idades (no eixo x) em relação a uma variedade de "aderencia_investimento", utilizando caixas (caixas) que representam uma mediana "aderencia_investimento". Esse dispositivo permanente como uma identificação é distribuída em diferentes níveis ou categorias de produtos ao investimento. Os graficos a seguir vão seguir ou mesmo padrão de racicinio.

px.box (dados, x = "idade", cor = "aderencia_investimento")

![Captura de tela 2024-01-09 222734](https://github.com/marxeugenio/AluraCursoDeClassificacao/assets/78555292/6fb5ad07-7f3e-483a-bdb0-836d762b7171)


px.box (dados, x = "saldo", cor = "aderencia_investimento")

![imagem](https://github.com/marxeugenio/AluraCursoDeClassificacao/assets/78555292/62dc87c3-2a11-40e8-ad19-20a92a16f169)

px.box (dados, x = "tempo_ult_contato", cor = "aderencia_investimento")

![Captura de tela 2024-01-09 223000](https://github.com/marxeugenio/AluraCursoDeClassificacao/assets/78555292/6673b8d1-fe98-401c-8794-7c2e270eb857)

px.box (dados, x = "numero_contatos", cor = "aderencia_investimento")

![Captura de tela 2024-01-09 223108](https://github.com/marxeugenio/AluraCursoDeClassificacao/assets/78555292/b804a5c7-3722-47cd-87d7-f7c4e89447fe)

---------------------------------- ---------------------------------- ---------------------------------- ---------------------------------- ------------------ ------------------ ------------------ ------------------ ----------------------

# Módulo 2: Transforma de Dados










