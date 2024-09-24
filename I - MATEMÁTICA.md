# Matemática

## 1. Cálculo Básico

### 1.1 - Funções

#### 1.1.1 - Definição de Função

Uma função é uma relação entre dois conjuntos, onde cada elemento do primeiro conjunto (domínio) está associado a um único elemento do segundo conjunto (contradomínio). A função é uma regra que determina como cada elemento do domínio se relaciona com um elemento do contradomínio.

Matematicamente, uma função $$f$$ de um conjunto $$A$$ para um conjunto $$B$$ é denotada por:

$$f: A \to B$$

Para cada $$x \in A$$, existe um único $$y \in B$$ tal que $$y = f(x)$$. O conjunto $$A$$ é chamado de **domínio**, e o conjunto dos valores resultantes $$f(x)$$ é chamado de **imagem** da função.

#### 1.1.2 - Notação e Exemplos Simples

- **Notação**: $$f(x)$$, onde $$f$$ é o nome da função e $$x$$ é a variável independente.
- **Exemplo**: A função $$f(x) = 2x + 3$$ associa cada número $$x$$ a um valor $$y$$ que é o dobro de $$x$$ somado a 3.

#### 1.1.3 - Fórmulas e Exemplos de Funções Comuns

##### 1.1.3.1 - Função Linear

Uma função linear tem a forma:

$$f(x) = ax + b$$

Onde:
- $$a$$ é o coeficiente angular (inclinação da reta).
- $$b$$ é o coeficiente linear (ponto de interseção com o eixo $$y$$).

**Exemplo**: $$f(x) = 2x + 1$$
- Para $$x = 0$$, $$f(0) = 2(0) + 1 = 1$$.
- Para $$x = 2$$, $$f(2) = 2(2) + 1 = 5$$.

A função descreve uma reta com inclinação 2 e intercepta o eixo $$y$$ no ponto (0, 1).

##### 1.1.3.2 - Função Quadrática

Uma função quadrática tem a forma:

$$f(x) = ax^2 + bx + c$$

Onde:
- $$a, b, c$$ são constantes.
- A função forma uma parábola.

**Exemplo**: $$f(x) = x^2 - 4x + 3$$
- Para $$x = 0$$, $$f(0) = 0^2 - 4(0) + 3 = 3$$.
- Para $$x = 1$$, $$f(1) = 1^2 - 4(1) + 3 = 0$$.

##### 1.1.3.3 - Função Exponencial

A função exponencial é dada por:

$$f(x) = a \cdot b^x$$

Onde:
- $$a$$ é o valor inicial.
- $$b$$ é a base da função exponencial.

**Exemplo**: $$f(x) = 2 \cdot 3^x$$
- Para $$x = 0$$, $$f(0) = 2 \cdot 3^0 = 2$$.
- Para $$x = 2$$, $$f(2) = 2 \cdot 3^2 = 18$$.

#### 1.1.4 - Como Determinar o Domínio de uma Função

O domínio de uma função são todos os valores possíveis de $$x$$ que podem ser inseridos na função. Para funções polinomiais (linear, quadrática), o domínio é todos os números reais ($$\mathbb{R}$$).

**Exemplo de Determinação do Domínio:**
- Para $$f(x) = \frac{1}{x - 2}$$, o domínio é todos os números reais exceto $$x = 2$$, pois dividir por zero não é permitido.

#### 1.1.5 - Gráficos de Funções

Os gráficos ajudam a visualizar como a função se comporta. O gráfico de uma função linear é uma linha reta, enquanto o de uma função quadrática é uma parábola.

**Exemplo Gráfico:**
- A função $$f(x) = x^2 - 4x + 3$$ forma uma parábola que cruza o eixo $$x$$ nos pontos onde $$f(x) = 0$$.

### 1.2 - Limites

#### 1.2.1 - Definição de Limite

O limite é um conceito fundamental no cálculo que descreve o comportamento de uma função à medida que a variável independente se aproxima de um determinado valor. Em termos simples, o limite de uma função $$f(x)$$ quando $$x$$ tende a um valor $$a$$ é o valor que $$f(x)$$ se aproxima quando $$x$$ se aproxima de $$a$$.

Matematicamente, escrevemos o limite de $$f(x)$$ quando $$x$$ tende a $$a$$ da seguinte forma:

$$\lim_{x \to a} f(x) = L$$

Onde:
- $$L$$ é o valor que a função se aproxima.
- $$a$$ é o valor para o qual $$x$$ tende.

#### 1.2.2 - Exemplos Simples de Limites

1. **Exemplo 1: Limite de uma função constante**

   $$\lim_{x \to 3} 5 = 5$$

   Neste caso, não importa o valor de $$x$$, o limite é sempre 5.

2. **Exemplo 2: Limite de uma função linear**

   $$\lim_{x \to 2} (3x + 1) = 3(2) + 1 = 7$$

   A função se aproxima do valor 7 quando $$x$$ se aproxima de 2.

3. **Exemplo 3: Limite que não existe**

   Se uma função se aproxima de valores diferentes à medida que $$x$$ se aproxima de um ponto de direções diferentes, o limite não existe.

   **Exemplo:**

   $$\lim_{x \to 0} \frac{1}{x}$$

   À medida que $$x$$ se aproxima de 0 pela esquerda, o valor da função vai para $$-\infty$$. Quando se aproxima pela direita, o valor vai para $$\infty$$. Portanto, o limite não existe.

#### 1.2.3 - Propriedades dos Limites

1. **Limite da soma**:

   $$\lim_{x \to a} [f(x) + g(x)] = \lim_{x \to a} f(x) + \lim_{x \to a} g(x)$$

2. **Limite do produto**:

   $$\lim_{x \to a} [f(x) \cdot g(x)] = \lim_{x \to a} f(x) \cdot \lim_{x \to a} g(x)$$

3. **Limite do quociente** (se o denominador não é zero):

   $$\lim_{x \to a} \frac{f(x)}{g(x)} = \frac{\lim_{x \to a} f(x)}{\lim_{x \to a} g(x)}$$

4. **Limite da função constante**:

   $$\lim_{x \to a} c = c$$

   Onde $$c$$ é uma constante.

#### 1.2.4 - Limites Laterais

Os limites laterais são usados para analisar o comportamento de uma função à medida que $$x$$ se aproxima de um ponto específico, tanto pela esquerda quanto pela direita.

- **Limite pela esquerda**: Denotado por $$\lim_{x \to a^-} f(x)$$, indica que $$x$$ está se aproximando de $$a$$ pela esquerda.
- **Limite pela direita**: Denotado por $$\lim_{x \to a^+} f(x)$$, indica que $$x$$ está se aproximando de $$a$$ pela direita.

#### 1.2.5 - Limites no Infinito

Os limites no infinito descrevem o comportamento de uma função quando $$x$$ tende a $$\infty$$ (ou $$-\infty$$).

- **Exemplo**:

  $$\lim_{x \to \infty} \frac{1}{x} = 0$$

  À medida que $$x$$ cresce, o valor da função $$\frac{1}{x}$$ se aproxima de 0.

### 1.3 - Derivadas

#### 1.3.1 - Definição de Derivada

A derivada de uma função mede a taxa de variação instantânea de uma função em relação a uma variável. Geometricamente, a derivada representa a inclinação da reta tangente à curva de uma função em um ponto específico.

Matematicamente, a derivada de $$f(x)$$ em relação a $$x$$ é definida como:

$$f'(x) = \lim_{\Delta x \to 0} \frac{f(x + \Delta x) - f(x)}{\Delta x}$$

