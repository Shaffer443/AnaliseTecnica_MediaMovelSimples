# Análise Tecnica Média Movel Simples

Analisando dados da Vale3, com média móvel simples com python, pandas e yfinance

Na análise técnica, a média móvel é um dos indicadores mais utilizados pelos investidores e traders.
Neste mini tutorial te ensianremos a criá-la utilizando o Python

Criado e usando o Google Colab

Usando a biblioteca yfinance par dados financeiros e também a biblioteca pandas para cria o Data Frame

- !pip install yfinance
- import yfinance as yf
- import pandas as pd

1 - Criamos duas váriáveis para desterminar o começo e o fim do periodo a ser analisado.

2 - Iniciar a importação dos dados de ações. Vamos obter os dados da _Vale3_. Utilize esse mesmo modelo para buscar dados de qualquer outro papel.
E não esuqeçad e adicionar o ".SA" ao fim das ações brasileiras.

3 - Função head(), mostra os 5 primeiros reaultados do Data Frame, e tail(), mostra os 5 ultimos resultados do Data Frame.

4 - Criação das médias móveis de fato. No entanto, precisamos primeiramente definir: O que são média móveis.

5 - a média móvel simples é basicamente a média de N variáveis passados. Por exemplo: a média móvel simples de 20 periodos retorna a média
dos ultimos X dias.

6 - Criar dois objetos: Um contendo a média móvel de 20 periodos e outro de 60 periodos.

7 -  basta plotar a coluna de preços ajutsados de _Vale 3_ com duas colunas das m


