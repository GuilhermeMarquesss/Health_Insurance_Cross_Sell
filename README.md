# Health_Insurance_Cross_Sell
<img src="/src/health.jpg" alt="health"/>
==============================
## Contexto
Nosso cliente é uma Seguradora que forneceu Seguro Saúde para seus clientes agora eles precisam da sua ajuda na construção de um modelo para prever se os segurados (clientes) do ano passado também terão interesse no Seguro de Veículos fornecido pela empresa.

Construir um modelo para prever se um cliente estaria interessado em Seguro de Veículo é extremamente útil para a empresa, pois ela pode planejar adequadamente sua estratégia de comunicação para alcançar esses clientes e otimizar seu modelo de negócios e receita. **Nesse contexto, é essencial identificar quais clientes tem uma maior propensão à compra de um segundo produto que seria o seguro para veículo, uma vez que a parte comercial só dá conta de fazer 2000 ligações, tendo em vista que existe uma base de 380 mil registros de clientes.**

Cada apólice de seguro custa em média R$ 5.000,00 anual de forma que o seguro para cada apólice é R$ 100.000,00. Levando em consideração o levantamento que o time de analytics da empresa fez sobre o percentual e a probabilidade das pessoas que acabam ganhando o seguro, em média, a cada 100 clientes que compram o seguro de carro, 2 pessoas acabam ganhando o seguro, com um desvio padrão de +/- 1.

Agora, para prever se o cliente estaria interessado em seguro de veículo, você tem informações sobre dados demográficos (gênero, idade, tipo de código de região), Veículos (idade do veículo, danos), apólice (Premium, canal de fornecimento) etc.

## Objetivo do negócio:
* Fazer um ranqueamento das pessoas que tem uma probabilidade para compra do seguro de veículo.

## Entendimento do negócio:
1. Qual a motivação?
    * O pedido para o ranqueamento dos clientes com maiores chances de comprar o seguro foi feito pelo diretor comercial.
2. Qual a causa raíz do problema?
    * Dificuldade em determinar quais seriam as melhores pessoas para fazer ligação sobre a compra do produto, uma vez a base de clientes contava com 300 mil, e o time comercial só havia capacidade para fazer 2000 ligações.
3. Quem é o dono do problema?
    * Diretor Comercial da seguradora.
4. Qual é o formato da solução?
    * **Granularidade:** Previsão por cliente
    * **Tipo do problema:** Classificação e ranqueamento
    * **Potenciais métodos:** Classificação
    * **Formato de entrega:**
        - Lista com os nomes e informações dos clientes que estiverem mais propensos às compras.
# Condições
* Será adotado um valor médio de R$ 5.000,00 para cada apólice adquirida por um cliente
* Por causa de custo, apenas 20000 pessoas poderão ser ligadas.
* O valor do prêmio será de até R$ 100.000,00 com a probabilidade de haver apenas 1 pessoa ganhadora a cada 100 clientes


# Resultado
* Esse projeto teve um retorno de R$ 1,240,000.00

* O ganho desse projeto em relação a uma operação feita ao acaso pode ser dado a partir da curva lift do modelo escolhido, 
portanto temos a estimativa de um retorno acima da operação aletória de R$723,333.33
