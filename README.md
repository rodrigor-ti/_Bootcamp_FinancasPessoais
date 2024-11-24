Gerar um dataset com campos relacionados a finanças pessoais para analisar comportamento de consumo com 1000 exemplos inserindo valores nulos e outliers sendo a primeira coluna a de ID que representa o identificador único para cada registro com os dados separados por ponto e vírgula

Usar o nome do csv gerado e carregar o arquivo em um dataframe separado por ponto e vírgula exibindo as 10 primeiras linhas do dataset no formato string

Exibir os dados do dataset no formato string

Exibir informações sobre o dataset

Exibir as informações do dataset

Exibir as dimensões do dataset

Exibir os nome das colunas do dataset

Exibir os tipos de dados de cada coluna do dataset

Exibir estatísticas descritivas do dataset

Exibir o valor único dos dados de cada metadado do dataset

Exibir a quantidade de valores nulos por campo do dataset

Preencher os valores nulos de cada coluna do dataset com a moda sem usar o inplace no dataset

Exibir histogramas dos dados do dataset

Exibir gráficos de dispersão dos campos do dataset

Selecionar apenas colunas numéricas; Inicializar contador de outliers; Detectar outliers usando o método IQR para cada coluna numérica; Contar outlier; Calcular o percentual de contaminação de outliers no dataset.

Exibir boxplot para cada coluna numérica para visualizar os outliers do dataset

Usando a técnica de Isolation Forest com o percentual de contaminação definido obter os inliers e outliers exibindo os dados

Contar quantos Outliers e Inliers existem no dataset

Usando a técnica MinMaxScaler iterar pelas colunas numéricas do dataset adicionando os dados normalizados e exibir o novo dataset

Verificar se as colunas 'pc1' e 'pc2' já existem no dataset; Substituir valores NaN por 0; Aplicar PCA com 2 componentes principais; Criar as colunas 'pc1' e 'pc2' no dataset original com os componentes principais; Se as colunas 'pc1' e 'pc2' já existem, atualizar os valores com os novos componentes principais; Substituir valores NaN por 0; Aplicar PCA com 2 componentes principais;  Atualizar os valores das colunas 'pc1' e 'pc2'

Selecionar apenas as colunas com o sufixo "_minmax"; Lista para armazenar a inércia para diferentes valores de K; Testar valores de K de 2 a 10; Plotar o gráfico do cotovelo; Encontrar o melhor valor de K (o ponto de inflexão no gráfico); Exibir o melhor valor de k

Definir os hiperparâmetros do KMeans

Selecionar apenas as colunas com o sufixo "_minmax"; Substituir valores NaN por 0; Criar o modelo kmeans com os hiperparâmetros definidos; Ajustar o modelo aos dados; Obter os rótulos dos clusters para cada amostra; Adicionar os rótulos dos clusters ao dataset; Exibir os dados com os rótulos dos clusters

Contar a quantidade de exemplos por cluster; Exibir os resultados

Plotar o gráfico dos clusters com base nos componentes principais (PCA)

Obter informações estatísticas para cada cluster

Contar a quantidade de dados para cada classe; Obter a classe minoritária; Obter a classe majoritária; Separar os dados em conjuntos de acordo com a classe; Realizar o balanceamento por meio do método de reamostragem (upsampling/oversampling) da classe minoritária; Combinar os dados majoritários e os dados minoritários reamostrados; Verificar se o balanceamento foi realizado com sucesso

Definir as regras de atribuição para as colunas; Aplicar as regras às colunas do dataset; Exibir as regras de atribuição

Separar os dados em treino e teste (80/20); Exibir o tamanho dos conjuntos de treino e teste; Apresentar o conteúdo dos conjuntos de treino e teste

Definir os hiperparâmetros para o modelo MultiLayer Perceptron

Definir os hiperparâmetros para o modelo Support Vector Machine

Treinar e avaliar o modelo com validação cruzada; Imprimir os resultados da validação cruzada; Treinar o modelo com os dados de treinamento completos; Fazer previsões com o modelo no conjunto de teste; Calcular as métricas de avaliação para o modelo MLP

Treinar e avaliar o modelo com validação cruzada; Imprimir os resultados da validação cruzada; Treinar o modelo com os dados de treinamento completos; Fazer previsões com o modelo no conjunto de teste; Calcular as métricas de avaliação para o modelo SVM

Verificar qual o modelo campeão; Salvar o modelo; Carregar o modelo e usar os dados de teste para validar exibindo as métricas
