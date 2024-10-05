# Projeto Final REPROGRAMA: Mulheres e Racismo no Brasil: Desafios e Oportunidades em um Contexto de Desigualdade

## Base de Dados
**Atlas de Vulnerabilidade Social - IPEA**  
**Fonte:** [IPEA - Atlas de Vulnerabilidade Social](https://ivs.ipea.gov.br/#/repositorio#shapes)  
**Autoras:** Jéssica Bernardo e Nathália Pereira  

## Objetivo Central
Examinar como as diferenças raciais impactam as oportunidades e condições de vida das mulheres no Brasil, considerando dimensões sociais, econômicas e educacionais.

## Etapa 1 da Análise Exploratória
Na primeira etapa da análise exploratória, foi realizada uma triagem inicial dos dados da planilha bruta referente à base do Atlas de Vulnerabilidade Social (IPEA), que contém 103 colunas e 340.787 linhas. Dada a complexidade e o volume dos dados, a visualização direta no VSCode apresentou limitações na leitura e manipulação inicial do arquivo xlsx. 

Assim, optou-se por uma análise preliminar utilizando o Excel, onde foram excluídas 68 colunas de indicadores que não serão abordados nesta análise. Além disso, foi feito um recorte temporal, restringindo os dados aos últimos cinco anos disponíveis, ou seja, de 2018 a 2022, de forma a focar nas informações mais recentes e relevantes para o estudo.

## Etapa 2 da Análise Exploratória
Na segunda etapa da análise exploratória, foi possível realizar a leitura do arquivo diretamente no visualizador de dados, o que facilitou uma abordagem mais detalhada. Com base na definição prévia das visualizações que serão o foco da análise, foi realizada uma filtragem mais refinada do dataset, envolvendo as seguintes ações:

- **Limpeza detalhada do dataset:** Excluíram-se colunas que apresentavam ambiguidades ou que não estavam alinhadas com o objetivo central das visualizações planejadas.
- **Tratamento de valores nulos:** Foi realizada uma análise dos valores ausentes, com a substituição das células preenchidas com caractere hífen para representar valores nulos (NaN).
- **Remoção de duplicatas:** Foram identificadas e eliminadas possíveis entradas duplicadas, garantindo a integridade dos dados.
- **Tipagem dos dados:** Correção da tipagem realizada pela leitura do arquivo em colunas numéricas identificadas inicialmente como `Object` devido ao caractere separador decimal ser vírgula ao invés de ponto.
- **Filtragem:** Incluir apenas dados específicos de cor, filtrando informações gerais de ambas as cores. Incluir apenas dados gerais sobre domicílio (urbano e rural).
- **Salvamento do dataset final:** Após a aplicação dessas limpezas e ajustes, o dataset final foi salvo em formato `.csv`, estando pronto para as análises e visualizações subsequentes.

Essa etapa de limpeza e refinamento dos dados garante que o conjunto de dados final seja coeso, claro e pronto para a exploração mais aprofundada.

## Período Observado
**2018 a 2022 (5 anos)**

## Perguntas Respondidas
- A renda per capita mediana de 2018-2022 de mulheres brancas é maior que a de mulheres negras?
- Qual é a taxa de formalidade no emprego entre pessoas brancas e pretas nas diversas regiões do Brasil?
- Qual é a cor predominante entre a população com a maior taxa de trabalho precoce?
- De que maneira o índice de expectativa de vida reflete as disparidades raciais na qualidade de vida e no acesso à saúde?

