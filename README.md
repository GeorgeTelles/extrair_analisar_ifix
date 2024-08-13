<div>
  <img src="https://raw.githubusercontent.com/GeorgeTelles/georgetelles/f69531ec6b293b5148563588a764c010015d315e/logo_clara.png" alt="logo clara" width="300" style="display: inline-block; vertical-align: top; margin-right: 10px;">
  <img src="https://raw.githubusercontent.com/GeorgeTelles/georgetelles/f69531ec6b293b5148563588a764c010015d315e/logo_dark.png" alt="logo dark" width="300" style="display: inline-block; vertical-align: top;">
</div>

# Extração e Analise do IFIX
<a href="https://github.com/GeorgeTelles/extrair_analisar_ifix/blob/42dc5cc9f1cbb00217c0a16bb362510b94aa8000/Extra%C3%A7%C3%A3o%20e%20analise%20do%20IFIX%20-%20Fundos%20Imobiliarios.ipynb" target="_parent">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab" width="150" style="display: inline-block; vertical-align: top;">
  </a>

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

# O que é o IFIX?

O IFIX representa uma carteira teórica com os fundos imobiliários mais negociados do mercado. Esse índice foi criado pela B3, bolsa de valores brasileira, em 2012, com o objetivo de mostrar o retorno médio dos FIIs. Para isso, ele considera a variação dos preços e a distribuição de dividendos dos fundos imobiliários que compõem a carteira teórica.

A cada quatro meses, essa carteira é revista, ocasiões nas quais são retirados do índice os FIIs que não preenchem mais seus pré-requisitos, e acrescentados os que estão de acordo com os seus critérios.

<img src="https://github.com/GeorgeTelles/extrair_analisar_ifix/blob/1d2a44c43a00abe7ba6bb17d326a4dec464bef1f/output.png">

