# Segmentação de Clientes para Marketing

Projeto de análise e segmentação de clientes com foco em apoiar estratégias de marketing por meio de agrupamento de perfis de consumo. A proposta é identificar padrões entre clientes com base em idade, renda anual e pontuação de gastos, gerando segmentos que possam orientar ações mais personalizadas. 

## Sobre o projeto

Este projeto utiliza dados de clientes para construir uma segmentação em grupos, permitindo analisar o comportamento de consumo de diferentes perfis. A base contém 500 registros e considera variáveis como idade, renda anual e pontuação de gastos, além do cluster atribuído a cada cliente após a segmentação.

O resultado foi apresentado em um dashboard com indicadores gerais e visuais comparativos entre os segmentos, facilitando a interpretação dos grupos formados e apoiando decisões na área de marketing.

## Objetivo

O principal objetivo deste projeto é agrupar clientes com características semelhantes para:

- identificar perfis de consumo;
- apoiar campanhas segmentadas;
- melhorar ações de relacionamento;
- direcionar estratégias com base em dados.

## Dados utilizados

A base de dados contém as seguintes variáveis:

- `id`: identificador do cliente
- `idade`: idade do cliente
- `renda_anual`: renda anual estimada
- `pontuacao_gastos`: score de gastos do cliente
- `cluster`: segmento atribuído após o processo de agrupamento

## Principais insights

A análise identificou 3 segmentos principais de clientes:

- **Segmento 0**: clientes com maior renda anual média, em torno de 120 mil, idade média de 54 anos e pontuação média de gastos de 47.
- **Segmento 1**: clientes com menor renda anual média, em torno de 52 mil, idade média de 53 anos e a maior pontuação média de gastos, com 54.
- **Segmento 2**: clientes mais jovens, com idade média de 27 anos, renda anual média de aproximadamente 82 mil e pontuação média de gastos de 43.

Além disso:
- a base possui **500 clientes** no total;
- o segmento 1 possui **187 clientes**;
- o segmento 2 possui **167 clientes**;
- o segmento 0 possui **146 clientes**;
- a média geral de idade é **44,73 anos**;
- a média geral de renda anual é **81.557,17**;
- a média geral da pontuação de gastos é **48,51**.

## Dashboard

O dashboard apresenta:

- média de pontuação de gastos por segmento;
- total de clientes por segmento;
- média de renda anual por segmento;
- média de idade por segmento;
- indicadores gerais da base.

## Tecnologias e ferramentas

- Python
- Pandas
- Scikit-learn
- Power BI
- CSV
- Análise de dados
- Clusterização

## Estrutura do projeto

```bash
segmentacao-clientes-marketing/
├─ dados_clientes.csv
├─ segmentos.csv
├─ dashboard.png
└─ README.md
```

## Possíveis aplicações

Este projeto pode ser aplicado em cenários como:

- campanhas de marketing segmentadas;
- definição de ofertas por perfil de cliente;
- priorização de públicos com maior potencial de consumo;
- análise de comportamento para retenção e fidelização.

## Próximos passos

- incluir visualizações adicionais com dispersão entre renda e gastos;
- documentar o algoritmo de clusterização utilizado;
- testar diferentes números de clusters;
- avaliar métricas de qualidade dos agrupamentos.

## Autor

Projeto desenvolvido para fins de estudo e portfólio na área de dados, analytics e inteligência de negócio.
