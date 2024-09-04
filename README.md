# IV - DADOS E BASES DE DADOS

## 1. Conceitos fundamentais de dados: o que são dados; processos geradores de dados; tipos e classes de dados; formatos de arquivos de dados comuns (txt, csv, xlsx, xml, json e parquet).

### 1.1 O que são dados? 📊

Dados são representações de informações que podem ser processadas por computadores. Eles podem ser números, textos, imagens, sons ou qualquer forma de input que possa ser interpretado e analisado para gerar conhecimento.

**Exemplo**: Números em uma planilha de vendas (quantidades, preços, datas) são dados que, quando organizados e analisados, ajudam a entender o desempenho da empresa.

### 1.2 Processos geradores de dados 🔍

Dados podem ser gerados de várias maneiras, refletindo eventos do mundo real ou atividades computacionais. Os principais processos geradores incluem:

- **Entrada manual**: Inserção de dados por humanos, como o preenchimento de formulários.
- **Sensores e dispositivos IoT**: Captura automática de dados, como temperatura, localização, movimentos, etc.
- **Transações digitais**: Compras online, operações bancárias, registros de login.
- **Log de sistemas**: Registros de eventos e atividades de sistemas operacionais, aplicativos ou redes.
- **Web scraping e APIs**: Extração de dados da internet, coletando informações de sites e serviços online.

**Exemplo**: Um sistema de e-commerce gera dados a partir das transações dos clientes, incluindo informações como produtos comprados, quantidade, tempo de compra e método de pagamento.

### 1.3 Tipos e classes de dados 🗂️

Os dados podem ser categorizados com base na forma como são estruturados e na sua natureza:

- **Dados Estruturados**: Dados organizados em formatos predefinidos, como tabelas com linhas e colunas (ex.: banco de dados SQL).
  - **Exemplo**: Tabelas de um banco de dados relacional com colunas para nome, idade e cidade.
  
- **Dados Semiestruturados**: Têm uma estrutura parcial, mas não são rígidos como os estruturados. São comuns em formatos como XML e JSON.
  - **Exemplo**: Um documento JSON que armazena dados de um usuário em pares chave-valor.

- **Dados Não Estruturados**: Dados sem uma estrutura definida, como imagens, vídeos, e-mails, documentos de texto, etc.
  - **Exemplo**: Fotografias e vídeos armazenados em um servidor.

- **Dados Qualitativos**: Dados descritivos que não são numéricos, como opiniões ou feedback de clientes.
  - **Exemplo**: Comentários deixados por clientes sobre produtos.

- **Dados Quantitativos**: Dados que podem ser medidos e expressos numericamente.
  - **Exemplo**: Números de vendas diárias ou medições de temperatura.

### 1.4 Formatos de arquivos de dados comuns 📂

- **TXT (Text File)**: Formato básico que armazena dados como texto simples. É amplamente usado para registros de log e armazenamento de pequenas quantidades de dados.
  - **Exemplo**: Arquivos de log de servidores onde cada linha é um registro de evento.

- **CSV (Comma-Separated Values)**: Formato tabular onde os valores são separados por vírgulas. Muito utilizado para exportação e importação de dados em tabelas.
  - **Exemplo**: Uma planilha de Excel exportada como CSV contendo informações de vendas.

- **XLSX (Excel File)**: Formato proprietário do Microsoft Excel que armazena dados em planilhas com múltiplas abas, fórmulas e gráficos. Usado para manipulação e análise de dados tabulares.
  - **Exemplo**: Relatórios financeiros que utilizam fórmulas complexas para calcular lucros e perdas.

- **XML (eXtensible Markup Language)**: Formato que armazena dados em uma estrutura hierárquica, sendo útil para transferir dados entre sistemas de forma legível tanto para humanos quanto para máquinas.
  - **Exemplo**: Arquivos de configuração de software ou troca de dados entre aplicativos (ex.: sistemas de reservas de passagens aéreas).

- **JSON (JavaScript Object Notation)**: Formato leve para troca de dados, com estrutura de chave-valor que facilita a leitura e escrita por humanos e sistemas. Muito utilizado em APIs e aplicações web.
  - **Exemplo**: Respostas de APIs que retornam informações do usuário, como nome, idade e endereço em formato JSON.

