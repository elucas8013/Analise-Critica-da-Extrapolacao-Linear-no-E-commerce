<a id="english-version"></a>
# 🇺🇸 English Version
 
**[Versão em Português 🇧🇷](#versao-em-portugues)**

# Predictive Model for Revenue Growth at Magazine Luiza (MGLU3)

## 📊 Critical Analysis of Linear Extrapolation in E-commerce

This project aims at the critical analysis and predictive modeling of Magazine Luiza's (MGLU3) net revenue growth, exploring its relationship with macroeconomic variables and financial health indicators. The objective is to demonstrate the limitations of linear extrapolation in a volatile sector like e-commerce and to validate growth using non-linear models.

## 📁 Repository Structure

The repository is organized to facilitate navigation and reproducibility of the project:

| Directory | Content |
| :--- | :--- |
| **Data/** | Raw and processed files (`.CSV`) used as input for the analyses. |
| **Graphics/** | Images (`.png`) of the generated plots and visualizations. |
| **Notebooks/** | Analysis scripts in Jupyter Notebook format (`.ipynb`), numbered in order of execution. |
| **Technical_Report - Relatorio_Tecnico/** | Document (`.pdf`) detailing the methodology, data analysis, results, and conclusions of the project. |

## 🧪 Methodology

The project followed the standard **CRISP-DM (Cross Industry Standard Process for Data Mining)** methodology, encompassing the following application phases:

* **1. Business Understanding:** (Choice of e-commerce and problem definition)
* **2. Data Understanding and Preparation:** (CSV processing and dataset construction)
* **3. Modeling:** (Multiple Linear Regression and Random Forest)
* **4. Evaluation:** (Model Projection and Validation)

## 💻 Technologies and Tools

**Development:**
* **Language:** Python 3.12.3
* **Development Environment:** Visual Studio Code (1.105.1) with `venv` (virtual environment)
* **Documentation (Report):** Onlyoffice (9.1.0.173) and Master PDF Editor (4.3.89 Qt5)

**Main Python Libraries (Details in `requirements.txt`):**
* `pandas`
* `numpy`
* `scikit-learn` (sklearn)
* `matplotlib`
* `seaborn`

## 🛠️ How to Reproduce the Analysis

To successfully reproduce the scripts contained in `./Notebooks/`:

### 1. Preparation and Activation of the Virtual Environment (venv)

**On Linux:**
```bash
# Installs, creates, and activates the virtual environment
sudo apt install python3.12-venv 
python3 -m venv venv
source venv/bin/activate
```
**On Windows:**
```bash
# Creates and activates the virtual environment
python -m venv venv
.\venv\Scripts\activate
```
### 2. Installation of the Premises

With the virtual environment ENABLED (indicated by (venv) in the terminal), install all the libraries:

```bash
pip install -r requirements.txt
```

## 📊 Conclusion of Projections and Metrics

The comparative models showed large discrepancies. The Random Forest model proved to be more stable and aligned with the economic variables, while Linear Extrapolation indicated a clear divergence from the expected reality.

<div style="display: table; margin: 0 auto; margin-bottom: 30px; margin-top: 30px;">

| Model | Metric | Value (%) |
| :--- | :---: | ---: |
| Random Forest | R² (Accuracy) | 0.92 |
| Linear Regression | R² (Accuracy) | 0.78 |

</div>

<div style="width: 100%; overflow: auto; margin-bottom: 50px;">
  
  <div style="width: 50%; float: left; text-align: center; padding-right: 15px; box-sizing: border-box;">
    <h3>Linear Regression</h3>
    <img src="./Graphics/4.1.Projected Annual Revenue Growth for MGLU3 (Until 2030).png" alt="Projeção Linear" width="100%">
  </div>
  
  <div style="width: 50%; float: left; text-align: center; padding-left: 15px; box-sizing: border-box;">
    <h3>Random Forest</h3>
    <img src="./Graphics/4.2.Projected Annual Revenue Growth for MGLU3 (Random Forest - Until 2030).png" alt="Projeção Random Forest" width="100%">
  </div>
</div>

### 5. Recommendations and Next Steps

For future analyses, it is recommended to:

Explore Advanced Non-Linear Models: Use models such as XGBoost or Prophet to check projections and capture non-linear market nuances.

Continuous Validation: Establish an annual validation routine with new real data, ensuring the model adapts to new macroeconomic dynamics.
 
---
Note: This is a machine-translated version, provided for convenience. Please refer to the original Portuguese version for accuracy.
---

<a id="versao-em-portugues"></a>
# 🇧🇷 Versão em Português
 
**[English Version 🇺🇸](#english-version)**

# Modelo Preditivo para Crescimento de Receita da Magazine Luiza (MGLU3)

## 📊 Análise Crítica da Extrapolação Linear no E-commerce

Este projeto visa a análise crítica e a modelagem preditiva do crescimento da Receita Líquida da Magazine Luiza (MGLU3), explorando a relação com variáveis macroeconômicas e indicadores de saúde financeira. O objetivo é demonstrar a limitação da Extrapolação Linear em um setor volátil como o e-commerce e validar o crescimento com modelos não-lineares.

## 📁 Estrutura do Repositório

O repositório está organizado para facilitar a navegação e a reprodutibilidade do projeto:

| Diretório | Conteúdo |
| :--- | :--- |
| **Data/** | Arquivos (`.CSV`) brutos e tratados utilizados como *input* para as análises. |
| **Graphics/** | Imagens (`.png`) das plotagens e visualizações geradas. |
| **Notebooks/** | Scripts de análise em formato Jupyter Notebook (`.ipynb`), numerados na ordem de execução. |
| **Technical_Report - Relatorio_Tecnico/** | Documento (`.pdf`) detalhando a metodologia, análise dos dados, resultados e conclusões do projeto. |

## 🧪 Metodologia

O projeto seguiu a metodologia padrão **CRISP-DM (Cross Industry Standard Process for Data Mining)**, abrangendo as seguintes fases de aplicação:

* **1. Entendimento do Negócio:** (Escolha do e-commerce e definição do problema)
* **2. Entendimento e Preparação de Dados:** (Tratamento dos CSVs e construção do dataset)
* **3. Modelagem:** (Regressão Linear Múltipla e Random Forest)
* **4. Avaliação:** (Projeção e Validação dos Modelos)

## 💻 Tecnologias e Ferramentas

**Desenvolvimento:**
* **Linguagem:** Python 3.12.3
* **Ambiente de Desenvolvimento:** Visual Studio Code (1.105.1) com `venv` (ambiente virtual)
* **Documentação (Relatório):** Onlyoffice (9.1.0.173) e Master PDF Editor (4.3.89 Qt5)

**Bibliotecas Python Principais (Detalhes no `requirements.txt`):**
* `pandas`
* `numpy`
* `scikit-learn` (sklearn)
* `matplotlib`
* `seaborn`

## 🛠️ Como Reproduzir a Análise

Para reproduzir os scripts contidos em `./Notebooks/` com sucesso:

### 1. Preparação e Ativação do Ambiente Virtual (venv)

**No Linux:**
```bash
# Instala, cria e ativa o ambiente virtual
sudo apt install python3.12-venv 
python3 -m venv venv
source venv/bin/activate
```
**No Windows:**
```bash
# Cria e ativa o ambiente virtual
python -m venv venv
.\venv\Scripts\activate
```
### 2. Instalação das Dependências

Com o ambiente virtual ATIVADO (o que é indicado por (venv) no terminal), instale todas as bibliotecas:

```bash
pip install -r requirements.txt
```

## 📊 Conclusão das Projeções e Métricas

Os modelos comparativos apresentaram grandes discrepâncias. O modelo Random Forest mostrou-se mais estável e alinhado com as variáveis econômicas, enquanto a Extrapolação Linear indicou uma clara divergência da realidade esperada.

<div style="display: table; margin: 0 auto; margin-bottom: 30px; margin-top: 30px;">

| Modelo | Métrica | Valor (%) |
| :--- | :---: | ---: |
| Random Forest | R² (Acurácia) | 0.92 |
| Regressão Linear | R² (Acurácia) | 0.78 |

</div>
  
<div style="width: 100%; margin-bottom: 50px;">
    <div style="display: inline-block; width: 49%; text-align: center; vertical-align: top; margin-right: 1%;">
    <h3>Projeção Linear</h3>
    <img src="./Graphics/4.1.Projeção do Crescimento Anual da Receita MGLU3 (Até 2030).png" alt="Projeção Linear" width="100%">
    </div>
    <div style="display: inline-block; width: 49%; text-align: center; vertical-align: top;">
    <h3>Random Forest</h3>
    <img src="./Graphics/4.2.Projeção do Crescimento Anual da Receita MGLU3 (Random Forest - Até 2030).png" alt="Projeção Random Forest" width="100%">
    </div>
</div>

### 5. Recomendações e Próximos Passos

Para análises futuras, é recomendado:

Explorar Modelos Não-Lineares Avançados: Utilizar modelos como XGBoost ou Prophet para conferir as projeções e capturar nuances não lineares do mercado.
Validação Contínua: Estabelecer uma rotina de validação anual com novos dados reais, garantindo a adaptação do modelo às novas dinâmicas macroeconômicas.
