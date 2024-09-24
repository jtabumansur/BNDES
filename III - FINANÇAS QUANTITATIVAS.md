### III - FINANÇAS QUANTITATIVAS

#### 1. Matemática Financeira

A matemática financeira envolve técnicas e fórmulas para calcular e avaliar o valor do dinheiro ao longo do tempo. Esses conceitos são amplamente utilizados em finanças para tomada de decisões sobre investimentos, empréstimos e outras operações financeiras.

##### 1.1 Convenções de Cálculo de Juros

Existem duas principais convenções de cálculo de juros:

- **Juros Simples**: O juro é calculado apenas sobre o valor principal, não sobre os juros acumulados. A fórmula básica é:

  `J = P × i × n`

  Onde:
  - `J` = Juros
  - `P` = Principal (valor inicial)
  - `i` = Taxa de juros por período
  - `n` = Número de períodos

  **Exemplo**: Se você investe R$ 1.000,00 a uma taxa de 5% ao ano por 3 anos, o juro simples será `J = 1000 × 0,05 × 3 = R$ 150,00`.

- **Juros Compostos**: Os juros são calculados sobre o principal mais os juros acumulados. A fórmula é:

  `M = P × (1 + i)^n`

  Onde:
  - `M` = Montante (valor futuro)
  - `P` = Principal
  - `i` = Taxa de juros por período
  - `n` = Número de períodos

  **Exemplo**: Se você investe R$ 1.000,00 a uma taxa de 5% ao ano por 3 anos, o montante final será `M = 1000 × (1 + 0,05)^3 = R$ 1.157,63`.

##### 1.2 Valor Presente Líquido (VPL)

O VPL é usado para calcular o valor presente de fluxos de caixa futuros, descontados a uma taxa de desconto específica. É utilizado para avaliar a viabilidade de projetos de investimento.

`VPL = Σ (FC_t / (1 + i)^t) - I_0`

Onde:
- `FC_t` = Fluxo de caixa no período `t`
- `i` = Taxa de desconto
- `t` = Período
- `I_0` = Investimento inicial

**Exemplo**: Um projeto com investimento inicial de R$ 10.000,00 e fluxos de caixa de R$ 4.000,00 anuais por 3 anos, com taxa de desconto de 10%, terá:

`VPL = (4000 / (1 + 0,1)^1) + (4000 / (1 + 0,1)^2) + (4000 / (1 + 0,1)^3) - 10000 = R$ 2.486,85`

##### 1.3 Taxa Interna de Retorno (TIR)

A TIR é a taxa de desconto que faz o VPL de um projeto ser igual a zero. É usada para comparar a rentabilidade de investimentos diferentes.

**Cálculo**: A TIR é encontrada iterativamente (ou usando calculadoras financeiras/software), resolvendo a equação do VPL para a taxa que torna o resultado zero.

**Exemplo**: Para um projeto com investimento inicial de R$ 10.000,00 e fluxos de caixa anuais de R$ 4.000,00 por 3 anos, a TIR é aproximadamente 23,37%.

##### 1.4 Projeção de Fluxos de Caixa Futuros

Projeções de fluxos de caixa envolvem estimar as entradas e saídas de dinheiro ao longo do tempo. São essenciais para avaliar a viabilidade de projetos, calcular o retorno esperado e analisar a capacidade de uma empresa de honrar compromissos financeiros.

**Métodos Comuns**:
- **Método Direto**: Projeta-se diretamente as entradas e saídas baseadas em histórico e expectativas de mercado.
- **Método Indireto**: Baseia-se nas demonstrações financeiras, ajustando o lucro líquido pelas variações em contas do balanço patrimonial e itens não monetários.



#### 2. Mercados de Taxas de Juros

O mercado de taxas de juros é essencial para entender como os preços de instrumentos financeiros, como títulos e contratos futuros, são determinados com base nas taxas de juros de mercado. Ele abrange diversos conceitos e técnicas para avaliar e prever o comportamento das taxas de juros ao longo do tempo.

##### 2.1 Instrumentos de Renda Fixa

