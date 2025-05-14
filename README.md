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

## 📊 Análises Realizadas

### 1. Descrição dos Dados

- Colunas com dados faltantes:
  - `Valor de Compra`: 100% faltantes
  - `Complemento`: ~77% faltantes
- Foco em variáveis principais: `Produto`, `Valor de Venda`, `Bandeira`, `Região`

### 2. Preço Médio por Região

- Cálculo do preço médio por tipo de combustível em cada região
- Tendência de preços menores em regiões próximas a refinarias e centros de distribuição

### 3. Distribuição Regional da Venda

- A região Sudeste possui a maior quantidade de registros
- Gráfico de pizza mostra a representatividade de cada região

### 4. Participação dos Tipos de Combustível

- Gasolina (comum e aditivada) lidera o mercado
- Etanol aparece em segundo
- GNV tem baixa participação

### 5. Evolução dos Preços ao Longo do Ano

- Queda nos preços entre maio e julho
- Retomada no segundo semestre
- Etanol é o mais barato; GNV apresenta maior estabilidade

### 6. Preço por Bandeira

- Cálculo dos preços médios por bandeira
- Algumas bandeiras têm preços significativamente maiores, outras se aproximam da média geral

## 📦 Tecnologias Utilizadas

- Linguagem: **R**
- Bibliotecas: `tidyverse`, `lubridate`, `ggplot2`, `flextable`
- Documentação: **RMarkdown**

## 📌 Conclusões

- O preço dos combustíveis varia conforme região, tipo de produto e bandeira do posto
- A análise oferece base para decisões logísticas, políticas públicas e compreensão do mercado de combustíveis no Brasil
