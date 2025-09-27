# Case Soutag

## Etapas

### 1. Ingestão

- **Realização**: Usei o Databricks Community Edition para importar o dataset e criar as tabelas SQL. Para armazenar o banco de dados e conectar com o Power BI, usei o SQLite online.

### 2. Tratamento
- **Realização**: Usei PySpark e SparkSQL para os tratamentos e normalização dos dados, bem como os refinamentos e limpezas, criando colunas formatadas para o formato de data BR, além do solicitado no teste.

### 3. **Análise de Dados**
#### Feitas as devidas consultas e criação das views para a utilização na criação do dashboard em Power BI, conforme os anexos.
- Top países com mais títulos.
- Evolução por mês-ano de lançamentos.
- Distribuição de filmes x séries.
- Análise de elenco

### **Linguagens usadas**

- Usados PySpark (python) para a leitura do dataset, criação do dataframe, normalização de dados e para salvar o dataframe como uma tabela SQL, e, SparkSQL para a criação das tabelas seguintes, além de mais processos de limpeza dos dados, consultas e criação das views para a utilização no processo de BI;

- A ferramenta usada no processo de criação do dashboard foi o Microsoft Power BI;

### Entrega

- Os códigos usados durante todo o processo estão disponíveis nesse repositório (arquivos - 01_Ingestão de dados - Case Soutag.ipynb | 02_ETL - Case Soutag.ipynb | 03_Análises Finais- Case Soutag.ipynb).

- Dashboard - Link e prints disponíveis no arquivo "Dashoboard_Soutag".

- Pensando em como realizar esse teste, optei em usar o Databricks Community Edition para todo o processo de ingestão dos dados até a finalização das análises. O armazenamento do banco fiz no SQLite online a parte de Data Viz, optei pelo Power BI, pois possuo mais afinidade com a ferramenta. Optei em usar Databricks e SQLite por conta do contato recente que tive com a ferramenta (Databricks), o que fez com que eu pensasse no, quanto seria interessante o processo dos dados ficarem salvos na nuvem, onde posso consultar de forma rápida e com a opção não somente do SQL, mas também usar python para algumas análises.

### Conclusão
- Foi um processo interessante, onde pude transformar o dataset da Netflix em informações organizadas e de fácil interpretação, usando as habilidades que possuo em Python PySpark e SQL, tornando possível identificar os KPIs esperados, analisar a evolução dos lançamentos, comparar filmes e séries e entender a distribuição de elenco. Esses insights fornecem uma visão clara do catálogo, podendo apoiar possíveis decisões estratégicas relacionadas a marketing, parcerias e preferências do público.
