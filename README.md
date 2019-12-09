# case_itau_2019
# Descrição
Este repositório é dedicado a compartilhar a solução do case proposto pelo processo de seleção para cientistas de dados.
O arquivo ipynb encontra-se neste repositório para análise.
# Detalhes
O código com a solução encontra-se comentado para facilitar o entendimento do raciocínio proposto. A seguir, compartilho alguns detalhes utilizados na solução:

# 1- Algoritmo Random Forest Classifier:

Trata-se de um algoritmo de aprendizagem supervisionada que gera várias árvores de decisão, cada uma com suas particularidades, e por fim combina o resultado de classificação de cada uma delas, gerando a predição final.

# 2- GridSearchCV:

Trata-se de uma ferramenta que possibilita o teste de vários hiperparâmetros juntamente com cross-validation a fim de indicar qual a melhor escolha tanto do modelo quanto dos parâmetros a serem inputados neste. Essa indicação é medida através da métrica de avaliação inserida dentro do GridSearchCV.

# 3- Biblioteca FKlearn:

Trata-se de uma biblioteca liberada recentemente pelo Nubank com vários recursos de Machine Learning. Utilizei recursos de divisão de bases baseadas em períodos de tempo, conforme pode ser visto no código disponibilizado neste repositório.

# 4- SelectKBest
Trata-se de uma técnica de seleção de variáveis, em que define-se um número k de variáveis mais relacionadas com o target.Nesse caso, escolhemos uma função para avaliação das features (chi2, f_classif, etc) e apenas as k features com maior score resultante dessas funções irão ser consideradas para aplicação no modelo preditivo.


