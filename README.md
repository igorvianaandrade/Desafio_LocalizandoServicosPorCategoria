# Microsoft Azure: Serviços por Categoria

Este repositório serve como um guia de referência rápida para navegar no vasto ecossistema do **Microsoft Azure**. O objetivo é ajudar desenvolvedores e arquitetos a localizarem o serviço ideal com base na necessidade técnica ou de negócio.

## 📌 Sumário

* Computação
* Redes
* Armazenamento
* Bancos de Dados
* Inteligência Artificial e Machine Learning
* DevOps e Governança

---

## 💻 Computação

Serviços para hospedar aplicações, executar código e gerenciar containers.

| Serviço | Descrição | Caso de Uso |
| --- | --- | --- |
| **Virtual Machines** | Máquinas virtuais sob demanda. | Infraestrutura como Serviço (IaaS). |
| **App Service** | Plataforma para hospedagem de aplicações web e APIs. | Web Apps, Mobile Backends. |
| **Azure Functions** | Computação serverless baseada em eventos. | Microserviços, automação. |
| **AKS (Kubernetes)** | Gerenciamento de clusters Kubernetes. | Orquestração de containers em escala. |

## 🌐 Redes

Conectividade segura entre seus recursos e o mundo externo.

* **Virtual Network (VNet):** Isolamento de rede e segmentação.
* **Azure ExpressRoute:** Conexão privada entre o on-premises e o Azure.
* **Application Gateway:** Balanceador de carga de camada 7 com WAF.
* **Azure Front Door:** CDN moderna e segura para entrega global de conteúdo.

## 🗄️ Armazenamento

Soluções escaláveis para dados estruturados e não estruturados.

* **Blob Storage:** Armazenamento de objetos (imagens, vídeos, backups).
* **Azure Files:** Compartilhamentos de arquivos gerenciados em nuvem (SMB/NFS).
* **Disk Storage:** Discos persistentes para VMs.

## 📊 Bancos de Dados

Armazenamento gerenciado para diversos formatos de dados.

1. **Relacional:** Azure SQL Database, MySQL, PostgreSQL.
2. **Não-Relacional (NoSQL):** **Azure Cosmos DB** (distribuição global e baixa latência).
3. **Cache:** Azure Cache for Redis.

## 🤖 IA e ML

Ferramentas para integrar inteligência artificial em suas soluções.

* **Azure OpenAI:** Acesso aos modelos GPT e DALL-E.
* **Azure AI Search:** Recuperação de informações e busca inteligente.
* **Machine Learning Studio:** Ciclo de vida completo para cientistas de dados.

## ☁️ Fundamentos da Nuvem Azure (AZ-900)

### O que é Computação em Nuvem?

A computação em nuvem é o fornecimento de serviços de computação — incluindo servidores, armazenamento, bancos de dados, rede, software e análise — pela Internet (“a nuvem”) para oferecer inovação mais rápida, recursos flexíveis e economias de escala.

### Modelo de Responsabilidade Compartilhada

Na nuvem, a segurança e a gestão são uma via de mão dupla. A divisão de tarefas depende de onde o serviço se hospeda:

* **SaaS (Software como Serviço):** O provedor (Microsoft) gerencia quase tudo.
* **PaaS (Plataforma como Serviço):** Você foca no código e nos dados; o Azure cuida do SO e hardware.
* **IaaS (Infraestrutura como Serviço):** Você gerencia o SO e as aplicações; o Azure cuida da infraestrutura física.

---

## 🏗️ Modelos de Nuvem

| Modelo | Descrição | Casos de Uso Apropriados |
| --- | --- | --- |
| **Pública** | Recursos de propriedade de um provedor de serviços de nuvem de terceiros. | Startups, aplicações web de escala rápida, e-commerce. |
| **Privada** | Recursos usados exclusivamente por uma única organização. | Órgãos governamentais, dados altamente sensíveis, legado físico. |
| **Híbrida** | Combina nuvens públicas e privadas, permitindo que dados e apps sejam compartilhados entre elas. | Transição gradual para a nuvem, conformidade de dados locais. |

---

## 💰 Modelos Econômicos e de Preços

### Modelo Baseado no Consumo

Diferente do modelo tradicional de TI, no Azure você não paga por recursos ociosos.

* **Sem custos iniciais:** Não é necessário comprar hardware caro.
* **Pagamento pelo uso:** Você é cobrado apenas pelo que consome (minutos, GBs, requisições).
* **Escalabilidade:** Capacidade de interromper o pagamento por recursos que não são mais necessários.

### Comparativo de Preços (CapEx vs. OpEx)

* **CapEx (Gastos de Capital):** É o gasto inicial de fundos em infraestrutura física. O custo é deduzido ao longo do tempo.
* *Exemplo:* Comprar um servidor físico.


* **OpEx (Gastos Operacionais):** É o gasto atual com serviços ou produtos. Você é cobrado imediatamente e pode deduzir o gasto no mesmo ano fiscal.
* *Exemplo:* Assinatura mensal do Azure.
---

## Cursos Microsoft - AZURE AZ 900

# Introdução à Infraestrutura de Nuvem - Descrever conceitos de nuvem:
https://learn.microsoft.com/pt-br/training/paths/microsoft-azure-fundamentals-describe-cloud-concepts/
