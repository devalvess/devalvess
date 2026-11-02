### Olá! Eu sou o Edilson Santos 👋

**Engenheiro de Dados** · Azure Databricks · Lakehouse · CDC · SQL
Ribeirão Preto/SP

Construo plataformas de dados no Azure: ingestão de bancos transacionais e sistemas legados,
arquitetura medalhão (Bronze, Silver e Gold) com Unity Catalog, governança de dados pessoais e
controle de custo.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/edilson-alves-dos-santos-23b0a51ba/)

---

### Projeto em destaque

#### [Banking CDC Lakehouse Lab](https://github.com/devalvess/banking-cdc-lakehouse-lab)

Laboratório de ponta a ponta para um banco migrando de sistemas legados on-premises para o
Azure Databricks:

- **CDC por log**: IBM Db2 → Debezium → Kafka → Lakeflow com AUTO CDC (SCD2)
- **Reverse ETL**: devolução de dados da Gold para o Db2 on-prem via staging + procedure, sem
  travar a produção, com validação por contagem e soma e auditoria dos dois lados
- **Legado sem CDC**: carga incremental via JDBC, detecção de deletes e reconciliação
- **Governança e FinOps**: máscaras de PII e filtro por região no Unity Catalog; custo real do
  projeto lido da fatura do Azure
- **Infraestrutura como código**: Terraform (VNet, NSG, peering), Docker Compose e Databricks
  Asset Bundles

[![Arquitetura do laboratório](https://raw.githubusercontent.com/devalvess/banking-cdc-lakehouse-lab/main/docs/img/arquitetura.gif)](https://github.com/devalvess/banking-cdc-lakehouse-lab)

---

### Tecnologias

![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
