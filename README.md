# Fundamentos_da_Descoberta_de_Dados
Descrição do Projeto

Este projeto faz parte do Módulo 13 do curso de Cientista de Dados e tem como objetivo aplicar conceitos estatísticos e de visualização de dados para analisar um conjunto de dados de produtos de um supermercado no Chile. O dataset contém informações sobre produtos, incluindo preços normais, descontos aplicados, marcas e categorias.

Os principais objetivos do projeto são:





Calcular a média e a mediana dos preços normais por categoria de produto e identificar discrepâncias.



Analisar o desvio padrão dos preços por categoria e entender o comportamento da média e mediana nas categorias com maior variabilidade.



Visualizar os dados por meio de gráficos interativos, como boxplots e treemaps, para explorar a distribuição dos preços e descontos.

Estrutura do Repositório





Profissao_Cientista_de_Dados_M13_Projeto.ipynb: Notebook Jupyter contendo o código, análises estatísticas e visualizações.



MODULO7_PROJETOFINAL_BASE_SUPERMERCADO.csv: Arquivo CSV com os dados do supermercado.



average_discounts_treemap.html: Arquivo HTML gerado com o treemap interativo de média de descontos por categoria e marca.

Dependências

Para executar o notebook, você precisará das seguintes bibliotecas Python:





pandas



matplotlib



plotly

Você pode instalá-las usando os seguintes comandos:

pip install pandas
pip install matplotlib
pip install plotly

Como Executar





Clone este repositório para sua máquina local:

git clone <URL_DO_REPOSITORIO>



Certifique-se de que o arquivo CSV (MODULO7_PROJETOFINAL_BASE_SUPERMERCADO.csv) está no mesmo diretório do notebook.



Abra o notebook Profissao_Cientista_de_Dados_M13_Projeto.ipynb em um ambiente Jupyter Notebook ou Jupyter Lab.



Execute as células do notebook sequencialmente para carregar os dados, realizar as análises e gerar os gráficos.



Para visualizar os gráficos interativos, como o treemap, abra o arquivo HTML gerado (average_discounts_treemap.html) em um navegador.

Análises Realizadas

1. Média e Mediana dos Preços por Categoria





Calculamos a média e a mediana da coluna Preco_Normal para cada categoria.



Identificamos categorias onde a média diverge significativamente da mediana, indicando possíveis assimetrias na distribuição dos preços.

2. Desvio Padrão por Categoria





Calculamos o desvio padrão da coluna Preco_Normal por categoria.



Analisamos o comportamento da média e mediana nas categorias com maior desvio padrão, observando a presença de outliers e distribuições assimétricas.

3. Visualizações





Boxplot: Um boxplot foi gerado para a categoria com maior desvio padrão, permitindo a visualização da distribuição dos preços e a identificação de outliers.



Treemap Interativo: Um treemap interativo foi criado com Plotly para mostrar a média de descontos por categoria e marca. O gráfico permite explorar os dados hierarquicamente, com retângulos proporcionais à média de desconto e cores indicando a magnitude dos descontos.

Resultados





Média e Mediana: A média geral dos preços normais é de aproximadamente 2071 reais, enquanto a mediana é de 1269 reais, indicando uma distribuição assimétrica com muitos preços baixos e alguns preços muito altos.



Desvio Padrão: Categorias como lacteos apresentaram maior desvio padrão, refletindo uma alta variabilidade nos preços, possivelmente devido à presença de produtos premium (ex.: leites especiais com preços altos).



Visualizações:





O boxplot da categoria lacteos revelou uma distribuição assimétrica com vários outliers, indicando que alguns produtos têm preços muito acima da mediana.



O treemap interativo destacou que a categoria lacteos tem as maiores médias de desconto, especialmente para marcas como Colun (média de 1005 reais), enquanto categorias como frutas e verduras não apresentaram descontos significativos.

Observações





Os dados contêm muitos valores de desconto iguais a 0, que foram filtrados em algumas análises para evitar distorções nas médias.



As categorias estão em espanhol (ex.: lacteos, congelados, belleza-y-cuidado-personal), refletindo a origem chilena do dataset.



Não há informações geográficas no dataset, então "mapas interativos" foram interpretados como gráficos interativos (ex.: treemaps).

Autor

Este projeto foi desenvolvido por [Vinicius Martins Guimaraes] como parte do curso de Cientista de Dados. Para dúvidas ou sugestões, entre em contato via [viniciusmartinsguimaraes6@gmail.com].

Licença
