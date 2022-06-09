# Mercari_Price_Suggestion_Challenge
![Enforcing-Recommended-Retail-Prices](https://user-images.githubusercontent.com/98356094/172762581-0e225b7a-369e-420b-8e58-d936cc788f8c.jpeg)


# Previsão de Preço de Vendas da Loja Mercari


Este é um projeto realizado com dados públicos disponibilizados pela empresa na plataforma do [KAGGLE](https://www.kaggle.com/datasets/manchitas/mercaritrain).


## 1. Problema de Negócio
O Mercari, o maior aplicativo de compras baseado na comunidade do Japão, gostaria de oferecer sugestões de preços aos vendedores, mas não entendem como poderiam fazer essas sugestões porque seus vendedores podem colocar qualquer tipo de produto em seu Marketplace.
Em face disso, a Mercari juntou seu time de cientistas de dados com o objetivo de trazer uma solução que sugira preços certos dos produtos de forma automática.

## 2. Entendimento do Negócio
#### Motivação
A empresa fez uma pesquisa em seus banco de dados e percebeuque seus clientes possuem certa dificuldade ao precificar seus produtos.

#### Causa Raiz do Problema
A diferença de produtos pelas suas caracteristicas torna difícil conseguir um padrão na precificação

#### Quem é o Stakeholder
Os clientes da empresa.


#### Formato da Solução
* Modelo Algorítmo de Precificação 
 
## 3. Metodologia de Desenvolvimento do Projeto
 O projeto está sendo desenvolvido pela técnica CRISP-DM
 * Versão END-TO_END da solução,
 * Velocidade na entrega de valor,
 * Mapeamento de todos os possíveis problems.


##### Passo 01 - Descrição dos dados: Conhecimento dos dados, tipos, métricas estatísticas para identificar outliers, analise das métricas estatísticas e ajustes em features do dataset (preenchimento de NA's).


##### Passo 02 - Feature Engineering: Desenvolvimento de mapa mental para analisar o fenômeno, as variáveis e os principais aspectos que impactam cada uma delas. 


##### Passo 03 - Filtragem dos dados: Filtragem das linhas e excluir as colunas que não são relevantes para o modelo ou não fazem parte do escopo do negócio. EX: Dias em que as lojas estavam fevhadas ou inoperantes.


##### Passo 04 - Análise Exploratória dos dados: Exploração dos dados para encontrar insights.


##### Passo 05 - Preparação dos dados: Preparação para as aplicações de modelos de machine learning.


##### Passo 06 - Seleção de Features: Seleção dos melhores atributos para treinar o modelo. Utilizamos o algoritmo Boruta para essa seleção.


##### Passo 07 - Modelagem de Machine Learning: Foram realizados testes e treinamentos de alguns modelos de machine learning, para possibilitar a comparação da performance e escolha do modelo ideal para o projeto. Foi utilizada a técnica de Cross Validation para garantir a performance real sobre os dados selecionados.


## 4. Entendendo os Dados
* Dados disponibilizados pela empresa na plataforma do [KAGGLE](https://www.kaggle.com/c/mercari-price-suggestion-challenge/data).

| VARIÁVEL  |  DEFINIÇÃO  |
| ------------------- | ------------------- |
|  Train_id or Test_id	 |  The id of the listing.|
|  Name |  the title of the listing. Note that we have cleaned the data to remove text that look like prices (e.g. $20) to avoid leakage. These removed prices are represented as [rm].|
|Item_condition_id	| The condition of the items provided by the seller.|
|Category_name	| category of the listing.|
|Brand_name | Código da região do cliente.|
|Price | the price that the item was sold for. This is the target variable that you will predict. The unit is USD. This column doesn't exist in test.tsv since that is what you will predict.|
|Shipping | 1 if shipping fee is paid by seller and 0 by buyer.|
|Item_description | the full description of the item. Note that we have cleaned the data to remove text that look like prices (e.g. $20) to avoid leakage. These removed prices are represented as [rm].|


## 5. Performance do Modelo


### Comparação da performance dos modelos


## 7. Resultado Final


## - Conclusão

