📊 Análise de Evasão de Clientes — Telecom X
🧠 Visão Geral

Este projeto realiza uma Análise Exploratória de Dados (EDA) sobre a base de clientes da empresa fictícia Telecom X, uma operadora de telecomunicações que enfrenta altos índices de evasão de clientes (churn).
O objetivo é identificar padrões de comportamento, fatores de risco e perfis de clientes mais propensos ao cancelamento, fornecendo insights estratégicos para apoiar decisões de negócio e futuras soluções analíticas.

O projeto segue as etapas clássicas de um pipeline de análise de dados: extração, limpeza, análise e comunicação de resultados.

🎯 Objetivos do Projeto

Analisar a distribuição da evasão de clientes na base de dados

Identificar perfis com maior propensão ao churn

Avaliar o impacto de variáveis contratuais, financeiras e de serviços

Gerar insights acionáveis para estratégias de retenção

Consolidar os resultados de forma clara e estruturada

🛠️ Tecnologias Utilizadas

Python

Pandas — limpeza e manipulação de dados

Matplotlib & Seaborn — visualização de dados

Google Colab — ambiente de desenvolvimento

Git & GitHub — versionamento e publicação

📂 Estrutura do Projeto
📁 telecomx-churn-analysis
├── 📄 TelecomX_Data.json     # Dataset original
├── 📄 notebook.ipynb         # Notebook com a análise completa
├── 📄 README.md              # Documentação do projeto
└── 📄 relatorio_final.md/pdf # Relatório final (opcional)

🔄 Etapas da Análise

Extração dos Dados

Importação do dataset no formato JSON

Limpeza e Tratamento

Padronização de variáveis categóricas

Conversão de tipos de dados

Tratamento de valores ausentes e inconsistentes

Criação de variáveis derivadas (ex: gastos diários)

Análise Exploratória (EDA)

Distribuição geral do churn

Análise por tipo de contrato, forma de pagamento e serviços

Avaliação de variáveis numéricas como tempo de contrato e cobranças

Uso de gráficos (barras, boxplots, histogramas)

Conclusões e Insights

Interpretação dos resultados

Recomendações estratégicas para redução da evasão

📈 Principais Insights

Clientes com contrato mensal (Month-to-month) apresentam maior taxa de churn

Clientes com menor tempo de permanência cancelam com mais frequência

Cobranças mensais elevadas estão associadas a maior evasão

Ausência de serviços adicionais (suporte técnico, segurança) aumenta o risco

Pagamento via Electronic Check apresenta maior taxa de cancelamento

📌 Conclusão

A análise indica que a evasão de clientes na Telecom X está fortemente relacionada a fatores contratuais, financeiros e de experiência do usuário.
Os resultados obtidos podem servir de base tanto para estratégias de retenção quanto para o desenvolvimento futuro de modelos preditivos de churn.

🚀 Próximos Passos

Desenvolvimento de modelos de Machine Learning para previsão de churn

Feature engineering avançado

Balanceamento de classes

Avaliação de métricas de classificação

👤 Autor

Kaique
Técnico em Desenvolvimento de Sistemas
Graduando em Sistemas de Informação
Interesse em Análise de Dados, Data Science e Desenvolvimento de Software

📌 Projeto desenvolvido para fins de estudo e portfólio.
