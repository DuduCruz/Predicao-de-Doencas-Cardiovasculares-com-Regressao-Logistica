# Predição-de-Doenças-Cardiovasculares-com-Regressão-Logística
Este projeto utiliza técnicas de Ciência de Dados e Machine Learning para identificar fatores de risco e prever a presença de doenças cardiovasculares com base em dados biológicos e comportamentais de pacientes.

📋 Visão Geral
O objetivo deste projeto foi explorar um dataset de saúde, realizar o pré-processamento adequado (limpeza, padronização e balanceamento) e treinar um modelo de Regressão Logística para classificação binária.

🚀 Tecnologias Utilizadas
Linguagem: Python

Bibliotecas: * Pandas e NumPy para manipulação de dados.

Seaborn e Matplotlib para visualização e análise exploratória.

Scikit-learn para pré-processamento e Machine Learning.

📊 Etapas do Projeto
1. Análise Exploratória (EDA)
Foram realizadas análises bivariadas para entender o impacto de variáveis como consumo de álcool e fumo. Através da Matriz de Correlação, identificamos que a idade, o colesterol e o peso são os principais influenciadores da doença.

2. Pré-processamento
Padronização: As variáveis contínuas (age, height, weight) foram transformadas utilizando o StandardScaler para garantir que todas estivessem na mesma escala que as variáveis binárias.

Balanceamento: Verificou-se que a base de dados já se encontrava balanceada (~50% para cada classe), garantindo um treino justo para o modelo.

3. O Modelo: Regressão Logística
Optou-se pela Regressão Logística por ser um modelo de classificação robusto e altamente interpretável.

Função Sigmóide: Utilizada para transformar a saída linear em uma probabilidade entre 0 e 1.

📈 Resultados e Métricas
O modelo final apresentou um desempenho consistente e clinicamente coerente:

Acurácia: 65.40%

AUC-ROC: ~0.71 (Indica boa capacidade discriminatória).

Principais Preditores:

Colesterol (Coeficiente positivo mais forte)

Peso

Idade

Atividade Física (Fator de proteção/Coeficiente negativo)

Matriz de Confusão
O modelo demonstrou equilíbrio entre Sensibilidade (Recall) e Precisão, conseguindo identificar corretamente a maioria dos pacientes em ambos os grupos.

📂 Como executar o projeto
Clone o repositório: git clone https://github.com/seu-usuario/seu-repositorio.git

Instale as dependências: pip install -r requirements.txt

Execute o notebook: jupyter notebook projeto_cardio.ipynb

✒️ Autor
Seu Nome - (https://www.linkedin.com/in/eduardo-pgc-filho/)
