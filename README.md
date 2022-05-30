Projeto onde aplico técnicas de Machine Learning para classificação de dados.

Esse é um projeto de estudo, onde sou um cientista de dados de uma startup fictícia que oferta serviços para empresas da área financeira.
O objetivo desse projeto para a startup, é incluir em seu portfólio um algortitmo de detecção de fraudes, aumentando assim a segurança do próprio negócio bem como dos clientes.

A base de dados utilizada nesse projeto é gerada através do simulador de dados financeiros PaySim, onde uma fração desses dados está disponível no Kaggle, sob o nome de Fraud Detection Example.

O projeto passa pelas seguintes etapas: <hr>

<b> ETL DOS DADOS </b>

Após carregamento dos dados, foi feito o tratamento dos dados usando o Pandas, onde:
- Verifiquei se existem dados nulos;
- Analisei as estratísticas descritivas;
- Renomeei as colunas para o padrão pt-br;
- Apliquei um encoding nos dados para correto tratamento com algorítimos de Machine Learning. <hr>
  
<b> TREINANDO O TESTANDO COM LOGISTIC REGRESSION </b>

Apliquei o primeiro modelo de Machine Learning, o Logistic Regression.
Utilizei a biblioteca Metrics para para avaliar a performance do modelo e obtive um interessante resultado de acurárcia, mas bem deficitário em relação à precisão, sensibilidade e F1.
Apliquei um balanceamento nos dados, pois existiam mais registros de transações não fraudulentas que fraudulentas, treinei o modelo novamente e obtive métricas mais balanceadas. 
Depois disso, fiz mais uma análise nos dados e formulei hipóteses que caracterizam as transações fraudulentas.<hr>

<b> APLICANDO OUTROS MODELOS: DECISION TREE E RANDOM FOREST </b>

Buscando ainda mais eficiência nos resultados, apliquei outros dois modelos de Machine Learning: Decision Tree e Random Forest.
Após uma análise nas métricas, escolhi o Random Forest como o modelo que seria aplicado nesse projeto.
Após a escolha, decidi trabalhar melhor nesse modelo a fim de obter um resultado ainda mais eficaz.<hr>

<b> MELHORANDO O MODELO E CONCLUINDO O PROJETO </b>

Analisei quais seriam os hyperparâmetros mais eficientes utilizando o RandomizedSearchCV e o ajustei o modelo, chegando a métricas acima de 99% de eficiência.
Por fim, respondi as hipóteses com soluções para diminuir a incidência de transações fraudulentas.