#### 1.3.2 - Notações Comuns

- Leibniz: $$\frac{dy}{dx}$$
- Lagrange: $$f'(x)$$
- Newton: $$\dot{y}$$

#### 1.3.3 - Regras Básicas de Derivação

1. **Derivada de uma Constante:**

   $$\frac{d}{dx}(c) = 0, \text{ onde } c \text{ é uma constante.}$$

2. **Derivada de uma Potência:**

   $$\frac{d}{dx}(x^n) = n \cdot x^{n-1}$$

   **Exemplo:**

   $$\frac{d}{dx}(x^3) = 3x^2$$

3. **Derivada da Soma:**

   $$\frac{d}{dx}[f(x) + g(x)] = f'(x) + g'(x)$$

4. **Derivada do Produto:**

   $$\frac{d}{dx}[f(x) \cdot g(x)] = f'(x) \cdot g(x) + f(x) \cdot g'(x)$$

   **Exemplo:**

   Para $$f(x) = x^2$$ e $$g(x) = 3x$$:

   $$\frac{d}{dx} (x^2 \cdot 3x) = 2x \cdot 3x + x^2 \cdot 3 = 6x^2 + 3x^2 = 9x^2$$

5. **Derivada do Quociente:**

   $$\frac{d}{dx} \left(\frac{f(x)}{g(x)}\right) = \frac{f'(x) \cdot g(x) - f(x) \cdot g'(x)}{[g(x)]^2}$$

   **Exemplo:**

   Para $$f(x) = x^2$$ e $$g(x) = x + 1$$:

   $$\frac{d}{dx} \left(\frac{x^2}{x + 1}\right) = \frac{2x \cdot (x + 1) - x^2 \cdot 1}{(x + 1)^2} = \frac{x(2x + 2 - x)}{(x + 1)^2}$$

6. **Regra da Cadeia (Chain Rule):**

   Se $$y = f(u)$$ e $$u = g(x)$$, então:

   $$\frac{dy}{dx} = \frac{dy}{du} \cdot \frac{du}{dx}$$

   **Exemplo:**

   Para $$y = (3x + 1)^2$$:

   $$u = 3x + 1 \implies \frac{du}{dx} = 3$$
   
   $$y = u^2 \implies \frac{dy}{du} = 2u$$
   
   $$\frac{dy}{dx} = 2(3x + 1) \cdot 3 = 6(3x + 1)$$

#### 1.3.4 - Derivadas de Funções Trigonométricas

1. $$\frac{d}{dx}(\sin x) = \cos x$$
2. $$\frac{d}{dx}(\cos x) = -\sin x$$
3. $$\frac{d}{dx}(\tan x) = \sec^2 x$$

**Exemplo:**

Para $$f(x) = \sin x + \cos x$$:

$$f'(x) = \cos x - \sin x$$

#### 1.3.5 - Aplicações das Derivadas

- **Taxa de variação:** Medir a rapidez com que uma quantidade muda.
- **Máximos e Mínimos:** Identificar pontos de máximo e mínimo em gráficos de funções.
- **Tangente a uma curva:** Encontrar a inclinação da tangente em um ponto específico.

### 1.4 - Derivadas Parciais

#### 1.4.1 - Definição de Derivada Parcial

As **derivadas parciais** são usadas quando uma função depende de mais de uma variável. A derivada parcial de uma função em relação a uma variável mede a taxa de variação da função mantendo as outras variáveis constantes.

Seja $$f(x, y)$$ uma função de duas variáveis, a derivada parcial de $$f$$ em relação a $$x$$ é denotada por:

$$\frac{\partial f}{\partial x}$$

e é definida como:

$$\frac{\partial f}{\partial x} = \lim_{\Delta x \to 0} \frac{f(x + \Delta x, y) - f(x, y)}{\Delta x}$$

#### 1.4.2 - Notações Comuns

- $$\frac{\partial f}{\partial x}$$ ou $$f_x$$
- $$\frac{\partial f}{\partial y}$$ ou $$f_y$$

#### 1.4.3 - Exemplos de Derivadas Parciais

1. **Função de Duas Variáveis:**

   Considere $$f(x, y) = x^2 + y^2$$.

   - Derivada parcial em relação a $$x$$:

     $$\frac{\partial f}{\partial x} = 2x$$

   - Derivada parcial em relação a $$y$$:

     $$\frac{\partial f}{\partial y} = 2y$$

2. **Função Mista:**

   Para $$f(x, y) = x^2y + 3xy^2$$:

   - Derivada parcial em relação a $$x$$:

     $$\frac{\partial f}{\partial x} = 2xy + 3y^2$$

   - Derivada parcial em relação a $$y$$:

     $$\frac{\partial f}{\partial y} = x^2 + 6xy$$

#### 1.4.4 - Derivadas Parciais de Funções com Mais de Duas Variáveis

Para funções com mais de duas variáveis, como $$f(x, y, z)$$, as derivadas parciais são calculadas em relação a cada uma das variáveis, mantendo as outras constantes.

**Exemplo:**

Para $$f(x, y, z) = x^2 + y^2 + z^2$$:

- $$\frac{\partial f}{\partial x} = 2x$$
- $$\frac{\partial f}{\partial y} = 2y$$
- $$\frac{\partial f}{\partial z} = 2z$$

#### 1.4.5 - Derivadas de Segunda Ordem

As derivadas parciais podem ser estendidas a derivadas de segunda ordem. Se $$f(x, y)$$ é uma função, suas derivadas de segunda ordem são:

- $$\frac{\partial^2 f}{\partial x^2}$$ - Derivada parcial de segunda ordem em relação a $$x$$.
- $$\frac{\partial^2 f}{\partial y^2}$$ - Derivada parcial de segunda ordem em relação a $$y$$.
- $$\frac{\partial^2 f}{\partial x \partial y}$$ ou $$\frac{\partial^2 f}{\partial y \partial x}$$ - Derivadas mistas.

**Exemplo de Derivadas de Segunda Ordem:**

Para $$f(x, y) = x^2y + y^3$$:

- $$\frac{\partial^2 f}{\partial x^2} = 2y$$
- $$\frac{\partial^2 f}{\partial y^2} = 6y$$
- $$\frac{\partial^2 f}{\partial x \partial y} = \frac{\partial^2 f}{\partial y \partial x} = 2x$$

### 1.5 - Máximos e Mínimos

#### 1.5.1 - Definição de Máximos e Mínimos

Os pontos de máximo e mínimo de uma função são valores específicos onde a função atinge seus picos (máximos) ou vales (mínimos). Estes pontos são importantes em várias aplicações, como otimização e análise de comportamento de funções.

- **Máximo Local:** Um ponto $$x = c$$ é um máximo local se $$f(c) \geq f(x)$$ para todos os $$x$$ próximos de $$c$$.
- **Mínimo Local:** Um ponto $$x = c$$ é um mínimo local se $$f(c) \leq f(x)$$ para todos os $$x$$ próximos de $$c$$.
- **Máximo Global:** O ponto onde a função atinge seu maior valor em todo o domínio.
- **Mínimo Global:** O ponto onde a função atinge seu menor valor em todo o domínio.

#### 1.5.2 - Condições para Máximos e Mínimos

1. **Primeira Derivada:** Para encontrar máximos e mínimos, primeiro encontramos os pontos críticos onde a derivada da função é zero ou indefinida.

   $$f'(x) = 0 \quad \text{ou} \quad f'(x) \text{ é indefinida}$$

