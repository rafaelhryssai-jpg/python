import pandas as pd

# Substitua pelo link real do seu arquivo CSV
url = "https://exemplo.com/dados.csv"
dados = pd.read_csv(url)

# Exibe as 5 primeiras linhas
dados.head()
