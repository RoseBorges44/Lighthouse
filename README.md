# Lighthouse
![image](https://github.com/RoseBorges44/Lighthouse/assets/122793017/436614c1-827c-4537-81d4-1884fb7bafbc)


Este repositório contém o código e os resultados do projeto de análise de dados de carros usados. O projeto "Lighthouse" visa explorar, analisar e prever o preço de carros usados com base em um conjunto de dados contendo informações relevantes.

## Análises Estatísticas e EDA

O conjunto de dados utilizado neste projeto consiste em registros de carros usados. Ele inclui informações como marca, modelo, ano, quilometragem, estado, transmissão, tipo de combustível, número de portas e preço.

As análises estatísticas e exploratórias de dados revelaram insights interessantes sobre os dados, incluindo:

- A marca mais popular de carros usados é a Volkswagen, seguida da Chevrolet, Toyota e da Hyundai.
- O modelo mais comum encontrado é Branco com Câmbio Automático.
- Os anos mais frequentes nos dados são 2020, 2017 e 2019.
- A quilometragem média dos carros é de aproximadamente 57434 km.
- O estado com o maior número de carros usados é o São PAulo, seguido da Rio de Janeiro e do Paraná.
- A transmissão automática é mais comum do que a manual entre os carros usados.
- A maioria dos carros possui quatro portas.

## Hipóteses de Negócio

Com base nas análises estatísticas e exploratórias realizadas, algumas hipóteses de negócio podem ser formuladas, incluindo:

1. Carros mais recentes têm uma tendência de ter preços mais altos em relação aos mais antigos.
3. Carros com menor quilometragem tendem a ter preços mais altos do que aqueles com quilometragem mais alta.
4. Carros com transmissão automática podem ter preços mais altos do que aqueles com transmissão manual.
6. Carros com quatro portas podem ter preços mais elevados em relação aos de duas portas.

## Previsão do Preço

Para prever o preço dos carros usados, foi utilizado um modelo de regressão linear múltipla. O modelo foi treinado e testado em um conjunto de dados. Com base nas características como marca, ano, quilometragem e estado.

## Resultados Finais

Os resultados finais do modelo de previsão podem ser encontrados no arquivo `predicted.csv`. Esse arquivo contém duas colunas: "id" (identificador do carro) e "price" (preço previsto do carro). Esses resultados podem ser utilizados para auxiliar vendedores e compradores de carros usados a tomar decisões informadas e negociar preços de forma mais eficiente.

## Contribuição

Este projeto está aberto a contribuições. Se você deseja sugerir melhorias, corrigir problemas ou adicionar novas funcionalidades, fique à vontade para abrir uma nova issue ou enviar um pull request.