2. **Segunda Derivada:** A segunda derivada é usada para determinar se o ponto crítico é um máximo ou um mínimo.

   - Se $$f''(x) > 0$$, o ponto é um **mínimo local** (concavidade para cima).
   - Se $$f''(x) < 0$$, o ponto é um **máximo local** (concavidade para baixo).
   - Se $$f''(x) = 0$$, a análise é inconclusiva; pode ser necessário um teste adicional.

#### 1.5.3 - Exemplos de Máximos e Mínimos

1. **Exemplo 1:**

   Considere a função $$f(x) = x^2 - 4x + 3$$.

   - Primeira derivada: 

     $$f'(x) = 2x - 4$$

     Encontrando os pontos críticos:

     $$2x - 4 = 0 \implies x = 2$$

   - Segunda derivada: 

     $$f''(x) = 2$$

     Como $$f''(2) > 0$$, $$x = 2$$ é um **mínimo local**.

   - Valor mínimo: 

     $$f(2) = 2^2 - 4 \cdot 2 + 3 = -1$$

2. **Exemplo 2:**

   Para $$f(x) = -x^2 + 4x - 3$$.

   - Primeira derivada: 

     $$f'(x) = -2x + 4$$

     Pontos críticos:

     $$-2x + 4 = 0 \implies x = 2$$

   - Segunda derivada:

     $$f''(x) = -2$$

     Como $$f''(2) < 0$$, $$x = 2$$ é um **máximo local**.

   - Valor máximo:

     $$f(2) = -2^2 + 4 \cdot 2 - 3 = 1$$

### 1.6 - Integrais

#### 1.6.1 - Definição de Integral

A integral de uma função representa a soma contínua de valores, calculando a área sob a curva de uma função. As integrais podem ser definidas como a inversa da derivada e podem ser utilizadas para calcular áreas, volumes e outras grandezas acumuladas.

#### 1.6.2 - Notação de Integral

- Integral indefinida: 

  $$\int f(x) \, dx$$

- Integral definida: 

  $$\int_a^b f(x) \, dx$$

#### 1.6.3 - Regras Básicas de Integração

1. **Integral de uma constante:**

   $$\int c \, dx = c \cdot x + C$$

2. **Integral de uma potência:**

   $$\int x^n \, dx = \frac{x^{n+1}}{n+1} + C \quad \text{(para } n \neq -1)$$

3. **Integral da soma:**

   $$\int [f(x) + g(x)] \, dx = \int f(x) \, dx + \int g(x) \, dx$$

4. **Integral do produto por uma constante:**

   $$\int c \cdot f(x) \, dx = c \cdot \int f(x) \, dx$$

#### 1.6.4 - Aplicações das Integrais

- **Cálculo de Áreas:** Encontrar a área entre curvas.
- **Cálculo de Volumes:** Determinar o volume de sólidos de revolução.
- **Movimento e Trabalho:** Aplicar integrais para calcular deslocamentos e trabalho realizado por forças variáveis.

#### 1.6.5 - Exemplos de Integrais

1. **Exemplo 1:**

   Calcule a integral indefinida de $$f(x) = 3x^2$$.

   $$\int 3x^2 \, dx = x^3 + C$$

2. **Exemplo 2:**

   Calcule a integral definida de $$f(x) = x$$ de $$0$$ a $$3$$.

   $$\int_0^3 x \, dx = \left[\frac{x^2}{2}\right]_0^3 = \frac{9}{2}$$


## 2 - Álgebra Linear

### 2.1 - Vetores e Matrizes

#### Vetores
Um **vetor** é uma quantidade matemática que possui magnitude e direção. Em Álgebra Linear, um vetor é representado como uma lista ordenada de números, que podem estar dispostos como uma linha (vetor linha) ou uma coluna (vetor coluna).

**Representação de Vetores:**

- **Vetor Coluna:**

$$v = \begin{bmatrix} v_1 \\ v_2 \\ \vdots \\ v_n \end{bmatrix}$$

- **Vetor Linha:**

$$v = [v_1, v_2, \ldots, v_n]$$

Exemplo de vetor em \( \mathbb{R}^3 \):

$$v = \begin{bmatrix} 2 \\ -1 \\ 4 \end{bmatrix}$$

#### Matrizes
Uma **matriz** é um arranjo retangular de números, símbolos ou expressões organizados em linhas e colunas. As matrizes são utilizadas para representar sistemas de equações lineares, transformações lineares e diversas operações em álgebra linear.

**Representação de uma Matriz:**

$$A = \begin{bmatrix} a_{11} & a_{12} & \ldots & a_{1n} \\ a_{21} & a_{22} & \ldots & a_{2n} \\ \vdots & \vdots & \ddots & \vdots \\ a_{m1} & a_{m2} & \ldots & a_{mn} \end{bmatrix}$$

onde:
- \(a_{ij}\) representa o elemento na \(i\)-ésima linha e \(j\)-ésima coluna.
- \(m\) é o número de linhas.
- \(n\) é o número de colunas.

**Exemplo de Matriz \(3 \times 3\):**

$$A = \begin{bmatrix} 1 & 2 & 3 \\ 4 & 5 & 6 \\ 7 & 8 & 9 \end{bmatrix}$$

#### Dimensão de Vetores e Matrizes
- **Vetor**: A dimensão de um vetor é o número de componentes que ele possui. Um vetor \(v \in \mathbb{R}^n\) tem \(n\) componentes.
- **Matriz**: A dimensão de uma matriz é dada pelo número de linhas \(m\) e colunas \(n\), representada como \(m \times n\).

#### Aplicações
Vetores e matrizes são utilizados em:
- **Geometria Analítica**: Representação de pontos, direções e transformações.
- **Computação Gráfica**: Manipulação de imagens e modelagem de objetos 3D.
- **Ciência de Dados**: Representação de dados e operações sobre grandes conjuntos de números.

#### Exercícios Práticos
1. Represente o vetor \(v = [3, -2, 5]\) como um vetor coluna.
2. Determine a dimensão da matriz 

$$B = \begin{bmatrix} 2 & -1 \\ 4 & 0 \\ -3 & 5 \end{bmatrix}.$$

3. Escreva uma matriz \(2 \times 3\) contendo números inteiros.

### 2.2 - Operações com Vetores e Matrizes

#### Operações com Vetores

1. **Soma de Vetores**: A soma de dois vetores de mesma dimensão é feita somando-se seus elementos correspondentes.

   **Exemplo:**

   Se 

$$u = [1, 2, 3]$$ 

e 

$$v = [4, -1, 2],$$ 

então:

$$u + v = [1 + 4, 2 + (-1), 3 + 2] = [5, 1, 5].$$

2. **Multiplicação por Escalar**: Multiplicar um vetor por um escalar consiste em multiplicar cada componente do vetor pelo escalar.

   **Exemplo:**

   Se 

$$v = [2, -3, 4]$$ 

e 

$$k = 3,$$ 

então:

$$k \cdot v = 3 \cdot [2, -3, 4] = [6, -9, 12].$$

3. **Produto Escalar (Dot Product)**: O produto escalar de dois vetores é uma soma dos produtos de seus elementos correspondentes.

   **Exemplo:**

   Para 

$$u = [1, 2, 3]$$ 

e 

$$v = [4, -1, 2],$$ 

temos:

$$u \cdot v = (1 \times 4) + (2 \times -1) + (3 \times 2) = 4 - 2 + 6 = 8.$$

#### Operações com Matrizes

