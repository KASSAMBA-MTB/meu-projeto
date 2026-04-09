# 🚗 Classificação de Aceitabilidade de Carros com Árvore de Decisão

## 📌 Descrição do Projeto

Este projeto tem como objetivo aplicar técnicas de **Aprendizado de Máquina Supervisionado** para classificar a aceitabilidade de veículos com base em diferentes atributos.

O modelo foi desenvolvido utilizando o algoritmo **Decision Tree Classifier**, da biblioteca *scikit-learn*.

---

## 🧠 Tecnologias Utilizadas

* Python
* Pandas
* Matplotlib
* Scikit-learn
* Google Colab

---

## 📊 Base de Dados

* Dataset: Avaliação de carros
* Fonte: Repositório público no GitHub
* Atributos utilizados:

  * Preço
  * Manutenção
  * Número de portas
  * Capacidade de pessoas
  * Bagageiro
  * Segurança

---

## ⚙️ Pré-processamento

Os dados categóricos foram convertidos para valores numéricos para permitir o treinamento do modelo.

Exemplo de transformação:

* baixo → 0
* medio → 1
* alto → 2
* muitoalto → 3

---

## 🔀 Divisão dos Dados

* Treinamento: 90%
* Teste: 10%
* Método: `train_test_split`

---

## 🌳 Modelo de Machine Learning

* Algoritmo: Árvore de Decisão
* Biblioteca: scikit-learn

---

## 🌳 Visualização da Árvore de Decisão

> ⚠️ Observação: a imagem abaixo representa a estrutura completa da árvore gerada pelo modelo.

![Árvore de Decisão](Arvore.png)

---

## 📈 Resultados

### 🔹 Exemplos de Predição

Entrada:
[0, 0, 5, 5, 2, 2]
Saída: **muitobom**

Entrada:
[0, 0, 5, 5, 2, 0]
Saída: **inaceitavel**

---

### 🎯 Acurácia do Modelo

**98,3%**

---

## 📉 Análise Crítica

Apesar da alta acurácia, é importante considerar:

* O dataset possui estrutura relativamente simples
* Possível ocorrência de overfitting
* Não foi utilizada validação cruzada

### 🔍 Melhorias Futuras:

* Aplicar **K-Fold Cross Validation**
* Testar outros algoritmos:

  * Random Forest
  * K-Nearest Neighbors (KNN)
* Ajustar hiperparâmetros do modelo

---

## 📁 Estrutura do Projeto

```
├── notebook.ipynb
├── script.py
├── README.md
└── Arvore.png
```

---

## 👨‍💻 Autor

Walter Junio Pontes Teixeira

---

## 📌 Considerações Finais

O modelo apresentou excelente desempenho na tarefa de classificação, demonstrando a eficácia das Árvores de Decisão em problemas com dados estruturados.

Este projeto reforça a importância do pré-processamento e da escolha adequada do algoritmo para obtenção de bons resultados em Aprendizado de Máquina.
