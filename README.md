# Desafio: Criação de um Sistema de Predição Inteligente de Estoque usando IA da Amazon
Olá! Estou animado para compartilhar com vocês meu mais recente projeto, que envolve a criação de um repositório de estoque inteligente utilizando o Amazon SageMaker Canvas. O objetivo deste projeto é desenvolver um sistema de predição inteligente de estoque, aproveitando as poderosas capacidades de inteligência artificial oferecidas pela Amazon.

## Sobre o Projeto
Gerenciar o estoque de maneira eficiente é um desafio constante para muitas empresas. A falta ou o excesso de produtos pode resultar em perdas financeiras significativas. Com isso em mente, decidi criar um sistema que usa a IA para prever a demanda de produtos, ajudando assim a otimizar os níveis de estoque e melhorar a eficiência operacional.

## Ferramentas Utilizadas
Para este projeto, escolhi o Amazon SageMaker Canvas, uma ferramenta robusta que facilita a criação de modelos de machine learning sem a necessidade de escrever código. Com ele, posso construir e treinar modelos preditivos usando dados históricos de estoque, além de realizar análises detalhadas para obter insights valiosos.

## Dataset Utilizado
Utilizei uma planilha de dataset com 1000 entradas, que inclui informações sobre preço variável e renovação de estoque. Esses dados foram essenciais para treinar o modelo de predição e garantir a precisão das previsões.

## Indicativos de Desempenho
Durante a análise realizada pelo Amazon SageMaker Canvas, obtivemos os seguintes indicativos de desempenho do modelo preditivo:

° Avg. wQL (Average weighted Quantile Loss): 1.000
    - Mede a perda quantílica ponderada média. Um valor menor indica um modelo melhor. No nosso caso, o valor é 1.000, o que sugere que o modelo precisa ser refinado.

° MAPE (Mean Absolute Percentage Error): 1.000
    - Indica o erro percentual absoluto médio. Um valor menor é melhor, e 1.000 mostra que o modelo precisa de melhorias para ser mais preciso.

° WAPE (Weighted Absolute Percentage Error): 1.000
    - Representa o erro percentual absoluto ponderado. Tal como o MAPE, um valor menor indica maior precisão, e aqui também obtivemos 1.000.

° RMSE (Root Mean Squared Error): 3.326
    - É a raiz do erro quadrático médio. Um valor menor é melhor, e 3.326 indica a precisão das previsões em termos de unidades de estoque.

° MASE (Mean Absolute Scaled Error): 0.018
    - Mede o erro absoluto médio escalado. Valores menores indicam melhor desempenho, e 0.018 mostra que o modelo tem um bom desempenho relativo a um modelo de referência simples.

## Resultados Esperados
Espero que este sistema de predição inteligente de estoque ajude empresas a reduzir custos, minimizar desperdícios e melhorar a satisfação do cliente, garantindo que os produtos certos estejam disponíveis na hora certa.

# Conclusão
Estou entusiasmado com o potencial deste projeto e acredito que ele pode fazer uma diferença significativa na forma como os estoques são gerenciados. Agradeço seu interesse e estou aberto a sugestões e colaborações para aprimorar ainda mais este sistema.