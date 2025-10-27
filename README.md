# AwsFoundations
💡 Este repositório é parte da minha jornada de estudos em Cloud Computing e AWS.
Materiais, anotações e exercícios sobre AWS Foundations, cobrindo os principais conceitos de computação em nuvem, serviços essenciais da AWS e boas práticas.
## 📌 Estrutura do Repositório
- **Dicas** → Recursos extras de estudo e boas práticas.  
- **Módulo 1** → Introdução à AWS, infraestrutura global, modelo de negócios e primeiros passos.  
- **Amazon EC2** → Estudo sobre instâncias, famílias de máquinas e gerenciamento.
- **Redes na AWS (VPC, Route 53, CloudFront)** → Conceitos de rede, segurança e distribuição de conteúdo.
- **Bancos de Dados na AWS (RDS, DynamoDB)** → Bancos relacionais e NoSQL, backup e recuperação.
- **Serviços de Armazenamento e CDN (S3, Glacier, CloudFront)** → Armazenamento e entrega de conteúdo global.
- **Serviços Intermediários e Avançados (Lambda, ECS, EKS, SNS, SQS)** → Funções serverless, containers e comunicação assíncrona.
- **Diagramas** → Arquivos visuais feitos com [draw.io](https://www.drawio.com/).  

---

## 📝 Anotações

📒 Todas as anotações detalhadas estão disponíveis no meu [Notion](https://www.notion.so/Santander-Code-Girls-2621fec5a7ae80e9a3fed1bb77c02fdf?pvs=21)

### 🔹 Dicas
- **Artigos/Fórum:** Compartilhar conteúdos técnicos através de [Artigos da DIO](https://web.dio.me/articles) ou tirar dúvidas nos Fóruns.  
- **Pesquisa:** Use buscadores como complemento para entender conceitos, erros e exemplos de aplicação.  

---

### 🔹 Introdução à AWS e Conceitos Básicos
- **Visão geral da AWS**: história, infraestrutura global e modelo de negócios.  
- **Conceitos fundamentais**: regiões, zonas de disponibilidade, serviços gerenciados.  
- **Configuração da conta AWS e práticas de segurança.**  

### 🌍 Infraestrutura Global
- **Regiões** → Áreas geográficas compostas por 2 ou mais zonas de disponibilidade.  
- **Availability Zones (AZs)** → Data centers independentes para alta disponibilidade.  

📌 Pontos importantes na escolha da região:
- Compliance  
- Disponibilidade de serviços  
- Custo  
- Latência  

#### 💰 Modelo de Negócios
- **OPEX** → Pagamento pelo uso, sem grandes investimentos iniciais.  
- **CAPEX** → Investimento em infraestrutura física.  

#### ☁️ Modelos de Computação na Nuvem
- **SaaS** → Software como serviço (E-mail, CRM, ERP).  
- **PaaS** → Plataforma como serviço (Streaming, desenvolvimento, web apps).  
- **IaaS** → Infraestrutura como serviço (Servidores virtuais, sistemas de gestão).  

---

### 🔹 Amazon EC2 (Elastic Compute Cloud)
- Serviço de **máquinas virtuais na nuvem** → exemplo clássico de IaaS.  
- Permite escalar capacidade de forma elástica.  

#### 📂 Famílias de Instâncias EC2
- Diferentes tipos de instâncias para atender a cargas específicas (geral, memória, computação, GPU, etc).  

#### ⚙️ Comandos úteis
```bash
# Configuração inicial do CLI
aws configure

# Listar configurações
aws configure list
```
---

### 🛜 Rede na AWS

- Amazon VPC (Virtual Private Cloud): rede isolada dentro da AWS.
- Subnets: subdivisões da VPC (públicas e privadas).
- Security Groups: controle de tráfego de entrada e saída.
- Route 53: serviço DNS gerenciado para roteamento inteligente.
- Amazon CloudFront: distribuição de conteúdo global (CDN).
- Elastic Load Balancer (ELB): balanceamento de carga entre instâncias EC2.

### 🎲 Banco de Dados na AWS

- Amazon RDS: banco de dados relacional gerenciado (MySQL, PostgreSQL, etc).
- Amazon DynamoDB: banco NoSQL de alta performance.
- Backup e Recuperação: snapshots automáticos e restauração de dados.

### 🗃️ Serviços de Armazenamento e CDN
- Amazon S3: armazenamento de objetos com alta durabilidade.
- Amazon Glacier: armazenamento para arquivamento e backup.
- Amazon CloudFront: aceleração e distribuição de conteúdo global.
- Integração entre serviços: uso de S3, CloudFront e Route 53 para sites estáticos.

### 📨 Serviços Intermediários e Avançados

- AWS Lambda: execução de código sem provisionar servidores (serverless).
- Amazon ECS / EKS: orquestração de containers (Docker e Kubernetes).
- Amazon SNS: envio de notificações em massa.
- Amazon SQS: filas de mensagens para comunicação assíncrona.

### 🏛️ Governança e gerenciamento na AWS

- AWS CloudWatch: Monitoramento de eventos.
- CloudTrail: Auditoria operacional.
- CloudFormation: Automação de recursos.
- AWS IAM: Gestão de acesso.


---

## 🧠 Objetivo
Consolidar o aprendizado dos principais serviços da AWS e criar uma base sólida para certificações como AWS Certified Cloud Practitioner (CLF-C02).
