# Modelo Preditivo para Crescimento de Receita da Magazine Luiza (MGLU3)

## 📊 Análise Crítica da Extrapolação Linear no E-commerce

Este projeto visa a análise crítica e a modelagem preditiva do crescimento da Receita Líquida da Magazine Luiza (MGLU3), explorando a relação com variáveis macroeconômicas e indicadores de saúde financeira. O objetivo é demonstrar a limitação da Extrapolação Linear em um setor volátil como o e-commerce e validar o crescimento com modelos não-lineares.

## 📁 Estrutura do Repositório

O repositório está organizado para facilitar a navegação e a reprodutibilidade do projeto:

| Diretório | Conteúdo |
| :--- | :--- |
| **Data/** | Arquivos CSV brutos e tratados utilizados como *input* para as análises. |
| **graficos/** | Imagens (`.png`, `.jpg`) das plotagens e visualizações geradas. |
| **Notebooks/** | Scripts de análise em formato Jupyter Notebook (`.ipynb`), numerados na ordem de execução. |
| **Relatorio_Tecnico/** | Documento (`.pdf`) detalhando a metodologia, análise dos dados, resultados e conclusões do projeto. |

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


| Modelo | Métrica | Valor (%) |
| :--- | :--- | :--- |
| Random Forest | R² (Acurácia) | 0.92 |
| Regressão Linear | R² (Acurácia) | 0.78 |


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

### 5. Recomendações e Próximos Passos

Para análises futuras, é recomendado:

Explorar Modelos Não-Lineares Avançados: Utilizar modelos como XGBoost ou Prophet para conferir as projeções e capturar nuances não lineares do mercado.

Validação Contínua: Estabelecer uma rotina de validação anual com novos dados reais, garantindo a adaptação do modelo às novas dinâmicas macroeconômicas.
