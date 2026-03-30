# 🌤️ Análise Climática: Macau e Mossoró (RN)

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Google Colab](https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&color=525252)

## 📋 Sobre o Projeto
Este projeto realiza uma análise exploratória de dados meteorológicos ao longo de um período de 30 anos (1990 - 2019) para as cidades de Macau e Mossoró, no estado do Rio Grande do Norte. O objetivo principal é investigar o comportamento sazonal, calcular acumulados anuais e compreender como o perfil climático influencia as dinâmicas socioeconômicas locais.

As variáveis analisadas incluem:
- Temperatura média (°C)
- Precipitação (mm)
- Radiação solar (MJ/m²)
- Umidade relativa do ar (%)

## 🎯 Objetivos da Análise
1. **Sazonalidade:** Identificação de padrões mensais, períodos de seca/chuva e comparação dos extremos entre as duas cidades.
2. **Acumulado Anual:** Cálculo do volume total de precipitação e radiação ao longo de três décadas, evidenciando as diferenças geográficas.
3. **Interpretação Geral:** Cruzamento dos dados meteorológicos com a vocação econômica dos municípios (indústria salineira vs. fruticultura irrigada).

## 💻 Tecnologias e Bibliotecas Utilizadas
- **Python:** Linguagem base para a análise.
- **Pandas & NumPy:** Limpeza, tratamento (correção de separadores decimais, adequação de datas) e agregação dos dados.
- **Matplotlib:** Criação de gráficos de linhas e barras para visualização de tendências históricas.
- **Plotly:** Construção de painéis interativos (*facets*) para exploração detalhada dos resumos estatísticos.

## 📊 Principais Insights
* **Padrões de Precipitação:** O semestre chuvoso concentra-se na primeira metade do ano, mas atua de forma distinta. Macau atinge seu pico hídrico em março, enquanto Mossoró prolonga o acúmulo pesado de chuvas até junho.
* **Umidade e Temperatura:** Macau apresenta uma forte amplitude na umidade relativa (caindo drasticamente no segundo semestre) e médias de temperatura mais altas. Mossoró mantém uma atmosfera mais úmida e estável ao longo do ano.
* **Impacto Econômico:** * O clima severamente seco, com alta radiação e baixíssima precipitação acumulada de **Macau** cria o cenário ideal para a **indústria salineira**.
  * O maior volume histórico de chuvas e a estabilidade da umidade em **Mossoró**, aliados à alta incidência solar, são o motor fundamental para o sucesso da sua **fruticultura irrigada** voltada à exportação.

## 🚀 Como Executar
1. Clone este repositório:
   ```bash
   git clone [https://github.com/seu-usuario/analise-climatica-rn.git](https://github.com/seu-usuario/analise-climatica-rn.git)
