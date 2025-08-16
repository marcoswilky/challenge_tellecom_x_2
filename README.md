Challenge Telecom X 2 – Predição de Evasão de Clientes
Este projeto utiliza análise exploratória de dados e modelos de machine learning para prever a evasão (churn) de clientes de uma operadora de telecomunicações. O notebook apresenta todo o pipeline, desde o carregamento dos dados até a avaliação dos modelos.

Estrutura do Notebook
Carregamento dos Dados:
Os dados tratados são carregados diretamente de um arquivo CSV hospedado no GitHub.

Pré-processamento:

Remoção de colunas irrelevantes (customerID)
Conversão da variável alvo (Churn) para tipo numérico
Transformação de variáveis categóricas em numéricas via One-Hot Encoding
Análise Exploratória:

Proporção de clientes que evadiram vs. permaneceram
Visualizações (boxplots, scatterplots, matriz de correlação) para identificar fatores de evasão
Preparação dos Dados:

Separação entre features e variável alvo
Divisão em conjuntos de treino e teste
Balanceamento das classes com SMOTE
Padronização das features (StandardScaler e MinMaxScaler)
Modelagem:

Regressão Logística (com normalização)
Random Forest (sem normalização)
Avaliação dos modelos com métricas: acurácia, precisão, recall, F1-score, matriz de confusão
Comparação e Análise dos Modelos:

Discussão sobre desempenho, vantagens e limitações de cada abordagem
Insights e Estratégias de Retenção:

Identificação dos principais fatores de evasão
Propostas de estratégias para retenção de clientes
Principais Resultados
Regressão Logística:

Melhor recall e F1-score para identificar clientes que evadiram
Modelo mais interpretável
Random Forest:

Modelo mais flexível para capturar padrões complexos
Desempenho semelhante, mas menor recall
Como Executar
Instale as dependências:
Execute o notebook no Jupyter ou VS Code.
Próximos Passos
Feature engineering para enriquecer os dados
Otimização de hiperparâmetros dos modelos
Teste de outros algoritmos (XGBoost, LightGBM, Redes Neurais)
Análise de importância das features
Referência dos Dados
Os dados utilizados estão disponíveis em:
challenge_tellecom_x_2/dados_tratados.csv

Autor
Marcos Wilky


Arquivo principal:
Challenge_Tellecom_X_2.ipynb
