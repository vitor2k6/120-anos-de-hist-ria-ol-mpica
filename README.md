# 🏅 Análise de Dados dos Jogos Olímpicos (1896–2016)

Este projeto realiza uma análise exploratória de dados sobre os Jogos Olímpicos, utilizando a base histórica disponível no Kaggle. O objetivo é extrair insights relevantes a partir de um conjunto de dados rico e diversificado, explorando atletas, países, esportes, desempenho e transformações ao longo do tempo.

## 📦 Base de Dados

As informações foram obtidas a partir do dataset [120 Years of Olympic History](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results), que contém duas tabelas principais:

- `athlete_events.csv`: informações sobre atletas, esportes, países (NOC), medalhas, altura, peso, idade, entre outros.
- `noc_regions.csv`: tabela de apoio com os nomes completos dos países e regiões para cada código NOC.

## 🔧 Etapas do Projeto

### 1. Seleção dos Dados
- Fonte: Kaggle (dataset público)
- Tabelas utilizadas: `athlete_events.csv` e `noc_regions.csv`
- Ferramentas: Python, Pandas, Plotly

### 2. Análise Exploratória
Foram exploradas tendências, padrões e distribuições. Destaques:
- Evolução do número de atletas por ano
- Países com maior número de medalhas
- Distribuição por sexo dos atletas
- Relação entre idade, IMC e grupo etário
- Perfil físico dos atletas por modalidade

### 3. Tratamento e Preparação dos Dados
- Remoção e imputação de valores ausentes
- Padronização de colunas categóricas
- Criação de novas colunas: `BMI (IMC)` e `Age_Group`
- Junção com a tabela de regiões para obter nomes completos dos países

### 4. Visualização de Dados
Foram criadas visualizações interativas com Plotly:

- 📈 Linha: Evolução do número de atletas por edição
- 🥇 Barras: Top 10 países com mais medalhas
- 👥 Pizza: Proporção de atletas por sexo
- 📦 Boxplot: IMC por faixa etária
- 🗺️ Mapa: Distribuição geográfica de medalhas

As visualizações também podem ser utilizadas em painéis no **Looker Studio** ou ferramentas de BI.

## 📊 Principais Insights

- Crescimento constante da participação de atletas ao longo das décadas.
- Estados Unidos lideram o quadro histórico de medalhas.
- Participação feminina aumentou drasticamente desde o início dos Jogos.
- Modalidades esportivas influenciam o perfil físico dos atletas.
- Modalidades mais técnicas como hipismo e tiro envolvem atletas mais velhos.