1. **Soma de Matrizes**: Duas matrizes podem ser somadas se e somente se tiverem a mesma dimensão, somando-se os elementos correspondentes.

   **Exemplo:**

   Se 

$$A = \begin{bmatrix} 1 & 2 \\ 3 & 4 \end{bmatrix}$$ 

e 

$$B = \begin{bmatrix} 5 & 6 \\ 7 & 8 \end{bmatrix},$$ 

então:

$$A + B = \begin{bmatrix} 1 + 5 & 2 + 6 \\ 3 + 7 & 4 + 8 \end{bmatrix} = \begin{bmatrix} 6 & 8 \\ 10 & 12 \end{bmatrix}.$$

2. **Multiplicação por Escalar**: Cada elemento da matriz é multiplicado pelo escalar.

   **Exemplo:**

   Para 

$$A = \begin{bmatrix} 2 & 4 \\ 1 & -3 \end{bmatrix}$$ 

e 

$$k = 3,$$ 

temos:

$$k \cdot A = \begin{bmatrix} 3 \cdot 2 & 3 \cdot 4 \\ 3 \cdot 1 & 3 \cdot -3 \end{bmatrix} = \begin{bmatrix} 6 & 12 \\ 3 & -9 \end{bmatrix}.$$

3. **Multiplicação de Matrizes**: Para multiplicar duas matrizes \(A\) e \(B\), o número de colunas de \(A\) deve ser igual ao número de linhas de \(B\). O produto é obtido multiplicando-se as linhas da primeira matriz pelas colunas da segunda.

   **Exemplo:**

   Se 

$$A = \begin{bmatrix} 1 & 2 \\ 3 & 4 \end{bmatrix}$$ 

e 

$$B = \begin{bmatrix} 5 & 6 \\ 7 & 8 \end{bmatrix},$$ 

então:

$$A \cdot B = \begin{bmatrix} (1 \times 5 + 2 \times 7) & (1 \times 6 + 2 \times 8) \\ (3 \times 5 + 4 \times 7) & (3 \times 6 + 4 \times 8) \end{bmatrix} = \begin{bmatrix} 19 & 22 \\ 43 & 50 \end{bmatrix}.$$

4. **Transposição de Matrizes**: A transposição de uma matriz é obtida trocando suas linhas por colunas.

   **Exemplo:**

   Para 

$$A = \begin{bmatrix} 1 & 2 \\ 3 & 4 \end{bmatrix},$$ 

temos:

$$A^T = \begin{bmatrix} 1 & 3 \\ 2 & 4 \end{bmatrix}.$$

#### Aplicações
Operações com vetores e matrizes são amplamente usadas em:
- **Resolução de Sistemas Lineares.**
- **Transformações Lineares.**
- **Modelagem de Dados** na Ciência de Dados e Machine Learning.

#### Exercícios Práticos
1. Calcule o produto escalar de \(u = [2, -1, 3]\) e \(v = [4, 0, -2]\).
2. Encontre o produto da matriz 

$$A = \begin{bmatrix} 1 & -2 \\ 0 & 3 \end{bmatrix}$$ 

com o escalar \(5\).
3. Multiplique 

$$A = \begin{bmatrix} 1 & 0 \\ 2 & 3 \end{bmatrix}$$ 

pela matriz 

$$B = \begin{bmatrix} 4 & 1 \\ 2 & -1 \end{bmatrix}.$$

### 2.3 - Tipos de Matrizes

#### 1. Matriz Quadrada
Uma matriz é dita quadrada quando o número de linhas é igual ao número de colunas (\(m = n\)).

**Exemplo:**

$$A = \begin{bmatrix} 1 & 2 & 3 \\ 4 & 5 & 6 \\ 7 & 8 & 9 \end{bmatrix}.$$

#### 2. Matriz Diagonal
Uma matriz diagonal é uma matriz quadrada onde todos os elementos fora da diagonal principal são zero.

**Exemplo:**

$$D = \begin{bmatrix} 4 & 0 & 0 \\ 0 & 5 & 0 \\ 0 & 0 & 6 \end{bmatrix}.$$

#### 3. Matriz Identidade
Uma matriz identidade é uma matriz diagonal onde todos os elementos da diagonal principal são iguais a 1. Representada por \(I\).

**Exemplo:**

$$I = \begin{bmatrix} 1 & 0 & 0 \\ 0 & 1 & 0 \\ 0 & 0 & 1 \end{bmatrix}.$$

#### 4. Matriz Nula (ou Zero)
Uma matriz nula é uma matriz onde todos os seus elementos são iguais a zero.

**Exemplo:**

$$O = \begin{bmatrix} 0 & 0 & 0 \\ 0 & 0 & 0 \\ 0 & 0 & 0 \end{bmatrix}.$$

#### 5. Matriz Simétrica
Uma matriz simétrica é uma matriz quadrada que é igual à sua transposta (\(A = A^T\)).

**Exemplo:**

$$S = \begin{bmatrix} 1 & 2 & 3 \\ 2 & 4 & 5 \\ 3 & 5 & 6 \end{bmatrix}.$$

#### 6. Matriz Anti-Simétrica (ou Matriz Skew-Simétrica)
Uma matriz anti-simétrica é uma matriz quadrada onde a transposta é igual à matriz original multiplicada por \(-1\) (\(A^T = -A\)).

**Exemplo:**

$$A = \begin{bmatrix} 0 & -2 & 3 \\ 2 & 0 & -1 \\ -3 & 1 & 0 \end{bmatrix}.$$

#### 7. Matriz Triangular Superior
Uma matriz triangular superior é uma matriz quadrada onde todos os elementos abaixo da diagonal principal são zero.

**Exemplo:**

$$U = \begin{bmatrix} 2 & 3 & 4 \\ 0 & 5 & 6 \\ 0 & 0 & 7 \end{bmatrix}.$$

#### 8. Matriz Triangular Inferior
Uma matriz triangular inferior é uma matriz quadrada onde todos os elementos acima da diagonal principal são zero.

**Exemplo:**

$$L = \begin{bmatrix} 1 & 0 & 0 \\ 4 & 2 & 0 \\ 7 & 8 & 3 \end{bmatrix}.$$

#### 9. Matriz Ortogonal
Uma matriz ortogonal é uma matriz quadrada cuja transposta é igual à sua inversa (\(A^T A = I\)).

**Exemplo:**

$$Q = \begin{bmatrix} 1 & 0 \\ 0 & -1 \end{bmatrix}.$$

#### 10. Matriz de Permutação
Uma matriz de permutação é uma matriz obtida trocando as linhas de uma matriz identidade.

**Exemplo:**

$$P = \begin{bmatrix} 0 & 1 & 0 \\ 1 & 0 & 0 \\ 0 & 0 & 1 \end{bmatrix}.$$

#### Aplicações
Diferentes tipos de matrizes são usados em diversas áreas, como:
- **Soluções de Sistemas Lineares.**
- **Transformações Lineares e Geometria.**
- **Análise de Dados e Algoritmos Computacionais.**

#### Exercícios Práticos
1. Determine se a matriz 

$$A = \begin{bmatrix} 0 & -3 \\ 3 & 0 \end{bmatrix}$$ 

é simétrica ou anti-simétrica.
2. Verifique se a matriz 

$$B = \begin{bmatrix} 1 & 0 & 0 \\ 0 & 2 & 0 \\ 0 & 0 & 3 \end{bmatrix}$$ 

é diagonal.
3. Classifique a matriz 

