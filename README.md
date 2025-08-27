# Alura Store

![Challenge (4)](https://github.com/user-attachments/assets/f5af95f7-551a-476e-be93-2dbcf2f56680)

## Visão Geral do Projeto
Este projeto tem como objetivo analisar dados de vendas da Alura Store, identificando padrões de faturamento, categorias mais vendidas e comportamento do frete. A análise foi desenvolvida em um Jupyter Notebook como parte de um desafio prático de Ciência de Dados.

## Estrutura do Projeto
- `ChallengeAluraStoreBr.ipynb` — Notebook principal com todo o processo de análise.
- `README.md` — Documento com instruções e explicações do projeto.

##   Requisitos

+ **Analisar os dados das lojas:** avaliar informações como faturamento, categorias mais vendidas, avaliações dos clientes, produtos mais vendidos e frete médio.
+ **Criar gráficos para visualização:** decidir quais tipos de gráficos usar para apresentar os resultados de maneira clara e visual (Mínimo de 3 gráficos diferentes, que podem incluir gráficos de barras, pizza, dispersão, entre outros).
+ **Apresentar uma recomendação:** Após as análises, escrever um texto explicando qual loja o Senhor João deve vender e por quê, com base nos dados apresentados.

## Tecnologias Utilizadas

![Python](https://img.shields.io/badge/python-%2314354C.svg?style=for-the-badge&logo=python&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-0064a5?style=for-the-badge&logo=matplotlib&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3f4f75?style=for-the-badge&logo=plotly&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-2b7489?style=for-the-badge&logo=seaborn&logoColor=white)
![Folium](https://img.shields.io/badge/Folium-77B829?style=for-the-badge&logo=leaflet&logoColor=white)

## Estrutura dos Dados
Os dados foram fornecidos em arquivos .csv e importados diretamente para o notebook usando a biblioteca pandas por meio de links do github.

Os principais campos disponíveis são:
- **Produto e Categoria**: Itens vendidos e suas classificações.
- **Preço e Frete**: Valores das vendas e custos associados.
- **Data de Compra e Local**: Informações temporais e geográficas.
- **Avaliação da Compra**: Feedback dos clientes.
- **Tipo de Pagamento e Parcelas**: Métodos utilizados pelos clientes.
- **Coordenadas Geográficas**: Localização das transações.

## Análise de Faturamento
Foi utilizada a biblioteca matplotlib para criar gráficos e assim adquirir diversos insights sobre cada uma das lojas. 

<p align="center">
  <img width="544" height="479" alt="image" src="https://github.com/user-attachments/assets/fe10c75c-bd6b-48ad-80f9-9cd3100d387a" />
</p>

De acordo com esse gráfico, a Loja 1 é a loja que mais faturou, representado 26.1% do total do faturamento da empresa, enquanto a loja 4 é a que menos faturou, representando 23.6% do faturamento total.

## Conclusão
Para determinar a loja com menor eficiência para a venda, é necessário considerar um panorama geral baseado em todas as análises feitas anteriormente.

- A Loja 1, apesar de ter o maior faturamento, apresenta a menor média de avaliação e a maior média de frete. A baixa avaliação pode indicar problemas de satisfação do cliente que podem impactar a sustentabilidade do faturamento a longo prazo. O frete mais caro também pode ser um fator de desvantagem competitiva.
- A Loja 3 se destaca pela alta avaliação dos clientes, o que é um ponto positivo para a fidelização e reputação. Seu faturamento é relevante e a média de frete é intermediária.
- As Lojas 2 e 4 possuem um desempenho intermediário em faturamento e avaliação. A Loja 4 se diferencia por ter a menor média de frete, o que pode ser um atrativo para alguns clientes.

Considerando o objetivo de iniciar um novo empreendimento e a necessidade de identificar a loja com menor eficiência em um sentido mais amplo de desempenho e potencial de crescimento, a Loja 1 se apresenta como a candidata mais provável para venda. Isso porque, apesar de gerar o maior faturamento no momento, a Loja 1 demonstra sinais de menor eficiência em termos de satisfação do cliente (menor avaliação) e competitividade de custos de envio (maior frete médio). Uma baixa satisfação do cliente pode levar a uma diminuição do faturamento no futuro. Vender a loja com a menor avaliação média pode ser a melhor estratégia no momento para focar em lojas com clientes mais satisfeitos e com maior potencial de crescimento sustentável.

## Certificado do Desafio
Este projeto foi desenvolvido como parte do Challenge ONE - Praticando Python para Data Science da Alura em parceria com a Oracle, através do programa Oracle Next Education (ONE).

<p align="center">
  <img width="300" height="300" alt="AluraStore" src="https://github.com/user-attachments/assets/6e2957d8-581b-4657-a721-44c81ebd6b78" />
</p>

Você pode também acompanhar a publicação que fiz sobre a conclusão deste projeto em meu LinkedIn! Fique a vontade também para se conectar comigo nessa rede social. 

<p>
  <a href="URL-DO-SEU-POST-NO-LINKEDIN-AQUI">
    <img src="https://img.shields.io/badge/Ver%20Postagem-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Post">
  </a>
</p>
