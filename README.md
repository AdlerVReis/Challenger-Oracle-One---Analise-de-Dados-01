# 📊 Análise de Vendas de Lojas - Challenge Alura Data Science

Este projeto tem como objetivo analisar os dados de vendas de quatro lojas, fornecidos pelo Challenge da Alura, utilizando a linguagem Python e bibliotecas como `pandas`, `matplotlib` e `numpy`. A análise inclui informações sobre faturamento, distribuição de categorias vendidas, avaliações, produtos mais vendidos e frete médio.

---

## 📥 Importação dos Dados

Os dados de vendas de cada loja foram importados diretamente de arquivos `.csv` hospedados no GitHub da Alura:

```python
import pandas as pd

url = "https://.../loja_1.csv"
url2 = "https://.../loja_2.csv"
url3 = "https://.../loja_3.csv"
url4 = "https://.../loja_4.csv"

loja = pd.read_csv(url)
loja2 = pd.read_csv(url2)
loja3 = pd.read_csv(url3)
loja4 = pd.read_csv(url4)
💰 1. Análise do Faturamento
Foi calculado o faturamento total de cada loja com base nos preços dos produtos vendidos.

Faturamento total:

Loja 1: R$ 1.534.509,12

Loja 2: R$ 1.488.459,06

Loja 3: R$ 1.464.025,03

Loja 4: R$ 1.384.497,58

Gráfico de barras foi gerado para melhor visualização do desempenho financeiro.

🛍️ 2. Vendas por Categoria
Foi realizada a contagem das categorias de produtos vendidos em cada loja e gerado um gráfico de pizza por loja.

As principais categorias são:

Eletrônicos

Móveis

Brinquedos

Eletrodomésticos

A distribuição foi semelhante entre as lojas, com eletrônicos representando entre 17% e 20% das vendas.

🌟 3. Média de Avaliação das Lojas
Cálculo da média de avaliação fornecida pelos clientes:

Loja 1: 3.98

Loja 2: 4.04

Loja 3: 4.05

Loja 4: 4.00

As avaliações são próximas entre si, com destaque ligeiro para a Loja 3.

🔝 4. Produtos Mais e Menos Vendidos
Foram identificados os produtos mais e menos vendidos por loja. Essa análise pode ajudar na gestão de estoque e definição de estratégias de marketing.

🚚 5. Frete Médio por Loja
O custo médio de frete por loja foi calculado:

Loja 1: R$ 34,69

Loja 2: R$ 33,62

Loja 3: R$ 33,07

Loja 4: R$ 31,28

📌 Conclusão
Com base nas análises realizadas:

A Loja 1 possui o maior faturamento.

A Loja 3 apresenta a melhor média de avaliação dos clientes.

A Loja 4, embora tenha menor faturamento, possui o menor custo de frete médio.

As categorias de produtos estão equilibradas entre as lojas, indicando padrões semelhantes de consumo.

Recomendação: Considerando a eficiência de custo e desempenho geral, a Loja 4 é a mais indicada para continuidade ou investimento, dado o bom desempenho em avaliações e logística.

🛠️ Tecnologias Utilizadas
Python 3.10+

Pandas

Matplotlib

Numpy

