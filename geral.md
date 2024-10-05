
# Geral

## Matemática

### Limites
- **Definição**: Um limite descreve o comportamento de uma função à medida que sua variável independente se aproxima de um determinado valor.

  $$ \lim_{x \to a} f(x) = L $$

- **Exemplo**:

  $$ \lim_{x \to 0} \frac{\sin(x)}{x} = 1 $$

### Derivadas
- **Definição**: A derivada mede a taxa de variação de uma função em relação a sua variável independente.

  $$ \frac{d}{dx} f(x) = f'(x) $$

- **Produto de funções**:

  $$ \frac{d}{dx} [f(x) \cdot g(x)] = f'(x) \cdot g(x) + f(x) \cdot g'(x) $$

- **Quociente de funções**:

  $$ \frac{d}{dx} \left( \frac{f(x)}{g(x)} \right) = \frac{f'(x) g(x) - f(x) g'(x)}{g(x)^2} $$

- **Regra da Cadeia**:  
  Se \( y = f(g(x)) \), então:

  $$ \frac{dy}{dx} = \frac{dy}{dg} \cdot \frac{dg}{dx} $$

### Derivadas Parciais
- **Definição**: Utilizadas quando uma função depende de mais de uma variável, sendo que a derivada é calculada em relação a uma dessas variáveis, mantendo as outras constantes.

  $$ \frac{\partial f}{\partial x}, \frac{\partial f}{\partial y} $$

## Álgebra Linear

### Matrizes
- **Matriz Quadrada**: O número de linhas é igual ao número de colunas.
- **Matriz Identidade**:

  $$ I = \begin{bmatrix} 1 & 0 \\ 0 & 1 \end{bmatrix} $$

- **Matriz Diagonal**: Todos os elementos fora da diagonal principal são zero.

### Autovalores e Autovetores
- **Autovalores (\( \lambda \))**: Um fator de escalonamento associado a um autovetor.
- **Autovetores (\( v \))**: Vetores que, quando transformados por uma matriz, têm sua direção preservada, apenas escalados por um autovalor.

  $$ A \cdot v = \lambda \cdot v $$

## Normas

### Definição
Normas são usadas para medir o tamanho ou magnitude de vetores e matrizes, proporcionando uma métrica para quantificar erros ou distâncias.

### Tipos de Normas
- **Norma \( L_1 \) ou Manhattan**:

  $$ \| x \|_1 = \sum_{i=1}^{n} |x_i| $$

- **Norma \( L_2 \) ou Euclidiana**:

  $$ \| x \|_2 = \sqrt{\sum_{i=1}^{n} x_i^2} $$

- **Norma \( L_\infty \)**:

  $$ \| x \|_\infty = \max_i |x_i| $$

## Decomposição Matricial

### Definição
A decomposição matricial divide uma matriz em várias matrizes mais simples que, quando combinadas, produzem a matriz original. Isso facilita o trabalho com dados complexos.

### Exemplo: SVD (Singular Value Decomposition)
O SVD decompõe uma matriz \( A \) em três matrizes \( U \), \( \Sigma \), e \( V^T \), onde \( U \) e \( V^T \) representam os autovetores e \( \Sigma \) os autovalores.

## Otimização Matemática

### Definição
A otimização matemática busca encontrar a melhor solução para um problema, minimizando ou maximizando uma função objetivo, dada uma série de restrições.

### Otimização Convexa
- **Definição**: Um tipo de otimização onde a função objetivo é convexa, garantindo um único mínimo global.

- **Exemplo**: Usada em problemas financeiros para otimizar carteiras de investimento, buscando maximizar o retorno e minimizar o risco.

## Estatística

### Probabilidade
- **Definição**: A probabilidade é a medida da chance de um evento ocorrer.

  $$ P(A) = \frac{\text{número de resultados favoráveis}}{\text{número total de resultados}} $$

### Distribuições de Probabilidade
- **Distribuição Binomial**:

  $$ P(X = k) = \binom{n}{k} p^k (1 - p)^{n - k} $$

- **Distribuição Normal**:

  $$ f(x) = \frac{1}{\sqrt{2 \pi \sigma^2}} e^{-\frac{(x - \mu)^2}{2 \sigma^2}} $$

## Integrais

### Regras Básicas de Integração

1. **Integral de uma constante**:

   $$ \int c \, dx = c \cdot x + C $$

2. **Integral de potência**:

   $$ \int x^n \, dx = \frac{x^{n+1}}{n+1} + C $$
