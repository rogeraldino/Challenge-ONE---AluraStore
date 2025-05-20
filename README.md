# Challenge-ONE---AluraStore

📌 Descrição do Projeto

Este projeto tem como objetivo realizar uma análise detalhada do desempenho de quatro lojas virtuais pertencentes ao Senhor João. A partir de dados de vendas, avaliações de clientes, valores de frete e produtos comercializados, desenvolvemos métricas e visualizações para ajudar na tomada de decisão sobre qual loja deve ser vendida.

📊 Objetivos da Análise

Calcular o faturamento total de cada loja.

Identificar as categorias de produtos mais vendidas.

Calcular a média de avaliação dos clientes.

Determinar os produtos mais e menos vendidos.

Calcular o frete médio por loja.

Gerar gráficos para facilitar a visualização dos dados.

Produzir um relatório final com recomendação de qual loja vender.

🧰 Tecnologias Utilizadas
Python 3.11+

    Pandas – para manipulação e análise de dados.
    Matplotlib – para criação de gráficos e visualizações.
    Google Colab – ambiente de desenvolvimento e execução.

📌 Resultados Obtidos

A Loja 1 apresentou o melhor desempenho geral, com o maior faturamento (R$ 1.616.347,09), melhor média de avaliação (3.98), e produtos de alto giro.

A Loja 4 foi a que teve o menor desempenho em diversos aspectos, sendo recomendada para venda.

✅ Conclusão

Com base na análise de dados e nas visualizações geradas, foi possível recomendar com segurança a venda da Loja 4, preservando as demais lojas que apresentam maior potencial de retorno e engajamento do cliente.


📊 Exemplos de Gráficos e Insights Obtidos

    🔹 Faturamento Total por Loja
    
       Loja 1 lidera com R$ 1.616.347,09 de faturamento.
    
       A Loja 4 teve o menor desempenho financeiro.
    
    🔹 Vendas por Categoria (Loja 1)
    
       A categoria móveis é consistentemente a mais vendida.
    
       Categorias como livros e utilidades domésticas apresentam menor volume de vendas.
    
    🔹 Frete Médio por Loja
    
       A Loja 4 possui o menor frete médio (R$ 31,28), o que pode representar menor custo logístico, mas também menor valor agregado aos produtos.

📈 Insights Relevantes

A Loja 1 se destaca em praticamente todos os indicadores: maior faturamento, melhor média de avaliação (3.98) e alta rotatividade de produtos.

A Loja 4, embora apresente o menor frete médio, teve o menor desempenho de faturamento, menor diversidade de produtos mais vendidos e avaliações medianas.


🗂️ Estrutura do Projeto
O projeto está organizado da seguinte forma:


    📦 base-de-dados-challenge-1
    
    │
    
    ├── loja_1.csv
    
    ├── loja_2.csv
    
    ├── loja_3.csv
    
    └── loja_4.csv
    
    📄 AluraStoreBrRodrigo.ipynb  # Notebook principal com toda análise e visualizações
    
    📄 README.md                  # Documentação do projeto

A pasta base-de-dados-challenge-1 contém os arquivos CSV com os dados das quatro lojas.

O arquivo AluraStoreBrRodrigo.ipynb é o notebook principal onde toda a análise é feita.

O README.md documenta o projeto, objetivos, resultados e instruções.

▶️ Como Executar o Projeto no Google Colab

Abra o Google Colab em https://colab.research.google.com/.

Faça upload do arquivo AluraStoreBrRodrigo.ipynb para o ambiente do Colab.

Como os dados estão hospedados no GitHub, o notebook já carrega diretamente os CSVs pelas URLs, não sendo necessário fazer upload dos arquivos manualmente.

Execute as células do notebook em ordem para reproduzir toda a análise, visualizações e relatório.
