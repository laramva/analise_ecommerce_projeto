# Análise Estatística de Dados de E-commerce

Projeto desenvolvido como parte da prática de análise de dados utilizando Python, Pandas, Seaborn, Matplotlib e ambiente WSL + VS Code.

Este repositório contém:

O dataset tratado

O notebook com toda a análise

Gráficos exploratórios

Modelagem estatística

Etapas completas de preparação, limpeza e visualização dos dados

📌 Objetivo do Projeto

O objetivo do projeto é realizar uma análise estatística completa de um conjunto de dados de um e-commerce, explorando:

Entendimento de variáveis numéricas e categóricas

Preparação e limpeza dos dados

Geração de estatísticas descritivas (média, mediana, moda, variância etc.)

Análise de correlação entre variáveis

Criação de diversos gráficos exploratórios

Construção de um modelo simples de Regressão Linear para prever quantidade de vendas

🧰 Tecnologias Utilizadas
Tecnologia	Uso
Python 3.10	Análise e modelagem
Pandas	Limpeza, tratamento e exploração de dados
Matplotlib / Seaborn	Visualização gráfica
Scikit-Learn	MinMaxScaler, LabelEncoder e Regressão Linear
WSL 2 (Ubuntu)	Ambiente Linux para desenvolvimento
VS Code	IDE padrão do projeto
Git & GitHub	Controle de versão e portfólio
📊 Etapas Realizadas na Análise
1️⃣ Carregamento e exploração do dataset

Leitura do CSV

Verificação de tipos

Identificação de valores nulos

Contagem de valores únicos

2️⃣ Tratamento e preparação dos dados

Conversão de colunas para tipos adequados

Limpeza de formatações incorretas

Criação de colunas derivadas (ex.: Preço calculado)

Remoção de colunas desnecessárias

Transformação de variáveis numéricas com:

MinMaxScaler

Codificação de variáveis categóricas com:

LabelEncoder

Frequência relativa (value_counts)

3️⃣ Análise Estatística

Cálculo de:

Média

Mediana

Moda

Variância

Desvio padrão

Quartis

Correlação entre variáveis

4️⃣ Visualização de Dados

Foram gerados os seguintes gráficos:

📌 Gráficos produzidos:

Histograma

Gráfico de dispersão

Mapa de calor (heatmap)

Gráfico de barras

Gráfico de pizza

Gráfico de densidade (KDE)

Gráfico de regressão

Cada gráfico contém:
✔ Título
✔ Eixos nomeados
✔ Estilo padronizado

5️⃣ Modelo de Regressão Linear

Separação em treino e teste

Ajuste do modelo com Regressão Linear

Previsão dos valores

Cálculo das métricas:

R² (Coeficiente de Determinação)

RMSE (Raiz do Erro Quadrático Médio)

Desvio padrão da variável alvo

📂 Estrutura do Repositório
📁 analise-ecommerce-projeto
│
├── analise_ecommerce.ipynb   # Notebook completo do projeto
├── ecommerce_estatistica.csv # Dataset utilizado
├── README.md                 # Documentação do projeto
└── (imagens/gráficos, se quiser adicionar)

🚀 Como Executar o Projeto Localmente
1️⃣ Clone o repositório:
git clone https://github.com/laramva/analise-ecommerce-projeto.git

2️⃣ Entre na pasta:
cd analise-ecommerce-projeto

3️⃣ Instale as dependências:
pip install pandas matplotlib seaborn scikit-learn

4️⃣ Abra o notebook:
jupyter notebook


Ou abra pelo VS Code usando a extensão de Jupyter.

📈 Resultados Obtidos

A análise permitiu:

Identificar padrões de venda

Visualizar relações entre avaliações, preço e quantidade vendida

Criar insights sobre comportamento dos produtos

Construir um modelo simples que prevê a quantidade vendida com base em variáveis tratadas
