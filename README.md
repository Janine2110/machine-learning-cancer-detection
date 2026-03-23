# 🧠 Classificação de Câncer de Mama com Machine Learning

Este projeto utiliza algoritmos de Machine Learning para classificar tumores como **benignos** ou **malignos**, com base no dataset `Breast Cancer Wisconsin`.

## 📌 Tecnologias utilizadas

* Python
* Scikit-learn
* NumPy

## 📊 Dataset

O dataset utilizado é o **Breast Cancer Wisconsin**, disponível na biblioteca `sklearn.datasets`.

Ele contém:

* 569 amostras
* 30 atributos numéricos
* Classes: **maligno** e **benigno**

---

## ⚙️ Como funciona

O projeto segue as seguintes etapas:

1. **Carregamento dos dados**
2. **Separação em treino e teste**
3. **Normalização dos dados (StandardScaler)**
4. **Treinamento de modelos**

   * K-Nearest Neighbors (KNN)
   * Árvore de Decisão
5. **Avaliação dos modelos com acurácia**

---

## 🤖 Modelos utilizados

### 🔹 KNN (K-Nearest Neighbors)

* `n_neighbors = 18`
* `weights = "distance"`

### 🌳 Árvore de Decisão

* `max_depth = 4`
* `criterion = "gini"`

---

## 📈 Resultados

O código imprime a acurácia dos modelos, por exemplo:

```
Acurácia do Modelo Knn: XX.XX%
Acurácia do Modelo Árvore de Decisão: XX.XX%
```

---
## 🎯 Objetivo

Comparar diferentes algoritmos de classificação e analisar seu desempenho em um problema real de diagnóstico médico.

---

## ✍️ Autor

Janine Veigas Farias
Miguel Rubim Vencato

---
