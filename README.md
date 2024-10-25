# iFood Data Analyst Case - Uma Análise Exploratória em Python

Nesse projeto busquei em extrair o máximo de informações sobre as características dos clientes e como cada uma influencia seus hábitos de compra e aceitação de cada campanha. Optei por fazer uma análise exploratória completa focando em métodos estatísticos e técnicas de programação em Python simples, sem utilizar algoritmos de machine learning.
Esse projeto foi utilizado como prática para o que venho estudando ao longo dos últimos meses e escolhi o case do iFood por ser uma empresa que gosto muito e por me possibilitar simular um cenário real. Qualquer sugestão ou crítica construtiva é bem vinda! 


## Objetivos
1. Exploração dos dados – fornecer uma melhor compreensão das características dos respondentes;
2. Propor uma segmentação de clientes baseada em seus comportamentos.

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
| `Income`                  | Renda anual do cliente                                                                            |
| `MntFishProducts`         | Valor gasto em produtos de peixe nos últimos 2 anos                                               |
| `MntMeatProducts`         | Valor gasto em produtos de carne nos últimos 2 anos                                               |
| `MntFruits`               | Valor gasto em frutas nos últimos 2 anos                                                          |
| `MntSweetProducts`        | Valor gasto em produtos doces nos últimos 2 anos                                                  |
| `MntWines`                | Valor gasto em vinhos nos últimos 2 anos                                                          |
| `MntGoldProds`            | Valor gasto em produtos de ouro nos últimos 2 anos                                                |
| `NumDealsPurchases`       | Número de compras feitas com desconto                                                             |
| `NumCatalogPurchases`     | Número de compras feitas via catálogo                                                             |
| `NumStorePurchases`       | Número de compras feitas diretamente em lojas                                                     |
| `NumWebPurchases`         | Número de compras feitas pelo site da empresa                                                     |
| `NumWebVisitsMonth`       | Número de visitas ao site da empresa no último mês                                                |
| `Recency`                 | Número de dias desde a última compra                                                              |

