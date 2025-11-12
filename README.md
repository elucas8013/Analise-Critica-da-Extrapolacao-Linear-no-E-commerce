# Analise-Critica-da-Extrapolacao-Linear-no-E-commerce
Um projeto que visa a análise crítica e a modelagem preditiva do crescimento da Receita Líquida da Magazine Luiza (MGLU3), explorando a relação com variáveis macroeconômicas e indicadores de saúde financeira.
=======
# Modelo Preditivo para Crescimento de Receita da Magazine Luiza (MGLU3)

## 📊 Análise Crítica da Extrapolação Linear no E-commerce

Este projeto visa a análise crítica e a modelagem preditiva do crescimento da Receita Líquida da Magazine Luiza (MGLU3), explorando a relação com variáveis macroeconômicas e indicadores de saúde financeira.

## 📁 Estrutura do Repositório

| Diretório | Conteúdo |
| :--- | :--- |
| **Data/** | Arquivos CSV brutos e tratados, utilizados para as análises e plotagens. |
| **graficos/** | Plotagens geradas. | 
| **Notebooks/** | Scripts de análise em formato Jupyter Notebook (`.ipynb`), numerados na ordem de execução. |
| **Relatorio_Tecnico/** | Documento (.pdf) detalhando a metodologia, análise dos dados, resultados e conclusões do projeto. |

## 🧪 Metodologia

O projeto seguiu a metodologia **CRISP-DM**, abrangendo as seguintes etapas:

* Escolha do e-commerce para aplicação dos modelos analiticos
* Preparação de Dados
* Análise Macroeconômica
* Modelagem Preditiva (Regressão Linear Múltipla e Random Forest)
* Projeção e Validação

## 💻 Tecnologias e Ferramentas

**Desenvolvimento:**
* **Linguagem:** Python 3.12.3
* **Ambiente de Desenvolvimento:** Visual Studio Code (1.105.1) com `venv` (ambiente virtual)
* **Documentação (Relatório):** Onlyoffice (9.1.0.173) e Master PDF Editor (4.3.89 Qt5)

**Bibliotecas Python Principais:**
* `pandas`
* `numpy`
* `scikit-learn` (sklearn)
* `matplotlib`
* `seaborn`

## 🛠️ Como Reproduzir a Análise

Para reproduzir os scripts contidos em `./Notebooks/`, siga as instruções abaixo:

### 1. Instalação das Dependências (no linux executar o passo 2 primeiro)

pip install -r requirements

### 2. Preparação do Ambiente Virtual (venv)

**No Linux:**
```bash
# Instala o kernel venv (se necessário)
sudo apt install python3.12-venv 

# Cria a chamada venv
python3 -m venv venv

# Habilita o ambiente virtual
source venv/bin/activate
```

## 📊 Conclução das Projeções
A projeção do modelo linear e Random Forest apresentaram grandes discrepancias, sendo o modelo mais estavel o Random Forest, enquanto existe uma clara divergencia da realidade na extrapolação linear:


<table style="width:100%;">
  <tr>
    <td style="width:50%; text-align:center;">
      <img src="https://github.com/elucas8013/Analise-Critica-da-Extrapolacao-Linear-no-E-commerce/blob/main/graficos/4.1.%20Modelagem%20e%20Proje%C3%A7%C3%A3o%20(IA)%20Proje%C3%A7%C3%A3o%20at%C3%A9%202030.png?raw=true?raw=true" alt="Projeção Linear" width="100%">
    </td>
    <td style="width:50%; text-align:center;">
      <img src="https://github.com/elucas8013/Analise-Critica-da-Extrapolacao-Linear-no-E-commerce/blob/main/graficos/4.2.%20Modelagem%20e%20Proje%C3%A7%C3%A3o%20(IA)%20Proje%C3%A7%C3%A3o%20at%C3%A9%202030%20com%20Random%20Forest%20Regressor.png?raw=true" alt="Projeção Random Forest" width="100%">
    </td>
  </tr>
</table>


