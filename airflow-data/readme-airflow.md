## Apache Airflow
Se trata de uma ferramenta de orquestração de processos em batch. Onde utiliza de DAGs para definir a ordem de execução e dependências dos workflows.

## Formas de interação com Airflow

- CLI
- Web

## Pontos Fortes

- Capaz de gerar logs valiosos e criar scrips para executar ações com bases nesses logs (erros/sucessos)
- Ingestão de Dados (Paralelismo)
- Gerenciamento de Conectores e Conexões com diversos ambientes/plataformas
- Imagem de Docker geralmente já vem com um postgres default para armazenamento de Metadados (To Do: Explorar essa feature)

### 1. DAGs
#### 1.1 Operadores
- O que é executado
**Tipos de Tasks:**
- **Sensor:** Monitoramento das atividades ou diretórios.
- **Transfer:** Movimentação de Dados.
- **Action:** Executa scripts (python, bash, cmd)

#### 1.2 Providers
- Databricks, Postgres, MySQL e etc.