- **Parquet**: Formato de armazenamento otimizado para leitura e compressão, usado principalmente em Big Data para armazenar dados analíticos. É colunar, permitindo consultas rápidas e eficientes.
  - **Exemplo**: Dados de log de grandes volumes processados por ferramentas como Apache Spark ou Hadoop.

### Resumo das Possíveis Cobranças em Provas:

- **Definição de Dados**: Pode ser cobrada a definição e exemplos práticos de como dados são usados.
- **Tipos de Dados**: Questões podem focar nas diferenças entre dados estruturados, semiestruturados e não estruturados, com exemplos.
- **Processos Geradores de Dados**: Questões podem pedir que você identifique processos que geram dados (ex.: sensores IoT) e como esses dados são usados.
- **Formatos de Arquivos**: É comum que perguntas abordem os formatos de dados (ex.: diferença entre JSON e CSV) e seus usos apropriados em diferentes cenários.

## 2. Introdução a Bases de Dados: o que são bases de dados; tipos de bases de dados; metadados; tidy data.

### 2.1 O que são Bases de Dados?

Bases de dados são coleções organizadas de informações que permitem o armazenamento, recuperação e manipulação eficiente dos dados. Elas são essenciais para gerenciar grandes quantidades de informações de forma estruturada e acessível.

- **Exemplo**: Um sistema de gestão de clientes (CRM) que armazena informações de contato, histórico de compras e interações de cada cliente em um banco de dados relacional.

### 2.2 Tipos de Bases de Dados

- **Bases de Dados Relacionais**: Estruturadas em tabelas com linhas e colunas, onde os dados são organizados em registros e os relacionamentos são definidos por chaves. Utilizam SQL (Structured Query Language) para manipulação de dados.

  - **Exemplo**: MySQL, PostgreSQL, Oracle.

- **Bases de Dados NoSQL**: Projetadas para lidar com grandes volumes de dados não estruturados ou semiestruturados, como documentos, grafos ou chave-valor, oferecendo flexibilidade e escalabilidade.

  - **Subtipos**:
    - **Chave-Valor**: Armazena dados em pares chave-valor. Exemplo: Redis.
    - **Documentos**: Armazena dados como documentos JSON ou BSON. Exemplo: MongoDB.
    - **Grafos**: Otimizadas para explorar relações entre dados. Exemplo: Neo4j.
    - **Colunares**: Armazenam dados por colunas, otimizadas para leitura rápida. Exemplo: Apache Cassandra.

- **Bases de Dados Distribuídas**: Armazenam dados em múltiplos servidores ou locais, distribuindo a carga de processamento e aumentando a disponibilidade.

  - **Exemplo**: Google Bigtable, Amazon DynamoDB.

- **Data Warehouses**: Projetadas para análise de grandes volumes de dados históricos. Focam na otimização de consultas complexas.

  - **Exemplo**: Amazon Redshift, Snowflake.

### 2.3 Metadados

Metadados são "dados sobre dados". Eles descrevem as propriedades e características dos dados, como tipo, formato, estrutura e restrições, ajudando a organizar, entender e gerenciar as bases de dados.

- **Exemplo**: Em uma tabela de um banco de dados, metadados incluem informações como o nome da tabela, nomes das colunas, tipos de dados das colunas (ex.: inteiro, texto) e restrições (ex.: chave primária, chave estrangeira).

- **Funções dos Metadados**:
  - Facilitam a gestão e busca de informações dentro de uma base de dados.
  - Descrevem a estrutura dos dados para garantir consistência e integridade.
  - Ajudam na documentação e compreensão dos dados por usuários e sistemas.

### 2.4 Tidy Data

"Tidy data" refere-se a um formato padrão para organizar dados de forma limpa e estruturada, facilitando a análise. Em tidy data, cada variável forma uma coluna, cada observação forma uma linha, e cada tipo de unidade observacional forma uma tabela.

