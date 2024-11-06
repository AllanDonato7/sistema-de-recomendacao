# 🎬 Sistema de Recomendação de Filmes com Python

Este projeto é um sistema de recomendação de filmes desenvolvido em Python, voltado para fornecer sugestões personalizadas com base no gosto dos usuários. Utiliza uma combinação de técnicas, como filtragem colaborativa e recomendações baseadas em conteúdo. O projeto se destaca pelo uso de gráficos visualmente atraentes para explorar e entender padrões de interesse dos usuários.

## 🌟 Funcionalidades

- **Recomendações Baseadas em Conteúdo**: Sugestões de filmes similares, considerando gênero, elenco, diretor e sinopse.
- **Filtragem Colaborativa**: Recomendação com base nas preferências de usuários semelhantes.
- **Gráficos Interativos e Atraentes**: Visualizações de dados para análise intuitiva de tendências e padrões de comportamento.
- **Exploração de Dados de Filmes**: Análise de popularidade, avaliações médias, tendências por gênero, e outras métricas.
- **Relatórios de Recomendação**: Visualizações detalhadas mostrando o processo de recomendação, facilitando a interpretação dos dados.

## 📊 Tecnologias Utilizadas

- **Python**: Linguagem principal.
- **Pandas**: Manipulação e análise de dados.
- **NumPy**: Operações matemáticas e vetoriais.
- **Scikit-Learn**: Algoritmos de recomendação.
- **Matplotlib e Seaborn**: Visualizações estatísticas e estéticas.
- **Plotly**: Gráficos interativos e personalizados para análise avançada.
- **NLTK ou SpaCy**: Processamento de texto para recomendações baseadas em sinopses).

## Estrutura do Projeto

- **data/**: Contém os dados de filmes e avaliações.
- **notebooks/**: Notebooks Jupyter para análise exploratória e desenvolvimento.
- **src/**: Código-fonte do projeto:
  - **data_processing.py**: Processamento e preparação dos dados.
  - **content_based.py**: Implementação de recomendações baseadas em conteúdo.
  - **collaborative_filtering.py**: Filtragem colaborativa para recomendações.
  - **visualization.py**: Funções para criação de gráficos e visualizações.
- **README.md**: Este arquivo com informações do projeto.

## 📈 Exemplos de Gráficos

### Popularidade dos Gêneros de Filmes
- Visualize quais gêneros são mais populares e frequentemente assistidos por diferentes grupos de usuários. O gráfico mostra a frequência dos gêneros, com barras coloridas por gênero e interativas para facilitar a exploração.

### Análise de Classificações por Ano
- Um gráfico de linha que mostra a média das avaliações de filmes ao longo dos anos, evidenciando as tendências e picos de interesse por novos lançamentos ou clássicos.

### Recomendação Visualizada
- Gráficos que ilustram como a recomendação foi feita para cada usuário, destacando a relação com os filmes já assistidos e preferidos. Gráficos de dispersão e mapas de calor ajudam a visualizar a proximidade entre filmes com base nas características.