$$C = \begin{bmatrix} 1 & 2 & 0 \\ 0 & 1 & 4 \\ 0 & 0 & 3 \end{bmatrix}$$ 

quanto ao seu tipo.

### 2.4 - Transformações Lineares

#### 2.4.1 - Definição de Transformação Linear

Uma **transformação linear** é uma função que mapeia vetores de um espaço vetorial para outro, preservando as operações de adição de vetores e multiplicação por escalares. Em outras palavras, se $$T: V \to W$$ é uma transformação linear, então para todos os vetores $$u, v \in V$$ e para todo escalar $$c$$, as seguintes propriedades são satisfeitas:

1. **Adição**: 

   $$T(u + v) = T(u) + T(v)$$

2. **Multiplicação por Escalar**: 

   $$T(c \cdot u) = c \cdot T(u)$$

#### 2.4.2 - Representação Matricial de Transformações Lineares

Qualquer transformação linear pode ser representada por uma matriz. Se $$T: \mathbb{R}^n \to \mathbb{R}^m$$ é uma transformação linear, existe uma matriz $$A$$ de dimensão $$m \times n$$ tal que:

$$
T(x) = A \cdot x
$$

onde $$x$$ é um vetor em $$\mathbb{R}^n$$.

**Exemplo:**

Considere a transformação linear $$T: \mathbb{R}^2 \to \mathbb{R}^2$$ definida por:

$$
T\left(\begin{bmatrix} x \\ y \end{bmatrix}\right) = \begin{bmatrix} 2x + y \\ 3x - y \end{bmatrix}
$$

A transformação pode ser representada pela matriz:

$$
A = \begin{bmatrix} 2 & 1 \\ 3 & -1 \end{bmatrix}
$$

Então, $$T(x) = A \cdot x$$.

#### 2.4.3 - Aplicações das Transformações Lineares

As transformações lineares são amplamente usadas em diversas áreas, como:

- **Geometria Analítica**: Descrição de rotações, reflexões, projeções e escalonamentos.
- **Ciência de Dados**: Redução de dimensionalidade, como no PCA (Análise de Componentes Principais).
- **Gráficos Computacionais**: Transformações de objetos para renderização.

### 2.5 - Espaços e Subespaços Vetoriais de $$R^n$$

#### 2.5.1 - Definição de Espaço Vetorial

Um **espaço vetorial** é um conjunto de vetores que satisfazem determinadas propriedades de adição e multiplicação por escalares. Um espaço vetorial deve satisfazer as seguintes condições:

1. Fechamento sob adição e multiplicação por escalares.
2. Existência de um vetor nulo.
3. Existência de um vetor oposto.
4. Propriedades distributivas e associativas.

#### 2.5.2 - Subespaços Vetoriais

Um **subespaço vetorial** é um subconjunto de um espaço vetorial que é ele próprio um espaço vetorial com as mesmas operações de adição e multiplicação por escalares. Para que um subconjunto seja um subespaço, ele deve incluir o vetor nulo e ser fechado sob adição e multiplicação por escalares.

**Exemplo:**

Considere o espaço vetorial $$R^2$$ e o subconjunto $$S = \{(x, 0) \mid x \in R\}$$. Esse subconjunto é um subespaço de $$R^2$$ pois satisfaz todas as propriedades necessárias.

#### 2.5.3 - Exemplos de Subespaços Comuns

1. **Linhas e Planos que Passam pela Origem:** Em $$R^3$$, linhas e planos que passam pela origem são subespaços.

2. **Espaço Nulo:** O conjunto que contém apenas o vetor nulo é um subespaço.

3. **Espaço de Linhas e Colunas de Matrizes:** Em uma matriz $$A$$, o espaço de linhas e o espaço de colunas são subespaços do espaço vetorial em questão.

### 2.6 - Sistemas de Equações Lineares

#### 2.6.1 - Definição de Sistemas de Equações Lineares

Um **sistema de equações lineares** é um conjunto de equações que têm as mesmas variáveis. A solução de um sistema é o conjunto de valores das variáveis que satisfazem todas as equações ao mesmo tempo.

Um sistema linear de duas equações e duas variáveis tem a forma:

$$
\begin{cases}
a_1x + b_1y = c_1 \\
a_2x + b_2y = c_2
\end{cases}
$$

onde \(a_1, b_1, c_1, a_2, b_2, c_2\) são constantes.

#### 2.6.2 - Representação Matricial

Um sistema de equações lineares pode ser representado de forma compacta usando matrizes. A forma geral de um sistema linear pode ser escrita como:

$$
A\mathbf{x} = \mathbf{b}
$$

onde:
- \(A\) é a matriz dos coeficientes.
- \(\mathbf{x}\) é o vetor das incógnitas.
- \(\mathbf{b}\) é o vetor dos termos independentes.

**Exemplo:**

Considere o sistema:

$$
\begin{cases}
2x + 3y = 5 \\
4x - y = 1
\end{cases}
$$

A forma matricial é:

$$
\begin{bmatrix} 2 & 3 \\ 4 & -1 \end{bmatrix} \begin{bmatrix} x \\ y \end{bmatrix} = \begin{bmatrix} 5 \\ 1 \end{bmatrix}
$$

#### 2.6.3 - Métodos de Resolução

1. **Eliminação de Gauss:** Método que transforma o sistema em uma forma escalonada através de operações elementares com as linhas da matriz.

2. **Substituição:** Método onde se resolve uma das equações para uma variável e substitui-se na outra.

3. **Método de Gauss-Jordan:** Uma extensão da eliminação de Gauss que transforma a matriz do sistema na forma reduzida para resolver diretamente.

4. **Regra de Cramer:** Usa determinantes para resolver sistemas lineares onde o número de equações é igual ao número de incógnitas.

#### 2.6.4 - Tipos de Soluções

1. **Sistema Consistente:** Tem pelo menos uma solução.
   - **Solução Única:** O sistema possui exatamente uma solução.
   - **Infinitas Soluções:** O sistema possui mais de uma solução.

2. **Sistema Inconsistente:** Não tem solução (as equações se contradizem).

#### 2.6.5 - Exemplos de Resolução

**Exemplo 1: Solução Única**

Resolva o sistema:

$$
\begin{cases} 
3x + 4y = 7 \\ 
2x - y = 1 
\end{cases}
$$

Usando eliminação de Gauss, encontramos a solução \(x = 2\) e \(y = -\frac{1}{4}\).

**Exemplo 2: Sistema Inconsistente**

Considere o sistema:

$$
\begin{cases} 
x + 2y = 3 \\ 
2x + 4y = 7 
\end{cases}
$$

As equações representam duas retas paralelas, logo o sistema é inconsistente e não possui solução.


### 2.7 - Normas

As **normas** são funções que atribuem um comprimento ou "tamanho" a vetores em espaços vetoriais. Elas são amplamente utilizadas para medir a distância, avaliar erros, e para outras aplicações em análise numérica, otimização e álgebra linear. As normas mais comuns incluem as normas \(L_1\), \(L_2\), norma infinita, norma \(p\)-generalizada, de Minkowski, e de Chebyshev.

#### 2.7.1 - Norma \(L_1\) (Norma Manhattan)

A norma \(L_1\) de um vetor é a soma dos valores absolutos de seus componentes. Ela é frequentemente usada para medir distâncias em espaços de alta dimensão.

$$
\|x\|_1 = |x_1| + |x_2| + \ldots + |x_n|
$$

**Exemplo:**

Para o vetor \(x = [3, -4, 2]\):

$$
\|x\|_1 = |3| + |-4| + |2| = 3 + 4 + 2 = 9
$$

