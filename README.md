![image](https://github.com/marxeugenio/AluraCursoDeClassificacao/assets/78555292/01362131-8f16-4e20-a8b7-e166d27da5c6)# Classificação: uma vez um pai clássico com Machine Learning

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

[Captura de tela 2024-01-09 215638!](https://github.com/marxeugenio/AluraCursoDeClassificacao/assets/78555292/f2630512-d089-41c3-9eac-ab0791d686d3)

px.histograma (dados, x = "inadimplencia", text_auto = True, color = "aderencia_investimento", barmode = "group")

[Captura de tela 2024-01-09 215708!](https://github.com/marxeugenio/AluraCursoDeClassificacao/assets/78555292/844c1683-6db2-49d1-871c-6670540d717d)

px.histograma (dados, x = "fez_emprestimo", text_auto = True, color = "aderencia_investimento", barmode = "group")

[Captura de tela 2024-01-09 221218!](https://github.com/marxeugenio/AluraCursoDeClassificacao/assets/78555292/3456aab1-8414-467b-b330-13200fa11e37)

---------------------------------- ---------------------------------- ---------------------------------- ---------------------------------- ------------------ ------------------ ------------------ ------------------ ------------------ ----------------------

# Anotações

"" "Variáveis quantitativas ou numéricas
São características que podem ser medidas a partir de valores numéricos que são enviados e divididos entre diferentes discretas e contínuas.

Discretas variadas: características médicas apenas por um número finito ou condomínio de valores. Só fez sentido para valores inteiros. Por exemplo: número de arquivos, número de vendas.
Variáveis contidas: características médicas que assumem valores em escala contínua (na reta real), em que faz sentido valorres fracionários. Exemplo: peso, ritmo, alta.
Variáveis qualitativas ou categorias
São características que não possuem valores quantitativos e definidos por categorias ou classes. São divisões em nominais e ordinais.

Variáveis nominais: não existe ordenação entre categorias. Exemplo: sexo biológico, pais, rotatividade.
Variáveis ordinais: existe um ordem entre como categorias. Exemplo: escolaridade, mês."""

---------------------------------- ---------------------------------- ---------------------------------- ---------------------------------- ------------------ ------------------ ------------------ ------------------ ----------------------

# Continuação dos Gráficos :

O grafico a seguir mais uma distribuição das idades (no eixo x) em relação a uma variada de "aderencia_investimento", utilizando caixas (caixas) que representam uma mediana "aderencia_investimento". Esse dispositivo permanente como uma identificação é distribuída em diferentes níveis ou categorias de produtos ao investimento. Os graficos a seguir vão seguir ou mesmo padrão de racicinio.

px.box (dados, x = "idade", cor = "aderencia_investimento")

[Captura de tela 2024-01-09 222734!](https://github.com/marxeugenio/AluraCursoDeClassificacao/assets/78555292/6fb5ad07-7f3e-483a-bdb0-836d762b7171)


px.box (dados, x = "saldo", cor = "aderencia_investimento")

[imagem!](https://github.com/marxeugenio/AluraCursoDeClassificacao/assets/78555292/62dc87c3-2a11-40e8-ad19-20a92a16f169)

px.box (dados, x = "tempo_ult_contato", cor = "aderencia_investimento")

[Captura de tela 2024-01-09 223000!](https://github.com/marxeugenio/AluraCursoDeClassificacao/assets/78555292/6673b8d1-fe98-401c-8794-7c2e270eb857)

px.box (dados, x = "numero_contatos", cor = "aderencia_investimento")

[Captura de tela 2024-01-09 223108!](https://github.com/marxeugenio/AluraCursoDeClassificacao/assets/78555292/b804a5c7-3722-47cd-87d7-f7c4e89447fe)

---------------------------------- ---------------------------------- ---------------------------------- ---------------------------------- ------------------ ------------------ ------------------ ------------------ ------------------ ----------------------

# Módulo 2: Transforma de Dados

Aqui nós estamos importando novamente uma base de dados :

importar pandas como pd 

dados = pd.read_csv (r "C: \ Usuários \ marx \ OneDrive \ Área de Trabalho \ Alura2024 \ ClassificaçãoAprendendoaClassificarDadoscomMachineLearning \ marketing_investimento.csv")

dados

[!Captura de tela 2024-01-11 213834](https://github.com/marxeugenio/AluraCursoDeClassificacao/assets/78555292/66c7dd31-53c9-4b1d-99bf-9561a75c15bd)

E em seguida basicamente iremos excluir a coluna 'aderencia_investimento' mas estaremos add essa alteração a X e adicionando essa coluna excluida para Y :

x = dados.drop ("aderencia_investimento", eixo = 1)
y = dados["aderencia_investimento"]

x

[Captura de tela 2024-01-11 214151!](https://github.com/marxeugenio/AluraCursoDeClassificacao/assets/78555292/fecd1c30-ef42-45f3-884d-6b6a20153100)

e ágora Y:

[Captura de tela 2024-01-11 214255!](https://github.com/marxeugenio/AluraCursoDeClassificacao/assets/78555292/ae2072a8-b483-4394-bbf7-c637380b65ff)


Um guia de código utiliza uma biblioteca de pesquisa de código para aplicar uma codificação única em colunas específicas de um conjunto de dados x. Ele cria um transformador de colunas usando make_column_transformer, e o OneHotEncoder é aplicado a determinadas colunas categóricas. O parâmetro drop = "if_binary" evita um redundância ao lidar com variáveis binárias. O resultado da transformação é blindado na variável x.

de sklearn.compose import make_column_transformer
de sklearn.preprocessing import OneHotEncoder

colunas = x.columns
one_hot = make_column_transformer ((
 OneHotEncoder (drop = "if_binary")
    ["estado_civil", "escolaridade", "inadimplencia", "fez_emprestimo"]
),
 restante = "passthrough",
 sparse_threshold = 0)

x = one_hot.fit_transform (x)

one_hot.get_feature_names_out (colunas)

[Captura de tela 2024-01-11 214850!](https://github.com/marxeugenio/AluraCursoDeClassificacao/assets/78555292/1c672699-b0a1-4010-84cf-681bd7a68546)


O código cria um DataFrame para uma parte do conjunto de dados transformados x uma aplicação da codificação única. Ele usa os nomes das colunas obtidas após uma transformação, rasgado o DataFrame pronto para análise ou tratamento de modelos com colunas codificadas.

pd.DataFrame (x, colunas = one_hot.get_feature_names_out (colunas))

[Captura de tela 2024-01-11 215357!](https://github.com/marxeugenio/AluraCursoDeClassificacao/assets/78555292/fd986250-39ee-4090-b84f-c7fb3190ed33)

Este é o código de utilização utilizado pelo LabelEncoder da biblioteca scikit-learn para transformar os papéis da classe em valores numéricos

de sklearn.preprocessing import LabelEncoder

label_ecoder = LabelEncoder ()

y = label_ecoder.fit_transform (y)

y

Resultado : 

[0 1 0 2]

---------------------------------- ---------------------------------- ---------------------------------- ---------------------------------- ---------------------------------- ---------------------------------- --------------------------

# Módulo 3: Ajustando Modelo


Divisão de trabalho e teste para realizar essa separação de dados, utilizando uma diversidade da biblioteca scikit-learn, conhecida como train_test_split (). Primeiros, vamos importar uma diversão.

de sklearn.model_selection import train_test_split

Após fez uma importação, podemos dividir os nossos dados. Isso será feito armazenando uma parte dos pais para o treino e o outro para o teste. Faremos isso tanto quanto x quanto para y, que são variados explicativos e alvo.

x_treino, x_teste, y_treino, y_teste = train_test_split (x, y, estratify = y, random_state = 5)

Já tem uma base de dados separados em partes: um para tratamento do modelo, nenhum modelo de comparação ou apresentação de dados e realização como classificações; e um outro para o teste do modelo, sobre vamos avaliar o desempenho do modelo, realizar comodificações e comparações com os resultados que são na base de teste. Assim, vamos verificar se o modelo está disponível como classificações correcionais.

### Modelo de base

Para os arquivos do processo de modelagem, vamos chegar com o modelo mais simples possível, classificador de manequim chamado. Esse algoritmo classifica todos os registros da base de dados com base na categoria de variação de maior frequência, ou seja, que tem um contágio maior na base de dados.

Na análise exploratória, verificados que uma classe com mais frequência é uma que não é um investimento. Logo, é mais provável que uma pessoa não faça parte de um investimento do que o contrário. Uma idéia do algoritmo é justamente essa.

Ele não considera as características da pessoa na variância explicativa. O algoritmo sempre foi realizado para classificar a quantidade de peso pelo valor "Não", que é o valor 0, transformado pelo LabelEncoder.

Pode cirurgir uma dúvida: esse algoritmo não é possível assim, porque ele não está disponível para determinar uma classificação do cliente. Ele simplifica vai chutar ou mesmo valor. De fato, ele não será um algoritmo utilizado no mundo real para o jogo como classificações. Não há entanto, será importante para termos um critério de comparação para outros modelos mais complexos que vamos usar.

Se um modelo mais complexo não apresenta um método mais simples que o modelo base (classificador de manequim), que simplifica as tarefas como classificações, entre o modelo que é um modelo complexo que não é usado para ser utilizado. Ele cria muitas regras para fazer uma classificação, mas não tem um valor que parece ser o modelo básico.

Para chegar, vamos importar o modelo DummyClassifier para confirmar a classificação de uma parte do jogo. Novamente, vamos utilizar uma biblioteca de pesquisa de conteúdo para criar uma importação de diversão e utilização de algoritmos de análise.

Na primeira célula, vamos escrever ou seguinte comando :

de sklearn.dummy import DummyClassifier

Esse será o processo para os algoritmos do scikit-learn, que sempre tem uma idéia de utilização. Primeiro, vamos inicializar ou modelar. Assim, um par de algoritmos, inicializa um modelo que vai armazenar em um variável. Vamos chamar essa varia de manequim. Então, vamos descobrir que manequim será igual a DummyClassifier ().

manequim = DummyClassifier ()

Da mesma forma que os dispositivos com o OneHotEnconder e LabelEncoder que utilizam. Nenhum item oficial é modelo para a diversão DummyClassifier (), depois, a partir de, ele se ajusta a nós dados.

Para fazer isso, digitemos na mesma célula, na linha abixo, ou como dummy.fit (), diversão responsável por render ou pelo pai dos pais. Nenhum algoritmo de caso desse, qual será o valor do produto?

Ele vai para um nível variável e específico qual é uma categoria mais presente na base de dados. Com base na categoria, ele vai realizar como classificações a partir de. Portante, para esse método fit (), vamos passar os dados do tratamento. Da mesma forma, vamos passar x_treino e y_treino.

manequim = DummyClassifier ()
dummy.fit (x_treino, y_treino)

Você pode escolher: por que os requisitos passam x_treino, se não houver um modelo, ele vai se render aos resultados da variação alvo, que é o y?

Porque ele também precisa compreender quais são as colunas para fazer uma classificação. Ele armazena essas informações na mesma ordem das colunas; foram transformadas como criaram como novas colunas com o OneHotEncoder.

Ele vai armazenar que, para realizar essa classificação, ele precisa das categorias, daquelas características. Por fim, depôis que utilizamos o fit (), uma regra para realizar uma classificação de técnica armada em um manequim variável. Após isso, podemos avaliar como será o desempenho desse modelo nos dados de teste. Como Fazemos isso?

Pegamos um manequim variável seguida de .score (). Essa diversão vai gerar um imposto de acesso ao modelo. Portante, para fazer esse score (), passamos o x_teste e y_teste. O que será utilizado com x_teste e y_teste?

O modelo vai realizar uma classificação de novos pais a partir de x_teste. Após obter os resultados de 0 e 1, que são variados, ele compara ou resulta com y_teste. Ele vai fazer uma comparação de linhas e verificá-lo como um imposto de acesso, que será um porcentagem entre 0 e 1.

manequim = DummyClassifier ()
dummy.fit (x_treino, y_treino)

dummy.score (x_teste, y_teste)

Ao executar esse código, obtenha um imposto de 0,60. Isso significa que, em 60% das vezes, esse modelo realiza uma classificação de forma correta. Justamente porque, sem equilíbrio da variação alvo, existem 60% dos dados da classe "Não" e 40% da classe "Sim". Como ele disse como enviar a classe "Não", tem um resultado de 60% de acerto.
