# NYC-Schools
Every year, school test results impact the college admissions fate of millions of students.  In this project, you will use standardized test performance data from NYC's public schools to identify the schools with top math results, look at how performance varies by borough, and find the city's top ten performing schools!


Which NYC schools have the best math results?

    The best math results are at least 80% of the *maximum possible score of 800* for math.
    Save your results in a pandas DataFrame called best_math_schools, including "school_name" and "average_math" columns, sorted by "average_math" in descending order.

What are the top 10 performing schools based on the combined SAT scores?

    Save your results as a pandas DataFrame called top_10_schools containing the "school_name" and a new column named "total_SAT", with results ordered by "total_SAT" in descending order ("total_SAT" being the sum of math, reading, and writing scores).

Which single borough has the largest standard deviation in the combined SAT score?

    Save your results as a pandas DataFrame called largest_std_dev.
    The DataFrame should contain one row, with:
        "borough" - the name of the NYC borough with the largest standard deviation of "total_SAT".
        "num_schools" - the number of schools in the borough.
        "average_SAT" - the mean of "total_SAT".
        "std_SAT" - the standard deviation of "total_SAT".
    Round all numeric values to two decimal places.


![New York City schoolbus](schoolbus.jpg)

Photo by [Jannis Lucas](https://unsplash.com/@jannis_lucas) on [Unsplash](https://unsplash.com).
<br>

Every year, American high school students take SATs, which are standardized tests intended to measure literacy, numeracy, and writing skills. There are three sections - reading, math, and writing, each with a **maximum score of 800 points**. These tests are extremely important for students and colleges, as they play a pivotal role in the admissions process.

Analyzing the performance of schools is important for a variety of stakeholders, including policy and education professionals, researchers, government, and even parents considering which school their children should attend. 

You have been provided with a dataset called `schools.csv`, which is previewed below.

You have been tasked with answering three key questions about New York City (NYC) public school SAT performance.


1. Importação de Bibliotecas
As bibliotecas utilizadas incluem:
• Manipulação e processamento de dados: pandas , numpy
• Visualização: seaborn , matplotlib
• Modelagem e validação: sklearn
• Ferramentas adicionais: yellowbrick (para análise de resíduos e previsões)

2. Funções Auxiliares
• Função get_metrics : Um dicionário para calcular métricas de avaliação de modelos, como R²,
MAE, MAPE e RMSE.

3. Exploração do Dataset
O dataset utilizado contém informações sobre:
• age: Idade do indivíduo.
• sex: Gênero (male ou female).
• bmi: Índice de Massa Corporal.
• children: Número de dependentes.
• smoker: Se o indivíduo é fumante (yes ou no).

• charges: Custos médicos cobrados.
Análises incluem:
• Distribuições e correlações entre variáveis.
• Identiﬁcação de padrões relacionados aos custos médicos.
• Impacto do hábito de fumar nos custos.

4. Pré-processamento
• Imputação de valores ausentes: Substituição de dados faltantes usando SimpleImputer .
• Normalização de dados: Uso de MinMaxScaler .
• Codiﬁcação de variáveis categóricas: OneHotEncoder .

5. Divisão de Dados
• Treinamento e teste: Separar os dados para treinamento e validação dos modelos.

6. Modelagem Preditiva
Modelos utilizados:
• DummyRegressor: Baseline para comparação.
• Regressão Linear: Modelo linear simples.
• Modelos Avançados:
◦ LassoCV
◦ RidgeCV
◦ Random Forest Regressor
◦ Gradient Boosting Regressor

7. Validação e Ajuste de Modelos
• Uso de GridSearchCV para encontrar os melhores hiperparâmetros.
• Avaliação das previsões com métricas customizadas e visualização de resíduos.

8. Visualização dos Resultados
• Análise gráﬁca de previsões e resíduos usando o Yellowbrick.
• Comparativo entre diferentes modelos e suas métricas.

Requisitos
Para executar o notebook, certiﬁque-se de que as seguintes dependências estejam instaladas:
pip install numpy pandas seaborn matplotlib scikit-learn yellowbrick
Como Utilizar
1. Clone o repositório:
git clone https://github.com/seu-usuario/insurance-analysis.git
