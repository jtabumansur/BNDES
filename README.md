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