- **Princípios de Tidy Data**:
  - Cada coluna representa uma variável.
  - Cada linha representa uma observação.
  - Cada tabela armazena um tipo de unidade observacional.

- **Exemplo**:
  
  | Nome  | Idade | Cidade    |
  |-------|-------|-----------|
  | João  | 25    | São Paulo |
  | Maria | 30    | Rio       |

Neste exemplo, a tabela segue o formato tidy data, onde cada linha representa uma pessoa, e cada coluna representa uma característica (variável) dessa pessoa.

### Resumo das Possíveis Cobranças em Provas:

- **Definição de Bases de Dados**: Questões podem abordar o conceito de bases de dados e sua importância na organização de informações.
- **Tipos de Bases de Dados**: Questões podem diferenciar entre bases de dados relacionais, NoSQL, distribuídas e data warehouses, incluindo suas aplicações.
- **Metadados**: Podem ser cobradas as funções e exemplos de metadados dentro de uma base de dados.
- **Tidy Data**: Podem ser abordados os princípios do tidy data e sua importância na análise de dados.

## 3. Introdução ao Armazenamento de Dados: armazenamento de arquivos; principais estruturas de armazenamento de dados analíticos (data warehouse, data mart, data lake, data lakehouse, vector stores), suas diferenças conceituais e casos de uso; armazenamento na nuvem.

### 3.1 Armazenamento de Arquivos

Armazenamento de arquivos refere-se à prática de guardar dados em sistemas de arquivos tradicionais, onde os dados são organizados em pastas e subpastas. É um método comum para armazenar documentos, imagens, vídeos, e outros tipos de arquivos não estruturados.

- **Exemplo**: Armazenar documentos em um servidor de arquivos da empresa ou em um serviço de armazenamento em nuvem como Google Drive ou Dropbox.

### 3.2 Estruturas de Armazenamento de Dados Analíticos

#### 3.2.1 Data Warehouse

- **Definição**: Um data warehouse é um sistema de armazenamento de dados estruturados projetado para análise e relatórios. Ele consolida dados de diferentes fontes e os organiza de forma otimizada para consultas complexas e rápidas.

- **Características**:
  - Armazenamento de dados históricos.
  - Estruturado para análises e relatórios.
  - Alta performance em consultas complexas.
  
- **Caso de Uso**: Utilizado por empresas para gerar relatórios financeiros, análises de vendas e outras métricas de negócios.

- **Exemplo**: Amazon Redshift, Google BigQuery.

#### 3.2.2 Data Mart

- **Definição**: Um data mart é uma versão menor e mais focada de um data warehouse, destinada a atender as necessidades específicas de um departamento ou área de negócios.

- **Características**:
  - Segmento de um data warehouse.
  - Focado em um conjunto específico de dados (ex.: vendas, marketing).
  - Rápido e direcionado para usuários finais.

- **Caso de Uso**: Departamentos de marketing usam data marts para acessar dados relevantes para campanhas e análise de clientes.

- **Exemplo**: Data mart focado em vendas dentro de um data warehouse maior.

#### 3.2.3 Data Lake

- **Definição**: Um data lake é um repositório que permite armazenar grandes volumes de dados brutos em seu formato original, sejam eles estruturados, semiestruturados ou não estruturados.

- **Características**:
  - Armazena dados em sua forma bruta.
  - Suporta diversos formatos de dados (JSON, XML, CSV, etc.).
  - Flexível e escalável.

- **Caso de Uso**: Usado para ingestão e armazenamento de grandes volumes de dados que podem ser analisados posteriormente com técnicas de machine learning ou big data.

- **Exemplo**: Azure Data Lake, Amazon S3.

#### 3.2.4 Data Lakehouse

- **Definição**: Um data lakehouse combina as vantagens do data warehouse e do data lake, oferecendo uma estrutura unificada que permite o armazenamento de dados brutos e a execução de análises estruturadas.

- **Características**:
  - Combina a flexibilidade do data lake com o desempenho do data warehouse.
  - Suporta dados estruturados e não estruturados.
  - Facilita análises em tempo real e batch.

