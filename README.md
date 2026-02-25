<<<<<<< HEAD
# Projeto Billboard Hot 100 Analysis

## Descrição
Análise exploratória do dataset histórico da Billboard Hot 100 (1958–2024) com foco em ranking, 
longevidade e presença de artistas no chart.
Projeto desenvolvido para prática de análise de dados com dataset real.

## Dataset
Billboard Hot 100 (1958–2024)
Fonte: Kaggle — Billboard Hot 100 (1958–2024)

Colunas:
=======
# Billboard Hot 100 Analysis

## Descrição

Análise exploratória do dataset histórico da Billboard Hot 100 (1958–2024) com foco em ranking, longevidade e presença de artistas no chart.

Projeto desenvolvido para prática de análise de dados com dataset real.

## Dataset

Fonte: Kaggle — Billboard Hot 100 (1958–2024)

### Colunas
>>>>>>> e538007 (correção do nome + update insights)

- chart_week — semana do chart
- current_week — posição na semana
- title — música
- performer — artista
<<<<<<< HEAD
- last_week — posição na semana anterior
=======
- last_week — posição na chart anterior
>>>>>>> e538007 (correção do nome + update insights)
- peak_pos — melhor posição alcançada
- wks_on_chart — semanas no chart

Total de registros: 343.600

## Exploração inicial
<<<<<<< HEAD
Foram realizadas verificações iniciais:

- Visualização dos dados (head)
- Tipos de dados (info)
- Estatísticas gerais (describe)
- Verificação de duplicados
- Verificação de valores nulos

Resultado:
=======

### Etapas realizadas

- Visualização dos dados (head)
- Tipos de dados (info)
- Estatísticas descritivas (describe)
- Verificação de duplicados
- Verificação de valores nulos

### Resultados
>>>>>>> e538007 (correção do nome + update insights)

- Dataset consistente
- Sem duplicados
- Valores nulos apenas em last_week (entradas novas no chart)


## Tecnologias

- Python
- Pandas
<<<<<<< HEAD
- Jupyter Notebook
=======
- Matplotlib
- Seaborn
- Jupyter Notebook

## Análises realizadas

- Correlação entre métricas do chart
- Ranking de artistas no Top 100, Top 10 e #1
- Ranking considerando músicas únicas (remoção de duplicados)
- Primeira entrada no #1 por artista
- Identificação de One Hit Wonders
- Análise por década
- Tempo médio de permanência no chart
- Tempo médio até atingir o pico (#1)

## Principais insights

- O chart é altamente concentrado: poucos artistas acumulam grande volume de entradas. Nos rankings de presença total, artistas como Taylor Swift lideram com ampla vantagem, evidenciando concentração no topo do mercado (A-list), inclusive a mesma estavaa no topo, enquanto fazia esse projeto, e o Bad Bunny possuia 5 músicas no top 20.

- Rankings mudam significativamente quando duplicados são removidos. Artistas com forte longevidade e catálogo amplo sobem, enquanto artistas dependentes de poucos hits recorrentes caem, mostrando o impacto direto da metodologia, a exemplo disso em épocas festivas como natal temos reentradas de músicas com mais de 60 anos de lançamento nos charts.

- A quantidade de One Hit Wonders(artistas de um único hit) permanece relevante em todas as décadas, mas apresenta redução relativa nas décadas mais recentes (ex.: 1990s: 792 vs 2020s: 458), sugerindo maior recorrência e retenção de artistas no chart moderno.

- A permanência média no chart cresce de forma clara entre 1950s (8 semanas) e o pico entre 1990s–2000s (15 semanas), indicando aumento da longevidade dos hits. Nos 2020s há queda (10 semanas), sugerindo ciclo de consumo mais rápido.

- A dinâmica de chegada ao topo mudou: métricas recentes mostram redução no tempo até o pico e casos de estreia direta em posições altas. Em décadas recentes, a média de semanas até o #1 chega a valores próximos de zero ou negativos, refletindo estreias já no topo.

- O comportamento moderno do chart é fortemente influenciado por fatores externos ao rádio tradicional, como redes sociais, streaming e exposição em filmes e séries, que impulsionam estreias altas e também o ressurgimento de músicas antigas no chart.

## Como executar

### Clonar o repositório

```bash
git clone https://github.com/SBussola/Projeto_Billboard_Hot_100_Analysis.git
```

### Instalar dependências

```bash
pip install pandas matplotlib seaborn
```

### Abrir o notebook

```
analise.ipynb
```

Executar as células.
>>>>>>> e538007 (correção do nome + update insights)
