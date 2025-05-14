# Análise de Preços de Combustíveis no Brasil (2023)

Este projeto realiza uma análise exploratória dos dados de preços de combustíveis vendidos no Brasil em 2023. O objetivo é identificar padrões regionais, comportamentos sazonais e relações entre variáveis como tipo de combustível, região e bandeira do posto.

## 📁 Fonte de Dados

Os dados foram extraídos de dois arquivos compactados:

- `ca-2023-01.zip`
- `ca-2023-02.zip`

OBS: Os arquivos CSV são muito grandes para estarem neste repositório. Você pode baixá-los aqui:

- [ca-2023-01(primeiro semestre) e ca-2023-02(segundo semestre) (Google Drive)](https://drive.google.com/drive/folders/1TSp6xCLFS0PwVoBWzBSeO5ZWuUUJADQG?usp=drive_link)

Eles contêm cerca de **904.000 observações** e **16 variáveis**, com informações como:

- Identificação da revenda
- Localização (estado, município, região)
- Produto comercializado
- Valor de venda
- Data da coleta
- Bandeira do posto

## 📊 Análises Realizadas:

### - Descrição dos Dados
### - Preço Médio por Região
### - Distribuição Regional da Venda
### - Participação dos Tipos de Combustível
### - Evolução dos Preços ao Longo do Ano
### - Preço por Bandeira

## 📦 Tecnologias Utilizadas

- Linguagem: **R**
- Bibliotecas: `tidyverse`, `lubridate`, `ggplot2`, `flextable`
- Documentação: **RMarkdown**
