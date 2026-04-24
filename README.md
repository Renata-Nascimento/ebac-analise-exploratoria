# ebac-analise-exploratoria
Este projeto faz parte do curso Analista de Dados da EBAC e analisa os dados de logística e entregas da empresa Loggi no Distrito Federal para identificar oportunidades de otimização.
O dado bruto é um arquivo do tipo JSON com uma lista de instâncias de entregas.

## Contexto
As entregas são feitas por veículos que pertencem a hubs, que são centros de distribuição. Cada instância representa um conjunto de entregas que devem ser realizadas pelos veículos do hub regional.
Nessa análise podemos observar o volume de entregas associadas a cada hub e suas disposições geográficas. Também podemos obervar a distribuição espacial dos endereços de entrega e suas distâncias dos hubs.

## 🛠️ Pacotes e bibliotecas

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-blue?style=for-the-badge&logo=python&logoColor=white)
![JSON](https://img.shields.io/badge/json-5E5E5E?style=for-the-badge&logo=json&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%231c1c1c.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Geopandas](https://img.shields.io/badge/Geopandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

## 📈 Análise
* Tratamento de dados brutos da Loggi.
* Visualização de mapas de entrega por região.
* Insights sobre a proporção de entregas por hubs.

## Insights gerados:

* A distribuição das entregas está muito concentrada nos hubs das regiões 1 e 2, mas pouco no da região 0. Contudo a capacidade dos veículos é mesma para todos os hubs, logo os veículos poderiam ser deslocados para as regiões de maior tráfego.
* As entregas estão corretamente alocadas aos seus respectivos hubs;
* Os hubs das regiões 0 e 2 fazem entregas em locais distantes do centro e entre si, o que pode gerar um tempo e preço de entrega maior.
* A empresa poderia usar veículos com menor capacidade para economizar combustível na região 0 ou realocar parte desses veículos de maior capacidade para as regiões 1 e 2.

## 🔗 Link para o Notebook
[Clique aqui para abrir o projeto no Google Colab](https://colab.research.google.com/github/Renata-Nascimento/ebac-analise-exploratoria/blob/main/Profiss%C3%A3o_Analista_de_dados_M16_1_Exerc%C3%ADcio.ipynb)
