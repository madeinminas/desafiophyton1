🛍️ Alura Store - Análise de Vendas
Este projeto tem como objetivo analisar os dados de vendas da rede Alura Store, composta por quatro lojas. Através da análise exploratória de dados (EDA), buscamos entender o desempenho das lojas, produtos mais vendidos, categorias em destaque e o faturamento gerado, extraindo insights relevantes para o negócio.

📁 Estrutura do Projeto
O projeto é composto por um notebook Google Colab contendo:

Importação e tratamento dos dados

Análise do faturamento por loja

Comparação de vendas por categoria

Visualizações gráficas para melhor interpretação

Geração de insights acionáveis para o negócio

📊 Exemplos de Gráficos e Insights

📌 Faturamento por Loja
Visualização em formato de gráfico de pizza representando o percentual do faturamento total por loja:

python
Copiar
Editar
plt.pie(faturamentos, ...)

📌 Vendas por Categoria
Gráfico de barras agrupadas comparando a quantidade de vendas por categoria em cada loja:

python
Copiar
Editar
plt.bar(x - 1.5*width, v1, ...)
Essas visualizações permitiram identificar:

Quais lojas são mais representativas em termos de faturamento;

As categorias mais populares em cada loja;

Possíveis oportunidades de crescimento.

▶️ Como Executar o Notebook
Para executar este projeto, siga os passos abaixo:

1) Acesse o Google Colab com sua conta Google.
2) Faça upload do arquivo AluraStoreBr.ipynb.
3) Execute as células em sequência.

🧠 Conclusão
Este projeto exemplifica como análises simples e bem visualizadas podem trazer insights importantes para decisões estratégicas em um negócio varejista. Aproveite e adapte à sua realidade!
