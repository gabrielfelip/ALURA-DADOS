# 📊 Imersão de Dados com Python - Alura

Este repositório documenta os notebooks e projetos desenvolvidos durante a **Imersão de Dados** promovida pela Alura.  
O projeto utiliza **Python** e bibliotecas como **Pandas**, **Matplotlib**, **Seaborn**, **Plotly** e **Streamlit**, com desenvolvimento realizado no **Google Colab** e em ambiente local.

---

## 👨‍🏫 Aulas e Conteúdo

### **Aula 1 – Introdução ao Python e Manipulação de Dados**
**Objetivos:**
- Apresentar o Python e suas aplicações em Ciência de Dados.
- Manipular dados utilizando a biblioteca **Pandas**.
- Compreender a estrutura de um **DataFrame**.

**Conteúdo:**
- Criação e exploração de DataFrames.
- Seleção e filtragem de dados.
- Identificação de valores nulos.
- Boas práticas e organização de código.

---

### **Aula 2 – Limpeza de Dados**
**Objetivos:**
- Tratar dados ausentes e inconsistentes.
- Renomear colunas e aplicar filtros.
- Gerar estatísticas descritivas.

**Conteúdo:**
- Verificação de dados nulos (`isnull()`, `sum()`).
- Preenchimento e exclusão de valores ausentes (`fillna()`, `ffill()`, `bfill()`).
- Conversão de tipos de dados (`astype()`).
- Continuação das boas práticas.

---

### **Aula 3 – Criação de Gráficos Estatísticos**
**Objetivos:**
- Criar e personalizar gráficos para análise de dados.
- Utilizar bibliotecas **Pandas**, **Matplotlib**, **Seaborn** e **Plotly**.

**Conteúdo:**
- Gráficos básicos com Pandas (`.plot()`).
- Gráficos estéticos com Seaborn (`.barplot()`, `.histplot()`, `.boxplot()`).
- Personalização de gráficos (títulos, rótulos).
- Gráficos interativos com Plotly.

---

### **Aula 4 – Criação de Dashboards Interativos com Streamlit**
**Objetivos:**
- Desenvolver um **dashboard interativo** utilizando **Streamlit**.
- Publicar o projeto online para acesso público.

**Conteúdo:**
- Instalação e configuração do Python e VSCode.
- Criação de ambiente virtual para isolar dependências.
- Instalação das bibliotecas necessárias (**Pandas**, **Plotly**, **Streamlit**, **PyCountry**) via `requirements.txt`.
- Desenvolvimento do arquivo `app.py` com título, ícone e layout.
- Carregamento de dados de salários a partir de um link no GitHub.
- Implementação de barra lateral com filtros dinâmicos (ano, tipo de contrato).
- Exibição de métricas: salário médio, salário máximo, total de registros e cargos mais frequentes.
- Criação de gráficos interativos (distribuição de salários, cargos com maior média salarial).
- Mapa com média salarial de cientistas de dados em diferentes países.
- Publicação no **Streamlit Cloud**.

---

## 📂 Estrutura do Repositório
- `aula1.ipynb`: Código das aulas 1 e 2. **(colab)**
- `aula3.ipynb`: Código da aula 3. **(colab)**
- `aula4/`: Arquivos do dashboard interativo com Streamlit. **(vscode)**

---

## 🚀 Tecnologias Utilizadas
- **Python 3**
- **Google Colab**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Plotly**
- **Streamlit**
- **PyCountry**

---

## 🌐 Publicação
O dashboard desenvolvido na Aula 4 está disponível online via **Streamlit Cloud**:  
[🔗 Acessar Dashboard](https://mundo-salarios.streamlit.app)  

---

## 📚 Fonte
Curso **Imersão de Dados** – [Alura](https://www.alura.com.br)
