📊 Análise Exploratória de Multas Pagas em São Paulo

Projeto de Análise Exploratória de Dados (EDA) desenvolvido em Python com o objetivo de analisar dados de multas pagas no Estado de São Paulo em julho de 2026, identificando padrões relacionados aos municípios, tipos de infrações, veículos e categorias.

O projeto foi desenvolvido como parte do meu portfólio de Análise de Dados, aplicando conceitos de tratamento, exploração, visualização e interpretação de dados.

🎯 Objetivo

O objetivo da análise é explorar a base de multas pagas e responder perguntas como:

Qual é o volume total de ocorrências?
Quais municípios concentram mais ocorrências?
Quais são as infrações mais frequentes?
Quais tipos de veículos aparecem com maior frequência?
Qual é a participação do município de São Paulo no total?
Como fica o ranking dos municípios quando São Paulo é retirado?
Existem diferenças entre as infrações de automóveis e motocicletas?
Existe concentração das ocorrências em poucos tipos de infração?
🛠️ Tecnologias utilizadas
Python
Pandas
NumPy
Matplotlib
Google Colab
Jupyter Notebook
🔎 Etapas do projeto

O projeto foi desenvolvido seguindo as principais etapas de uma análise exploratória:

Importação e carregamento dos dados
Compreensão da estrutura da base
Verificação da qualidade dos dados
Identificação e tratamento de valores ausentes
Verificação de registros duplicados
Criação de indicadores
Análise por município
Análise das infrações
Análise por tipo e categoria de veículo
Análise da UF das placas
Comparação entre automóveis e motocicletas
Análise de São Paulo em relação aos demais municípios
Análise de concentração utilizando o conceito de Pareto
Identificação dos principais insights
Exportação dos resultados
📈 Indicadores da base

A análise identificou:

24.849 registros
208.655 ocorrências
625 municípios
313 tipos de infração

A quantidade de registros da base é diferente da quantidade total de ocorrências, pois a variável QTDE representa a quantidade associada a cada combinação de características presente nos dados.

💡 Principais insights

A análise permitiu identificar alguns padrões relevantes:

O município de São Paulo concentra aproximadamente 70% das ocorrências registradas na base.
Os automóveis apresentam o maior volume de ocorrências, seguidos pelos motociclos.
Veículos da categoria Particular representam a maior parte das ocorrências.
Uma parcela relevante das ocorrências está concentrada em um grupo relativamente pequeno de tipos de infração.
A retirada do município de São Paulo da visualização permite comparar melhor a distribuição das ocorrências entre os demais municípios.
A comparação entre automóveis e motocicletas permite observar diferenças no perfil das principais infrações associadas a cada tipo de veículo.
📊 Análises realizadas

Durante o projeto foram desenvolvidas visualizações e análises para:

Top 10 municípios por quantidade de ocorrências
Top 10 infrações mais frequentes
Distribuição por tipo de veículo
Distribuição por categoria de veículo
Distribuição pela UF da placa
Principais infrações envolvendo automóveis
Principais infrações envolvendo motocicletas
Ranking dos municípios sem a cidade de São Paulo
Participação de São Paulo no total
Concentração das infrações por meio da análise de Pareto
⚠️ Limitações da análise

A base analisada representa apenas julho de 2026. Portanto, não é possível avaliar tendências de crescimento ou redução das ocorrências ao longo do tempo.

Além disso, os resultados utilizam números absolutos de ocorrências.

Por esse motivo, não é possível concluir apenas com esses dados que determinado município possui proporcionalmente maior incidência de infrações.

Para esse tipo de comparação seriam necessárias informações adicionais, como:

frota de veículos;
população;
volume de circulação;
quantidade de veículos por município.
🚀 Próximos passos

Como evolução deste projeto, pretendo:

Incorporar dados de outros meses;
Criar uma análise temporal das ocorrências;
Comparar a evolução mês a mês;
Calcular variações percentuais;
Desenvolver novos indicadores;
Criar um dashboard interativo no Power BI.
📁 Estrutura do projeto
analise-multas-sp/
│
├── README.md
├── analise_multas_sp.ipynb
│
└── dados/
    └── multas_pagas.csv
▶️ Como executar o projeto
Clone ou baixe este repositório.
Abra o arquivo analise_multas_sp.ipynb no Google Colab ou Jupyter Notebook.
Certifique-se de que o arquivo CSV esteja disponível no caminho utilizado pelo notebook.
Execute as células na ordem apresentada.

📌 Sobre o projeto

Este projeto foi desenvolvido com foco na prática das principais etapas de uma análise de dados, desde a preparação e tratamento da base até a construção de visualizações e interpretação dos resultados.

O objetivo é demonstrar conhecimentos em Python, Pandas, análise exploratória de dados e visualização de dados, além da capacidade de transformar dados brutos em informações úteis para tomada de decisão.
