# **Curso livre de ciência de Dados**

### Oferecido pelo instituto federal do Mato Grosso do Sul (IFMS).

## **Introdução a Machine Learning**

A Capacidade da máquina de não somente aumentar sua performance em uma tarefa, mas também, aprender durante o processo, é caracterizado com _aprendizagem de máquina_ (AM). Técnicas e algoritmos considerados como de _AM_ buscam simular o processo de aprendizagem, de forma automatizada em computadores.

A inferência lógica indutiva é o fundamento por de trás do _Aprendizado Indutivo de Máquina_ (AIM), que busca a partir de um conjunto de instâncias especificas, generalizar uma expressão de conceitos que consiga caracterizar novas instâncias ou agrupa-las de formas mais homogênia possível, entre outros.

O conjunto de instâncias fornecido como entrada a um algoritmo indutivo de _AM_ é usualmente chamado de _conjunto de treinamento_.

A representação das instâncias do conjunto de treinamento, na dependência de ter (ou não) uma informação associada, identificada como classe, de certa forma colabora na identificação do tipo do algoritmo de _AM_ adequando para um determinado conjunto de instâncias.

Algoritmos que fazem uso da informação fornecida pelas classes associadas as instâncias de dados são geralmente chamadas de _algoritmos supervisionados_.

Algoritmos que não utilizam a informação da classe ou, então, que foram propostos com o intuito de apenas serem agrupadores de subconjuntos de instâncias do conjunto original de instâncias fornecidas, são caracterizados como _algoritmos não supervisionados_.

Existem também os algoritmos conhecidos como _semisupervisionados_ que, alternativamente, utilizam técnicas de aprendizado supervisionado e não supervisionado para conduzirem o processo de aprendizado.

~~O _aprendizado por reforço_ se concentra em ensinar uma agenda a tomar ações apropriadas em um ambiente para maximizar uma recompensa acumulada. É baseado em conceitos de recompensa e punição, onde o agente aprende a tomar ações ótimas ao longo do tempo através da experimentação e do recebimento de recompensas. Este tipo de aprendizado é amplamente utilizado em problemas de controle de sistemas, jogo, robótica e outras áreas~~

!wget 'https://archive.ics.uci.edu/ml/machine-learning-databases/iris/iris.data

Algoritmo que não utilizam a informação da classe ou, então, que foram propostos com o intuito de apenas serem agrupados de subconjuntos de instâncias fornecidos, são caracterizados como algoritmos não-supervisionados.

Existem também os algoritmos conhecidos como semisupervisionados que, alternativamente, utilizam técnicas de aprendizado supervisionado e não supervisionado para conduzirem o processo de aprendizado.

O aprendizado por reforço se concentra em ensinar um agente a tomar ações apropriadas em um ambiente para maximizar uma recompensa acumulada. É baseado em conseitos de recompensa e punição, onde o agente aprende a tomar ações ótimas ao longo do tempo através da experimentação e do recebimento de recompensas. Este tipo de é amplamente utilizado em problemas de controle de sistemas, jogos, robótica e outras áreas.

- Algoritmo Supervisionados

- Regressão

- Classificação

- Regressão

A _regressão_ é uma técnica de aprendizagem de máquina que visa prever o valor de uma váriavel dependente (também chamada de saída ou resposta) com base em uma ou mais variáveis independentes (também chamadas de variáveis de entrada ou explicativas).

Os principais algorítmos de regressão incluem:

A _Regressão Linear_ é o algoritmo mais simples e busca a reta de melhor ajuste que minimize a soma dos quadrados dos erros entre os valores previstos e os valores reais.

Regressão Logística é usada para problemas de classificação binária e estima a probabilidade de pertencimento a uma classe.

Regressão Polinomial é uma extensão da regressão linear que permite modelar relações não lineares entre as variáveis independente e dependentes.

Árvores de decisão é uma técnica de aprendizado supervisionado que pode ser usada tanto para classificação quanto para regressão.

Random Forest é uma técnica de aprendizado por ensemble que combina várias árvores de decisão para melhorar a precisão das previsões.

SMV (Support Vector Machine) é uma técnica de aprendizado supervisionado que procura encontrar a melhor separação entre as classes de dados. Pode ser usada tanto para classificação quanto para regressão.

CLASSIFICAÇÃO

O algoritmo de classificação é uma técnica de aprendizado supervisionado que visa prever a categoria a que uma determinada amostra pertence (classificação) com base em caracteristicas ou recursos de entrada.

Alguns dos principais algoritmos de classificação incluem:

K-Nearest Neighbors(KNN) é um algoritmo baseado em instância que classifica novos exemplos com báse na similaridade com os exemplos presentes no conjunto de treinamento.