#### 2.7.2 - Norma \(L_2\) (Norma Euclidiana)

A norma \(L_2\) é a norma mais comum, também conhecida como norma Euclidiana, que calcula a raiz quadrada da soma dos quadrados dos componentes do vetor.

$$
\|x\|_2 = \sqrt{x_1^2 + x_2^2 + \ldots + x_n^2}
$$

**Exemplo:**

Para o vetor \(x = [3, -4, 2]\):

$$
\|x\|_2 = \sqrt{3^2 + (-4)^2 + 2^2} = \sqrt{9 + 16 + 4} = \sqrt{29}
$$

#### 2.7.3 - Norma Infinita (\(\infty\))

A norma infinita de um vetor é o valor absoluto do maior componente do vetor.

$$
\|x\|_\infty = \max(|x_1|, |x_2|, \ldots, |x_n|)
$$

**Exemplo:**

Para o vetor \(x = [3, -4, 2]\):

$$
\|x\|_\infty = \max(3, 4, 2) = 4
$$

#### 2.7.4 - Norma \(p\)-Generalizada

A norma \(p\)-generalizada é uma generalização das normas \(L_1\) e \(L_2\), definida por:

$$
\|x\|_p = \left( |x_1|^p + |x_2|^p + \ldots + |x_n|^p \right)^{\frac{1}{p}}
$$

**Exemplo:**

Para \(p = 3\) e o vetor \(x = [1, -2, 3]\):

$$
\|x\|_3 = \left( |1|^3 + |-2|^3 + |3|^3 \right)^{\frac{1}{3}} = (1 + 8 + 27)^{\frac{1}{3}} = 36^{\frac{1}{3}} \approx 3.3
$$

#### 2.7.5 - Norma de Minkowski

A norma de Minkowski é uma extensão da norma \(p\)-generalizada e é utilizada para medir distâncias em espaços métricos.

$$
\Vert x \Vert_p = \left( \sum_{i=1}^{n} |x_i|^p \right)^{1/p}
$$

#### 2.7.6 - Norma de Chebyshev

A norma de Chebyshev de um vetor é similar à norma infinita, e mede o maior valor absoluto das diferenças entre os componentes de dois vetores.

**Exemplo:**

Para os vetores \(x = [1, 2, 3]\) e \(y = [2, 4, 1]\):

$$\|x - y\|_{\text{Chebyshev}} = \max(|1 - 2|, |2 - 4|, |3 - 1|) = \max(1, 2, 2) = 2$$

#### 2.7.7 - Aplicações das Normas

As normas são utilizadas em diversas áreas, como:

- **Otimização**: Para minimizar funções de erro.
- **Análise Numérica**: Para avaliar a precisão de aproximações numéricas.
- **Aprendizado de Máquina**: Para regularização e ajuste de modelos.

#### Exercícios Práticos

1. Calcule a norma \(L_1\) do vetor \(x = [5, -3, 4]\).
2. Encontre a norma \(L_2\) do vetor \(y = [7, 1, -2]\).
3. Determine a norma infinita do vetor \(z = [-3, 0, 8]\).

### 2.8 - Autovalores e Autovetores

Os autovalores (ou valores próprios) e autovetores (ou vetores próprios) são conceitos fundamentais em Álgebra Linear, especialmente em transformações lineares e análise de matrizes. Eles ajudam a entender como uma transformação linear age sobre um vetor, escalando-o sem mudar sua direção.

#### 2.8.1 - Definição de Autovalores e Autovetores

Seja a matriz $$A$$ uma matriz quadrada de ordem $$n$$. Um número $$\lambda$$ é chamado de **autovalor** de $$A$$ se existe um vetor não nulo $$v$$ tal que:

$$Av = \lambda v$$

Nesse caso, o vetor $$v$$ é chamado de **autovetor** associado ao autovalor $$\lambda$$.

#### 2.8.2 - Como Encontrar Autovalores e Autovetores

Para encontrar os autovalores de uma matriz $$A$$, resolvemos a equação característica:

$$\det(A - \lambda I) = 0$$

Onde:
- $$\det$$ denota o determinante da matriz.
- $$I$$ é a matriz identidade da mesma ordem de $$A$$.
- $$\lambda$$ é o autovalor.

Após encontrar os autovalores, os autovetores associados são encontrados resolvendo o sistema linear $$(A - \lambda I)v = 0$$.

#### 2.8.3 - Exemplo de Cálculo de Autovalores e Autovetores

Considere a matriz:

$$A = \begin{bmatrix} 2 & 1 \\ 1 & 2 \end{bmatrix}$$

Para encontrar os autovalores, calculamos:

$$\det(A - \lambda I) = \det\begin{bmatrix} 2 - \lambda & 1 \\ 1 & 2 - \lambda \end{bmatrix} = (2 - \lambda)^2 - 1 = \lambda^2 - 4\lambda + 3$$

Resolvendo $$\lambda^2 - 4\lambda + 3 = 0$$, obtemos os autovalores $$\lambda_1 = 3$$ e $$\lambda_2 = 1$$.

# 3 - Otimização Matemática

## 3.1 - Programação Linear Inteira e Mista

A **Programação Linear Inteira (PLI)** e a **Programação Linear Mista (PLM)** são subcampos da programação linear onde algumas ou todas as variáveis de decisão são restritas a serem inteiros. Esses métodos são amplamente usados em problemas onde decisões discretas são necessárias, como planejamento de produção, alocação de recursos e otimização de rotas.

### 3.1.1 - Definição de Programação Linear Inteira

A Programação Linear Inteira envolve a otimização de uma função objetivo linear sujeita a um conjunto de restrições lineares, onde todas as variáveis de decisão devem assumir valores inteiros.

**Exemplo de Formulação de um Problema de PLI:**

Maximizar:

$$
Z = 3x_1 + 2x_2
$$

Sujeito a:

$$
\begin{cases}
x_1 + x_2 \leq 4 \\
2x_1 + x_2 \leq 5 \\
x_1, x_2 \geq 0 \\
x_1, x_2 \in \mathbb{Z}
\end{cases}
$$

Nesse exemplo, o objetivo é maximizar \(Z\) com restrições lineares, onde \(x_1\) e \(x_2\) devem ser inteiros.

### 3.1.2 - Programação Linear Mista

A Programação Linear Mista permite que algumas variáveis sejam inteiras, enquanto outras podem assumir valores contínuos. Essa flexibilidade é útil em problemas onde certas decisões são discretas (como o número de unidades produzidas), enquanto outras podem ser fracionárias (como a quantidade de matéria-prima).

**Exemplo de Formulação de um Problema de PLM:**

Maximizar:

$$
Z = 5x_1 + 4x_2 + 3x_3
$$

Sujeito a:

$$
\begin{cases}
x_1 + 2x_2 + x_3 \leq 6 \\
2x_1 + x_2 + 3x_3 \leq 8 \\
x_1, x_2 \geq 0, \ x_3 \in \mathbb{Z}
\end{cases}
$$

Nesse caso, \(x_1\) e \(x_2\) são variáveis contínuas, enquanto \(x_3\) é uma variável inteira.

### 3.1.3 - Métodos de Resolução

1. **Método do Plano de Corte (Branch and Bound):** Um dos métodos mais comuns para resolver PLI, que consiste em dividir o problema em subproblemas menores e excluir regiões inviáveis.

2. **Método do Branch and Cut:** Uma extensão do Branch and Bound que inclui cortes para remover soluções fracionárias, refinando a busca por soluções inteiras.

