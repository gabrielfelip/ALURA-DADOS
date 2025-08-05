# ALURA-DADOS

# 📊 Imersão de Dados - Alura (Aula 1)

Este repositório contém os códigos e anotações desenvolvidos durante a **Imersão de Dados da Alura**, utilizando Python e a biblioteca Pandas no Google Colab.

## ✅ Aula 1 - Análise de Dados com Pandas

Nesta primeira aula, realizamos as seguintes atividades:

### 🔹 Carregamento de Dados

- Leitura do arquivo `salaries.csv` com dados de profissionais da área de tecnologia:
  - Fonte: [GitHub - guilhermeonrails](https://github.com/guilhermeonrails/data-jobs)

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/guilhermeonrails/data-jobs/refs/heads/main/salaries.csv")
```

🔹 Exploração Inicial dos Dados
Visualização das primeiras linhas com df.head()
Informações sobre tipos de dados com df.info()
Estatísticas descritivas com df.describe()
Verificação do número de linhas e colunas com df.shape

🔹 Renomeação das Colunas
Tradução dos nomes das colunas para português para facilitar a leitura e entendimento.

🔹 Análise de Colunas Categóricas
Contagem de categorias das colunas:
senioridade
contrato
remoto
tamanho_empresa

Mapeamento dos códigos para descrições mais claras, como por exemplo:
SE → senior
FT → integral
100 → remoto
M → media

🔹 Estatísticas das Colunas Categóricas
Uso do describe(include='object') para verificar:
Número de categorias únicas
Categoria mais frequente
Frequência dessa categoria

❓ Perguntas que já conseguimos responder:
Qual o nível de experiência mais comum na base de dados?
Qual é o tipo de contrato mais frequente?
Qual o cargo mais recorrente?
De qual país são a maioria dos profissionais?
Qual o regime de trabalho mais comum?
Qual o tamanho mais comum das empresas?

📌 Tecnologias utilizadas
Python
Pandas
Google Colab

📅 Progresso
✅ Aula 1 concluída

🔜 Aula 2 em breve...
