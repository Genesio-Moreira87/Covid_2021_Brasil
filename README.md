Painel COVID
### **1. Contexto**
Painel COVID Brasil 2021

O Painel COVID é um projeto dedicado à análise exploratória de dados relacionados à pandemia de COVID-19. O objetivo principal é fornecer uma visão abrangente e interativa das tendências, padrões e estatísticas associadas à propagação do vírus em diferentes regiões.

### **Descrição do Problema:**
A pandemia de COVID-19, causada pelo coronavírus SARS-CoV-2, teve um impacto global significativo na saúde pública, na economia e na sociedade como um todo. O acompanhamento e análise dos dados relacionados ao COVID-19 são cruciais para entender a evolução da doença, identificar áreas de maior impacto e avaliar a eficácia das medidas de contenção.

### **Objetivos do Painel:**

**Monitoramento Global**: Apresentar uma visão geral da situação global, destacando o número total de casos confirmados, recuperados e óbitos.

**Análise por Região**: Permitir a análise detalhada da situação em diferentes regiões, incluindo países, estados ou províncias, destacando variações nas taxas de infecção, mortalidade e recuperação.

**Tendências Temporais**: Apresentar gráficos interativos para visualizar as tendências ao longo do tempo, identificando picos, declínios e possíveis padrões sazonais.

**Comparação de Medidas**: Analisar a eficácia de diferentes medidas de contenção adotadas por diferentes regiões e países, como lockdowns, distanciamento social e campanhas de vacinação.

**Informações Demográficas**: Integrar dados demográficos para entender como diferentes grupos populacionais são afetados, considerando fatores como idade, sexo e condições de saúde pré-existentes.


### **1.2. Dados**

Os dados sobre **casos da COVID-19** são compilados pelo centro de ciência de sistemas e engenharia da universidade americana **John Hopkins** ([link](https://www.jhu.edu)). Os dados são atualizados diariamente deste janeiro de 2020 com uma granularidade temporal de dias e geográfica de regiões de países (estados, condados, etc.). O website do projeto pode ser acessado neste [link](https://systems.jhu.edu/research/public-health/ncov/) enquanto os dados, neste [link](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_daily_reports). Abaixo estão descritos os dados derivados do seu processamento.

**Colunas** utilizadas para analise:
 - **date**: data de referência;
 - **state**: estado;
 - **country**: país;
 - **population**: população estimada;
 - **confirmed**: número acumulado de infectados;
 - **confirmed_1d**: número diário de infectados;
 - **confirmed_moving_avg_7d**: média móvel de 7 dias do número diário de infectados;
 - **confirmed_moving_avg_7d_rate_14d**: média móvel de 7 dias dividido pela média móvel de 7 dias de 14 dias atrás;
 - **deaths**: número acumulado de mortos;
 - **deaths_1d**: número diário de mortos;
 - **deaths_moving_avg_7d**: média móvel de 7 dias do número diário de mortos;
 - **deaths_moving_avg_7d**: média móvel de 7 dias dividido pela média móvel de 7 dias de 14 dias atrás;
 - **month**: mês de referência;
 - **year**: ano de referência.

- **Autor**: Genésio Moreira Coutinho

- **Linkedin**: [link](https://www.linkedin.com/in/genesio-coutinho-554733124/)

- **Kaggle Notebook**: [link](https://www.kaggle.com/code/genesiomoreira/notebook-dashboard-covid-brasil-2021)

- **Google Colab Notebook**: [link](https://colab.research.google.com/drive/1NZd3X8e0rQh_lFvDPXb-7ZUDCdIhZMAh?usp=sharing)
