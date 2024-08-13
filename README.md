# Extração e Analise do IFIX


Esse projeto extrai e análisa o desempenho dos fundos de investimento que compõem o índice IFIX da B3. Este projeto realiza as seguintes etapas:

- Coleta de Dados dos Ativos: Obtém a lista de todos os fundos imobiliários que fazem parte do IFIX diretamente do site da B3.

- Download de Dados de Cotação: Utiliza a biblioteca yfinance para baixar dados históricos de cotações dos fundos listados.

- Análise de Rentabilidade: Calcula e lista os 10 fundos mais rentáveis durante o período configurado.

- Normalização dos Dados: Normaliza os dados de rentabilidade para facilitar a comparação entre os fundos.

- Visualização: Plota um gráfico mostrando a rentabilidade dos fundos, proporcionando uma visão clara e intuitiva do desempenho dos fundos.

Funcionalidades
- Listagem de Fundos do IFIX: Identifica e lista todos os fundos que compõem o índice IFIX.
- Baixa os Dados: Faz download dos dados de cotação para cada fundo usando yfinance.
- Ranking de Rentabilidade: Classifica os fundos e exibe os 10 mais rentáveis em um período especificado.
- Normalização e Plotagem: Normaliza os dados para uma comparação justa e cria gráficos de rentabilidade.
