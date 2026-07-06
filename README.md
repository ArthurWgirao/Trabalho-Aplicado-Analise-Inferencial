#  Análise Inferencial da Quantidade de Gols em Copas do Mundo

Projeto desenvolvido para a disciplina de **Análise Inferencial**, com o objetivo de aplicar conceitos de Estatística Inferencial na investigação de uma hipótese relacionada às partidas da Copa do Mundo FIFA.

##  Objetivo

Investigar se partidas das fases eliminatórias (**mata-mata**) apresentam uma quantidade média de gols inferior às partidas da **fase de grupos**, utilizando dados históricos oficiais da Copa do Mundo.

##  Pergunta de Pesquisa

> Partidas de mata-mata da Copa do Mundo possuem menos gols do que partidas da fase de grupos?

##  Base de Dados

Foi utilizado um conjunto de dados histórico contendo informações detalhadas das partidas da Copa do Mundo FIFA.

A análise foi realizada utilizando apenas o arquivo:

- `match_details.json`

Após o pré-processamento, os dados foram convertidos para formato CSV e organizados para análise.

##  Metodologia

O trabalho foi desenvolvido seguindo as principais etapas da Análise Inferencial:

- Limpeza e preparação dos dados;
- Análise exploratória;
- Estatística descritiva;
- Estimação pontual;
- Construção de intervalos de confiança;
- Verificação dos pressupostos estatísticos;
- Teste de hipóteses;
- Interpretação dos resultados.

##  Técnicas Estatísticas Utilizadas

- Média
- Mediana
- Variância
- Desvio padrão
- Histogramas
- Boxplots
- Intervalo de confiança (95%)
- Teste de Shapiro-Wilk
- Teste de Levene
- Teste de Mann-Whitney U

##  Hipóteses

Hipótese nula:

> A quantidade de gols nas partidas da fase de grupos e do mata-mata não apresenta diferença estatisticamente significativa.

Hipótese alternativa:

> Existe diferença estatisticamente significativa na quantidade de gols entre as duas fases da competição.

##  Principais Resultados

- Média de gols (Fase de Grupos): **2,77**
- Média de gols (Mata-mata): **2,96**
- Intervalos de confiança apresentaram ampla sobreposição.
- O teste de Shapiro-Wilk indicou ausência de normalidade.
- O teste de Levene confirmou homogeneidade das variâncias.
- Foi aplicado o teste não paramétrico de Mann-Whitney.

### Resultado do teste

- Estatística U = **63563**
- Valor-p = **0.3184**

Como o valor-p foi superior ao nível de significância de 5%, **não houve evidências estatísticas suficientes para rejeitar a hipótese nula**.

##  Conclusão

Embora as partidas de mata-mata tenham apresentado uma média de gols ligeiramente superior à fase de grupos, essa diferença não foi estatisticamente significativa.

Dessa forma, os dados analisados não corroboram a hipótese de que partidas eliminatórias apresentam menos gols do que partidas da fase de grupos.

## 🛠️ Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- SciPy
- Matplotlib
- Jupyter Notebook

##  Estrutura do Projeto

```
.
├── data/
│   ├── match_details.json
│   └── match_details.csv
│
├── notebook/
│   └── Analise_Inferencial_Copa_do_Mundo.ipynb
│
├── README.md
└── requirements.txt
```

##  Como Executar

Clone o repositório:

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
```

Instale as dependências:

```bash
pip install -r requirements.txt
```

Abra o notebook:

```bash
jupyter notebook
```

ou

```bash
jupyter lab
```

Execute todas as células do notebook para reproduzir a análise.

##  Autores

Projeto desenvolvido para a disciplina de **Análise Inferencial**.

- Vinícius Carvalho Lima
- Arthur Wagner Girão Muniz