- **Caso de Uso**: Empresas que necessitam tanto de armazenamento de dados brutos para aprendizado de máquina quanto de dados estruturados para relatórios rápidos.

- **Exemplo**: Databricks Lakehouse, Google BigLake.

#### 3.2.5 Vector Stores

- **Definição**: Armazenamento de vetores é utilizado para armazenar representações vetoriais de dados, como embeddings gerados por modelos de aprendizado de máquina para tarefas como busca semântica, recomendação de produtos e análise de sentimentos.

- **Características**:
  - Armazena dados na forma de vetores.
  - Otimizado para buscas rápidas e comparações de similaridade.
  - Usado em inteligência artificial e aprendizado de máquina.

- **Caso de Uso**: Empresas que usam modelos de IA para recomendação de produtos, buscas semânticas e outros algoritmos de similaridade.

- **Exemplo**: Pinecone, Milvus.

### 3.3 Armazenamento na Nuvem

- **Definição**: Armazenamento na nuvem refere-se ao uso de serviços fornecidos por provedores de nuvem para armazenar dados remotamente, acessíveis via internet. Oferece escalabilidade, flexibilidade e acessibilidade global.

- **Principais Provedores**:
  - **Amazon Web Services (AWS)**: S3, EBS, Glacier.
  - **Microsoft Azure**: Blob Storage, Azure Data Lake.
  - **Google Cloud**: Google Cloud Storage, BigQuery.

- **Vantagens**:
  - Escalabilidade quase ilimitada.
  - Pagamento conforme o uso.
  - Redundância e alta disponibilidade.

- **Caso de Uso**: Empresas de todos os tamanhos usam armazenamento na nuvem para backups, hospedagem de sites, armazenamento de grandes volumes de dados e análise de big data.

### Resumo das Possíveis Cobranças em Provas:

- **Armazenamento de Arquivos**: Questões podem abordar conceitos básicos de armazenamento de arquivos e sua importância.
- **Estruturas de Armazenamento Analítico**: Podem ser cobradas as diferenças entre data warehouse, data mart, data lake, data lakehouse e vector stores, além de seus casos de uso.
- **Armazenamento na Nuvem**: Perguntas podem focar nas vantagens, principais provedores e usos comuns do armazenamento em nuvem.
## 4. Sistemas Gerenciadores de Base de Dados (SGBD): definição de SGBD; principais funções; principais tipos de SGBDs (SQL e NoSQL) e suas diferenças; transações e índices.

### 4.1 Definição de SGBD

Um Sistema Gerenciador de Base de Dados (SGBD) é um software que permite criar, gerenciar, manipular e acessar bases de dados de maneira eficiente e organizada. Ele fornece ferramentas para a definição de estruturas de dados, inserção, atualização, exclusão e consulta dos dados, garantindo segurança, integridade e consistência.

- **Exemplo**: MySQL, PostgreSQL, MongoDB.

### 4.2 Principais Funções dos SGBDs

- **Criação de Bases de Dados**: Define a estrutura da base de dados, incluindo tabelas, colunas e tipos de dados.
- **Manipulação de Dados**: Permite inserir, atualizar, excluir e consultar dados.
- **Controle de Acesso**: Garante que apenas usuários autorizados possam acessar ou modificar os dados.
- **Segurança e Integridade**: Protege os dados contra acessos não autorizados e mantém a integridade das informações armazenadas.
- **Gerenciamento de Transações**: Permite que operações sejam executadas de forma atômica, consistente, isolada e durável (ACID).
- **Recuperação de Falhas**: Possui mecanismos para restaurar a base de dados após falhas, mantendo a consistência.

### 4.3 Principais Tipos de SGBDs (SQL e NoSQL)

#### 4.3.1 SGBDs SQL (Relacionais)

- **Definição**: SGBDs que utilizam uma linguagem estruturada de consulta (SQL) para manipular dados em bases de dados relacionais, onde os dados são organizados em tabelas com colunas e linhas.

- **Características**:
  - Estrutura de dados rígida e bem definida.
  - Relacionamentos entre tabelas usando chaves primárias e estrangeiras.
  - Suporte a transações ACID, garantindo integridade e consistência.
  
