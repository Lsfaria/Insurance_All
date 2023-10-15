# Insurance_All

# 1. Business Problem

A Insurance All é uma empresa que oferece seguro saúde aos seus clientes, e a equipe de produtos está analisando a possibilidade de oferecer aos segurados um novo produto: seguro automotivo. Assim como o seguro saúde, os clientes deste novo plano de seguro automotivo precisam pagar um valor anual à Insurance All para obter um valor segurado pela empresa, destinado aos custos de um eventual acidente ou dano ao veículo.
Ao contatar alguns clientes por telefone, a empresa obteve um sucesso relativo com resultados sólidos após oferecer o produto a aproximadamente 380.000 clientes. No entanto, os altos custos operacionais tornaram a execução da operação proibitiva para os 127 mil novos clientes que ainda não conhecem a oferta. Portanto, a empresa recorreu a uma consultoria de ciência de dados, na esperança de que os dados do cliente em seu banco de dados pudessem ajudar a minimizar custos e esclarecer algumas dúvidas.


# 2. Solution Strategy

Minha estratégia para resolver esse desafio foi:

**Step 01. Data Description**
- Features Description 
- Data Dimentions
- Data Types
- Check NA
- Change Types
- Descriptive Statistical 

**Step 02. Feature Engineering**

- Hypotheses criation
- Feature Engineering 

**Step 03. Data Filtering**
- It was not necessary

**Step 04. Exploratory Data Analysis**
- Univariate Analysis
- Bivariate Analysis
- Multivariate Analysis

**Step 05. Data Preparation**
- Standardization
- Rescaling Features
- Features Transformation
- Validation Preparation

**Step 06. Feature Selection**
- Features Importance

**Step 07. Machine Learning Modelling**
- KNN
- Logistic Regression
- Random Forest
- Decision Tree
- XGB
- Lightgbm
- Catboost

**Step 08. Hyperparameter Fine Tunning**
- Logistic Regression fine tunning

**Step 09. Convert Model Performance to Business Values**


# 3. Top 3 Data Insights:

**Hipótese 01:** Clientes do gênero feminino possuem maior probabilidade de adquirir um seguro para carro.

**Falsa**  - Clientes do gênero masculino possuem maior probabilidade de adquirir um seguro para carro

**Hipótese 02:** Clientes que não possuem carteira de motorista são menos propensos a adquirir um seguro de carro.

**Verdadeira**  - Clientes que não possuem carteira são menos propensos a adquirir um seguro de carro.

**Hipótese 03:** Clientes que possuem carros novos são mais propensos a adquirir um seguro para carro.

**Falso** - Clientes que possuem carros usados são mais propensos a adquirir um seguro para carro.

# 4. Machine Learning Model Applied
- LightGBM Classifier

# 5. Business Results
**Com os resultados conseguimos atingir mais de 80% dos clientes na base e com um lucro de aproximadamente 62%..**

# 6. Conclusions
- O projeto atingiu seu objetivo, que era otimizar a venda de seguros para clientes propensos a aceitá-lo.

# 7. Lessons Learned
- Classification model for database ranking

# 8. Next Steps to Improve
- Realizar o deploy