- **Instrumentos de Renda Fixa**: São títulos que pagam juros regulares ou retornos fixos aos investidores, como títulos do governo, debêntures e CDBs. Eles são amplamente utilizados para captação de recursos e como investimento seguro.

##### 2.2 Taxa Spot e Taxa Forward

- **Taxa Spot**: Refere-se à taxa de juros atual para um determinado prazo, ou seja, a taxa à qual se pode investir ou tomar emprestado hoje para um prazo específico.

- **Taxa Forward**: Refere-se à taxa de juros acordada hoje para um investimento que começará no futuro. É utilizada para prever a taxa futura com base na taxa spot e na estrutura de prazos.

##### 2.3 Relações Básicas de Não Arbitragem no Mercado de Juros

- **Princípio da Não Arbitragem**: No mercado de juros, as oportunidades de arbitragem (ganhos sem risco) devem ser inexistentes, pois os preços dos ativos se ajustam para eliminar essas oportunidades. Isso mantém as relações de preços entre diferentes instrumentos financeiros consistentes.

##### 2.4 Curvas de Juros e Bootstraping de Curvas de Juros

- **Curvas de Juros**: Representam a relação entre a taxa de juros e os diferentes prazos de vencimento de títulos. As curvas mais comuns são a curva de rendimento (yield curve), a curva spot, e a curva forward.

- **Bootstraping de Curvas de Juros**: Técnica para construir uma curva de juros spot a partir de dados de mercado, como preços de títulos. Através de um processo iterativo, é possível extrair as taxas spot para diferentes prazos.

##### 2.5 Duration e Convexidade

- **Duration**: Mede a sensibilidade do preço de um título às mudanças nas taxas de juros. É o prazo médio ponderado dos fluxos de caixa de um título, e quanto maior a duration, maior o risco de taxa de juros.

- **Convexidade**: Refina a medida de duração ao capturar a curvatura na relação entre o preço de um título e as mudanças nas taxas de juros. Uma convexidade positiva indica que o preço do título aumentará mais do que cairá para pequenas mudanças nas taxas de juros.

##### 2.6 Técnicas de Interpolação de Taxas de Juros

- **Interpolação**: Técnica usada para estimar taxas de juros para prazos que não possuem taxas observadas diretamente. Métodos comuns incluem interpolação linear, spline cúbica e métodos polinomiais.

##### 2.7 Modelos de Svensson e de Nelson-Siegel

- **Modelo de Nelson-Siegel**: Um dos modelos mais populares para ajustar curvas de juros, ele utiliza uma combinação de funções exponenciais para capturar a forma da curva.

- **Modelo de Svensson**: Uma extensão do modelo de Nelson-Siegel, adicionando mais flexibilidade com um termo adicional que permite ajustar melhor a forma da curva de juros em condições de mercado complexas.



#### 3. Medidas de Desempenho e de Riscos

As medidas de desempenho e de risco são fundamentais para avaliar o retorno ajustado ao risco de investimentos e estratégias financeiras. Elas ajudam a entender a volatilidade, o risco de perdas extremas e a eficiência dos investimentos.

##### 3.1 Volatilidade

- **Volatilidade**: Mede a intensidade e a frequência das variações no preço de um ativo. Uma alta volatilidade indica um risco maior, pois os preços do ativo sofrem grandes flutuações.

  **Exemplo**: Um ativo com volatilidade anual de 20% é mais arriscado que um com 10%, pois seus preços tendem a variar mais amplamente.

##### 3.2 Value at Risk (VaR)

- **Value at Risk (VaR)**: Medida estatística que quantifica a perda potencial máxima de um portfólio em um determinado horizonte de tempo, com um nível de confiança especificado.

  **Exemplo**: Um VaR diário de 5% com um nível de confiança de 95% significa que há 95% de probabilidade de que a perda diária não exceda esse valor.

##### 3.3 Conditional Value at Risk (CVaR)

- **Conditional Value at Risk (CVaR)**: Também conhecido como Expected Shortfall, é a média das perdas que excedem o VaR, oferecendo uma visão mais completa do risco extremo.

  **Exemplo**: CVaR é utilizado para entender o impacto das perdas além do VaR, capturando eventos de cauda na distribuição de retornos.

