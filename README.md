# Projeto de Clustering em Dados de Vendas

## Descrição do Projeto

Este projeto aplica diferentes **algoritmos de clustering** a um conjunto de dados de vendas para agrupar clientes com base em seus comportamentos de compra. O objetivo é identificar padrões, perfis e comportamentos de clientes, fornecendo insights que possam direcionar estratégias de marketing e melhorar a personalização dos serviços oferecidos.

## Visão Geral

1. **Análise Exploratória dos Dados**: Avaliação inicial do conjunto de dados, incluindo estatísticas descritivas e visualização dos dados de venda.
2. **Pré-processamento e Transformação dos Dados**: Limpeza dos dados, tratamento de valores ausentes e normalização para preparar o dataset para clustering.
3. **Algoritmos de Clustering Utilizados**:
   - **K-Means**: Clustering baseado em centroides para minimizar a distância entre pontos e centros.
   - **DBSCAN**: Algoritmo baseado em densidade para identificar clusters de formas e tamanhos variados.
   - **Agglomerative Clustering (Hierarchical)**: Método hierárquico que organiza os dados em uma estrutura de árvore.
   - **Mean Shift**: Algoritmo que identifica regiões de alta densidade sem a necessidade de definir o número de clusters previamente.
4. **Métricas de Avaliação de Clusters**:
   - **Silhouette Score**: Avalia a similaridade entre pontos de um cluster em comparação a outros clusters.
   - **Davies-Bouldin Index**: Mede a dispersão dos clusters, considerando a distância e variabilidade entre clusters.
   - **Calinski-Harabasz Index**: Calcula a razão entre a dispersão entre clusters e a dispersão interna, sendo que valores maiores indicam melhor separação.
5. **Visualização dos Resultados**: Gráficos que ilustram os clusters e ajudam a interpretar padrões de compra, utilizando Seaborn e Matplotlib.

## Tecnologias Utilizadas

- **Python**: Linguagem de programação principal para manipulação e análise de dados.
- **Pandas**: Manipulação e organização dos dados de vendas.
- **NumPy**: Computação numérica e operações com arrays.
- **Scikit-learn**: Implementação dos algoritmos de clustering e cálculo das métricas de avaliação.
- **Seaborn e Matplotlib**: Visualização dos dados e dos clusters gerados para interpretação dos resultados.

## Estrutura dos Dados

O dataset `data.csv` contém informações transacionais relevantes para a análise de clustering:

- **InvoiceNo**: Número da fatura.
- **StockCode**: Código do item.
- **Description**: Descrição do item comprado.
- **Quantity**: Quantidade de itens comprados.
- **InvoiceDate**: Data da transação.
- **UnitPrice**: Preço unitário do item.
- **CustomerID**: Identificação única do cliente.
- **Country**: País onde a compra foi realizada.

Essas informações foram processadas e transformadas para facilitar a criação de clusters significativos com base nos padrões de compra dos clientes.

## Resultados

Os resultados deste projeto incluem:

- **Clusters Otimizados e Significativos**: Cada algoritmo gera clusters de clientes com características semelhantes, facilitando a segmentação e identificação de perfis de compra.
- **Comparação de Qualidade entre Algoritmos**: Métricas como Silhouette Score, Davies-Bouldin Index e Calinski-Harabasz Index ajudam a avaliar a eficácia de cada algoritmo, permitindo a escolha do método de clustering mais adequado.
- **Visualização e Interpretação dos Clusters**: Gráficos gerados com Seaborn e Matplotlib oferecem uma análise visual dos clusters, destacando diferentes perfis de clientes, que podem ser utilizados para campanhas de marketing direcionadas e personalizadas.

## Contato
Se você tiver dúvidas ou sugestões, entre em contato por [vitttormuniz@gmail.com](mailto:vitttormuniz@gmail.com).
