# Cálculo Básico

## 1. Funções
- **Definição**: Uma função é uma relação que associa a cada elemento $x$ de um domínio um único elemento $y$ em um contradomínio.
- **Exemplo**: A função $f(x) = x^2$ associa a cada $x$ o valor de seu quadrado.
- **Notação**: $f: \mathbb{R} \to \mathbb{R}$, $f(x) = x^2$.

## 2. Limites
- **Definição**: O limite de uma função $f(x)$ quando $x$ tende a $a$ é o valor que $f(x)$ se aproxima à medida que $x$ se aproxima de $a$.
- **Fórmula da Soma**: 
  $$\lim_{x \to a} [f(x) + g(x)] = \lim_{x \to a} f(x) + \lim_{x \to a} g(x)$$
- **Fórmula do Produto**: 
  $$\lim_{x \to a} [f(x) \cdot g(x)] = \lim_{x \to a} f(x) \cdot \lim_{x \to a} g(x)$$
- **Fórmula do Quociente**: 
  $$\lim_{x \to a} \frac{f(x)}{g(x)} = \frac{\lim_{x \to a} f(x)}{\lim_{x \to a} g(x)}, \quad \text{se } \lim_{x \to a} g(x) \neq 0$$

## 3. Derivadas
- **Definição**: A derivada de uma função $f(x)$ mede a taxa de variação instantânea de $f$ em relação a $x$.
- **Notação**: $f'(x)$ ou $\frac{df}{dx}$.
- **Fórmula da Soma**: 
  $$\frac{d}{dx} [f(x) + g(x)] = f'(x) + g'(x)$$
- **Fórmula do Produto**: 
  $$\frac{d}{dx} [f(x) \cdot g(x)] = f'(x) \cdot g(x) + f(x) \cdot g'(x)$$
- **Fórmula do Quociente**: 
  $$\frac{d}{dx} \left[\frac{f(x)}{g(x)}\right] = \frac{f'(x) \cdot g(x) - f(x) \cdot g'(x)}{[g(x)]^2}$$
- **Derivada de Potência**: 
  $$\frac{d}{dx} [x^n] = n \cdot x^{n-1}$$

## 4. Derivadas Parciais
- **Definição**: Derivadas parciais são usadas para funções de várias variáveis e representam a taxa de variação em relação a uma variável, mantendo as outras constantes.
- **Notação**: $\frac{\partial f}{\partial x}$.
- **Fórmula da Soma**: 
  $$\frac{\partial}{\partial x} [f(x, y) + g(x, y)] = \frac{\partial f}{\partial x} + \frac{\partial g}{\partial x}$$
- **Exemplo**: Se $f(x, y) = x^2 + y^2$, então $\frac{\partial f}{\partial x} = 2x$ e $\frac{\partial f}{\partial y} = 2y$.

## 5. Máximos e Mínimos
- **Definição**: Máximos e mínimos são os pontos onde a função atinge seus valores mais altos (máximos) ou mais baixos (mínimos).
- **Critério da Derivada**: Um ponto $x = c$ é um ponto crítico se $f'(c) = 0$.
- **Teste da Segunda Derivada**:
  - Se $f''(c) > 0$, $x = c$ é um ponto de mínimo.
  - Se $f''(c) < 0$, $x = c$ é um ponto de máximo.

## 6. Integrais
- **Definição**: A integral de uma função $f(x)$ é a soma acumulada dos valores de $f(x)$ ao longo de um intervalo, representando a área sob a curva de $f(x)$.
- **Notação**: $\int f(x) \, dx$.

### Regras de Integração:
1. **Integral da Soma**: 
   $$\int [f(x) + g(x)] \, dx = \int f(x) \, dx + \int g(x) \, dx$$
2. **Integral do Produto por uma Constante**: 
   $$\int k \cdot f(x) \, dx = k \int f(x) \, dx$$
3. **Integral de Potência**: 
   $$\int x^n \, dx = \frac{x^{n+1}}{n+1} + C, \quad \text{para } n \neq -1$$
4. **Integral da Função Exponencial**: 
   $$\int e^x \, dx = e^x + C$$
5. **Integral da Função Seno e Cosseno**: 
   $$\int \sin(x) \, dx = -\cos(x) + C$$
   $$\int \cos(x) \, dx = \sin(x) + C$$
6. **Integral de Funções Racionais**: 
   $$\int \frac{1}{x} \, dx = \ln|x| + C$$


# Álgebra Linear

## 1. Vetores e Matrizes
- **Vetores**: Sequências ordenadas de números que representam pontos no espaço. Um vetor em $\mathbb{R}^n$ tem $n$ componentes.
  - **Exemplo**:
    
$$
v = \left(\begin{array}{c}
v_1 \\
v_2 \\
\vdots \\
v_n
\end{array}\right)
$$

