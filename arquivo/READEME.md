# Projeto Billboard Hot 100 Analysis

## Descrição
Análise exploratória do dataset histórico da Billboard Hot 100 (1958–2024) com foco em ranking, 
longevidade e presença de artistas no chart.
Projeto desenvolvido para prática de análise de dados com dataset real.

## Dataset
Billboard Hot 100 (1958–2024)
Fonte: Kaggle — Billboard Hot 100 (1958–2024)

Colunas:

- chart_week — semana do chart
- current_week — posição na semana
- title — música
- performer — artista
- last_week — posição na semana anterior
- peak_pos — melhor posição alcançada
- wks_on_chart — semanas no chart

Total de registros: 343.600

## Exploração inicial
Foram realizadas verificações iniciais:

- Visualização dos dados (head)
- Tipos de dados (info)
- Estatísticas gerais (describe)
- Verificação de duplicados
- Verificação de valores nulos

Resultado:

- Dataset consistente
- Sem duplicados
- Valores nulos apenas em last_week (entradas novas no chart)


## Tecnologias

- Python
- Pandas
- Jupyter Notebook