import pandas as pd

pd.read_csv("/content/nome_do_arquivo.csv")
import pandas as pd
dados = pd.read_csv("cole-aqui-o-link-do-arquivo-csv")
dadosCopiarEditar 
dados = pd.read_csv("https://exemplo.com/dados.csv") dados = pd.read_csv("https://exemplo.com/dados.csv") 
dados 

dados.hist()
dados["nome-da-coluna"].hist()
### Resumoimport pandas as pd 
dados = pd.read_csv("exercicio.csv") 
dados["minutos_exercicio"].hist() dados["nome-da-coluna"].value_counts()dados["Quantas horas de sono você costuma ter em uma noite durante a semana?"].value_counts()dados["Quantas bebidas açucaradas você consome em uma semana?"].value_counts()Turma A 
2 livros    10 
3 livros     8 
4 livros     6 Turma B 
1 livros    9 
2 livros    10 
3 livros    5 dados.describe()media_sono = dados["Quantas horas de sono você costuma ter em uma noite durante a semana?"].mean()
mediana_sono = dados["Quantas horas de sono você costuma ter em uma noite durante a semana?"].median()
print(media_sono)
print(mediana_sono)media_bebidas = dados["Quantas bebidas açucaradas você consome em uma semana?"].mean()
mediana_bebidas = dados["Quantas bebidas açucaradas você consome em uma semana?"].median()
print(media_bebidas)
print(mediana_bebidas)### Comparando com outras fontes