- **Matrizes**: Arranjos retangulares de números dispostos em linhas e colunas.
  - **Exemplo**:
    
$$
A = \left(\begin{array}{cc}
1 & 2 \\
3 & 4
\end{array}\right)
$$

## 2. Operações com Vetores e Matrizes
- **Adição de Vetores**: Soma componente a componente.
    
$$
\mathbf{u} + \mathbf{v} = \left(\begin{array}{c}
u_1 + v_1 \\
u_2 + v_2 \\
\vdots \\
u_n + v_n
\end{array}\right)
$$

- **Multiplicação de Escalar por Vetor**: Multiplica cada componente do vetor por um escalar $c$.
    
$$
c \cdot \mathbf{v} = \left(\begin{array}{c}
c \cdot v_1 \\
c \cdot v_2 \\
\vdots \\
c \cdot v_n
\end{array}\right)
$$

- **Multiplicação de Matrizes**: Combinação de elementos de linhas e colunas.
    
(A · B)_{ij} = Σ_{k} A_{ik} · B_{kj}


- **Transposição**: Troca linhas por colunas de uma matriz.
  - Notação: $A^T$.

## 3. Tipos de Matrizes
- **Matriz Diagonal**: Todos os elementos fora da diagonal são zero.
- **Matriz Identidade ($I$)**: Matriz diagonal onde todos os elementos da diagonal são 1.
- **Matriz Simétrica**: $A$ é simétrica se $A = A^T$.
- **Matriz Ortogonal**: $A$ é ortogonal se $A \cdot A^T = I$.

## 4. Transformações Lineares
- **Definição**: Funções que mapeiam vetores para outros vetores preservando operações de adição e multiplicação por escalares.
  - **Exemplo**: $T(\mathbf{x}) = A \cdot \mathbf{x}$, onde $A$ é uma matriz e $\mathbf{x}$ é um vetor.
- **Aplicação**: Representam rotações, reflexões, dilatações e outras transformações no espaço.

## 5. Espaços e Subespaços Vetoriais de $\mathbb{R}^n$
- **Espaço Vetorial**: Conjunto de vetores que é fechado sob adição e multiplicação por escalar.
- **Subespaço**: Subconjunto de um espaço vetorial que é, ele próprio, um espaço vetorial.
  - **Exemplo**: O conjunto de todos os vetores múltiplos de um vetor fixo em $\mathbb{R}^3$.

## 6. Sistemas de Equações Lineares
- **Definição**: Conjunto de equações lineares que podem ser representadas na forma $A \cdot \mathbf{x} = \mathbf{b}$, onde $A$ é uma matriz de coeficientes, $\mathbf{x}$ é o vetor de incógnitas e $\mathbf{b}$ é o vetor de resultados.
- **Métodos de Resolução**: Eliminação de Gauss, Regra de Cramer, método da matriz inversa.

## 7. Normas de Vetores
- **Norma $L1$**: Soma dos valores absolutos dos componentes.
    
$$
||\mathbf{x}||_1 = \sum |x_i|
$$

- **Norma $L2$ (Euclidiana)**: Raiz quadrada da soma dos quadrados dos componentes.
    
$$
||\mathbf{x}||_2 = \sqrt{\sum x_i^2}
$$

- **Norma Infinita**: Valor absoluto máximo dos componentes.
    
$$
||\mathbf{x}||_\infty = \max |x_i|
$$

- **Norma $p$-Generalizada**: Raiz $p$-ésima da soma dos valores absolutos elevados a $p$.
    
$$
||\mathbf{x}||_p = \left(\sum |x_i|^p\right)^{1/p}
$$

- **Norma de Minkowski**: Generalização da norma $L_p$.
- **Norma de Chebyshev**: Igual à norma infinita.

## 8. Autovalores e Autovetores
- **Definição**: Dado uma matriz $A$, um vetor $\mathbf{v}$ não nulo é um autovetor de $A$ se $A \cdot \mathbf{v} = \lambda \cdot \mathbf{v}$, onde $\lambda$ é o autovalor correspondente.
- **Aplicação**: Usados para entender as propriedades de transformações lineares e resolver sistemas diferenciais.

## 9. Decomposição Matricial
- **Decomposição de Cholesky**:
  - **Definição**: Decompõe uma matriz simétrica e definida positiva $A$ em $A = L \cdot L^T$, onde $L$ é uma matriz triangular inferior.
  - **Aplicação**: Usada para resolver sistemas lineares de forma eficiente.
- **Singular Value Decomposition (SVD)**:
  - **Definição**: Decompõe uma matriz $A$ em $A = U \cdot \Sigma \cdot V^T$, onde $U$ e $V$ são matrizes ortogonais e $\Sigma$ é uma matriz diagonal com os valores singulares de $A$.
  - **Aplicação**: Compressão de dados, análise de componentes principais (PCA) e processamento de imagens.

