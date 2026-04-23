# 📊 Análise do Programa Pé de Meia (Brasil)

Este projeto realiza uma análise exploratória dos dados do programa Pé de Meia no Brasil, com foco na distribuição de recursos públicos e na evolução temporal dos pagamentos.

O objetivo é transformar dados brutos em insights estruturados, permitindo entender padrões geográficos e comportamentais da execução do programa.

---

## 🎯 Objetivo

Analisar a distribuição dos recursos do programa Pé de Meia no Brasil, explorando padrões geográficos e temporais para identificar concentração e evolução dos pagamentos ao longo do tempo.

---

## 🧠 Perguntas de análise

A partir dos dados, buscamos responder:

- Como os recursos estão distribuídos entre estados e municípios?
- Existem regiões com maior concentração de pagamentos?
- Como os valores evoluem ao longo dos meses?
- Há padrões claros na execução do programa ao longo do tempo?

---

## 🛠️ Tecnologias utilizadas

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  


## 📊 Principais análises realizadas
Consolidação de múltiplos arquivos CSV mensais
Limpeza e padronização dos dados
Engenharia de variáveis temporais (ano/mês)
Agregações por estado e município
Análise de evolução temporal dos pagamentos
Visualização de tendências e rankings
## 📈 Principais insights
Identificação de concentração regional dos recursos
Estados e municípios com maior volume financeiro
Evolução dos pagamentos ao longo do tempo
Padrões de distribuição que ajudam a entender a execução do programa
## 🚀 Como executar o projeto
Clone este repositório

Instale as dependências necessárias:

pip install pandas numpy matplotlib seaborn

Execute o notebook principal:

notebooks/analise_pe_de_meia.ipynb
Explore os gráficos e resultados gerados em /outputs
💡 Possíveis melhorias futuras
Criação de dashboard interativo (Power BI ou Plotly Dash)
Análise por perfil socioeconômico (se dados disponíveis)
Modelos preditivos de evolução dos pagamentos
Automação do pipeline de atualização dos dados
👤 Autor

Luis Antonio
Projeto desenvolvido para portfólio em análise de dados, com foco em dados públicos e storytelling analítico.

---

## 📁 Estrutura do projeto

```text
analise-dados-publicos/
│
├── notebooks/
│   └── analise_pe_de_meia.ipynb   # Notebook principal
│
├── data/
│   ├── raw/                       # Dados originais (zip/csv)
│   └── processed/                # Dados tratados
│
├── outputs/
│   ├── graficos/
│   └── dataset_final.csv
│
└── README.md
