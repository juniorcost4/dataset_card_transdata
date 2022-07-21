# Base de dados para treinamento de algoritmos de classificação

Dataset criado tendo como base o dataset original "Credit Card Fraud" obtido no Kaggle datasets.

O dataset original pode ser encontrado através do seguinte link: https://www.kaggle.com/datasets/dhanushnarayananr/credit-card-fraud

Esse repositório contem uma base de treinamento (arquivo *.csv) gerado a partir das primeiras 100 mil instâncias do dataset original.

## 1. Apresentação dos atributos da base:

Atributo: distance_from_home
Tipo: numérico
Descrição: Distância total entre a residência do proprietário do cartão e o endereço onde a transação aconteceu.

Atributo: distance_from_last_transaction
Tipo: numérico
Descrição: Distância total entre o endereço da transação atual em relação com o local onde a última transação aconteceu.

Atributo: ratio_to_median_purchase_price
Tipo: numérico
Descrição: Razão entre o preço da compra e o preço médio das compras anteriores.

Atributo: repeat_retailer
Tipo: categórico
Descrição: Sim, caso a compra esteja sendo executada no mesmo varejista. Não caso contrário.

Atributo: used_chip
Tipo: categórico
Descrição: Sim, caso seja uma compra feita utilizando o cartão físico. Não caso contrário.

Atributo: used_pin_number
Tipo: categórico
Descrição: Sim, caso a senha de dígitos tenha sido usada para validar a transação. Não caso contrário.

Atributo: online_order
Tipo: categórico
Descrição: Sim, caso tenha sido uma compra online. Não caso contrário.
