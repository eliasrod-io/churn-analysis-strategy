# 📊 Análise de Churn e Estratégias de Retenção

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-Data_Viz-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Status](https://img.shields.io/badge/Status-Concluído-success?style=for-the-badge)

## 💼 Contexto do Negócio
Uma empresa de serviços com mais de **50.000 clientes** enfrentava um desafio crítico:
uma taxa de cancelamento (**Churn Rate**) de **56.75%**, impactando diretamente a
receita recorrente e a sustentabilidade do negócio.

O objetivo deste projeto não foi apenas calcular indicadores, mas realizar uma
**Análise Exploratória de Causa Raiz**, identificando padrões comportamentais
associados ao churn e estimando o impacto potencial de ações corretivas
baseadas em dados.

## 🎯 Objetivos
1. **Diagnóstico:** Identificar padrões de comportamento associados ao cancelamento.
2. **Correlação:** Mapear os principais ofensores (idade, contrato e interações).
3. **Prescrição:** Simular cenários exploratórios para apoiar decisões estratégicas
   de retenção.

## 🛠️ Tecnologias Utilizadas
- **Python:** Linguagem principal.
- **Pandas:** ETL (Extração, Transformação e Carga) e manipulação de dados.
- **Plotly Express / Graph Objects:** Visualizações interativas para análise
  e storytelling.

## 🔍 Principais Insights (Data Discovery)
A análise exploratória revelou que o churn não ocorre de forma aleatória,
mas está fortemente concentrado em alguns perfis críticos:

- 🚩 **Contratos Mensais:** Concentram praticamente todos os cancelamentos observados.
- 🚩 **Clientes com mais de 50 anos:** Alta taxa de churn, sugerindo possíveis
  problemas de UX, acessibilidade ou adequação da oferta.
- 🚩 **Fator Call Center:** Clientes que entram em contato mais de 4 vezes
  apresentam propensão muito elevada ao cancelamento, indicando falhas na
  resolução de problemas.

Esses fatores apresentam sobreposição significativa, indicando que parte dos
clientes afetados acumula múltiplos riscos simultaneamente.

## 📈 Resultados da Simulação (Análise Exploratória "What-If")
Foi desenvolvida uma simulação exploratória para estimar o impacto potencial
da mitigação desses três ofensores principais. Considerando a sobreposição
entre os grupos, os resultados observados foram:

| Cenário | Taxa de Churn |
| :--- | :--- |
| **Cenário Atual (Baseline)** | **56.75%** |
| **Cenário Simulado (Pós-Ações)** | **9.89%** |
| **Redução Potencial Estimada** | **46.86 p.p.** |

> ⚠️ **Importante:** O cenário simulado representa um **limite superior teórico**
> de redução de churn, assumindo eficácia total das ações.
> Na prática, parte do churn é estrutural e não seria eliminada apenas
> com essas iniciativas.

## 🧠 Conclusão
O estudo demonstra que o churn está fortemente concentrado em poucos fatores
críticos, indicando que **ações focadas nesses ofensores possuem alto potencial
de impacto na retenção**.

Mais do que fornecer números absolutos, a análise oferece uma base analítica
para priorização de iniciativas, desenho de testes controlados e tomada de
decisão orientada por dados.

## 📂 Estrutura do Projeto
- `Analise_Churn.ipynb`: Notebook com ETL, análises exploratórias, simulações
  e visualizações comentadas.
- `cancelamentos.csv`: Dataset utilizado (dados anonimizados).

## 👨‍💻 Autor
**Elias Rodrigues**  
*Focado em transformar dados brutos em inteligência de negócio.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/elias-rodrigues07/)