##### 3.4 Backtesting de Modelos de Risco

- **Backtesting de Modelos de Risco**: Técnica usada para avaliar a precisão de modelos de risco, comparando previsões com os resultados reais históricos.

  **Exemplo**: Backtesting do VaR é realizado para verificar se as perdas excedem o VaR conforme esperado pelo nível de confiança.

##### 3.5 Maximum Drawdown

- **Maximum Drawdown**: Mede a maior queda acumulada no valor de um portfólio desde o pico até o fundo, indicando a maior perda sofrida em um período.

  **Exemplo**: Um drawdown de 30% indica que o portfólio caiu 30% do seu valor de pico durante um período de queda.

##### 3.6 Sharpe Ratio

- **Sharpe Ratio**: Avalia o desempenho ajustado ao risco de um portfólio, calculando o excesso de retorno por unidade de risco (volatilidade).

  **Fórmula**: `(Retorno do Portfólio - Retorno Livre de Risco) / Volatilidade`

  **Exemplo**: Um Sharpe Ratio de 1,5 indica que o portfólio gera 1,5 unidades de retorno para cada unidade de risco.

##### 3.7 Information Ratio

- **Information Ratio**: Mede o desempenho de um portfólio em relação a um benchmark ajustado pelo risco, considerando o excesso de retorno por unidade de risco específico (tracking error).

  **Fórmula**: `(Retorno do Portfólio - Retorno do Benchmark) / Tracking Error`

  **Exemplo**: Um Information Ratio de 0,5 indica que o portfólio está gerando metade de uma unidade de excesso de retorno para cada unidade de erro de rastreamento.



#### 4. Otimização de Carteiras

A otimização de carteiras é uma técnica usada para construir portfólios de investimento que maximizam o retorno esperado para um dado nível de risco ou minimizam o risco para um nível de retorno desejado. Diversos modelos matemáticos são empregados para alcançar um equilíbrio ótimo entre risco e retorno.

##### 4.1 Modelo de Média-Variância

- **Modelo de Média-Variância**: Desenvolvido por Harry Markowitz, este modelo busca a combinação de ativos que proporciona o melhor equilíbrio entre risco (variância) e retorno esperado, usando uma fronteira eficiente de portfólios.

  - **Com Restrições**: Impõe limites, como a alocação mínima ou máxima em um ativo específico, ou restrições de alocação para atender a políticas de investimento.
  
  - **Sem Restrições**: Considera todas as possíveis combinações de ativos sem limitações específicas de alocação.

  **Exemplo**: Uma carteira diversificada de ações e títulos que minimiza a variância para um retorno esperado de 8% ao ano.

##### 4.2 Modelos de Paridade de Riscos

- **Modelos de Paridade de Riscos**: Estruturas de portfólios que buscam igualar a contribuição ao risco de cada ativo, ao invés de se focar na alocação de capital. A ideia é balancear o risco, não os valores investidos.

  **Exemplo**: Em um portfólio de paridade de risco, ações, títulos e commodities contribuem igualmente para o risco total da carteira.

##### 4.3 Modelos de Paridade de Riscos Hierárquica (HRP)

- **Modelos de Paridade de Riscos Hierárquica (HRP)**: Uma abordagem avançada de paridade de risco que utiliza algoritmos de clustering e hierarquia para estruturar a carteira. Isso reduz o impacto de ativos altamente correlacionados e distribui o risco de maneira mais eficiente.

  **Exemplo**: Um portfólio HRP organiza ativos em grupos com base em suas correlações, alocando o risco proporcionalmente entre os grupos para evitar concentrações de risco em setores correlacionados.

Esses modelos são amplamente utilizados por gestores de fundos e investidores institucionais para construir portfólios que equilibram retorno e risco, alinhando-se aos objetivos de investimento e restrições regulatórias.



#### 5. Simulação de Monte Carlo em Finanças

A Simulação de Monte Carlo é uma técnica estatística que utiliza modelos probabilísticos para prever o comportamento de variáveis financeiras e avaliar o impacto de incertezas nos preços de ativos e riscos. Em finanças, é amplamente usada para precificação de derivativos, análise de risco e otimização de portfólios.

