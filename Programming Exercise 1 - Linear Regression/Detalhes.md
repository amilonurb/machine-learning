* Exercícios de Programação 1 - Regressão Linear

* Linguagem: Octave
- warmUpExercise.m
    - exercício de aquecimento
    - calcula a matriz identidade 5x5

* Parte 1 - RL com uma variável
- computeCost.m
    - Calcula a *função de custo* do conjunto de treinamento
    - Parâmetros:
        - X: conjunto de entrada (Features/Variáveis)
        - y: saídas esperadas para X
        - theta: parâmetros de inicialização

- gradientDescent.m
    - É o algoritmo de *Gradiente Descendente* que ajusta os valores de __theta__ de modo a minimizar a função de custo.
    - Parâmetros:
        - X: conjunto de entrada (Features/Variáveis)
        - y: saídas esperadas para X
        - theta: parâmetros de inicialização
        - alpha: learning rate
        - num_iters: total de iterações do gradiente
    - Saídas:
        - theta: parâmetros ajustados
        - J_history: valor da função de custo em cada iteração
    
* Parte 2 - RL multivariável
