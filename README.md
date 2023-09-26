# E-Commerce-KDD

Este projeto de Data Science, intitulado "E-Commerce-KDD", representa uma abordagem abrangente e estruturada para a análise de dados em um contexto de comércio eletrônico. Organizado em uma série de notebooks, cada etapa foi projetada para conduzir uma investigação detalhada dos dados, desde o pré-processamento inicial até a tomada de decisões orientadas por dados.

## Dataset do Projeto

### Brazilian E-Commerce Public Dataset by Olist

O Conjunto de Dados Públicos de E-Commerce Brasileiro da Olist é a fonte de dados principal deste projeto. Esse conjunto de dados público contém informações sobre pedidos feitos na loja Olist, cobrindo um período de 2016 a 2018 e abrangendo vários marketplaces no Brasil. Ele fornece uma visão abrangente de cada pedido, incluindo detalhes sobre preço, método de pagamento, desempenho de frete, localização do cliente, atributos do produto e até avaliações escritas pelos clientes.

É importante notar que esses dados são reais, embora tenham sido anonimizados para proteger a privacidade das partes envolvidas. Além disso, para garantir a confidencialidade, as referências às empresas e parceiros nos textos das avaliações foram substituídas pelos nomes das grandes casas da série Game of Thrones.

### Fonte dos Dados

Os dados originais podem ser encontrados no Kaggle, no seguinte link:
[Dataset Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce?select=olist_order_items_dataset.csv)

## Dataset Unificado "relatório_vendas"

Após a aquisição dos dados do Conjunto de Dados Públicos de E-Commerce Brasileiro da Olist, foi realizado uma série de etapas de pré-processamento para garantir que os dados estivessem limpos, organizados e prontos para análise.  Uma etapa crucial desse processo de pré-processamento foi a junção dos vários arquivos de dados relacionados a itens_pedidos, pedidos, pagamentos, produtos, clientes, vendedores e avaliações em um único conjunto de dados centralizado intitulado "relatorio_vendas". Com isso permitirá ter uma visão holística e coesa de todas as informações relevantes para nossa análise de comércio eletrônico.

O "relatorio_vendas" se tornou a base das análises subsequentes para extrair insights significativos e tomar decisões orientadas por dados que podem beneficiar a organização.

## Etapas do Projeto

**1 - Pré-Processamento:** Inicialmente, abordaremos o notebook de pré-processamento. Esta etapa é essencial, pois estabelece as bases para toda a análise subsequente. Será realizado o processo de limpeza de dados, tratamento de valores ausentes, codificação de variáveis categóricas e normalização dos dados, assegurando que o conjunto de dados esteja preparado e de alta qualidade para análises subsequentes. O objetivo é criar um ambiente de dados confiável e consistente para explorar e modelar.

**2 - Análise Descritiva:** No segundo notebook, entramos na fase de análise descritiva. Apresentaremos estatísticas resumidas, gráficos informativos e insights iniciais sobre os principais atributos do conjunto de dados. Essa etapa permite obter uma compreensão geral da natureza dos dados, identificar tendências preliminares e iniciar o processo de geração de hipóteses para análises posteriores.

**3 - Análise Exploratória:** Avançando para o terceiro notebook, a análise exploratória nos levará a um nível mais profundo de compreensão dos dados. Serão realizadas análises estatísticas avançadas, criadas visualizações mais complexas e exploradas relações interativas entre variáveis. Essa etapa é crucial para revelar insights mais profundos e padrões ocultos que podem não ser evidentes na análise descritiva.

**4 - EDA-Conclusões e Insights:** No quarto notebook, consolidamos todas as informações e insights coletados durante as etapas anteriores de análise. Apresentaremos gráficos, tabelas e conclusões que ajudarão a contar a história dos dados de forma clara e eficaz. Este é um ponto crítico para comunicar de maneira persuasiva as descobertas e insights que extraímos, preparando o terreno para a fase de modelagem.

**5 - Modelos Preditivos:** A próxima fase envolve a construção de modelos preditivos em notebooks separados. Cada notebook se concentrará em um modelo específico, documentando detalhadamente o processo de treinamento, avaliação e otimização. Essa abordagem permite que os leitores compreendam o raciocínio por trás de cada modelo e avaliem os resultados individualmente.

**6 - Análise Prescritiva:** Neste ponto, chegamos ao último notebook, a fase de Análise Prescritiva. Consolidaremos todas as descobertas e insights até o momento, com foco em ações práticas e orientadas para dados. Destacaremos como as previsões dos modelos podem ser traduzidas em recomendações concretas e estratégias acionáveis para a organização. Além disso, discutiremos o impacto e as implicações dessas ações, demonstrando nosso compromisso em transformar análises em resultados tangíveis. Este notebook servirá como a culminação do projeto, fornecendo orientações claras para a implementação das recomendações e para as próximas etapas, reforçando assim nossa capacidade de criar valor a partir dos dados.
