# Customer-Churn-Predictor: Inteligência de Retenção para SaaS

![Status do Projeto](https://img.shields.io/badge/Status-Em_Desenvolvimento-yellow)
![Machine Learning](https://img.shields.io/badge/ML-Classificação-green)
![GCP](https://img.shields.io/badge/Cloud-Google_Cloud_Platform-blue)

## 📌 Contexto de Negócio
A retenção de clientes é um dos pilares de crescimento para empresas SaaS. 
Este projeto visa identificar precocemente clientes com alta probabilidade de cancelamento (Churn), permitindo que a equipe de *Customer Success* tome ações preventivas baseadas em dados para reduzir a perda de receita.

## 🚀 Objetivo Técnico
Desenvolver um modelo de Machine Learning de classificação para prever o Churn, utilizando técnicas avançadas de análise exploratória, tratamento de dados e modelagem estatística.

## 🛠️ Data Tech Stack
* **Linguagem:** Python (Pandas, Numpy, Scikit-Learn).
* **Estatística:** Análise de correlação e testes de hipóteses.
* **Modelagem:** Algoritmos de classificação (Random Forest / XGBoost).
* **Infraestrutura Sugerida:** Este modelo foi pensado para ser implementado via pipeline escalável utilizando **Google Cloud Storage e Vertex AI**.

## 📊 Estrutura do Projeto
1.  **EDA (Exploratory Data Analysis):** Identificação de padrões de comportamento e perfis de clientes.
2.  **Data Preprocessing:** Tratamento de dados nulos, Outliers e *Feature Encoding*.
3.  **Modelagem:** Treinamento, validação e tunagem de hiperparâmetros.
4.  **Avaliação:** Análise através de métricas de *Precision*, *Recall* e *F1-Score* para otimização do resultado de negócio.

## 🏗️ Arquitetura de Produção (GCP)
Como diferencial estratégico, o projeto inclui uma proposta de Cloud:
* **Ingestão:** BigQuery / Cloud Storage.
* **Processamento:** Vertex AI Pipelines para automação do ciclo de vida (MLOps).
* **Deploy:** Endpoints gerenciados para predições em tempo real.

---

## 📜 Licença

Distribuído sob a licença [MIT](LICENSE).
Uso livre para fins acadêmicos e pessoais.
