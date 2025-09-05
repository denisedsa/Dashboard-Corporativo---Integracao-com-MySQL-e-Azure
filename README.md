# Dashboard-Corporativo-Integrado-MySQL-e-Azure

Projeto final DIO: Integração de um banco de dados MySQL hospedado na Azure com o Power BI, realizando transformações, análises e geração de insights sobre a base de dados **Company**.

## 🚀 Etapas do Projeto

1. **Provisionamento do MySQL na Azure**
   Criação da instância e configuração inicial do banco de dados.
2. **Execução de scripts SQL**
   Criação das tabelas, definição de constraints e inserção de dados.
3. **Testes via MySQL Workbench**
   Conexão ao banco para validação das tabelas e consultas.
4. **Conexão do Power BI ao MySQL**
   Integração direta para análise de dados em tempo real.
5. **Transformações no Power Query**
   Limpeza, tratamento de dados e criação de colunas calculadas.
6. **Desenvolvimento de relatório no Power BI**
   Visualizações para identificar hierarquias, anomalias e métricas-chave.

## 🛠️ Tecnologias Utilizadas

* **MySQL 8.0** (Azure)
* **Power BI Desktop**
* **MySQL Workbench**
* **SQL**
* **GitHub**

## 🧩 Scripts Disponíveis

Todos os scripts SQL estão na pasta `/scripts`:

* `criar_bd_company.sql` – Criação do banco de dados e tabelas com constraints.
* `inserir_dados_e_queries.sql` – Inserção de dados e consultas de validação.

## 📊 Transformações no Power BI

* Alteração e padronização de tipos de dados
* Tratamento de valores nulos
* Junção das tabelas `employee` e `department`
* Criação de coluna de **nome completo**
* Vinculação de funcionários aos nomes dos gerentes
* Identificação de departamentos sem gerente
* Criação de campo combinado `departamento_localizacao`
* Contagem de colaboradores por gerente
