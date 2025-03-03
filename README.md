# Otimização por Enxame de Partículas (PSO)

Este projeto implementa o algoritmo de Otimização por Enxame de Partículas (PSO - Particle Swarm Optimization) para encontrar o mínimo global de uma função de custo. O PSO é um algoritmo de otimização metaheurístico inspirado no comportamento social de bandos de pássaros ou cardumes de peixes.

## Função de Custo

A função de custo utilizada neste projeto é:

$f(x, y) = -e^{-0.2 \sqrt{x^2 + y^2} + 3 (\cos(2x) + \sin(2y))}$

sujeita a -5 ≤ x ≤ 5 e -5 ≤ y ≤ 5.

## Parâmetros

Os parâmetros do algoritmo PSO podem ser ajustados na seção "Parâmetros iniciais" do notebook. Os parâmetros incluem:

* `tamanho_enxame`: O número de partículas no enxame.
* `dimensao`: A dimensão do espaço de busca.
* `max_iteracoes`: O número máximo de iterações.
* `cognitivo`: O parâmetro cognitivo.
* `social`: O parâmetro social.

## Resultados

Os resultados do algoritmo PSO são apresentados na seção "Resultados" do notebook. Os resultados incluem:

* O melhor custo global encontrado.
* A melhor posição global correspondente.
* Gráficos da evolução dos custos e do diagrama de Pareto.
* Uma animação do enxame de partículas em movimento.

## Observações

* O algoritmo PSO é um algoritmo estocástico, portanto os resultados podem variar entre as execuções.
* Os parâmetros do algoritmo PSO podem ser ajustados para melhorar o desempenho.
* O notebook inclui visualizações para ajudar a entender o comportamento do algoritmo PSO.

## Referência
Haupt, R. L. and Haupt, S. E. Practical Genetic Algorithms. Wiley-Interscience, 2ª Edição. 2004.
