# Análise Preditiva de Salários de TI (2024)

![Status do Projeto](https://img.shields.io/badge/status-conclu%C3%ADdo-green)
![Linguagem Principal](https://img.shields.io/badge/linguagem-Python-blue.svg)
![Bibliotecas](https://img.shields.io/badge/libs-Sklearn%20|%20XGBoost-orange)
[![Licença](https://img.shields.io/badge/licen%C3%A7a-MIT-blue)](./LICENSE)

> Um notebook de machine learning que compara o desempenho de três modelos de regressão (Linear, Random Forest e XGBoost) para prever salários na área de tecnologia.

---

## 📜 Sobre o Projeto

Este projeto é um exercício completo de machine learning focado em um problema de **regressão**: a previsão de salários (`salary_in_usd`) com base no dataset "Dataset salary 2024".

O objetivo principal foi seguir todo o fluxo de trabalho de ciência de dados:
1.  **Carregar** e inspecionar os dados.
2.  **Pré-processar** as *features*, tratando colunas categóricas com `LabelEncoder`.
3.  **Treinar** e **avaliar** três modelos de regressão diferentes.
4.  **Comparar** seus resultados objetivamente usando métricas (MAE, MSE, R²).
5.  **Interpretar** visualmente os resultados para determinar o modelo mais eficaz e as *features* mais importantes.

---

## ✨ Funcionalidades Principais

* **Pré-processamento:** Limpeza de dados e codificação de 6 colunas categóricas (como `job_title` e `experience_level`).
* **Treinamento de Modelos:** Implementação de:
    * `LinearRegression` (Regressão Linear)
    * `RandomForestRegressor` (Floresta Aleatória)
    * `XGBRegressor` (XGBoost)
* **Avaliação de Métricas:** Geração de uma tabela comparativa com os valores de **MAE** (Erro Absoluto Médio), **MSE** (Erro Quadrático Médio) e **R²** (Coeficiente de Determinação).
* **Análise Visual Dinâmica:** Geração automática de gráficos de diagnóstico (Real vs. Predito, Resíduos, Importância das Features) para o **modelo de melhor desempenho** identificado.
* **Análise Complementar:** Geração de gráficos de diagnóstico para os modelos de desempenho inferior, permitindo uma análise completa.

---

## 🚀 Tecnologias Utilizadas

* **Linguagem:** **Python 3**
* **Bibliotecas de Análise:**
    * **Pandas:** Para carregamento e manipulação de dados.
    * **NumPy:** Para operações numéricas.
* **Bibliotecas de Machine Learning:**
    * **Scikit-learn (sklearn):** Para `train_test_split`, `LabelEncoder`, `LinearRegression`, `RandomForestRegressor` e métricas.
    * **XGBoost:** Para `XGBRegressor`.
* **Bibliotecas de Visualização:**
    * **Matplotlib:** Para a base dos gráficos.
    * **Seaborn:** Para visualizações estatísticas mais atraentes.
* **Ambiente:**
    * **Jupyter Notebook** / **Google Colab**

---

## ⚙️ Como Executar o Projeto Localmente

**Pré-requisitos:**
* [Python 3.x](https://www.python.org/)
* `pip` (gerenciador de pacotes)
* [Jupyter Notebook](https://jupyter.org/install) (ou Google Colab)
* O arquivo `Dataset salary 2024.csv` no mesmo diretório.

**Passos:**

1.  **Clone o repositório (exemplo):**
    ```bash
    git clone https://github.com/jmtmds/Data-Science.git
    ```
2.  **Navegue até a pasta do projeto:**
    ```bash
    cd [NOME-DO-REPOSITORIO]
    ```
3.  **Instale as dependências:**
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn xgboost
    ```
4.  **Inicie o servidor Jupyter:**
    ```bash
    jupyter notebook
    ```
5.  **Execute o Notebook:**
    * Abra o arquivo `.ipynb` no seu navegador.
    * Execute a célula de instalação (`!pip install xgboost`) primeiro (se estiver no Colab).
    * Execute as demais células em ordem.

---

## 📄 Licença

Este projeto está sob a licença MIT.

---

## 👨‍💻 Autor

**João Marcos Tavares**

* **LinkedIn:** [linkedin.com/in/jmtmd](https://www.linkedin.com/in/jmtmds)
* **Email:** [jm3tavares@gmail.com](mailto:jm3tavares@gmail.com)
* **GitHub:** [github.com/jmtmds](https://github.com/jmtmds)