- **Exemplos**: MySQL, PostgreSQL, Oracle, SQL Server.

- **Caso de Uso**: Aplicações que exigem consistência e integridade, como sistemas financeiros, ERPs e CRMs.

#### 4.3.2 SGBDs NoSQL (Não Relacionais)

- **Definição**: SGBDs projetados para lidar com grandes volumes de dados não estruturados ou semiestruturados, oferecendo maior flexibilidade e escalabilidade em comparação aos SGBDs relacionais.

- **Principais Tipos de NoSQL**:
  - **Chave-Valor**: Dados armazenados em pares chave-valor. Exemplo: Redis, DynamoDB.
  - **Documentos**: Armazena dados em documentos JSON ou BSON. Exemplo: MongoDB, CouchDB.
  - **Grafos**: Otimizado para explorar relacionamentos complexos entre dados. Exemplo: Neo4j.
  - **Colunares**: Armazena dados por colunas, otimizando consultas de leitura. Exemplo: Cassandra, HBase.

- **Características**:
  - Flexibilidade de esquema, permitindo mudanças rápidas na estrutura dos dados.
  - Alta escalabilidade horizontal.
  - Desempenho otimizado para grandes volumes de dados e consultas específicas.

- **Caso de Uso**: Aplicações que lidam com grandes volumes de dados, como redes sociais, IoT, e-commerce, e big data.

### 4.4 Diferenças entre SQL e NoSQL

| Característica     | SQL                              | NoSQL                            |
|--------------------|----------------------------------|----------------------------------|
| **Estrutura**      | Tabelas, colunas e linhas       | Chave-valor, documentos, grafos, colunas |
| **Esquema**        | Fixo e pré-definido              | Flexível e dinâmico              |
| **Transações**     | Suporte completo a ACID          | Suporte variável (depende do tipo)|
| **Escalabilidade** | Vertical (melhoria de hardware)  | Horizontal (adição de servidores)|
| **Uso**            | Aplicações com alta consistência | Aplicações que requerem escalabilidade e flexibilidade |

### 4.5 Transações

- **Definição**: Uma transação é uma sequência de operações que são tratadas como uma única unidade lógica de trabalho. Transações são fundamentais para garantir a integridade dos dados em operações que envolvem múltiplas etapas.

- **Propriedades ACID**:
  - **Atomicidade**: Todas as operações dentro da transação são concluídas ou nenhuma é.
  - **Consistência**: A transação leva o banco de dados de um estado consistente a outro estado consistente.
  - **Isolamento**: Operações de uma transação não são visíveis para outras até serem finalizadas.
  - **Durabilidade**: Uma vez que uma transação é concluída, suas mudanças são permanentes.

- **Exemplo**: Em uma transação bancária, a transferência de fundos entre contas é tratada como uma transação para garantir que os fundos sejam debitados de uma conta e creditados em outra de forma segura.

### 4.6 Índices

- **Definição**: Índices são estruturas de dados que melhoram a velocidade de recuperação de registros em uma tabela de banco de dados, criando uma referência rápida para localizar dados sem precisar varrer toda a tabela.

- **Tipos de Índices**:
  - **Índice Primário**: Baseado na chave primária da tabela.
  - **Índice Secundário**: Baseado em colunas que não são chaves primárias.
  - **Índices Compostos**: Índices que utilizam múltiplas colunas para melhorar a performance de consultas específicas.

- **Caso de Uso**: Melhorar o desempenho de consultas que buscam dados específicos em grandes tabelas.

## 5. Modelo de Dados: modelo de entidade-relacionamento (ER); modelo relacional: tabelas, esquemas, chaves, consultas; dados estruturados, semiestruturados e não estruturados; modelo chave-valor; modelo colunar; modelo orientado a documentos; modelo orientado a grafos.

### 5.1 Modelo de Entidade-Relacionamento (ER)

- **Definição**: O Modelo de Entidade-Relacionamento (ER) é uma abordagem de modelagem de dados que descreve os dados em termos de entidades, atributos e relacionamentos. Ele é usado principalmente para o projeto de bases de dados relacionais.

