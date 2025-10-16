# Análise de Lucratividade de Filmes (Dataset TMDB 5000)

## 📄 Visão Geral do Projeto

Este projeto consiste em uma Análise Exploratória de Dados (EDA) profunda sobre um dataset de 5000 filmes do The Movie Database (TMDB). O objetivo principal é identificar os fatores que contribuem para o sucesso financeiro de um filme, analisando métricas como orçamento, receita, lucro, gêneros, diretores e elenco principal.

---

## ❓ Questões Analisadas

A análise foi guiada pelas seguintes perguntas:

1.  Qual a relação entre o **orçamento** de um filme e sua **receita** de bilheteria?
2.  Quais são os **filmes individualmente mais lucrativos**?
3.  Quais **gêneros** são os mais produzidos em comparação com os mais rentáveis?
4.  Quais **diretores, atores e atrizes** estão associados ao maior lucro acumulado?

---

## 📊 Principais Descobertas e Insights 💡

* **Orçamento vs. Receita:** Existe uma **correlação positiva moderada** entre orçamento e receita, indicando que, embora não seja uma garantia, maiores investimentos tendem a levar a maiores retornos de bilheteria.

* **Lucratividade por Gênero:** A análise revelou uma diferença significativa entre os gêneros mais produzidos e os mais lucrativos.
    * **Mais Produzidos:** `Drama` e `Comedy`.
    * **Maior Lucro Médio:** `Animation`, `Adventure` e `Fantasy`.
    * Isso sugere que filmes de "espetáculo", embora mais caros, trazem um retorno financeiro médio superior.

* **Talentos de Ouro:** A análise de lucratividade acumulada por pessoa revelou os nomes mais rentáveis de Hollywood.
    * **Diretores:** A lista é liderada por nomes consagrados como **Steven Spielberg** (sucesso consistente e longa carreira) e **James Cameron** (mega produções de altíssimo retorno).
    * **Atores e Atrizes:** Foram identificados os protagonistas masculinos e femininos que mais geraram lucro, destacando a importância de estrelas de grande apelo comercial em franquias de sucesso.

### Visualização Principal


---

## 🛠️ Tecnologias e Bibliotecas

* **Linguagem:** Python 3
* **Bibliotecas:**
    * `pandas` para manipulação, limpeza e junção de dados.
    * `matplotlib` e `seaborn` para visualização de dados.
    * `ast` para o parsing seguro de colunas com strings em formato JSON.
* **Ambiente:** Google Colab / Jupyter Notebook

---

## 📂 Sobre o Conjunto de Dados

O dataset utilizado foi o **TMDB 5000 Movie Dataset**, obtido através do [Kaggle](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata). Ele é composto por dois arquivos `.csv`: um com os metadados dos filmes e outro com os créditos (elenco e equipe).

---

## 🚀 Como Executar o Projeto

1.  Clone este repositório.
2.  Certifique-se de ter os arquivos `tmdb_5000_movies.csv` e `tmdb_5000_credits.csv` no diretório.
3.  Abra o notebook `.ipynb` no Google Colab ou em um ambiente Jupyter local.
4.  Execute as células do notebook em ordem sequencial para reproduzir a análise.

---

## 👨‍💻 Criado por

**Paloma Cordeiro**

* **LinkedIn:** [\[LinkedIn\]](br.linkedin.com/in/paloma-cordeiro-119750b6)
* **GitHub:** [\[GitHub\]](https://github.com/palomacdev)

**Repositório:** `movie-profitability-analysis` 
