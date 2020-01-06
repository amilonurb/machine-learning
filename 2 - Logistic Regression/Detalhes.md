* Exercícios de Programação 2 - Regressão Logística

* Linguagem: Octave

* Parte 1 - Regressão Logística
- sigmoid.m
    - Calcula a *função sigmóide* (ou função logística) para uma determinada entrada.
    - Parâmetros:
        - z: pode ser um escalar, vetor ou matriz

- costFunction.m
    - Calcula o custo do vetor __theta__ e as derivadas parciais de cada elemento do referido vetor. Esta função é utilizada pela função __fminunc__, que é uma função nativa do Octave para realizar otimização, ou seja, não é preciso mais escrever o algoritmo de otimização - no nosso caso, era o _Gradiente Descendente_.
    - Parâmetros:
        - X: conjunto de entrada (Features / Variáveis)
        - y: saídas esperadas para X
        - theta: parâmetros de inicialização

- predict.m
    - Classifica o valor de cada entrada, usando os parâmetros __theta__, em 0 ou 1.
    
* Parte 2 - Regressão Logística Regularizada
- costFunctionReg.m: similar a _costFunction.m_, mas utilizando o fator de regularização, tanto na função de custo quanto nas derivadas parciais. Na atividade, esta função também é utilizada pela função nativa __fminunc__.
