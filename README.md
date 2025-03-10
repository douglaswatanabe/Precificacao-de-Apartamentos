# [PROJETO: PRECIFICAÇÃO DE APARTAMENTOS À VENDA EM SÃO PAULO](https://github.com/douglaswatanabe/Precificacao-de-Apartamentos/blob/main/Precificacao%20de%20Apartamentos.ipynb)

Este projeto foi desenvolvido seguindo a metodologia **CRISP-DM (Cross Industry Standard Process for Data Mining)**, com o objetivo de criar um modelo preditivo para auxiliar na precificação de apartamentos em São Paulo, levando em conta dados históricos e características específicas dos anúncios.

A metodologia CRISP-DM organiza o processo analítico em seis etapas estruturadas: **Entendimento do Negócio, Entendimento dos Dados, Análise e Preparação dos Dados, Modelagem, Avaliação e Implementação.** Essa abordagem permite transformar dados em informações valiosas, promovendo previsões mais precisas e soluções eficazes para problemas complexos.

O projeto é apresentado de forma sistemática: inicialmente, abordamos o **contexto do mercado imobiliário e a definição do problema de negócio**, seguido pelo desenvolvimento das etapas metodológicas. Por fim, são discutidos os **resultados e impactos financeiros**, destacando os ganhos operacionais proporcionados pelo modelo implementado.
## Contexto do Mercado Imobiliário

O mercado imobiliário em São Paulo é extremamente dinâmico e competitivo, caracterizado por uma grande quantidade de imóveis sendo anunciados diariamente para venda ou aluguel. Nesse cenário, tanto imobiliárias quanto proprietários enfrentam desafios significativos para definir preços adequados, o que impacta diretamente no tempo de venda e na receita gerada. Propriedades subprecificadas tendem a ser vendidas abaixo do valor justo, acarretando prejuízos financeiros, enquanto imóveis superprecificados permanecem mais tempo no mercado, elevando custos com manutenção e anúncios. Nesse contexto, a utilização de modelos preditivos baseados em ciência de dados surge como uma oportunidade estratégica para oferecer precificações mais assertivas, otimizando o tempo de venda, aumentando a competitividade e maximizando a receita das transações imobiliárias.

## Problema de Negócio

O mercado imobiliário enfrenta desafios complexos relacionados à precificação de imóveis, especialmente em uma cidade dinâmica como São Paulo. As principais dificuldades são:  

- **Ineficiência nos processos de precificação:** A precificação é frequentemente realizada de forma manual ou intuitiva, consumindo tempo valioso que poderia ser direcionado ao atendimento personalizado e a estratégias comerciais mais eficazes. 

- **Risco financeiro:** Valores subestimados geram perda de receita para imobiliárias e proprietários, comprometendo a rentabilidade das operações.  

- **Superprecificação e permanência prolongada no mercado:** Imóveis com preços superestimados tendem a permanecer no mercado por longos períodos, gerando custos adicionais com manutenção, divulgação e perda de competitividade.  

**Objetivo Principal:**  
Desenvolver um modelo preditivo para auxiliar na definição do preço de venda de apartamentos em São Paulo, considerando dados históricos e características específicas dos anúncios.

## Resultados e Conclusão

A adoção do modelo de machine learning trouxe uma série de vantagens impactantes para o processo de precificação imobiliária, evidenciadas nas seguintes métricas e resultados quantitativos:

- **Melhoria na Competitividade:** Com um erro médio absoluto (MAE) de 14,229.54 e um erro percentual absoluto médio (MAPE) de 1.77%, a precificação permaneceu bastante competitiva, aumentando a atratividade dos imóveis e acelerando o ciclo de vendas.

- **Redução de Perdas:** O modelo conseguiu minimizar significativamente as perdas por subprecificação, reduzindo a perda total de 67,800,927.35 (subprecificação pelos corretores) para apenas 13,930,613.76 Isso representa uma redução de aproximadamente **79%** nas perdas. Como resultado, o retorno financeiro expressivo foi de 59,494,854.17.

- **Redução do Tempo de Venda:** A utilização do modelo resultou em uma redução do tempo médio de venda de imóveis de 120 dias para 90 dias (redução de 25%). Isso resultou em uma economia significativa de aproximadamente 10,466,765.09 em custos relacionados à manutenção, divulgação e impostos.

- **Eficiência Operacional:** A automatização do processo de precificação liberou os corretores de atividades manuais, permitindo que eles se concentrem em tarefas mais estratégicas, como negociações e atendimento ao cliente, aumentando a qualidade do serviço prestado.

- **Decisões Baseadas em Dados:** O uso de algoritmos inteligentes não só otimizou a precificação, mas também forneceu insights robustos para a tomada de decisões. Isso aumentou a assertividade e a confiança na definição de preços, alinhando-os de forma mais precisa com o mercado.

Em síntese, a implementação de um modelo preditivo de machine learning não apenas otimiza a precificação de imóveis, mas também contribui para uma operação mais eficiente e lucrativa. Os ganhos financeiros diretos, somados a uma experiência aprimorada para corretores, imobiliárias e proprietários, posicionam este modelo como uma solução inovadora e estratégica no mercado imobiliário. A combinação de precisão na precificação e eficiência operacional representa uma vantagem competitiva significativa, que pode ser decisiva em um ambiente dinâmico e em constante mudança.

## Observações sobre a Validação do Modelo

  - É importante destacar que os resultados deste projeto foram obtidos em um ambiente controlado, com dados históricos e simulações. O conjunto de teste utilizou **1.886 registros de apartamentos**, e algumas estimativas foram necessárias para calcular os impactos financeiros e operacionais. Embora os resultados indiquem grande potencial, o modelo ainda não foi validado em condições reais de mercado. Para uma avaliação definitiva, seria fundamental realizar testes práticos e acompanhar os impactos ao longo do tempo, considerando variações de mercado, sazonalidades e outros fatores externos.


