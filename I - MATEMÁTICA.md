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
