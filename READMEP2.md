# Projeto Prático 2

# 🤔 Etapa 1 - Entendendo o Problema

- Análise de vendas de jogos de vídeogames com mais de 100 mil cópias. Gerar insights sobre tais dados, com base no nome do jogo, plataforma, ano de lançamento, número de vendas e a região das vendas.
- Quais perguntas podemos responder?
- [x]  Quantos jogos temos disponíveis?
- [x]  Quais plataformas temos na base de dados?
- [x]  São jogos lançados em quais anos?
- [x]  Quais são os gêneros de jogos disponíveis?
- [x]  Quais são as regiões de vendas dos jogos?
- [x]  Como as variáveis se relacionam entre si?
- [x]  Qual jogo tem maior preço de venda?
- [x]  Qual plataforma tem maior preço de venda?
- [x]  Quantidade de jogos lançados por ano.
- [x]  Quais gêneros de jogos mais lançados?
- [x]  Dentro de cada ano entre 2008 e 2010, quais gêneros de jogos mais lançados?
- [x]  Qual o gênero de jogo tem o preço mais alto (globalmente)
- [x]  Quais as principais vendas globais por editor?
- [x]  Como são as vendas em cada região? E as vendas globais?
- [x]  Qual o gênero de jogo mais lançado por ano?
- [x]  Qual o gênero de jogo mais vendido por ano?
- [x]  Receita Total (Global_Sales) por região
- [x]  Distribuição de Vendas de jogos por região
- [x]  Histograma de Vendas por região
- [x]  Distribuição Bivariada de ano e vendas por região em relação ao gênero
- [x]  Como os valores de vendas variam em relação à região?
- Linguagem de Programação: Python
- Bibliotecas: Pandas, Numpy, Missingno, Matplotlib, Seaborn, Scipy

## 🧩 Etapa 2 - Coletando os Dados

- Fonte: Kaggle