Naives Bayes é um algoritmo probabilístico que supõe independência entre as variáveis de entrada e calcula a probabilidade de cada classe dados as caracteristivas de entrada.

Árvore de decisão é uma técnica de aprendizado supervisionado que constroi uma árvore de decisão para modelar a relação entre as váriaveis de entrada e a variável de saída categórica.

Random Forest é uma técnica de aprendizado assemble que combina várias árvores de decisão para melhorar a previsão das previsões.

SVM (Support Vector Machine) é uma técnica de aprendizado supervisionado que procura encontra a melhor separação entre as classes de dados.

ALGORITMOS NÃO SUPERVISIONADOS

Algoritmos não supervisionados são técnicas de aprendizado de máquina que não tem uma variável dependente ou rótulo para guiar o processo de treinamento. Em vez disso, esses algoritmos procuram descobrir padrões ou extruturas nos dados sem orientação externa.

Alguns dos principais algoritmos não supervisionados incluem:

Clustering é o processo de agrupamento de dados em grupos (cluster)com base em sua similaridade. Alguns exemplos incluem K-means, Hierarchical Clustering e DBSCAN.

Redução de demensionalidade é o processo de transformações de dados de alta dimensão em dados de baixa dimensão, mantendo a informação importante. Alguns exemplos incluem PCA (Análise de Componentes Principais) e t-SNE.

Aprendezado de Representação é o processo de aprendizagem de uma representação compacta e informativa dos dados, com o objetivo de facilitar tarefas de análise ou classificação futura. Alguns exemplos incluem autoenconders e word embbedding.

Análise de Componentes Independentes (ICA) É uma técnica que procura descobrir componentes não corelacionados nos dados.

Associação de Regras de Atributos (apriori) é uma técnica de mineiração de dados que busca encontrar regras de associação entre itens em grands conjuntos de dados.

CLUSTERING (GRUPAMENTOS)

Clustering é um tipo de algoritmo de aprendizado não supervisionado que tem como objetivo agrupar dados semelhantes em "clusters" ou grupos. O algoritmo procura encontrar estruturas ou padrões nos dados sem uma orientação externa, e os dados são classificados em diferentes grupos com base em sua similaridade.

Alguns dos principais algoritmos de clustering incluem:

K-Means é um algoritmo interativo que procura dividir os dados em K grupos fixos, minimizados a soma das distâncias dos pontos aos centróides dos respectivos grupos.

Hierarchical Clustering é um algoritmo que constroe uma árvore de agrupamento (ou dendrograma) a partir dos dados, onde cada nó representa um cluster.

DBSCAN (Density-Based Spatial Clustering of Applicatins with Noise) é um algoritmo baseado em densidade que procura encontrar agrupamentos densos de dados, sem especificar o número de clusters.

Gaussian Mixture Model (GMM) é uma técnica de modelagem probabilistica que supõe que os dados são gerados por uma mistura de distribuições normais.

Affinity Ṕropagation é um algoritmo que utiliza uma mensagem-passing iterativo para encontrar agrupamentos sem especificar o número de clusters.

Os algoritmos de clustering são amplamente utilizados em uma variedade de aplicações, incluindo seguimentação de clientes, análise de imagens, bioinformática e agrupamento de documentos.

Scikit-learn

Sciki-learn (sklearn) é uma bibliotéca de aprendizado de máquina em Python que oferece uma ampla variedade de ferramentas para tarefas de aprendizado de máquinas. É uma das bibliotécas na comunidade de aprendizado de máquina e oferece uma interface de programação de aplicativo (API) consistente para todos os seus algoritmos.

A bibliotéca sklearn inclui implementações eficientes e testeadas em produção de muitos algoritmos de aprendizado de máquina, incluindo regressão, classificação, agrupamento, redução de dimensionalidade, seleção de caracteristicas e outros. Também incluem muitas ferramentas para avaliar e otimizar o desempenho dos modelos, como validação cruzada, grid search e outras.

A biblioteca sklearn é fácil de usar, pois segue a filisofia "fit-transform-predict". Isso significa que você pode facilmente ajustar um modelo aos seus dados de treinamento, transforma-los como necessário e, em seguida, fazer previsões usando esse modelo ajustado. Além disso, a API padronizada da bibliotéca permite que vocÊ experimente vários algoritmos sem precisar aprender uma nova sintexe para cada um.

Em resumo, a biblioteca sklearn é uma ferramenta poderosa e fácil de usar para aprendizado de máquina em Python e é amplamente utilizada por cientistas de dados, engenheiros de machine learning e outro profissionais que precisam aplicar técnicas de aprendizado de máquina a seus dados.
