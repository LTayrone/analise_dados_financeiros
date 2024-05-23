# Análise Exploratória de Dados Financeiros

## 1. Introdução
Este projeto visa realizar uma Análise Exploratória de Dados (EDA) em um dataset financeiro. O objetivo é entender melhor os dados, identificar padrões, verificar a presença de outliers e dados nulos, e calcular a correlação entre as variáveis.

## 2. Descrição do Dataset
O dataset contém informações financeiras simuladas com as seguintes colunas:
- **Revenue (Receita)**
- **Expenses (Despesas)**
- **Profit (Lucro)**
- **Assets (Ativos)**
- **Liabilities (Passivos)**
- **Equity (Patrimônio Líquido)**

## 3. Requisitos
- Python 3.7 ou superior
- Jupyter Notebook
- 
Para executar este projeto, você precisará dos seguintes pacotes Python:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scipy`

Você pode instalar todos os pacotes necessários usando o comando:
```bash
pip install pandas numpy matplotlib seaborn scipy
```
## 4. Preparação do Ambiente
Clone este repositório:
```bash
Copiar código
git clone <URL_do_repositório>
cd <nome_do_repositório>
```
Instale as dependências do projeto:

```bash
pip install -r requirements.txt
```

Certifique-se de que todos os pacotes necessários estão instalados.
Coloque o arquivo Financial_Dataset.csv na mesma pasta que o notebook Jupyter.

## 5 - Resultados

Análise Descritiva
- As estatísticas descritivas para o dataset foram calculadas, mostrando a média, mediana, desvio padrão, valores mínimos e máximos.

Testes de Normalidade
- Os testes de Shapiro-Wilk e Kolmogorov-Smirnov indicam que os dados não seguem uma distribuição normal.

Correlação
- A matriz de correlação de Spearman mostrou correlações muito fracas entre as variáveis do dataset.
