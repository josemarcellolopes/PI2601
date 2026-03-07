# Projeto Integrador - Mineracao de Dados

Curso: Tecnologia em Banco de Dados

Disciplina: Projeto Integrador (Mineracao de Dados)

Instituicao: SENAC EAD

## Ciencia de Dados Aplicada a Situacoes de Mercado

Este projeto aplica tecnicas de **Analise Exploratoria de Dados (EDA)** em um conjunto de vendas de supermercado, com foco em gerar indicadores e visualizacoes para apoiar decisoes comerciais.

## Objetivo

- Explorar a base de vendas para identificar padroes de faturamento, margem e volume.
- Produzir visualizacoes claras para comparacao por categoria, regiao e periodo.
- Traduzir os resultados em insights acionaveis para negocio.

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

## Descricao do Dataset

Arquivo: `dataset_vendas_supermercado.csv`

Principais colunas:

- `id_venda`: identificador unico da venda.
- `data`: data da transacao.
- `regiao`: regiao de venda (ex.: Norte, Sul, Sudeste).
- `categoria`: categoria de produto.
- `produto`: nome do item vendido.
- `quantidade`: unidades vendidas.
- `preco_unitario`: valor unitario do item.
- `faturamento`: valor total da venda.
- `custo`: custo associado a venda.
- `margem`: diferenca entre faturamento e custo.
- `canal`: canal de venda (Loja Fisica, Delivery, E-commerce).
- `pagamento`: forma de pagamento (Pix, Cartao, Dinheiro).

## Como Executar

### Opcao 1: Google Colab

1. Clique no badge "Open in Colab" acima.
2. Execute as celulas na ordem do notebook.
3. Confira os indicadores e os 5 graficos gerados.

### Opcao 2: Ambiente local (Jupyter)

1. Crie e ative um ambiente virtual.
2. Instale as dependencias.
3. Abra o notebook no Jupyter Lab/Notebook.
4. Execute as celulas em sequencia.

Exemplo de instalacao:

```bash
pip install pandas numpy matplotlib jupyter
jupyter notebook projeto_integrador_colab.ipynb
```

## Analises e Visualizacoes

O notebook apresenta:

1. Faturamento por categoria.
2. Faturamento por regiao.
3. Evolucao mensal do faturamento.
4. Distribuicao do valor das vendas.
5. Top 10 produtos por quantidade vendida.

Tambem sao calculados indicadores de sintese, como:

- Faturamento total.
- Margem total.
- Ticket medio.

## Resultados Esperados

- Identificacao de categorias e regioes mais relevantes para receita.
- Visao de sazonalidade para apoio a metas e planejamento comercial.
- Entendimento da distribuicao dos valores de venda.
- Apoio a decisoes de estoque com base nos produtos mais vendidos.

## Integrantes

- BRUNO DOS SANTOS GUTERRES
- EDEN FERREIRA CARDOSO
- JOSE MARCELLO LOPES DE OLIVEIRA
- LUCAS DE CARVALHO FERREIRA
- RAUSTHER JOSE DE SOUZA
- RENATA MIEKO SABO INOUE
- SAVIO ANTONIO PEREIRA
- VITOR HAAG PEZZINI
- YAN SAVIO SANTOS DE MORAIS FONTES

## Observacoes

- O notebook foi estruturado para uso didatico e execucao sequencial.
- Caso execute localmente, mantenha o arquivo `dataset_vendas_supermercado.csv` no mesmo diretorio do notebook.
