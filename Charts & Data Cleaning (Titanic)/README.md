# Análise Exploratória e Limpeza (Dataset Titanic)

![Status do Projeto](https://img.shields.io/badge/status-conclu%C3%ADdo-green)
![Linguagem Principal](https://img.shields.io/badge/linguagem-Python-blue.svg)
![Bibliotecas](https://img.shields.io/badge/libs-Pandas%20|%20Seaborn-orange)
[![Licença](https://img.shields.io/badge/licen%C3%A7a-MIT-blue)](./LICENSE)

> Um notebook clássico de data science focado em limpeza de dados (data cleaning), análise exploratória (EDA) e visualização de insights com o dataset do Titanic.
> 
---

## 📜 Sobre o Projeto

Este projeto é um exercício fundamental em ciência de dados, utilizando o famoso dataset do Titanic. O foco não é a modelagem preditiva, mas sim as etapas cruciais que a antecedem: **limpeza de dados** e **análise exploratória (EDA)**.

O objetivo é transformar um dataset "sujo" e complexo em dados prontos para análise, e, no processo, extrair *insights* e responder perguntas através de visualizações.

Perguntas respondidas incluem:
* A classe social (`Pclass`) influenciou na sobrevivência?
* O sexo (`Sex`) foi um fator determinante?
* Houve diferença na sobrevivência com base na idade (`Age`)?

---

## ✨ Funcionalidades Principais

* **Limpeza de Dados (Data Cleaning):**
    * **Imputação:** Preenchimento inteligente de valores nulos (ex: `Age` preenchido com a mediana).
    * **Tratamento de Nulos:** Preenchimento de `Embarked` com a moda e remoção da coluna `Cabin` (excesso de nulos).
* **Engenharia de Features (Feature Engineering):**
    * Criação de novas colunas, como `FamilySize` (combinando `SibSp` e `Parch`), para simplificar a análise.
* **Análise Exploratória (EDA):**
    * Investigação de correlações entre variáveis (ex: `Pclass` vs. `Survived`).
    * Análise da distribuição de variáveis numéricas (ex: `Age`, `Fare`).
* **Visualização de Dados (Charts):**
    * `countplot` (Seaborn) para visualizar a sobrevivência por categorias (Sexo, Classe).
    * `histplot` (Seaborn) para entender a distribuição de idade dos passageiros.
    * `heatmap` (Seaborn) para mostrar a matriz de correlação entre as *features*.

---

## 🚀 Tecnologias Utilizadas

* **Linguagem:** **Python 3**
* **Bibliotecas de Análise:**
    * **Pandas:** Para carregamento, limpeza e manipulação de dados.
    * **NumPy:** Para operações numéricas.
* **Bibliotecas de Visualização:**
    * **Matplotlib:** Para a base dos gráficos.
    * **Seaborn:** Para visualizações estatísticas (countplots, heatmaps, boxplots).
* **Ambiente:**
    * **Jupyter Notebook** / **Google Colab**

---

## ⚙️ Como Executar o Projeto Localmente

**Pré-requisitos:**
* [Python 3.x](https://www.python.org/)
* `pip` (gerenciador de pacotes)
* [Jupyter Notebook](https://jupyter.org/install)

**Passos:**

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/jmtmds/Data-Science.git
    ```
2.  **Navegue até a pasta do projeto:**
    ```bash
    cd [NOME-DO-REPOSITORIO]
    ```
3.  **Instale as dependências:**
    ```bash
    pip install pandas numpy matplotlib seaborn
    ```
4.  **Inicie o servidor Jupyter:**
    ```bash
    jupyter notebook
    ```
5.  **Execute o Notebook:**
    * Abra o arquivo `.ipynb` no seu navegador e execute as células.

---

## 📄 Licença

Este projeto está sob a licença MIT.

---

## 👨‍💻 Autor

**João Marcos Tavares**

* **LinkedIn:** [linkedin.com/in/jmtmds](https://www.linkedin.com/in/jmtmds)
* **Email:** [jm3tavares@gmail.com](mailto:jm3tavares@gmail.com)
* **GitHub:** [github.com/jmtmds](https://github.com/jmtmds)