- **Componentes**:
  - **Entidades**: Representam objetos ou conceitos do mundo real (ex.: Cliente, Produto).
  - **Atributos**: Descrevem as propriedades das entidades (ex.: Nome, Idade).
  - **Relacionamentos**: Definem como as entidades se conectam (ex.: Cliente compra Produto).

- **Diagrama ER**: Visualiza a estrutura da base de dados e como os dados estão interligados.

### 5.2 Modelo Relacional

- **Definição**: O modelo relacional organiza os dados em tabelas (ou relações), onde cada tabela é composta por linhas (registros) e colunas (atributos). É a base dos SGBDs relacionais.

- **Componentes**:
  - **Tabelas**: Estruturas que armazenam dados organizados em linhas e colunas.
  - **Esquemas**: Estrutura que define a organização do banco de dados, incluindo tabelas, colunas e relacionamentos.
  - **Chaves**:
    - **Chave Primária**: Identifica de forma única cada registro em uma tabela.
    - **Chave Estrangeira**: Cria relacionamentos entre tabelas diferentes.
  - **Consultas**: Realizadas através de SQL para inserir, atualizar, deletar e buscar dados.

- **Exemplo**: Uma tabela de "Clientes" com colunas "ID", "Nome" e "Email".

### 5.3 Dados Estruturados, Semiestruturados e Não Estruturados

- **Dados Estruturados**: Organizados em um formato predefinido, como tabelas, onde cada dado segue um padrão específico.
  - **Exemplo**: Tabelas em um banco de dados SQL.

- **Dados Semiestruturados**: Possuem alguma estrutura, mas não são tão rígidos quanto os dados estruturados. Comuns em formatos como XML e JSON.
  - **Exemplo**: Arquivos JSON que contêm pares chave-valor.

- **Dados Não Estruturados**: Dados sem uma estrutura fixa, difíceis de categorizar em tabelas.
  - **Exemplo**: E-mails, imagens, vídeos.

### 5.4 Modelo Chave-Valor

- **Definição**: Armazena dados em pares chave-valor, onde cada chave é única e associada a um valor. É simples e rápido para operações de leitura e escrita.

- **Características**:
  - Alta flexibilidade e escalabilidade.
  - Sem estrutura rígida de dados.

- **Caso de Uso**: Sessões de usuário, caching, e armazenamento de configurações.

- **Exemplo**: Redis, Amazon DynamoDB.

### 5.5 Modelo Colunar

- **Definição**: Armazena dados por colunas em vez de linhas. Ideal para consultas que envolvem grandes volumes de dados, pois permite acesso rápido a colunas específicas.

- **Características**:
  - Otimizado para leitura de grandes volumes de dados.
  - Suporta compressão eficiente.

- **Caso de Uso**: Análise de grandes volumes de dados em data warehouses.

- **Exemplo**: Apache Cassandra, Google Bigtable.

### 5.6 Modelo Orientado a Documentos

- **Definição**: Armazena dados como documentos, geralmente em formatos como JSON, BSON ou XML. Cada documento é autônomo, contendo todas as informações necessárias para ser compreendido.

- **Características**:
  - Flexibilidade na estrutura de dados.
  - Ideal para aplicações que lidam com dados não estruturados.

- **Caso de Uso**: Aplicações que exigem rápido desenvolvimento e iteração de modelos de dados.

- **Exemplo**: MongoDB, CouchDB.

### 5.7 Modelo Orientado a Grafos

- **Definição**: Armazena dados como nós, arestas e propriedades, sendo ideal para representar e consultar relacionamentos complexos entre entidades.

- **Características**:
  - Otimizado para explorar conexões e relacionamentos.
  - Excelente para consultas que envolvem redes e hierarquias.

- **Caso de Uso**: Redes sociais, sistemas de recomendação, detecção de fraudes.

- **Exemplo**: Neo4j, Amazon Neptune.

### Resumo das Possíveis Cobranças em Provas:

