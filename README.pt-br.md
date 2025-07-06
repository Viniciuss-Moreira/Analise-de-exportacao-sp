# Analise-de-exportacao-sp
[![Python](https://img.shields.io/badge/Python-3.11-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=matplotlib&logoColor=white)](https://matplotlib.org/)
[![Pandas](https://img.shields.io/badge/Pandas-333333?style=flat&logo=pandas)](https://pandas.pydata.org)
---
**Link para o colab:** [**➡️ Link do notebook do colab**](https://colab.research.google.com/drive/1KfUo9tfXb2trnxrNUjuyHKOnOI3fyW_b?usp=sharing)
---
Esse notebook faz parte do projeto integrador da Fatec, que consiste em desenvolver uma aplicação web para visualizar de forma dinamica os dados das exportações de todos os municípios do estado de São Paulo.

![App Demo](./img/demo.gif)
---
## 📖 Descrição do notebook

Esse notebook realiza uma raspagem de dados em arquivos públicos fornecidos pelo governo federal (.csv) com a biblioteca Pandas, trata e formata esses dados e por meio das biblíotecas Numpy e Matplotlib exibem esses dados em forma de graficos dinamicos. O cliente ficticio consegue filtrar os dados de exportação por ano, município, valor por Kilo ou FOB, visualizar os top 5 municípios que mais exportam no estado e até comparar municípios entre sí.
---

## 🛠️ Workflow e funcionalidades do notebook
1. **Tratamento de dados:** Os dados extraídos dos arquivos .csv são formatados em tabelas que futuramente vão ser lidos para gerar os gráficos interativos.
2. **Formação de gráfico** O dataframe formatado é transformado em gráficos clicaveis que para que seja possível filtrar tópicos expecíficos, transformando os dados em isights valiosos.

---

## 🚀 Tech Stack

**Ciencia de dados:** Python, Numpy, Matplotlib, Pandas
---
## 🔮 Implementações futuras
**Banco de dados relacional:** Adição de um banco de dados para salvar esses dados e permitir que seja utilizado consultas por SQL.
**Scripts de automação:** Scripts em python para automatizar e incluir automaticamente novas informações que chegarem no site do governo no gráfico interativo.
