📊 Imersão de Dados com Python - Alura
Este repositório reúne os notebooks produzidos durante a Imersão de Dados com Python da Alura, utilizando Google Colab como ambiente e bibliotecas como Pandas, Matplotlib, Seaborn e Plotly para manipulação e visualização de dados.

👨‍🏫 Aula 1 — Introdução ao Python e Manipulação de Dados
📌 Objetivos

Conhecer o Python e seu uso em análise de dados.

Manipular dados com Pandas.

Explorar a estrutura de um DataFrame e aplicar filtros.

📚 Conteúdos

Introdução ao Google Colab.

Criação e exploração de DataFrames.

Seleção e filtragem (loc[], iloc[]).

Identificação de valores nulos.

Boas práticas de código.

💡 Exemplo

import pandas as pd

df = pd.DataFrame({
    'Nome': ['Ana', 'Bruno', 'Carlos'],
    'Idade': [25, 30, 35]
})

print(df.head())


🧼 Aula 2 — Limpeza de Dados
📌 Objetivos

Tratar dados ausentes.

Renomear colunas e aplicar filtros.

Obter estatísticas descritivas.

📚 Conteúdos

Verificação de dados nulos com isnull() e sum().

Preenchimento com fillna(), ffill() e bfill().

Exclusão de linhas incompletas.

Conversão de tipos de dados (astype()).

💡 Exemplo

df['Idade'] = df['Idade'].fillna(df['Idade'].mean())
df.info()


📊 Aula 3 — Visualização de Dados
📌 Objetivos

Criar gráficos estatísticos.

Utilizar bibliotecas Pandas, Matplotlib, Seaborn e Plotly.

Personalizar visualizações.

📚 Conteúdos

Pandas plot() → gráficos rápidos.

Seaborn → gráficos elegantes (sns.barplot(), sns.histplot(), sns.boxplot()).

Matplotlib → títulos e rótulos (plt.title(), plt.xlabel(), plt.ylabel()).

Plotly → gráficos interativos.

Desafio → visualizar salário médio por país para cientista de dados.

💡 Exemplo

import seaborn as sns
import matplotlib.pyplot as plt

sns.histplot(df['Idade'], bins=5)
plt.title("Distribuição de Idade")
plt.show()

📷 Exemplo de Gráfico

📂 Arquivos no Repositório
aula1.ipynb → Introdução ao Python e manipulação de dados.

aula2.ipynb → Limpeza de dados.

aula3.ipynb → Visualização de dados.

🚀 Tecnologias Utilizadas
Python 3 🐍
Google Colab ☁️
Pandas 🐼
Matplotlib 📈
Seaborn 🎨
Plotly 📊

📚 Fonte
Curso de Imersão de Dados — Alura