3. **Método de Relaxação Linear:** Resolver o problema como um problema de programação linear contínua e, em seguida, ajustar as soluções para atender às restrições inteiras.

### 3.1.4 - Aplicações de PLI e PLM

- **Planejamento de Produção:** Decisões sobre quantidades a produzir, transportes e estoques.
- **Problemas de Roteamento:** Otimização de rotas de veículos, minimização de custos de transporte.
- **Alocação de Recursos:** Distribuição ótima de recursos escassos em diferentes atividades.

## 3.2 - Problemas de Otimização Unidimensionais e Multidimensionais, com e sem Restrições

Os problemas de otimização podem ser classificados em unidimensionais e multidimensionais, dependendo do número de variáveis envolvidas. Esses problemas podem ainda ser com ou sem restrições, dependendo se há condições adicionais que as soluções devem satisfazer.

### 3.2.1 - Otimização Unidimensional

Na otimização unidimensional, a função objetivo depende de uma única variável. O objetivo é encontrar o ponto onde a função atinge seu máximo ou mínimo.

**Exemplo de Problema Unidimensional Sem Restrições:**

Minimizar:

$$
f(x) = (x - 3)^2 + 4
$$

Para encontrar o mínimo, derivamos a função:

$$
f'(x) = 2(x - 3)
$$

Igualando a zero:

$$
2(x - 3) = 0 \implies x = 3
$$

Neste exemplo, o mínimo ocorre em \(x = 3\).

### 3.2.2 - Otimização Multidimensional

A otimização multidimensional envolve funções que dependem de múltiplas variáveis. Essas funções podem ser otimizadas com ou sem restrições, e os métodos utilizados são geralmente mais complexos.

**Exemplo de Problema Multidimensional Sem Restrições:**

Minimizar:

$$
f(x, y) = x^2 + y^2 + 4x - 2y
$$

Calculando as derivadas parciais:

$$
\frac{\partial f}{\partial x} = 2x + 4, \quad \frac{\partial f}{\partial y} = 2y - 2
$$

Igualando a zero:

$$
2x + 4 = 0 \implies x = -2, \quad 2y - 2 = 0 \implies y = 1
$$

A solução é \( (x, y) = (-2, 1) \).

### 3.2.3 - Otimização com Restrições

Na otimização com restrições, além da função objetivo, o problema inclui condições adicionais que devem ser satisfeitas.

**Exemplo de Problema com Restrições:**

Minimizar:

$$
f(x, y) = x^2 + y^2
$$

Sujeito a:

$$
x + y = 1
$$

Usando o método dos multiplicadores de Lagrange, definimos:

$$
\mathcal{L}(x, y, \lambda) = x^2 + y^2 + \lambda (x + y - 1)
$$

Derivando e igualando a zero:

$$
\frac{\partial \mathcal{L}}{\partial x} = 2x + \lambda = 0, \quad \frac{\partial \mathcal{L}}{\partial y} = 2y + \lambda = 0, \quad \frac{\partial \mathcal{L}}{\partial \lambda} = x + y - 1 = 0
$$

Resolvendo, obtemos \(x = 0.5\) e \(y = 0.5\).

### 3.2.4 - Métodos de Resolução

1. **Método do Gradiente:** Utilizado para encontrar máximos ou mínimos locais de funções contínuas deriváveis.
   
2. **Método de Newton:** Um método iterativo que utiliza a derivada e a segunda derivada da função para encontrar raízes, e é amplamente usado em otimização unidimensional.

3. **Método dos Multiplicadores de Lagrange:** Utilizado para resolver problemas de otimização com restrições de igualdade.

### 3.2.5 - Aplicações

- **Economia:** Maximização de lucros ou minimização de custos em função de várias variáveis econômicas.
- **Engenharia:** Design de sistemas otimizados para desempenho máximo com restrições de recursos.
- **Ciência de Dados:** Ajuste de modelos complexos com múltiplas variáveis para minimizar erros de previsão.

## 3.3 - Otimização Convexa

### 3.3.1 - Definição de Problema Convexo

Um problema de otimização é considerado convexo se:

1. A função objetivo $$f(x)$$ é convexa, ou seja, para quaisquer $$x_1, x_2$$ e para $$\theta \in [0, 1]$$:

   $$f(\theta x_1 + (1 - \theta) x_2) \leq \theta f(x_1) + (1 - \theta) f(x_2)$$

2. O conjunto de restrições forma um conjunto convexo, ou seja, qualquer combinação linear de dois pontos viáveis também é viável.

### 3.3.2 - Exemplos de Funções Convexas

- **Função Quadrática:**

  $$f(x) = ax^2 + bx + c, \quad \text{com} \ a > 0$$

  A função é convexa porque sua segunda derivada é positiva.

- **Função Exponencial:**

  $$f(x) = e^x$$

  É convexa porque sua derivada é sempre positiva.

- **Função Normas:**

  $$f(x) = \|x\|_2^2$$

  É convexa devido à propriedade das normas.

### 3.3.3 - Problemas de Otimização Convexa

**Exemplo: Problema Convexo de Minimização**

Minimizar:

$$
f(x) = x_1^2 + x_2^2
$$

Sujeito a:

$$
x_1 + x_2 \geq 1
$$

O conjunto de restrições é convexo (um meio-espaço) e a função objetivo é convexa. Este problema pode ser resolvido por métodos como o Método do Gradiente ou Programação Quadrática.

### 3.3.4 - Métodos de Resolução

1. **Método do Gradiente:** Utiliza as derivadas para buscar o mínimo da função, ajustando iterativamente as variáveis.
   
2. **Método do Gradiente Projetado:** Útil quando há restrições; projeta o gradiente na região viável.

3. **Método de Programação Quadrática:** Resolve problemas convexos onde a função objetivo é quadrática e as restrições são lineares.

4. **Método de Ponto Interior:** Utilizado para resolver problemas convexos grandes, navegando no interior da região viável até encontrar a solução ótima.

### 3.3.5 - Aplicações de Otimização Convexa

- **Portfólios Financeiros:** Otimização do retorno esperado de investimentos com risco mínimo.
- **Machine Learning:** Ajuste de modelos como a regressão linear, onde a minimização da função de perda é um problema convexo.
- **Redes de Transporte:** Minimização de custos de transporte e rotas em redes complexas.

### 3.3.6 - Propriedades Importantes

1. **Unicidade da Solução:** Em problemas convexos, se existe uma solução viável, ela é única.
   
2. **Eficiência Computacional:** A convexidade permite o uso de algoritmos eficientes que garantem a convergência para o ótimo global.

3. **Estabilidade:** Pequenas alterações nos dados de entrada resultam em pequenas mudanças na solução, tornando-a robusta.

A otimização convexa é amplamente utilizada devido à sua garantia de encontrar soluções globais, simplicidade analítica e eficiência computacional.

## 3.4 - Programação Dinâmica

A Programação Dinâmica é uma técnica de otimização utilizada para resolver problemas complexos quebrando-os em subproblemas mais simples e armazenando suas soluções para evitar cálculos repetitivos. Ela é amplamente usada em problemas de otimização onde as soluções podem ser construídas a partir de subproblemas sobrepostos e repetidos.

### 3.4.1 - Princípio de Optimalidade

O princípio de optimalidade estabelece que uma solução ótima de um problema contém soluções ótimas dos seus subproblemas. Portanto, ao resolver cada subproblema e armazenar sua solução, é possível construir a solução para o problema maior.

