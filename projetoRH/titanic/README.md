# Titanic EDA

Este repositório contém uma Análise Exploratória de Dados (EDA) do dataset Titanic.

## Estrutura
```
titanic-eda/
├── data/
│   └── titanic.csv
├── figures/
│   ├── idade_hist.png
│   ├── fare_hist.png
│   ├── sexo_bar.png
│   ├── pclass_bar.png
│   ├── sobrevivencia_por_idade.png
│   ├── stack_survival_sex_pclass.png
│   └── correlation_heatmap.png
├── eda.ipynb
├── requirements.txt
└── LICENSE
```

## Como executar
1. Clone este repositório.
2. Instale dependências:
   ```bash
   pip install -r requirements.txt
   ```
3. Abra o notebook:
   ```bash
   jupyter notebook eda.ipynb
   ```

## Notas
- Gráficos feitos com Matplotlib (sem estilos personalizados).
- Foi gerado também `data/titanic_clean.csv` após tratamento básico.