- **Modelo ER**: Questões podem abordar a criação de diagramas ER e a definição de entidades, atributos e relacionamentos.
- **Modelo Relacional**: Perguntas podem focar na estrutura das tabelas, uso de chaves primárias e estrangeiras, e exemplos de consultas SQL.
- **Dados Estruturados vs. Semiestruturados e Não Estruturados**: Podem ser cobradas as diferenças e exemplos de cada tipo de dado.
- **Modelos de Dados Não Relacionais**: Questões podem explorar as características e casos de uso dos modelos chave-valor, colunar, orientado a documentos e orientado a grafos.
## 6. Ingestão e Armazenamento de Dados: definição de ingestão em lote (batch) e em tempo real (stream).

### 6.1 Definição de Ingestão de Dados

Ingestão de dados refere-se ao processo de coletar, importar e carregar dados de várias fontes para um sistema de armazenamento, como bancos de dados, data lakes ou data warehouses, para posterior processamento e análise. A ingestão de dados pode ocorrer de duas formas principais: em lote (batch) e em tempo real (stream).

### 6.2 Ingestão em Lote (Batch)

- **Definição**: A ingestão em lote envolve a coleta e o processamento de dados em grandes volumes de uma só vez, em intervalos regulares. Os dados são agrupados e processados de forma sequencial, geralmente durante períodos de baixa atividade para minimizar o impacto no desempenho do sistema.

- **Características**:
  - Ideal para processar grandes quantidades de dados de uma vez.
  - Pode ter um atraso significativo entre a coleta dos dados e o processamento.
  - Requer menor capacidade computacional em tempo real, pois o processamento é agendado.
  - Adequado para operações que não exigem atualização imediata dos dados.

- **Casos de Uso**:
  - Processamento de relatórios financeiros diários ou semanais.
  - Análise de dados históricos para identificar tendências.
  - Atualização de sistemas de back-office, como inventários.

- **Exemplo**: Um sistema de varejo que processa todas as vendas do dia à noite, gerando relatórios para análise no dia seguinte.

### 6.3 Ingestão em Tempo Real (Stream)

- **Definição**: A ingestão em tempo real, ou streaming, envolve o processamento contínuo e instantâneo de dados conforme eles são gerados. Esse método permite que as informações sejam capturadas e analisadas em tempo real, possibilitando ações imediatas.

- **Características**:
  - Processa dados continuamente, com latência mínima.
  - Ideal para aplicações que exigem respostas rápidas e em tempo real.
  - Requer maior capacidade de processamento e infraestrutura para lidar com o fluxo contínuo de dados.
  - Suporta decisões rápidas e automação baseada em eventos.

- **Casos de Uso**:
  - Monitoramento de fraudes em tempo real em transações financeiras.
  - Análise de tráfego de redes sociais para detectar tendências.
  - Sistemas de recomendação em tempo real, como sugerir produtos durante uma navegação de e-commerce.
  - Monitoramento de dispositivos IoT, como sensores de temperatura em ambientes industriais.

- **Exemplo**: Plataformas de streaming de vídeo, como Netflix, que monitoram o comportamento do usuário e ajustam a entrega de conteúdo em tempo real.

### Resumo das Possíveis Cobranças em Provas:

- **Definição e Diferenças**: Questões podem abordar a diferença entre ingestão em lote e em tempo real, incluindo características e vantagens de cada método.
- **Casos de Uso**: Perguntas podem focar em identificar qual tipo de ingestão é mais adequado para diferentes cenários de aplicação.
- **Exemplos Práticos**: Pode-se solicitar exemplos de situações em que a ingestão em lote ou em tempo real seria ideal.

  
## 7. Big Data: conceito de big data; conceitos gerais sobre técnicas e ferramentas para lidar com grandes volumes de dados (Spark, Hadoop, HDFS e MapReduce).

### 7.1 Conceito de Big Data

Big Data refere-se a grandes volumes de dados complexos que são gerados a uma alta velocidade e em formatos variados, tornando-os difíceis de gerenciar e processar usando métodos tradicionais. Esses dados são caracterizados pelos "5 Vs":

