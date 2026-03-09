# Projeto Integrador - Mineração de Dados

Curso: Tecnologia em Banco de Dados

Disciplina: Projeto Integrador (Mineração de Dados)

Instituição: SENAC EAD

## Ciência de Dados Aplicada a Situações de Mercado

Este projeto aplica técnicas de **Análise Exploratória de Dados (EDA)** em um conjunto de vendas de supermercado, com foco em gerar indicadores e visualizações para apoiar decisões comerciais.

## Objetivo

- Explorar a base de vendas para identificar padrões de faturamento, margem e volume.
- Produzir visualizações claras para comparação por categoria, região e período.
- Traduzir os resultados em insights acionáveis para o negócio.

## Abrir Notebook no Google Colab

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/josemarcellolopes/PI2601/blob/main/projeto_integrador_colab.ipynb)
[![Notebook no GitHub](https://img.shields.io/badge/GitHub-Abrir_Notebook-181717?logo=github)](https://github.com/josemarcellolopes/PI2601/blob/main/projeto_integrador_colab.ipynb)

## Tecnologias Utilizadas

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib

## Estrutura do Projeto

```text
pi_entrega/
|-- README.md
|-- projeto_integrador_colab.ipynb
|-- dataset_vendas_supermercado.csv
|-- PI.pdf
|-- relatorio_projeto_integrador.docx
|-- relatorio_projeto_integrador.pdf
`-- rendered/
    |-- page-1.png
    |-- page-2.png
    |-- page-3.png
    `-- relatorio_projeto_integrador.pdf
```

## Descrição do Dataset

Arquivo: `dataset_vendas_supermercado.csv`

Principais colunas:

- `id_venda`: identificador único da venda.
- `data`: data da transação.
- `regiao`: região de venda (ex.: Norte, Sul, Sudeste).
- `categoria`: categoria de produto.
- `produto`: nome do item vendido.
- `quantidade`: unidades vendidas.
- `preco_unitario`: valor unitário do item.
- `faturamento`: valor total da venda.
- `custo`: custo associado à venda.
- `margem`: diferença entre faturamento e custo.
- `canal`: canal de venda (Loja Física, Delivery, E-commerce).
- `pagamento`: forma de pagamento (Pix, Cartão, Dinheiro).

## Como Executar

### Opção 1: Google Colab

1. Clique no badge "Open in Colab" acima.
2. Execute as células na ordem do notebook.
3. Confira os indicadores e os 5 gráficos gerados.

### Opção 2: Ambiente local (Jupyter)

1. Crie e ative um ambiente virtual.
2. Instale as dependências.
3. Abra o notebook no Jupyter Lab/Notebook.
4. Execute as células em sequência.

Exemplo de instalação:

```bash
pip install pandas numpy matplotlib jupyter
jupyter notebook projeto_integrador_colab.ipynb
```

## Análises e Visualizações

O notebook apresenta:

1. Faturamento por categoria.
2. Faturamento por região.
3. Evolução mensal do faturamento.
4. Distribuição do valor das vendas.
5. Top 10 produtos por quantidade vendida.

Também são calculados indicadores de síntese, como:

- Faturamento total.
- Margem total.
- Ticket médio.

## Resultados Esperados

- Identificação de categorias e regiões mais relevantes para receita.
- Visão de sazonalidade para apoio a metas e planejamento comercial.
- Entendimento da distribuição dos valores de venda.
- Apoio a decisões de estoque com base nos produtos mais vendidos.

## Integrantes

- BRUNO DOS SANTOS GUTERRES
- EDEN FERREIRA CARDOSO
- JOSE MARCELLO LOPES DE OLIVEIRA
- RAUSTHER JOSE DE SOUZA
- RENATA MIEKO SABO INOUE
- SAVIO ANTONIO PEREIRA
- VITOR HAAG PEZZINI

## Observações

- O notebook foi estruturado para uso didático e execução sequencial.
- Caso execute localmente, mantenha o arquivo `dataset_vendas_supermercado.csv` no mesmo diretório do notebook.
