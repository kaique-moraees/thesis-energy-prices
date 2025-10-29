# ⚡ Aplicação de Árvores de Hoeffding para Predição de Preços de Energia Elétrica sob Mudanças de Conceito

<p align="justify">
O mercado de energia elétrica caracteriza-se por alta volatilidade e complexidade estrutural, tornando a previsão precisa de preços essencial para formulação de estratégias comerciais e mitigação de riscos financeiros. Abordagens tradicionais de aprendizado de máquina, como ARIMA e SVMs, frequentemente assumem estacionariedade dos dados, hipóteses que se tornam nulas em ambientes sujeitos a mudanças estruturais, sazonalidades complexas e fenômenos de deriva de conceito.
</p>

<p align="justify">
Este trabalho investiga a aplicabilidade de <strong>Árvores de Hoeffding</strong> e a variante <strong>Árvores Adaptativas de Hoeffding</strong> para predição de preços de energia elétrica considerando as eventuais mudanças de conceito. O objetivo é avaliar comparativamente o desempenho preditivo dos algoritmos de Hoeffding, verificando se a incorporação de mecanismos de detecção e adaptação a mudanças de conceito resulta em desempenho superior.
</p>

<p align="justify">
A metodologia, estruturada segundo os frameworks <strong>CRISP-DM</strong> e <strong>KDD</strong>, utiliza o dataset público <em><strong>"Hourly energy demand generation and weather"</strong></em> da Espanha, contendo 35.000 observações horárias de 2015 a 2018. Os modelos serão avaliados por métricas quantitativas (<strong>RMSE, MAE, MAPE, R²</strong>) e análises de adaptação a mudanças de conceito, incluindo tempo de recuperação e substituições de ramos.
</p>

<p align="justify">
Espera-se demonstrar que <strong>algoritmos adaptativos incrementais</strong> apresentam vantagens significativas em ambientes não estacionários, contribuindo para o avanço teórico e prático em predição de séries temporais energéticas.
</p>

---

## 🧩 Metodologia

- Melhorar o suporte de navegadores  
- Adicionar mais integrações  

---

## 🧠 Stack Utilizada

Uma stack de ML é composta por diversas categorias de ferramentas que cobrem o ciclo de vida completo de um projeto — desde a coleta de dados até a avaliação dos modelos.

---

### 🧱 1. Aquisição e Armazenamento de Dados

Ferramentas e infraestruturas para **coletar, armazenar e gerenciar dados**.

- **Dataset Público:** Python (pandas, Dask, PySpark) 

---

### 🧹 2. Engenharia e Processamento de Dados

Para **limpeza, transformação e pré-processamento** dos dados.

- **Linguagens / bibliotecas:** Python (pandas, Dask, PySpark), R  
- **Frameworks distribuídos:** Apache Spark, Ray, Flink  
- **Feature stores:** Feast, Tecton, Hopsworks

---

### 🤖 3. Modelagem e Treinamento

Ambientes e frameworks usados para **criar e treinar modelos de ML**.

- **Frameworks de ML / DL:** Scikit-learn, TensorFlow, PyTorch, XGBoost, LightGBM  
- **Ambientes de experimentação:** Jupyter, Colab, VS Code, MLflow, Weights & Biases  
- **Gerenciamento de experimentos:** MLflow, Neptune.ai, Comet.ml

---

### 🧮 4. Validação e Avaliação

Ferramentas para **avaliar performance e garantir qualidade** do modelo.

- **Validação de dados e modelos:** Great Expectations, Deepchecks  
- **Métricas e visualização:** matplotlib, seaborn, Plotly, SHAP, LIME

---

## 👨‍💻 Autores

- [Kaique Moraes](https://www.linkedin.com/in/kaiquemoraesti/)

---

## 🪪 Licença

[MIT](https://choosealicense.com/licenses/mit/)

---

## 🏷️ Etiquetas

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)  
[![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://www.python.org/)  
[![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Hoeffding%20Trees-orange.svg)]()