[Video Game Sales](https://www.kaggle.com/datasets/gregorut/videogamesales)

Dicionário de Dados

- Rank - ranking de vendas gerais (int)
- Name - nome dos jogos (object)
- Platform - plataforma de venda dos jogos (ou seja, PC, PS4, etc.) (object)
- Year - ano de lançamento do jogo (float)
- Genre - gênero do jogo (object)
- Publisher - editora do jogo (object)
- NA_Sales - Vendas na América do Norte (em milhões) (float)
- EU_Sales - Vendas na Europa (em milhões) (float)
- JP_Sales - Vendas no Japão (em milhões) (float)
- Other_Sales - Vendas no resto do mundo (em milhões) (float)
- Global_Sales - Vendas mundiais (em milhões) (float)

[https://drive.google.com/drive/u/0/folders/1urLWyYC5-MLAWz5subsjZaxoW2rzpG2o](https://drive.google.com/drive/u/0/folders/1urLWyYC5-MLAWz5subsjZaxoW2rzpG2o)

### 🧠 Etapa 3 - Análise Exploratória dos Dados

Aqui nós vamos destrinchar os dados, entender tudo o que for importante para responder nossas perguntas.

- Use sua caixa de ferramentas
    - Criatividade
    - Bibliotecas e Ferramentas
    - Regra de Negócio
- Bibliotecas úteis para Análise e Visualização de Dadas
    - Pandas
    
    [pandas](https://pandas.pydata.org/)
    
    - Numpy
    
    [NumPy](https://numpy.org/)
    
    - Missingno
    
    [missingno](https://pypi.org/project/missingno/)
    
    - Matplotlib
    
    [Tutorials - Matplotlib 3.6.2 documentation](https://matplotlib.org/stable/tutorials/index.html)
    
    - Seaborn
    
    [seaborn: statistical data visualization - seaborn 0.12.1 documentation](https://seaborn.pydata.org/)
    
    - Scipy
    
    [SciPy](https://scipy.org/)
    
    ### 📊Etapa 4 - Apresentação
    
    - [x]  Quantos jogos temos disponíveis?
    
    ![Untitled](Projeto%20Pra%CC%81tico%202%204704655c7a5444cc9d734d654b32f786/Untitled.png)
    
    - [x]  Quais plataformas temos na base de dados?
    
    ![Untitled](Projeto%20Pra%CC%81tico%202%204704655c7a5444cc9d734d654b32f786/Untitled%201.png)
    
    - [x]  São jogos lançados em quais anos?
    
    ![Untitled](Projeto%20Pra%CC%81tico%202%204704655c7a5444cc9d734d654b32f786/Untitled%202.png)
    
    - [x]  Quais são os gêneros de jogos disponíveis?
    
    ![Untitled](Projeto%20Pra%CC%81tico%202%204704655c7a5444cc9d734d654b32f786/Untitled%203.png)
    
    - [x]  Quais são as regiões de vendas dos jogos?
    
    ![Untitled](Projeto%20Pra%CC%81tico%202%204704655c7a5444cc9d734d654b32f786/Untitled%204.png)
    
    - [x]  Como as variáveis se relacionam entre si?
    
    ![Untitled](Projeto%20Pra%CC%81tico%202%204704655c7a5444cc9d734d654b32f786/Untitled%205.png)
    
    - [x]  Qual jogo tem maior preço de venda?
    
    ![Untitled](Projeto%20Pra%CC%81tico%202%204704655c7a5444cc9d734d654b32f786/Untitled%206.png)
    
    - [x]  Qual plataforma tem maior preço de venda?
    
    ![Untitled](Projeto%20Pra%CC%81tico%202%204704655c7a5444cc9d734d654b32f786/Untitled%207.png)
    
    - [x]  Quantidade de jogos lançados por ano
    
    ![Untitled](Projeto%20Pra%CC%81tico%202%204704655c7a5444cc9d734d654b32f786/Untitled%208.png)
    
    - [x]  Quais gêneros de jogos mais lançados?
    
    ![Untitled](Projeto%20Pra%CC%81tico%202%204704655c7a5444cc9d734d654b32f786/Untitled%209.png)
    
    - [x]  Dentro de cada ano entre 2008 e 2010, quais foram os gêneros de jogos mais lançados?
    
    ![Untitled](Projeto%20Pra%CC%81tico%202%204704655c7a5444cc9d734d654b32f786/Untitled%2010.png)
    
    - [x]  Qual o gênero de jogo tem o preço mais alto (globalmente)
    
    ![Untitled](Projeto%20Pra%CC%81tico%202%204704655c7a5444cc9d734d654b32f786/Untitled%2011.png)
    
    - [x]  Quais as principais vendas globais por editor?
    
    ![Untitled](Projeto%20Pra%CC%81tico%202%204704655c7a5444cc9d734d654b32f786/Untitled%2012.png)
    
    - [x]  Como são as vendas em cada região? E as vendas globais?
    
    Vendas na América do Norte
    
    ![Untitled](Projeto%20Pra%CC%81tico%202%204704655c7a5444cc9d734d654b32f786/Untitled%2013.png)
    
    Vendas na Europa
    
    ![Untitled](Projeto%20Pra%CC%81tico%202%204704655c7a5444cc9d734d654b32f786/Untitled%2014.png)
    
    Vendas no Japão
    
    ![Untitled](Projeto%20Pra%CC%81tico%202%204704655c7a5444cc9d734d654b32f786/Untitled%2015.png)
    
    Vendas em demais regiões
    
    ![Untitled](Projeto%20Pra%CC%81tico%202%204704655c7a5444cc9d734d654b32f786/Untitled%2016.png)
    
    Vendas globais
    
    ![Untitled](Projeto%20Pra%CC%81tico%202%204704655c7a5444cc9d734d654b32f786/Untitled%2017.png)
    
    - [x]  Qual o gênero de jogo mais lançado por ano?
    
    ![Untitled](Projeto%20Pra%CC%81tico%202%204704655c7a5444cc9d734d654b32f786/Untitled%2018.png)
    
    - [x]  Qual o gênero de jogo mais vendido por ano?
    
    ![Untitled](Projeto%20Pra%CC%81tico%202%204704655c7a5444cc9d734d654b32f786/Untitled%2019.png)
    
    - [x]  Receita Total (Global_Sales) por região
    
    ![Untitled](Projeto%20Pra%CC%81tico%202%204704655c7a5444cc9d734d654b32f786/Untitled%2020.png)
    
    - [x]  Distribuição de vendas de jogos por região
    
    ![Untitled](Projeto%20Pra%CC%81tico%202%204704655c7a5444cc9d734d654b32f786/Untitled%2021.png)
    
    - [x]  Histograma de Vendas por região
    
    ![Untitled](Projeto%20Pra%CC%81tico%202%204704655c7a5444cc9d734d654b32f786/Untitled%2022.png)
    
    - [x]  Distribuição Bivariada de ano e vendas por região em relação ao gênero
    
    ![Untitled](Projeto%20Pra%CC%81tico%202%204704655c7a5444cc9d734d654b32f786/Untitled%2023.png)
    
    - [x]  Como os valores de vendas variam em relação à região?
    
    ![Untitled](Projeto%20Pra%CC%81tico%202%204704655c7a5444cc9d734d654b32f786/Untitled%2024.png)
