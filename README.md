# 📘 Projeto 2 — Esteira de Machine Learning  
## Previsão de Popularidade de Livros Best-sellers da Amazon

Este projeto implementa uma esteira completa de aprendizado de máquina utilizando o dataset **Amazon Top 50 Bestselling Books (2009–2019)** do Kaggle.  
O objetivo é prever se um livro é **Popular (1)** ou **Não Popular (0)** com base em suas características.

O desenvolvimento e a execução do projeto foram realizados integralmente no **Google Colab**.

---

## 🧩 Etapas implementadas

- **Escolha da base (Kaggle)**
- **Estatísticas descritivas**
- **Transformações nos dados**
  - Colunas: *Label Encoding* + criação da coluna `Popular`
  - Linhas: remoção de nulos, preços inválidos e outliers
- **Divisão do conjunto de dados**
  - Treino (70%)
  - Validação (15%)
  - Teste (15%)
- **Treinamento do modelo Random Forest**
- **Avaliação do modelo**
  - Matriz de confusão
  - Acurácia
- **Predição final** usando um exemplo real do conjunto de teste

---

## ▶ Como reproduzir

### 1. Baixe o notebook deste repositório

### 2. Baixe o dataset original no Kaggle  
👉 **https://www.kaggle.com/datasets/sootersaalu/amazon-top-50-bestselling-books-2009-2019**

O arquivo utilizado é:  
`bestsellers with categories.csv`

---

## ▶ Execução no Google Colab

1. Acesse o Google Colab  
2. Faça **upload do notebook (.ipynb)**  
3. Execute as células na ordem  
4. Quando solicitado, faça **upload do arquivo**:  
   **`bestsellers with categories.csv`**

---

