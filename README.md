# iFood Data Analyst Case - Uma Análise Exploratória em Python
## Sobre Mim

Nesse projeto busquei em extrair o máximo de informações sobre as características dos clientes e como cada uma influencia seus hábitos de compra e aceitação de cada campanha. 
Embora ainda exista espaço para descobertas, principalmente usando técnicas de machine learning, optei por fazer uma análise exploratória completa focando em métodos estatísticos e técnicas de programação em Python simples.
Esse projeto foi utilizado como prática para o que venho estudando ao longo dos últimos meses e escolhi o case do iFood por ser uma empresa que gosto muito e por me possibilitar simular um cenário real. Qualquer sugestão ou crítica construtiva é bem vinda! 


# Sobre o iFood

O iFood é o principal aplicativo de entrega de comida no Brasil, com presença em mais de mil cidades em todo o país. Ele conecta milhões de usuários a uma ampla variedade de restaurantes, oferecendo desde fast food até culinária gourmet. A interface amigável da plataforma permite que os clientes naveguem facilmente pelos menus, façam pedidos e acompanhem as entregas em tempo real. 
Manter um alto engajamento dos clientes é fundamental para o crescimento e a consolidação da posição da empresa como líder de mercado. Os analistas de dados que trabalham na equipe de dados são constantemente desafiados a fornecer insights e valor para a empresa por meio de projetos de escopo aberto. Este caso tem como objetivo simular essa situação. Neste caso, você é apresentado a um conjunto de dados de exemplo, que simula metainformações sobre o cliente e sobre as interações das campanhas do iFood com esse cliente


## O Case
Considere uma empresa bem estabelecida que opera no setor de varejo de alimentos. Atualmente, eles têm milhares de clientes registrados e atendem quase um milhão de consumidores por ano. Eles vendem produtos de 5 categorias principais: vinhos, carnes raras, frutas exóticas, peixes especialmente preparados e produtos doces. Esses produtos podem ser divididos em categorias ouro e regulares. Os clientes podem encomendar e adquirir produtos por meio de 3 canais de vendas: lojas físicas, catálogos e o site da empresa. Globalmente, a empresa teve receitas sólidas e uma margem de lucro saudável nos últimos 3 anos, mas as perspectivas de crescimento do lucro para os próximos 3 anos não são promissoras... Por essa razão, várias iniciativas estratégicas estão sendo consideradas para reverter essa situação. Uma delas é melhorar o desempenho das atividades de marketing, com um foco especial nas campanhas de marketing.

## Objetivos
1. Explore os dados – seja criativo e preste atenção aos detalhes. Você precisa fornecer à equipe de marketing uma melhor compreensão das características dos respondentes;
2. Proponha e descreva uma segmentação de clientes baseada nos comportamentos dos clientes.

## O dataset

| **Coluna**              | **Descrição**                                                                                     |
|--------------------------|---------------------------------------------------------------------------------------------------|
| `AcceptedCmp1`            | 1 se o cliente aceitou a oferta na 1ª campanha, 0 caso contrário                                  |
| `AcceptedCmp2`            | 1 se o cliente aceitou a oferta na 2ª campanha, 0 caso contrário                                  |
| `AcceptedCmp3`            | 1 se o cliente aceitou a oferta na 3ª campanha, 0 caso contrário                                  |
| `AcceptedCmp4`            | 1 se o cliente aceitou a oferta na 4ª campanha, 0 caso contrário                                  |
| `AcceptedCmp5`            | 1 se o cliente aceitou a oferta na 5ª campanha, 0 caso contrário                                  |
| `Response`                | 1 se o cliente aceitou a oferta na última campanha, 0 caso contrário                              |
| `Complain`                | 1 se o cliente reclamou nos últimos 2 anos, 0 caso contrário                                      |
| `DtCustomer`              | Data de cadastro do cliente na empresa                                                            |
| `Education`               | Nível de educação do cliente                                                                      |
| `Marital`                 | Estado civil do cliente                                                                           |
| `Kidhome`                 | Número de crianças pequenas no domicílio do cliente                                               |
| `Teenhome`                | Número de adolescentes no domicílio do cliente                                                    |
| `Income`                  | Renda anual do domicílio do cliente                                                               |
| `MntFishProducts`         | Valor gasto em produtos de peixe nos últimos 2 anos                                               |
| `MntMeatProducts`         | Valor gasto em produtos de carne nos últimos 2 anos                                               |
| `MntFruits`               | Valor gasto em frutas nos últimos 2 anos                                                          |
| `MntSweetProducts`        | Valor gasto em produtos doces nos últimos 2 anos                                                  |
| `MntWines`                | Valor gasto em vinhos nos últimos 2 anos                                                          |
| `MntGoldProds`            | Valor gasto em produtos de ouro nos últimos 2 anos                                                |
| `NumDealsPurchases`       | Número de compras feitas com desconto                                                             |
| `NumCatalogPurchases`     | Número de compras feitas via catálogo                                                            |
| `NumStorePurchases`       | Número de compras feitas diretamente em lojas                                                     |
| `NumWebPurchases`         | Número de compras feitas pelo site da empresa                                                     |
| `NumWebVisitsMonth`       | Número de visitas ao site da empresa no último mês                                                |
| `Recency`                 | Número de dias desde a última compra                                                             |

## Entregas

1. Exploração de Dados;
2. Segmentação;
4. Apresentação de negócios.


