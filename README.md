# AWS Certified Cloud Practitioner

Este repositório tem como objetivo **centralizar recursos e dicas** que possam ajudar na preparação para o **exame AWS Certified Cloud Practitioner**.

## Conteúdos

1. [Pilares do Well-Architected Framework](#️-pilares-do-well-architected-framework)
2. [Resumo dos Serviços AWS](#-resumo-dos-serviços-aws)
3. [Materiais Oficiais](#-materiais-oficiais)

## 🏛️ Pilares do Well-Architected Framework

### ⚙️ Excelência Operacional

**Resumo:** *Monitoramento e melhoria de processos*

1. Automação e uso de Infraestrutura como Código (IaC);
2. Alterações frequentes, pequenas e reversíveis;
3. Uso de esteiras CI/CD para entrega;
4. Monitoramento e Observabilidade com métricas e logs;
5. Refinamento/otimização de processos operacionais.

---

### 🔐 Segurança

**Resumo:** *Proteção de informações e sistemas*

1. Gerenciamento de identidade e implementação de mínimo privilégio;
2. Segurança em camandas (VPC, Load Balancer, S.O, código, etc);
3. Proteger dados em repouso (criptografia) e em trânsito (HTTPS);
4. Rastreabilidade e detecção de eventos de segurança.

---

### 🤝 Confiabilidade

**Resumo:** *Recuperação de falhas e atendimento da demanda*

1. Recuperação automática de falhas;
2. Aplicar testes nos procedimentos de recuperação;
3. Escalabilidade, dimensionamento correto e monitoramento de limites/quotas.

---

### 🥇 Eficiência de Performance

**Resumo:** *Alocação simplificada de recursos de TI*

1. Acesso à tecnologias avançadas para inovação e experimentação;
2. Alcance global em minutos;
3. Arquiteturas sem servidor, para menor complexidade de gerenciamento.

---

### 💸 Otimização de Custos

**Resumo:** *Evitar custos desnecessários*

1. Gerenciamento financeiro dos custos na nuvem;
2. Modelos de consumo, padrões de uso e pagamento conforme o uso.

---

### 🌳 Sustentabilidade

**Resumo:** *Minimizar impactos ambientais*

1. Entender o impacto das cargas de trabalho;
2. Maximizar a utilização e implementar designs eficientes;
3. Adotar tecnologias mais eficientes e serviços gerenciados da nuvem.

## 📄 Resumo dos Serviços AWS

O resumo abaixo se baseia na **lista de serviços dentro do escopo da prova**, que pode ser acessada neste [link](https://docs.aws.amazon.com/pt_br/aws-certification/latest/cloud-practitioner-02/clf-02-in-scope-services.html) e referenciam as informações presentes nas [páginas de produto da AWS](https://aws.amazon.com/pt/products/).

### 📊 Analytics

| Serviço                         | Resumo                                   |
| ------------------------------- | ---------------------------------------- |
| ***Amazon Athena***             | Consulta SQL em dados armazenados no S3  |
| ***Amazon EMR***                | Processamento de Big Data                |
| ***AWS Glue***                  | Integração de dados (ETL)                |
| ***Amazon Kinesis***            | Streaming/Fluxo de dados em tempo real   |
| ***Amazon OpenSearch Service*** | Clusters gerenciados de pesquisa         |
| ***Amazon QuickSight***         | Dashboards de BI                         |
| ***Amazon Redshift***           | Data Warehouse                           |

### 🔔 Integração de aplicações

> [!IMPORTANT]
> Serviços relacionados com **arquiteturas distribuídas e desacoplamento**, para separação de componentes com mínima dependência entre si.

| Serviço                  | Resumo                                                   |
| ------------------------ | -------------------------------------------------------- |
| ***Amazon EventBridge*** | Barramento/Hub de eventos e agendamento                  |
| ***Amazon SNS***         | Tópicos e assinantes (Publicação/Assinatura)             |
| ***Amazon SQS***         | Filas de mensageria (Produtores/Consumidores)            |
| ***AWS Step Functions*** | Fluxo de trabalho visual para orquestração de aplicações |

### 💼 Aplicações empresariais

| Serviço              | Resumo                                     |
| -------------------- | ------------------------------------------ |
| ***Amazon Connect*** | Solução para atendimento ao cliente com IA |
| ***Amazon SES***     | Plataforma de envio/disparo de e-mails     |

### 💸 Gerenciamento financeiro da nuvem

| Serviço                                | Resumo                                         |
| -------------------------------------- | ---------------------------------------------- |
| ***AWS Budgets***                      | Monitoramento de gastos e alertas              |
| ***Relatórios de custo e uso da AWS*** | Dados sobre o uso e custos (formato CSV)       |
| ***AWS Cost Explorer***                | Visualização de uso e custos (gráficos)        |
| ***AWS Marketplace***                  | Catálogo digital para compra/venda de serviços |

### 🖥️ Computação

| Serviço                     | Resumo                                      |
| --------------------------- | ------------------------------------------- |
| ***AWS Batch***             | Computação em lote de forma gerenciada      |
| ***Amazon EC2***            | Instâncias (Máquinas Virtuais)              |
| ***AWS Elastic Beanstalk*** | Implantação de aplicações no modelo PaaS    |
| ***Amazon Lightsail***      | Servidor Privado Virtual (VPS) e hospedagem |
| ***AWS Outposts***          | Execução de serviços AWS localmente (Rack)  |

### 📦 Contêineres

| Serviço          | Resumo                                           |
| ---------------- | ------------------------------------------------ |
| ***Amazon ECR*** | Repositório de imagens                           |
| ***Amazon ECS*** | Orquestrador de containers da AWS                |
| ***Amazon EKS*** | Orquestrador Kubernetes (Open Source) gerenciado |

### 📚 Capacitação de clientes

| Serviço           | Resumo                       |
| ----------------- | ---------------------------- |
| ***AWS Support*** | Suporte para clientes da AWS |

### 🗃️ Banco de dados

| Serviço                  | Resumo                                                |
| ------------------------ | ----------------------------------------------------- |
| ***Amazon Aurora***      | Mecanismo com maior performance e confiabilidade      |
| ***Amazon DocumentDB***  | Baseado em documentos (MongoDB)                       |
| ***Amazon DynamoDB***    | Baseado em chave-valor; Não-relacional (NoSQL)        |
| ***Amazon ElastiCache*** | Serviço de Cache (Redis, Memcached e Valkey)          |
| ***Amazon Neptune***     | Baseado em grafos (Graph)                             |
| ***Amazon RDS***         | Relacional gerenciado (Postgres, MySQL, MariaDB, etc) |

### 🧑‍💻 Ferramentas do desenvolvedor

| Serviço                | Resumo                                               |
| ---------------------- | ---------------------------------------------------- |
| ***AWS CLI***          | Ferramenta de linha de comando da AWS                |
| ***AWS CodeBuild***    | Build de código fonte e execução de testes           |
| ***AWS CodePipeline*** | Pipeline automatizada de CI/CD                       |
| ***AWS X-Ray***        | Rastreamento de requisições atendidas por aplicações |

### 🏘️ Computação de usuário final

| Serviço                                | Resumo                              |
| -------------------------------------- | ----------------------------------- |
| ***Amazon AppStream 2.0***             | Streaming de aplicativos SaaS       |
| ***Amazon WorkSpaces***                | Desktops virtuais (Windows e Linux) |
| ***Amazon WorkSpaces Secure Browser*** | Navegador empresarial seguro        |

### 📱 Dispositivos móveis e web de frontend

| Serviço            | Resumo                                       |
| ------------------ | -------------------------------------------- |
| ***AWS Amplify***  | Criação de aplicativos móveis e para a Web   |
| ***AWS AppSync***  | Conectar aplicativos com eventos, dados e IA |

### 💡 Internet das Coisas (IoT)

| Serviço             | Resumo                                 |
| ------------------- | -------------------------------------- |
| ***AWS IoT Core***  | Conexão entre dispositivos IoT e a AWS |

### 🤖 Machine Learning

| Serviço                   | Resumo                                                |
| ------------------------- | ----------------------------------------------------- |
| ***Amazon Comprehend***   | Insights a partir de informações em documentos        |
| ***Amazon Kendra***       | Solução de pesquisa empresarial                       |
| ***Amazon Lex***          | Criação de Chatbots                                   |
| ***Amazon Polly***        | Conversão de texto para fala                          |
| ***Amazon Q***            | Assistente de IA para tarefas na AWS                  |
| ***Amazon Rekognition***  | Reconhecimento de imagens e vídeos                    |
| ***Amazon SageMaker***    | Criação, treinamento e implementação de modelos de IA |
| ***Amazon Textract***     | Extrai texto de documentos digitalizados              |
| ***Amazon Transcribe***   | Conversão de fala para texto                          |
| ***Amazon Translate***    | Tradução de texto entre idiomas                       |

### 🔨 Gerenciamento e governança

| Serviço                               | Resumo                                                |
| ------------------------------------- | ----------------------------------------------------- |
| ***AWS Auto Scaling***                | Automatiza a escalabilidade horizontal de recursos    |
| ***AWS CloudFormation***              | Infraestrutura como Código (IaC)                      |
| ***AWS CloudTrail***                  | Auditoria de atividades na AWS                        |
| ***Amazon CloudWatch***               | Monitoramento de saúde com métricas e logs            |
| ***AWS Compute Optimizer***           | Recomendações para performance e custos de computação |
| ***AWS Config***                      | Controle sobre a configuração de recursos             |
| ***AWS Control Tower***               | Governança e segurança de múltiplas contas            |
| ***AWS Health Dashboard***            | Página para acompanhar a saúde de serviços da AWS     |
| ***AWS License Manager***             | Gerenciamento de licenças (BYOL)                      |
| ***Console de Gerenciamento da AWS*** | Interface Web para trabalhar com a AWS                |
| ***AWS Organizations***               | Gerenciamento centralizado de múltiplas contas        |
| ***AWS Service Catalog***             | Catálogos de serviços aprovados em IaC                |
| ***Service Quotas***                  | Limites (Quotas) de serviços                          |
| ***AWS Systems Manager***             | Gerenciamento e automatização de tarefas em nós (EC2) |
| ***AWS Trusted Advisor***             | Conselheiro para recomendações de melhores práticas   |
| ***AWS Well-Architected Tool***       | Pilares para avaliar e otimizar workloads             |

### ✈️ Migração e transferência

| Serviço                                 | Resumo                                               |
| --------------------------------------- | ---------------------------------------------------- |
| ***AWS Application Discovery Service*** | Coleta dados sobre uso e configurações de serviços   |
| ***AWS Application Migration Service*** | Migração de aplicações on-premise para a nuvem       |
| ***AWS DMS***                           | Migração de BDs com o mínimo de inatividade          |
| ***Migration Evaluator***               | Insights e otimizações para migrar para a AWS        |
| ***AWS Migration Hub***                 | Descoberta, planos e status centralizados            |
| ***AWS SCT***                           | Migração de BDs com conversão de Schemas             |
| ***AWS Snow Family***                   | Dispositivos para migração em alta escala ou offline |

### 🌐 Redes e entrega de conteúdo

| Serviço                      | Resumo                                                     |
| ---------------------------- | ---------------------------------------------------------- |
| ***Amazon API Gateway***     | Gerenciamento e proteção de APIs em escala                 |
| ***Amazon CloudFront***      | Acelera a entrega de conteúdo usando locais de borda (CDN) |
| ***AWS Direct Connect***     | Conexão dedicada entre redes on-premise e a AWS            |
| ***AWS Global Accelerator*** | Disponibilização de aplicações à nível global na nuvem     |
| ***AWS PrivateLink***        | Conectividade privada VPCs e serviços AWS (Endpoints)      |
| ***Amazon Route 53***        | Registro e tradução de nomes/domínios (DNS)                |
| ***AWS Transit Gateway***    | Roteador de nuvem (entre VPCs, contas AWS e on-premise)    |
| ***Amazon VPC***             | Rede privada virtual, logicamente isolada                  |
| ***AWS Site-to-Site VPN***   | Conexão segura entre a AWS e redes on-premise              |

> [!TIP]
> **AWS Direct Connect x AWS Site-to-Site VPN**:
> - O Direct Connect corresponde à uma conexão dedicada (imagine um "cabo/fio") entre uma rede on-premise e a AWS, **aumentando a performance** por não utilizar a Internet pública (sem risco de latência ou gargalos);
> - Já o Site-to-Site VPN cria uma **conexão que CONTINUA passando pela Internet pública**, mas de forma segura através de **tunelamento e criptografia**. Sendo assim, NÃO possui a capacidade por si só de melhorar a performance.

### 🔐 Segurança, identidade e conformidade

| Serviço                               | Resumo                                                   |
| ------------------------------------- | -------------------------------------------------------- |
| ***AWS Artifact***                    | Relatórios de conformidade e segurança sob demanda       |
| ***AWS Audit Manager***               | Auditar e coletar provas de uso da AWS                   |
| ***AWS ACM***                         | Gerenciar certificados SSL/TLS de forma simplificada     |
| ***AWS CloudHSM***                    | Chaves criptográficas em Hardware (padrão FIPS)          |
| ***Amazon Cognito***                  | Plataforma de identidade (login) para aplicações         |
| ***Amazon Detective***                | Auxiliar para investigação de causa raiz                 |
| ***AWS Directory Service***           | Integração de workloads com Active Directory (AD)        |
| ***AWS Firewall Manager***            | Configurações centralizadas de Firewall entre contas     |
| ***Amazon GuardDuty***                | Detecção/monitoramento de atividades e ameaças           |
| ***AWS IAM***                         | Controle de identidade e acesso na AWS                   |
| ***Centro de Identidade do AWS IAM*** | Login único (SSO) para contas AWS e aplicações SaaS      |
| ***Amazon Inspector***                | Descoberta de vulnerabilidades em EC2, imagens e funções |
| ***AWS KMS***                         | Chaves criptográficas integradas aos serviços da AWS     |
| ***Amazon Macie***                    | Descobrir e proteger dados sensíveis (Ex: S3)            |
| ***AWS RAM***                         | Compartilhamento de recursos entre contas da nuvem       |
| ***AWS Secrets Manager***             | Gerenciamento de segredos (senhas, chaves de API, etc)   |
| ***AWS Security Hub***                | Visibilidade centralizada de segurança                   |
| ***AWS Shield***                      | Proteção de serviços contra ataques de DDoS              |
| ***AWS WAF***                         | Firewall de Aplicação (SQL Injection, XSS, etc)          |

> [!TIP]
> **Amazon GuardDuty x Inspector x Detective**:
> - O GuardDuty possui a função de **MONITORAR**, alertando caso encontre alguma **ameaça ou atividade suspeita ocorrendo em tempo real** através dos logs do CloudTrail, VPC Flow Logs, etc;
> - Já o inspector possui o objetivo de **ESCANEAR** recursos como EC2, imagens do ECR e funções Lambda, **buscando vulnerabilidades ANTES que sejam exploradas** (pacotes desatualizados, portas abertas, etc);
> - Por fim, o Detective funciona como um **ajudante de INVESTIGAÇÃO** para entender a causa raiz ou impacto de um **incidente que JÁ OCORREU** (alertado pelo GuardDuty, por exemplo).

### 😎 Tecnologia sem servidor

| Serviço           | Resumo                                              |
| ----------------- | --------------------------------------------------- |
| ***AWS Fargate*** | Mecanismo de computação para containers (ECS e EKS) |
| ***AWS Lambda***  | Execução de código (Função) baseado em eventos      |

### 💾 Armazenamento

| Serviço                             | Resumo                                                    |
| ----------------------------------- | --------------------------------------------------------- |
| ***AWS Backup***                    | Gerenciamento de backups de forma centralizada            |
| ***Amazon EBS***                    | Volumes de armazenamento para instâncias EC2 (Blocos)     |
| ***Amazon EFS***                    | Sistema de arquivos compatível com NFS                    |
| ***AWS Elastic Disaster Recovery*** | Recuperação escalável e econômica de aplicações (DR)      |
| ***Amazon FSx***                    | Sistema de arquivos especializado em alto desempenho      |
| ***Amazon S3***                     | Armazenamento de objetos em Buckets (HTTPS)               |
| ***Amazon S3 Glacier***             | Armazenamento de baixo custo para arquivamento e backups  |
| ***AWS Storage Gateway***           | Conecta on-premise com armazenamento "ilimitado" na nuvem |

## 📚 Materiais Oficiais

Para finalizar, os links listados abaixo correspondem à **materiais e recursos oficiais da Amazon Web Services (AWS)** sobre a certificação e assuntos relacionados:

- [Página da Certificação](https://aws.amazon.com/pt/certification/certified-cloud-practitioner/)
- [Guia do Exame](https://docs.aws.amazon.com/pt_br/aws-certification/latest/cloud-practitioner-02/cloud-practitioner-02.html)
- [Fundamentos da Nuvem AWS](https://aws.amazon.com/pt/getting-started/cloud-essentials/)
- [Glossário da AWS](https://docs.aws.amazon.com/pt_br/glossary/latest/reference/glos-chap.html)
- [AWS Cloud Adoption Framework (CAF)](https://d1.awsstatic.com/whitepapers/pt_BR/aws-cloud-adoption-framework_pt-BR.pdf)