# Otimização Matemática

## 1. Programação Linear Inteira e Mista
- **Programação Linear Inteira (PLI)**:
  - **Definição**: Problemas de programação linear onde todas as variáveis de decisão são restritas a valores inteiros.
  - **Exemplo**: Maximizar $z = 3x + 2y$ sujeito a $x + y \leq 4$, com $x, y \in \mathbb{Z}$.
  - **Aplicação**: Usada em problemas de alocação de recursos, roteamento e planejamento de produção.
- **Programação Linear Mista (PLM)**:
  - **Definição**: Problemas onde algumas variáveis de decisão são inteiras e outras podem ser contínuas.
  - **Exemplo**: Em um problema de planejamento de transporte, as variáveis que representam a quantidade de carga podem ser contínuas, enquanto as que indicam a presença ou ausência de uma rota são inteiras.
  - **Aplicação**: Usada em otimização de redes, problemas de logística e planejamento estratégico.

## 2. Problemas de Otimização Unidimensionais e Multidimensionais
- **Otimização Unidimensional**:
  - **Definição**: Problemas de otimização onde a função objetivo depende de uma única variável.
  - **Métodos**:
    - **Método da Bisseção**: Divide repetidamente o intervalo ao meio até encontrar um ponto ótimo.
    - **Método da Derivada**: Encontra os pontos onde a derivada da função é zero para identificar máximos e mínimos.
  - **Exemplo**: Minimizar $f(x) = (x - 2)^2$.
- **Otimização Multidimensional**:
  - **Definição**: Problemas onde a função objetivo depende de múltiplas variáveis.
  - **Métodos**:
    - **Gradiente Descendente**: Ajusta iterativamente os valores das variáveis na direção do gradiente para minimizar a função.
    - **Newton-Raphson**: Usa derivadas de segunda ordem (hessiana) para convergir ao ponto ótimo.
  - **Exemplo**: Minimizar $f(x, y) = x^2 + y^2$.

## 3. Problemas de Otimização com e sem Restrições
- **Otimização Sem Restrições**:
  - **Definição**: Problemas onde a função objetivo não está sujeita a restrições adicionais.
  - **Método**: Gradiente Descendente, que ajusta as variáveis diretamente para minimizar a função.
  - **Exemplo**: Minimizar $f(x) = x^2 + 2x + 1$.
- **Otimização com Restrições**:
  - **Definição**: Problemas onde a solução deve satisfazer um conjunto de restrições.
  - **Métodos**:
    - **Método dos Multiplicadores de Lagrange**: Usa multiplicadores para transformar um problema com restrições em um problema equivalente sem restrições.
      - **Fórmula**: $$\mathcal{L}(x, \lambda) = f(x) + \lambda (g(x) - c)$$
    - **Método da Barreira**: Adiciona penalidades na função objetivo para evitar violar as restrições.
  - **Exemplo**: Minimizar $f(x, y) = x^2 + y^2$, sujeito a $x + y \leq 1$.

## 4. Otimização Convexa
- **Definição**: Problemas de otimização onde a função objetivo e as restrições são convexas.
  - Uma função é convexa se, para qualquer dois pontos $x_1$ e $x_2$ no seu domínio, vale que:
  - 
$$
f(\lambda x_1 + (1 - \lambda) x_2) \leq \lambda f(x_1) + (1 - \lambda) f(x_2), \quad 0 \leq \lambda \leq 1
$$
    
- **Propriedade**: Em problemas de otimização convexa, qualquer ponto de mínimo local é também um mínimo global.
- **Métodos**:
  - **Gradiente Descendente**: Comportamento eficiente em funções convexas, onde convergirá para o mínimo global.
  - **Programação Quadrática**: Problemas convexos específicos onde a função objetivo é quadrática e as restrições são lineares.
- **Exemplo**: Minimizar $f(x) = x^2 + 4x + 5$.

## 5. Programação Dinâmica
- **Definição**: Abordagem para resolver problemas de otimização dividindo-os em subproblemas menores e solucionando-os de forma recursiva.
- **Princípio de Optimalidade**: A solução ótima de um problema pode ser construída a partir das soluções ótimas de seus subproblemas.
- **Estrutura**:
  - **Estados**: Representam a configuração do problema em um determinado ponto.
  - **Recursão**: Relaciona a solução de um estado com as soluções dos estados anteriores.
- **Aplicações**:
  - **Problemas de Roteamento**: Como o problema do caixeiro viajante.
  - **Problemas de Decisão**: Como alocação de recursos e planejamento de inventário.
- **Exemplo**: Problema da Mochila: Determinar quais itens levar em uma mochila para maximizar o valor total sem ultrapassar a capacidade.