- **Volume**: Enorme quantidade de dados gerados diariamente.
- **Velocidade**: A rapidez com que os dados são gerados, coletados e processados.
- **Variedade**: Diversidade de tipos de dados (estruturados, semiestruturados e não estruturados).
- **Veracidade**: Qualidade e confiabilidade dos dados.
- **Valor**: O potencial dos dados para gerar insights valiosos e impactar negócios.

**Exemplos de Big Data**:
- Registros de redes sociais (tweets, posts, curtidas).
- Dados de sensores IoT (temperatura, pressão).
- Logs de servidores e tráfego de websites.

### 7.2 Técnicas e Ferramentas para Lidar com Big Data

#### 7.2.1 Apache Hadoop

- **Definição**: Hadoop é um framework de código aberto que permite o processamento distribuído de grandes volumes de dados em clusters de servidores utilizando um modelo de programação simplificado.

- **Componentes Principais**:
  - **HDFS (Hadoop Distributed File System)**: Sistema de arquivos distribuído que armazena dados em múltiplos servidores, garantindo alta disponibilidade e redundância.
  - **MapReduce**: Modelo de programação que divide tarefas de processamento de dados em dois estágios: map (mapeamento) e reduce (redução).

- **Características**:
  - Processamento paralelo de grandes volumes de dados.
  - Alta tolerância a falhas através da replicação de dados.
  - Escalabilidade horizontal, permitindo a adição de novos nós ao cluster conforme a necessidade.

- **Caso de Uso**: Processamento de grandes conjuntos de dados para análises de mercado, detecção de fraudes, e indexação de grandes volumes de documentos.

#### 7.2.2 HDFS (Hadoop Distributed File System)

- **Definição**: HDFS é um sistema de arquivos distribuído projetado para armazenar grandes conjuntos de dados de forma redundante e acessível em clusters de servidores.

- **Características**:
  - Armazena dados em blocos distribuídos entre múltiplos nós no cluster.
  - Suporta alta tolerância a falhas replicando os dados em diferentes servidores.
  - Permite o acesso rápido a dados de grandes volumes para processamento paralelo.

- **Exemplo**: Uma empresa de análise de dados que precisa armazenar petabytes de dados históricos de vendas para análises futuras.

#### 7.2.3 MapReduce

- **Definição**: MapReduce é um modelo de programação utilizado no Hadoop que permite o processamento paralelo de grandes volumes de dados, dividindo o trabalho em duas fases: map (mapeamento) e reduce (redução).

- **Fases**:
  - **Map**: Divide a tarefa em pequenas partes e distribui para nós no cluster, onde os dados são processados de forma independente.
  - **Reduce**: Agrega os resultados parciais e gera o resultado final.

- **Características**:
  - Permite o processamento escalável de dados em ambientes distribuídos.
  - Gerencia automaticamente a divisão e recombinação de tarefas.

- **Caso de Uso**: Indexação de páginas da web para motores de busca, análise de grandes logs de servidores.

#### 7.2.4 Apache Spark

- **Definição**: Spark é um motor de processamento de dados em tempo real, que oferece um modelo de programação flexível e acelera o processamento distribuído de grandes volumes de dados.

- **Características**:
  - Suporta processamento em batch e em tempo real.
  - Usa memória para armazenamento intermediário, o que aumenta a velocidade de processamento comparado ao MapReduce.
  - Oferece bibliotecas para aprendizado de máquina (MLlib), processamento de gráficos (GraphX), e manipulação de dados estruturados (Spark SQL).

- **Exemplo**: Utilizado por empresas de tecnologia para análise em tempo real de dados de transações financeiras e monitoramento de sistemas.

### Resumo das Possíveis Cobranças em Provas:

- **Conceito de Big Data**: Questões podem focar nas características dos 5 Vs e em exemplos práticos de Big Data.
- **Ferramentas de Big Data**: Perguntas podem abordar as funções e características de Hadoop, HDFS, MapReduce e Spark, incluindo suas vantagens e casos de uso específicos.
- **Diferenças entre MapReduce e Spark**: Pode ser explorada a eficiência de cada ferramenta e seu impacto na velocidade e flexibilidade do processamento de grandes volumes de dados.
