# Mulheres e Racismo no Brasil: 

## Desafios e Oportunidades em um Contexto de Desigualdade* *2018 a 2022***

# Projeto Final REPROGRAMA: Mulheres e Racismo no Brasil: Desafios e Oportunidades em um Contexto de Desigualdade

## Base de Dados
**Atlas de Vulnerabilidade Social - IPEA**  
**Fonte:** [IPEA - Atlas de Vulnerabilidade Social](https://ivs.ipea.gov.br/#/repositorio#shapes)  
**Autoras:** Jéssica Bernardo e Nathália Pereira  

## Período Observado

**2018 a 2022 (5 anos)**

## 🧾Descrição do Projeto

Este projeto explora as interseções entre vulnerabilidade social e raça no contexto das mulheres no Brasil. Utilizando dados e análises estatísticas, o objetivo é examinar como as diferenças raciais impactam as oportunidades e condições de vida das mulheres no Brasil, considerando dimensões sociais, econômicas e educacionais.

## 🛠️Estrutura

O projeto está organizado em um Jupyter Notebook que contém:

1. **Coleta e tratamento de Dados**: Importação da fonte de dados, filtragem e limpeza do dataset.

2. **Análise Exploratória e visualizações**: Estudo sobre as desigualdades enfrentadas por mulheres negras em comparação com mulheres brancas.

3. **Insights**: Discussão dos principais achados e implicações para políticas públicas. Reflexões sobre os desafios e oportunidades para promover a equidade racial e de gênero.

   

### Etapa 1

Na primeira etapa foi realizada uma triagem inicial dos dados da planilha bruta referente à base do Atlas de Vulnerabilidade Social (IPEA), que contém 103 colunas e 340.787 linhas. Dada a complexidade e o volume dos dados, a visualização direta no VSCode apresentou limitações na leitura e manipulação inicial do arquivo .xlsx. 

Assim, optou-se por uma análise preliminar utilizando o Excel, onde foram excluídas 65 colunas de indicadores que não serão abordados nesta análise. Além disso, foi feito um recorte temporal, restringindo os dados aos últimos cinco anos disponíveis, ou seja, de 2018 a 2022, de forma a focar nas informações mais recentes e relevantes para o estudo.

### Etapa 2 

Na segunda etapa da análise exploratória, foi possível realizar a leitura do arquivo diretamente no visualizador de dados, o que facilitou uma abordagem mais detalhada. Com base na definição prévia das visualizações que serão o foco da análise, foi realizada uma filtragem mais refinada do dataset, envolvendo as seguintes ações:

- **Limpeza detalhada do dataset:** Excluíram-se colunas que apresentavam ambiguidades ou que não estavam alinhadas com o objetivo central das visualizações planejadas.
- **Tratamento de valores nulos:** Foi realizada uma análise dos valores ausentes, com a substituição das células preenchidas com caractere hífen para representar valores nulos (NaN).
- **Remoção de duplicatas:** Foram identificadas e eliminadas possíveis entradas duplicadas, garantindo a integridade dos dados.
- **Tipagem dos dados:** Correção da tipagem realizada pela leitura do arquivo em colunas numéricas identificadas inicialmente como `Object` devido ao caractere separador decimal ser vírgula ao invés de ponto.
- **Filtragem:** Incluir apenas dados específicos de cor, filtrando informações gerais de ambas as cores. Incluir apenas dados gerais sobre domicílio (urbano e rural).
- **Salvamento do dataset final:** Após a aplicação dessas limpezas e ajustes, o dataset final foi salvo em formato `.csv`, estando pronto para as análises e visualizações subsequentes.

Essa etapa de limpeza e refinamento dos dados garante que o conjunto de dados final seja coeso, claro e pronto para a exploração mais aprofundada.



#### **Etapa 3**

##### Perguntas Norteadoras

- ### Renda e Trabalho

  1. A análise da renda per capita mediana entre 2018 e 2022 revela que mulheres brancas apresentam rendimento superior ao de mulheres negras?
  2. Qual a proporcionalidade de raça entre mulheres que geram empregos e que ocupam cargos públicos, considerando que são aspectos indicativos de prosperidade profissional?
  3. Como se distribuem as taxas de trabalho informal entre os estados brasileiros, considerando o recorte racial?

  ### Sociedade e Oportunidade

  1. Qual é a cor predominante na população que apresenta a maior taxa de trabalho precoce?
  2. Qual é a cor predominante na população que apresenta a maior taxa de maternidade precoce?
  3. Qual é a proporção de mulheres chefes de família com filhos menores de 15 anos, e como essa distribuição varia entre diferentes raças?



## 💻Tecnologias Utilizadas

- Python
- Bibliotecas: Pandas, Matplotlib, Seaborn

## 🙌Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para enviar um pull request ou abrir uma issue para discutir melhorias ou novas análises.