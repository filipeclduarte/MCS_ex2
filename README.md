# MCS_ex2
Exercício n. 2 de MCS

O objetivo deste exercício foi realizar um experimento comparando estratégia de poda de múltiplos classificadores aplicada em três conjuntos de validação. Bagging foi escolhido como o gerador de um pool de 100 Perceptrons, os quais foram combinado pelo voto majoritário. Além disso, realizou-se a validação cruzada 10-folds. As métricas foram acurácia, f-measure, ROC e g-mean. Média e desvio-padrão foram computadas para todas as métricas e estratégias. 

As estratégias de poda empregadas foram GASEN e K-Best Means. GASEN utiliza algoritmos genéticos para determinar a combinação dos classificadores para formar o ensemble, enquanto o K-best Means utiliza o algoritmo K-means para criar clusters com base na similaridade entre os classificadores do pool gerado inicialmente. 


Experimento inspirado em: https://github.com/jpedrocm/pool-pruning-experiment

Dependências:

* Python >= 2.7.15
* NumPy >= 1.15.1
* SciPy >= 1.1.0
* pandas >= 0.23.4
* scikit-learn >= 0.19.2
