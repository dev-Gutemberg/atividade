## Perguntas

1. # Conceito:
# Explique, com suas palavras, o que é um Perceptron e qual a sua importância histórica para o desenvolvimento da Inteligência Artificial
>O Perceptron foi desenvolvido por Frank Rosenblatt em 1958 e é considerado o primeiro modelo formal de rede neural artificial. Inspirado no funcionamento de um neurônio biológico, o Perceptron é um algoritmo capaz de realizar classificações lineares a partir de entradas numéricas, que são ponderadas por pesos e processadas por uma função de ativação para gerar uma

2. # Funcionamento:
# O Perceptron é considerado um classificador linear. O que isso significa? Quais são as limitações desse tipo de modelo?
>O Perceptron é chamado de classificador linear porque ele separa dados em classes utilizando uma linha (no caso 2D), um plano (3D) ou um hiperplano (mais dimensões) no espaço de características. Ou seja, ele aprende pesos para cada entrada e faz uma combinação linear dessas entradas; depois, aplica uma função de ativação para decidir a classe.
>Limitações: Só funciona para problemas linearmente separáveis, não aprende funções não lineares complexas, como XOR,saída binária, sem medir probabilidades.

3. # Código:
# Ao analisar o código que você executou, quais foram as etapas principais do processo de treinamento do Perceptron?
>Inicialização: Define pesos e viés iniciais.
>Cálculo da saída: Soma ponderada das entradas + viés e aplicação da função de ativação.
>Cálculo do erro: Diferença entre saída desejada e saída prevista.
>Atualização: Ajusta pesos e viés com base no erro e taxa de aprendizado.
>Repetição: Itera sobre todas as entradas várias vezes até convergir.

4. # Aplicação prática:
# Dê um exemplo real em que o uso de um modelo simples como o Perceptron poderia ser útil.Justifique sua escolha.
>Um exemplo real seria filtrar e-mails como “spam” ou “não spam” com base em poucas características simples, como a presença de certas palavras-chave.
>Justificativa:O problema é binário (spam ou não), então o Perceptron consegue separar as duas classes.Com poucas variáveis relevantes, um modelo simples já pode ter desempenho aceitável sem a complexidadede redes neurais maiores.É rápido de treinar e fácil de interpretar, ideal para situações simples de classificação linear.
