# Projeto de Inteligência Artificial e Previsões

## Calcular Score de Crédito dos Clientes

### Case Proposto : 

Calcular _score_ de crédito dos clientes de um banco , com base nos dados dos mesmos disponíveis.

#### Base de dados para treino:

_Scores_ e dados dos clientes que já possuem classificação na base de dados.

### Bibliotecas em uso :

- pandas :

- scikit-learn :

    - sklearn.preprocessing -> LabelEncoder
    - sklearn.model_selection -> train_test_split
    - sklearn.ensemble -> RandomForestClassifier
    - sklearn.neighbors -> KNeighborsClassifier
    - sklearn.metrics -> accuracy_score



### Modelos utilizados:

- Árvore de decisão 

        Analisa cada caso, criando um caminho para cada um, tomando a decisão com base em cada parâmetro


- KNN

        Plota os casos de treino e teste em um gráfico e os compara com base na proximidade

##### Para realização de deploys
- Utilizar streamlit