### 3.4.2 - Estrutura de um Problema de Programação Dinâmica

Um problema pode ser resolvido por Programação Dinâmica se apresentar:

1. **Subproblemas Sobrepostos:** O problema pode ser dividido em subproblemas menores que se repetem várias vezes.
2. **Optimalidade Estrutural:** A solução ótima para o problema pode ser construída a partir das soluções ótimas dos subproblemas.

### 3.4.3 - Métodos de Implementação

1. **Memorização (Top-Down):** Solução recursiva que armazena os resultados dos subproblemas já resolvidos, evitando cálculos redundantes.
   
2. **Tabela (Bottom-Up):** Constrói a solução de forma iterativa preenchendo uma tabela, partindo dos subproblemas mais simples até chegar ao problema maior.

### 3.4.4 - Exemplo de Programação Dinâmica

**Exemplo: Problema da Mochila (Knapsack Problem)**

Dado um conjunto de itens, cada um com um peso e um valor, determine o número de cada item a ser incluído na mochila para que o valor total seja maximizado sem exceder a capacidade da mochila.

**Definição Recursiva:**

Seja \( V[i, w] \) o valor máximo que pode ser obtido com os primeiros \( i \) itens e capacidade \( w \). A relação de recorrência é:

$$
V[i, w] = \max(V[i-1, w], V[i-1, w - w_i] + v_i)
$$

Onde:
- \( w_i \) é o peso do item \( i \).
- \( v_i \) é o valor do item \( i \).

**Solução:**

Preencher uma tabela usando a relação de recorrência, começando do caso base onde a capacidade é zero.

### 3.4.5 - Aplicações da Programação Dinâmica

- **Problemas de Sequenciamento:** Como a sequência ótima de atividades.
- **Teoria dos Jogos:** Determinação de estratégias vencedoras.
- **Bioinformática:** Alinhamento de sequências genéticas.
- **Controle Ótimo:** Sistemas que precisam otimizar recursos ao longo do tempo.

### 3.4.6 - Vantagens e Desvantagens

**Vantagens:**

- **Eficiência Computacional:** Reduz o tempo de execução ao evitar cálculos redundantes.
- **Simplicidade na Implementação:** Fornece uma abordagem sistemática para resolver problemas complexos.

**Desvantagens:**

- **Alto Consumo de Memória:** Pode requerer grande quantidade de memória para armazenar as soluções dos subproblemas.
- **Complexidade de Implementação para Problemas Multidimensionais:** Pode ser difícil de programar em problemas que envolvem muitas variáveis.

### 3.4.7 - Técnicas Avançadas

1. **Programação Dinâmica com Espaço Reduzido:** Otimiza o uso de memória, mantendo apenas as linhas necessárias de uma tabela.
   
2. **Programação Dinâmica Estocástica:** Lida com problemas onde as entradas possuem incertezas e variabilidades.

3. **Programação Dinâmica Aproximada:** Usa aproximações para resolver problemas muito grandes, sacrificando precisão por velocidade e menor uso de recursos.

A Programação Dinâmica é uma ferramenta poderosa na otimização, particularmente útil em problemas onde a solução exata pode ser composta por soluções de subproblemas menores, tornando-a essencial em várias áreas da ciência e engenharia.


Para $$\lambda_1 = 3$$:

$$
(A - 3I)v = \begin{bmatrix} -1 & 1 \\ 1 & -1 \end{bmatrix}\begin{bmatrix} x \\ y \end{bmatrix} = 0
$$

Um autovetor associado é:

$$
v_1 = \begin{bmatrix} 1 \\ 1 \end{bmatrix}
$$

Para $$\lambda_2 = 1$$:

$$
(A - I)v = \begin{bmatrix} 1 & 1 \\ 1 & 1 \end{bmatrix}\begin{bmatrix} x \\ y \end{bmatrix} = 0
$$

Um autovetor associado é:

$$
v_2 = \begin{bmatrix} 1 \\ -1 \end{bmatrix}
$$


#### 2.8.4 - Aplicações de Autovalores e Autovetores

Autovalores e autovetores têm diversas aplicações, incluindo:

- **Análise de estabilidade**: Em sistemas dinâmicos, autovalores ajudam a determinar a estabilidade de equilíbrios.
- **Compressão de imagens**: Autovetores são usados na decomposição de matrizes em processamento de imagem.
- **Análise de redes**: Identificação de propriedades estruturais de redes complexas.
- **Transformações lineares**: Entendimento de como vetores se transformam em diferentes espaços.

### 2.9 - Decomposição Matricial (Cholesky e Singular Value Decomposition - SVD)

Decomposições matriciais são técnicas fundamentais em Álgebra Linear para simplificar cálculos com matrizes e resolver problemas complexos, como sistemas de equações lineares, otimização, e análise de dados. Entre as decomposições mais comuns estão a Decomposição de Cholesky e a Decomposição em Valores Singulares (SVD).

#### 2.9.1 - Decomposição de Cholesky

A decomposição de Cholesky é usada para decompor uma matriz simétrica, definida positiva, em um produto de uma matriz triangular inferior e sua transposta.

Seja $$A$$ uma matriz simétrica e definida positiva, então a decomposição de Cholesky de $$A$$ é dada por:

$$A = LL^T$$

onde:
- $$L$$ é uma matriz triangular inferior.
- $$L^T$$ é a transposta de $$L$$.

**Exemplo:**

Considere a matriz:

$$
A = \begin{bmatrix} 4 & 2 \\ 2 & 3 \end{bmatrix}
$$

A decomposição de Cholesky resulta em:

$$
L = \begin{bmatrix} 2 & 0 \\ 1 & \sqrt{2} \end{bmatrix}
$$

e

$$
L^T = \begin{bmatrix} 2 & 1 \\ 0 & \sqrt{2} \end{bmatrix}
$$

#### 2.9.2 - Singular Value Decomposition (SVD)

A Decomposição em Valores Singulares (SVD) é uma técnica que decompõe qualquer matriz $$A$$ (não necessariamente simétrica ou quadrada) em três matrizes:

$$
A = U \Sigma V^T
$$

onde:
- $$U$$ é uma matriz ortogonal contendo os autovetores da matriz $$AA^T$$.
- $$\Sigma$$ é uma matriz diagonal contendo os valores singulares (raízes quadradas dos autovalores de $$AA^T$$).
- $$V^T$$ é a transposta de uma matriz ortogonal contendo os autovetores de $$A^TA$$.

**Exemplo:**

Considere a matriz:

$$
A = \begin{bmatrix} 1 & 0 \\ 0 & 1 \\ 0 & 0 \end{bmatrix}
$$

A decomposição SVD de $$A$$ resulta em:

$$
U = \begin{bmatrix} 1 & 0 & 0 \\ 0 & 1 & 0 \\ 0 & 0 & 1 \end{bmatrix}
$$

$$
\Sigma = \begin{bmatrix} 1 & 0 \\ 0 & 1 \\ 0 & 0 \end{bmatrix}
$$

$$
V^T = \begin{bmatrix} 1 & 0 \\ 0 & 1 \end{bmatrix}
$$

#### 2.9.3 - Aplicações das Decomposições Matriciais

- **Resolução de sistemas lineares**: A decomposição de Cholesky é usada para resolver sistemas de equações lineares de maneira eficiente.
- **Compressão de dados**: A SVD é amplamente utilizada na compressão de imagens e redução de dimensionalidade em ciência de dados.
- **Análise de componentes principais (PCA)**: A SVD é essencial na PCA para identificar padrões nos dados.


