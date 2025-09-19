# AwsFoundations
💡 Este repositório é parte da minha jornada de estudos em Cloud Computing e AWS.
Materiais, anotações e exercícios sobre AWS Foundations, cobrindo os principais conceitos de computação em nuvem, serviços essenciais da AWS e boas práticas.

## 📌 Estrutura do Repositório
- **Dicas** → Recursos extras de estudo e boas práticas.  
- **Módulo 1** → Introdução à AWS, infraestrutura global, modelo de negócios e primeiros passos.  
- **Amazon EC2** → Estudo sobre instâncias, famílias de máquinas e gerenciamento.  
- **Diagramas** → Arquivos visuais feitos com [draw.io](https://www.drawio.com/).  

---

## 📝 Anotações

**Caderno de estudos:** [Notion](https://www.notion.so/Santander-Code-Girls-2621fec5a7ae80e9a3fed1bb77c02fdf?pvs=21)
### 🔹 Dicas
- **Artigos/Fórum:** Compartilhar conteúdos técnicos através de [Artigos da DIO](https://web.dio.me/articles) ou tirar dúvidas nos Fóruns.  
- **Pesquisa:** Use buscadores como complemento para entender conceitos, erros e exemplos de aplicação.  

---

### 🔹 Introdução à AWS e Conceitos Básicos
- **Visão geral da AWS**: história, infraestrutura global e modelo de negócios.  
- **Conceitos fundamentais**: regiões, zonas de disponibilidade, serviços gerenciados.  
- **Configuração da conta AWS e práticas de segurança.**  

#### 🌍 Infraestrutura Global
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
