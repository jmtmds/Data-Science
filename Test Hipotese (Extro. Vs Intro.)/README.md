# Teste de Hipótese (Extrovertidos vs. Introvertidos)

![Status do Projeto](https://img.shields.io/badge/status-conclu%C3%ADdo-green)
![Linguagem Principal](https://img.shields.io/badge/linguagem-Python-blue.svg)
![Bibliotecas](https://img.shields.io/badge/libs-SciPy%20|%20Pandas-orange)
[![Licença](https://img.shields.io/badge/licen%C3%A7a-MIT-blue)](./LICENSE)

> Uma análise estatística para determinar se existe uma diferença significativa (ex: no tempo de uso de um app ou pontuação em um teste) entre usuários extrovertidos e introvertidos.

---

## 📜 Sobre o Projeto

Este projeto é um exercício focado em **estatística inferencial** e **teste de hipótese**. O objetivo é usar métodos estatísticos formais para validar (ou rejeitar) uma suposição.

O fluxo de trabalho seguiu os passos clássicos de um teste A/B ou teste de grupo:
1.  **Carregar** e limpar os dados.
2.  **Formular Hipóteses:** Definir a Hipótese Nula (H₀) e a Hipótese Alternativa (H₁).
3.  **Visualizar:** Criar boxplots para comparar visualmente as distribuições dos dois grupos.
4.  **Testar:** Aplicar o teste estatístico apropriado (ex: Teste T de Student) para obter um **p-value**.
5.  **Interpretar:** Concluir se a diferença observada é estatisticamente significativa.

---

## ✨ Funcionalidades Principais

* **Limpeza de Dados:** Preparação do dataset para análise, filtrando e tratando valores ausentes.
* **Formulação de Hipótese:**
    * **H₀ (Hipótese Nula):** Não há diferença significativa entre a média dos extrovertidos e introvertidos.
    * **H₁ (Hipótese Alternativa):** Existe uma diferença significativa entre as médias.
* **Teste Estatístico:** Implementação do `ttest_ind` (Teste T para amostras independentes) da biblioteca **SciPy**.
* **Análise de Resultado:** Interpretação do **p-value** e do **T-statistic** para tomar uma decisão estatística.
* **Visualização Comparativa:** Uso de `boxplot` e `histplot` (Seaborn) para ilustrar as diferenças ou semelhanças entre os grupos.

---

## 🚀 Tecnologias Utilizadas

* **Linguagem:** **Python 3**
* **Bibliotecas de Análise:**
    * **Pandas:** Para carregamento e manipulação de dados.
    * **NumPy:** Para operações numéricas.
    * **SciPy (stats):** Para a execução do teste T.
* **Bibliotecas de Visualização:**
    * **Matplotlib:** Para a base dos gráficos.
    * **Seaborn:** Para visualizações estatísticas.
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
    pip install pandas numpy scipy matplotlib seaborn
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