##### 5.1 Principais Aplicações em Precificação

- **Precificação de Derivativos**: Monte Carlo é usado para calcular o preço de opções e outros derivativos complexos que não têm soluções analíticas fáceis. A simulação gera múltiplos cenários de preços futuros do ativo subjacente, estimando o valor esperado do derivativo.

  **Exemplo**: Precificação de uma opção de compra (call option) com múltiplos fatores de risco, onde o preço do ativo subjacente é simulado ao longo do tempo usando distribuições probabilísticas.

##### 5.2 Análise de Riscos

- **Cálculo do Value at Risk (VaR)**: Monte Carlo permite a simulação de cenários de mercado para estimar o VaR, capturando a perda potencial em condições extremas de mercado.

  **Exemplo**: Simulação de 10.000 cenários de retornos de um portfólio para determinar a perda máxima esperada em 99% dos casos em um período de 1 dia.

- **Stress Testing**: Avalia o impacto de condições adversas extremas nos portfólios, como grandes mudanças em taxas de juros, câmbio ou queda nos preços de ações.

##### 5.3 Otimização de Portfólios

- **Simulação de Retornos**: Ajuda a estimar a distribuição dos retornos futuros de um portfólio, considerando diferentes combinações de ativos, volatilidades e correlações, permitindo otimizar a alocação de ativos sob condições de incerteza.

  **Exemplo**: Simulação de diferentes cenários de mercado para um portfólio de ações e títulos, a fim de encontrar a combinação que minimiza o risco para um retorno desejado.



#### 6. Derivativos

Derivativos são instrumentos financeiros cujo valor deriva de um ativo subjacente, como ações, títulos, commodities, moedas ou índices de mercado. Eles são usados para proteção contra riscos (hedge), especulação e alavancagem.

##### 6.1 Conceitos Gerais

- **Derivativos**: Contratos financeiros que derivam seu valor de ativos subjacentes. Os principais tipos incluem opções, futuros, forwards e swaps.

  **Exemplo**: Um contrato futuro de petróleo estabelece um preço fixo para compra ou venda de petróleo em uma data futura, ajudando a mitigar o risco de variação de preços.

##### 6.2 Derivativos de Renda Variável

- **Derivativos de Renda Variável**: Relacionam-se a ativos como ações e índices de mercado. Incluem opções sobre ações, futuros de ações e contratos de índice.

  **Exemplo**: Opções de compra (call) permitem ao comprador adquirir ações a um preço fixo, enquanto as opções de venda (put) permitem vender ações a um preço predeterminado.

##### 6.3 Derivativos de Renda Fixa

- **Derivativos de Renda Fixa**: Ligados a instrumentos como títulos de dívida e taxas de juros. Incluem swaps de taxas de juros, futuros de títulos e opções sobre taxas de juros.

  **Exemplo**: Um swap de taxa de juros é um acordo onde duas partes trocam fluxos de caixa de juros, uma parte paga uma taxa fixa e recebe uma taxa variável, ajudando a gerenciar o risco de flutuações nas taxas de juros.

##### 6.4 Modelo de Black-Scholes

- **Modelo de Black-Scholes**: Um dos modelos mais famosos para a precificação de opções europeias. Ele calcula o preço da opção com base no preço do ativo subjacente, volatilidade, tempo até o vencimento, taxa de juros livre de risco, e preço de exercício.

  **Fórmula do Modelo de Black-Scholes**: 

  `C = S * N(d1) - X * e^(-rt) * N(d2)`

  Onde:
  - `C` = Preço da opção de compra (call)
  - `S` = Preço atual do ativo subjacente
  - `X` = Preço de exercício da opção
  - `r` = Taxa de juros livre de risco
  - `t` = Tempo até o vencimento
  - `N(d1)` e `N(d2)` = Funções de distribuição normal cumulativa

  **Exemplo**: Uso do modelo para precificar uma opção de compra de uma ação que vence em três meses com um preço de exercício de R$ 50,00, utilizando parâmetros de volatilidade e taxa de juros para determinar o preço justo da opção.



