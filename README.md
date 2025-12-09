# Classificação de Sentimento 🗣️

## Descrição do Projeto

Este repositório contém um projeto de **Classificação de Sentimento** (Sentiment Classification) focado em utilizar técnicas de Processamento de Linguagem Natural (PLN) e Machine Learning para classificar textos em categorias de polaridade (ex: positivo, negativo, neutro).

O projeto é dividido em etapas que cobrem desde a Análise Exploratória de Dados (EDA) até o treinamento e avaliação de modelos de classificação.

---

## 📊 Análise Exploratória de Dados (EDA)

O notebook principal nesta fase é o `Analise_sentimento_EDA_1.ipynb`. Ele detalha a análise inicial do conjunto de dados e as descobertas cruciais para as próximas etapas de pré-processamento e modelagem.

**Principais etapas abordadas na análise inicial (EDA Parte 1):**

**1 - Metadados como:**

  1.1. Dimensão do dataset após limpeza;
  
  1.2. Tipo de quantidade de atributos;
  
  1.3. Tema geral sobre as mensagens colhidas (indício)

**2 - Classes (target- sentimentoss) presentes no dataset;**

**3 - Análise estatística e gráfica, por sentimento, de elementos descritivos como:**

  3.1. Frequência de caracteres;
  
  3.2. Frequência de palavras;
  
  3.3. Frequência de sentenças;
  
  3.4. Média de palavras;
  
  3.5. Média de caracteres

**4 - Lingua predominante.**

**5 - Também pudemos averiguar a necessidade de alguns procedimentos prévios como:**

  5.1. Limpeza do texto
  
  5.2. Lematização

5.3. Identificação e eliminação de outliers
---

## 🛠️ Tecnologias Utilizadas no EDA Parte 1

O projeto foi desenvolvido em Python e utiliza bibliotecas padrão do ecossistema de Data Science e Machine Learning.

* **Linguagem:** Python
* **Bibliotecas:** pandas, numpy, seaborn, matplotlib, kagglehub, shutil, spacy, nltk, re, string, collections
* **Desenvolvimento:** Jupyter Notebook

---

## 📁 Estrutura do Repositório

A estrutura de pastas segue uma convenção comum para projetos de ciência de dados:
lassificacao_sentimento/ 
```bash
├── data/ 
├── src/ 
│ ├── Analise_sentimento_EDA_1.ipynb # Notebook de Análise Exploratória de Dados 
├── outputs / # datasets 
└── README.md
```
---

## 🚀 Como Executar o Projeto

Siga os passos abaixo para configurar o ambiente e executar o notebook de análise.

### 1. Clonar o Repositório

```bash
git clone [https://github.com/Fagner608/classificacao_sentimento.git](https://github.com/Fagner608/classificacao_sentimento.git)
cd classificacao_sentimento
```

### 2. Crie e ative um ambiente virtual (ex: com conda)
```bash
conda create -n sentiment_env python=3.9
conda activate sentiment_env
```

### 3. Instale as dependências (assumindo que há um requirements.txt)
```bash
pip install -r requirements.txt
```
Se não houver, você pode instalar as bibliotecas principais manualmente:
**pip install pandas numpy matplotlib seaborn nltk scikit-learn jupyter**

### 4. Execute
```bash
jupyter notebook
```


## 🚀 Em andamento o EDA Parte 2 (nível intermediário)
