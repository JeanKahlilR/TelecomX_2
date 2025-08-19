# 📊 Challenge Telecom X - Parte 2: Prevendo Churn
Este repositório contém a solução desenvolvida para o desafio da formação One Tech Foundation - Especialização em Data Science, 
uma parceria entre Alura e Oracle Next Education (ONE).

## 🎯 Missão
A Telecom_X, empresa do setor de telecomunicações, enfrenta altos índices de cancelamento (churn). A missão é
desenvolver modelos preditivos capazes de prever quais clientes têm maior chance de cancelar seus serviços para ajudar
a empresa a antecipar problemas de evasão.

## 🔍 Objetivo
. Preparar os dados para a modelagem (tratamento, encoding, normalização).
- Realizar análise de correlação e seleção de variáveis.
- Treinar dois ou mais modelos de classificação.
- Avaliar o desempenho dos modelos com métricas.
- Interpretar os resultados, incluindo a importância das variáveis.
- Criar uma conclusão estratégica apontando os principais fatores que influenciam a evasão.

## 🛠️ Tecnologias Utilizadas
 [![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
 [![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org/)
 [![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
 [![XGBoost](https://img.shields.io/badge/XGBoost-%1b1e23.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)](https://xgboost.ai/)

 [![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)](https://matplotlib.org/)
 [![Seaborn](https://img.shields.io/badge/Seaborn-8B1A1A?style=for-the-badge&logo=python&logoColor=white)](https://seaborn.pydata.org/)
 [![Jupyter Notebook](https://img.shields.io/badge/Jupyter-F37626.svg?style=for-the-badge&logo=Jupyter&logoColor=white)](https://jupyter.org/)

## 📂 Conjunto de Dados
O conjunto de dados esta no repositorio no formato csv, separador padrão e com o nome: `DadosChurn.csv`

#### Dicionario de dados:
* `ID_cliente`: número de identificação único de cada cliente
* `churn`: se o cliente deixou ou não a empresa
* `genero`: gênero (masculino e feminino)
* `idoso`: informação sobre um cliente ter ou não idade igual ou maior que 65 anos
* `possui_parceiro`: se o cliente possui ou não um parceiro ou parceira
* `possui_dependentes`: se o cliente possui ou não dependentes
* `servico_telefonico`: se o cliente possui serviço telefonico
* `multiplas_linhas`: se o cliente possui linha telefonica
* `servico_internet`: se o cliente possui serviço de internet
* `DSL`: se o cliente possui consexão de internet DSL
* `fibra_otica`: se o cliente possui conexão de internet Fibra Otica
* `segurança_online`: assinatura adicional de segurança online
* `backup_online`: assinatura adicional de backup online
* `protecao_do_dispositivo`: assinatura adicional de proteção no dispositivo
* `suporte_tecnico`: assinatura adicional de proteção no dispositivo
* `TV_cabo`: assinatura de TV a cabo
* `streaming_filmes`: assinatura de streaming de filmes 
* `fatura_online`: se recebe fatura online
* `tipo_contrato`: tipo de contrato
* `tempo_contrato`: duração do contrato
* `metodo_pagamento`: forma de pagamento
* `contas_diarias`: custo diario dos serviços
* `conta_mensal`: custo mensal dos serviços
* `total_gasto`: total gasto pelo cliente ate a geração do relatorio
* `Mensal`: contratos mensais
* `Anual`:  contratos anuais
* `Bienal`: contratos bienais
* `total_servicos`: total de serviços contratados

## 🚀 Como Executar

### 📌 Opção 1: Google Colab 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/seu-usuario/telecom-churn-analysis/blob/main/analise_churn.ipynb)

1. Clique no botão **"Open in Colab"** acima
2. Faça login com sua conta Google
3. Clique em **"Runtime" > "Run all"** para executar todo o notebook
4. Para salvar suas alterações:
   - **File > Save a copy in Drive**

### 💻 Opção 2: Execução Local

#### Pré-requisitos
- Python 3.8+
- Jupyter Notebook

#### Passo a passo:
1. Clique em "Code" > "Download ZIP" no GitHub
2. Extraia o arquivo ZIP em sua máquina
3. Na pasta em que foi extraido o arquivo, clique com botão direito e em `Abrir no Terminal`
4. No Terminal digite: `jupyter notebook`
5. Clique no arquivo `Analise_Churn_TeleconX.ipynb`
6. Clique em **"Runtime" > "Run all"** para executar todo o notebook
