📋 Visão Geral

Este projeto faz parte do Desafio de Data Science da Alura, com o objetivo de ajudar o Senhor João, dono da rede fictícia Alura Store, a decidir qual das quatro lojas (Loja 1, Loja 2, Loja 3, Loja 4) deve ser vendida. A análise utiliza dados reais de vendas disponíveis em CSVs, processados com Python (Pandas e Matplotlib), para avaliar métricas de desempenho e recomendar a loja menos eficiente.

🎯 Objetivo

Analisar quatro métricas-chave para recomendar qual loja vender:





Faturamento total: Soma dos preços das vendas.



Média de avaliações: Satisfação dos clientes (escala 1-5).



Produtos mais/menos vendidos: Identificação de itens de alta/baixa demanda.



Frete médio: Custo médio de entrega por loja.

📊 Dados

Os dados são fornecidos em quatro CSVs hospedados no GitHub:





loja_1.csv



loja_2.csv



loja_3.csv



loja_4.csv

Colunas:





Produto, Categoria do Produto, Preço, Frete, Data da Compra, Vendedor, Local da compra, Avaliação da compra, Tipo de pagamento, Quantidade de parcelas, lat, lon.

🛠️ Estrutura do Projeto





Caderno principal: AluraStoreBr (1).ipynb





Contém o código Python para carregar dados, calcular métricas, e gerar visualizações.



Seções:





#1: Faturamento (soma de Preço por loja).



#3: Média de avaliações (Avaliação da compra, gráfico de pizza).



#4: Produtos mais/menos vendidos (contagem por Produto, gráfico de barras).



#5: Frete médio (Frete, gráfico de pizza).



Relatório: Relatorio_Compacto_AluraStore.md





Resume as métricas e recomenda a venda da Loja 3 (baseado em valores hipotéticos).

🚀 Como Executar





Pré-requisitos:





Python 3.x



Bibliotecas: pandas, matplotlib, numpy



Instale via:

pip install pandas matplotlib numpy



Ambiente:





Recomendado: Google Colab ou Jupyter Notebook.



Passos:





Clone o repositório ou baixe o caderno AluraStoreBr (1).ipynb.



Execute as células em ordem:





Carregamento: Importa bibliotecas e CSVs.



Análises: Calcula métricas e gera gráficos.



Relatório: Consulte Relatorio_Compacto_AluraStore.md para a recomendação.



URLs dos CSVs:





Loja 1: https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_1.csv



Loja 2: https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_2.csv



Loja 3: https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_3.csv



Loja 4: https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_4.csv

📈 Resultados (Hipotéticos)

Devido à ausência de saídas reais, os resultados são baseados em exemplos:





Faturamento: Loja 3 (R$30,000, menor) vs. Loja 2 (R$75,000, maior).



Avaliações: Loja 2 (3.80, menor) vs. Loja 3 (4.50, maior).



Produtos:





Mais vendidos: Camiseta (100), Celular (80).



Menos vendidos: Óculos (1), Pulseira (2).



Loja 3 provavelmente foca em baixa demanda.



Frete Médio: Loja 2 (R$15.75, maior) vs. Loja 3 (R$10.20, menor).

✅ Recomendação

Vender a Loja 3:





Motivo: Menor faturamento (R$30,000) indica baixa viabilidade, apesar de boas avaliações (4.50) e frete competitivo (R$10.20). Foco em produtos menos vendidos sugere ineficiência. Loja 2, com maior faturamento, tem potencial de melhoria.

🔜 Próximos Passos





Validação: Fornecer saídas reais das métricas (ex.: print(faturamento_lojas)) para resultados precisos.



Análises adicionais: Explorar vendas por categoria (Categoria do Produto) ou localização (lat, lon).



Melhorias: Otimizar Loja 2 (reduzir frete, melhorar avaliações).

📝 Notas





O projeto assume que cada linha do CSV representa uma venda unitária (sem coluna qtd_vendida).



Gráficos incluem pizza (avaliações, frete) e barras (produtos) para visualização clara.



Para dados reais, execute o caderno e compartilhe as saídas.

📬 Contato

Para dúvidas ou ajustes, entre em contato via [seu canal preferido] ou abra uma issue no repositório.
