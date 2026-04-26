# 🎮 Do Arcade à Arena Global
### Crescimento da Indústria de Gaming e a Explosão dos E-Sports

---

## 📋 Sobre o Projeto

MVP desenvolvido para a disciplina de **Análise de Dados e Boas Práticas** da pós-graduação em Data Analytics da **PUC-Rio**.

O trabalho realiza uma análise exploratória (EDA) e pré-processamento de dados que conecta três dimensões da indústria de gaming: **vendas comerciais**, **premiações de e-sports** e **audiência de streaming** — revelando padrões que nenhuma fonte individual seria capaz de mostrar.

---

## 🗂️ Datasets

| # | Dataset | Registros | Período | Fonte |
|---|---------|-----------|---------|-------|
| 1 | [Video Game Sales 2024](https://www.kaggle.com/datasets/asaniczka/video-game-sales-2024) | 64.016 jogos | 1971–2024 | VGChartz / Kaggle |
| 2a | [E-Sports Earnings (General)](https://www.kaggle.com/datasets/rankirsh/esports-earnings) | 669 jogos | Agregado | Kaggle |
| 2b | [E-Sports Earnings (Historical)](https://www.kaggle.com/datasets/rankirsh/esports-earnings) | 10.239 registros | 1998–2024 | Kaggle |
| 3a | [Top Games on Twitch (por jogo)](https://www.kaggle.com/datasets/rankirsh/evolution-of-top-games-on-twitch) | 21.000 registros | 2016–2024 | Kaggle |
| 3b | [Top Games on Twitch (global)](https://www.kaggle.com/datasets/rankirsh/evolution-of-top-games-on-twitch) | 105 registros | 2016–2024 | Kaggle |

---

## 🔬 Hipóteses Investigadas

1. **Migração de plataformas** — Vendas migraram de consoles para PC/portáteis ao longo das décadas?
2. **E-sports como motor de longevidade** — Jogos com cena competitiva mantêm audiência por mais tempo na Twitch?
3. **Correlação premiação × audiência** — Maiores premiações se traduzem em mais horas assistidas?
4. **Dominância de gênero** — FPS e MOBA dominam e-sports e streaming, enquanto Sports e Action lideram vendas?

---

## 🏗️ Estrutura do Notebook

```
1. Contexto
2. Descrição do Problema
   2.1 Hipóteses do Problema
   2.2 Tipo de Problema
   2.3 Seleção de Dados
   2.4 Atributos dos Datasets
3. Importação das Bibliotecas e Carregamento dos Dados
4. Análise Exploratória dos Dados (EDA)
   4.1 Dimensões e Tipos de Dados
   4.2 Estatísticas Descritivas
   4.3 Valores Faltantes, Inconsistências e Outliers
   4.4 Visualizações Univariadas
   4.5 Visualizações Bivariadas e Multivariadas
   4.6 Conclusões da Análise Exploratória
5. Pré-Processamento dos Dados
   5.1–5.9 (Limpeza, Feature Engineering, Encoding, Normalização, etc.)
6. Respondendo às Hipóteses
   6.1–6.4 (Análise direcionada para cada hipótese)
7. Conclusão
8. Próximos Passos
```

---

## 📊 Estrutura do Repositório

```
mvp-data-analytics-pucrio/
├── README.md
├── mvp_data_analytics.ipynb
└── datasets/
    ├── vgchartz-2024.csv
    ├── GeneralEsportData.csv
    ├── HistoricalEsportData.csv
    ├── Twitch_game_data.csv
    └── Twitch_global_data.csv
```

---

## ⚙️ Como Executar

1. Clique no botão **"Open in Colab"**, dentro do arquivo **mvp_data_analytics.ipynb** nesse repositório.
2. No Colab, vá em **Runtime → Run all**
3. Pronto — todos os datasets são carregados automaticamente via GitHub

Nenhuma configuração adicional é necessária.

---

## 🛠️ Tecnologias

- Python 3
- Pandas / NumPy
- Matplotlib / Seaborn
- Scikit-learn
- Google Colab

---

## 📄 Licença

Projeto acadêmico — PUC-Rio, 2026.

Datasets utilizados sob licenças abertas (Kaggle).
