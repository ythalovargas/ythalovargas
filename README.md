# 👋 Olá, eu sou Ythalo!

Sou **Engenheiro de Software** com foco no desenvolvimento de sistemas escaláveis, APIs robustas e soluções voltadas para negócios.

Minha principal atuação está no ecossistema **Node.js**, especialmente utilizando **NestJS**, construindo aplicações com foco em arquitetura, regras de negócio e escalabilidade.

Atualmente trabalho principalmente com sistemas **SaaS**, **ERP**, integrações e aplicações que possuem regras de negócio complexas.

---

## 🚀 Sobre mim

Gosto de transformar problemas complexos em soluções bem estruturadas.

Tenho experiência e interesse principalmente em:

* 🏢 Sistemas ERP e aplicações corporativas
* ☁️ Arquiteturas SaaS e sistemas Multi-Tenant
* 🔌 Desenvolvimento de APIs REST
* 🧠 Inteligência Artificial aplicada a produtos
* 📊 Sistemas com regras de negócio complexas
* 💰 Módulos financeiros e controle de caixa
* 🛒 PDV e sistemas de vendas
* 🧾 Integrações fiscais
* 🔄 Processamento assíncrono e automações
* 📴 Aplicações com funcionamento Offline-First

---

# 🛠️ Stack Principal

### Backend

![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge\&logo=nestjs\&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge\&logo=node.js\&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge\&logo=typescript\&logoColor=white)

### Banco de Dados

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge\&logo=postgresql\&logoColor=white)

* PostgreSQL
* TypeORM
* Modelagem de banco de dados
* Performance e otimização de queries
* Arquitetura Multi-Tenant

### Outras Tecnologias

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge\&logo=docker\&logoColor=white)

* Docker
* Redis
* APIs REST
* Webhooks
* Filas e Jobs
* Integrações externas
* AWS
* Linux

---

# 🧠 Arquitetura e Engenharia de Software

Busco desenvolver sistemas pensando não apenas na funcionalidade atual, mas também na evolução do produto.

Alguns princípios que fazem parte do meu dia a dia:

```text
✔ SOLID
✔ Clean Architecture
✔ Domain-Driven Design
✔ Rich Domain Model
✔ Separation of Concerns
✔ Código escalável
✔ Regras de negócio bem isoladas
✔ Baixo acoplamento
```

Acredito que uma boa arquitetura deve permitir que o sistema cresça sem transformar cada nova funcionalidade em um problema.

---

# 🏗️ Projetos e Domínios

## 🏢 ERP SaaS

Desenvolvimento de sistemas corporativos com múltiplos módulos e regras de negócio complexas.

Principais desafios:

* Multi-Tenant
* Gestão de empresas
* Financeiro
* Controle de caixa
* PDV
* Configurações fiscais
* Certificados digitais
* Integrações externas

---

## 🛒 PDV Offline-First

Estudo e desenvolvimento de arquiteturas para sistemas de ponto de venda capazes de continuar funcionando mesmo sem conexão com a internet.

Arquitetura envolvendo:

```text
┌─────────────────────┐
│      ERP CLOUD      │
│                     │
│  NestJS + PostgreSQL│
└──────────┬──────────┘
           │
           │ Sincronização
           │
┌──────────▼──────────┐
│      PDV LOCAL      │
│                     │
│     SQLite          │
│                     │
│  Funcionamento      │
│     Offline         │
└─────────────────────┘
```

O foco é permitir operações como:

* Busca de produtos
* Consulta de clientes
* Aplicação de preços
* Registro de vendas
* Controle de pagamentos
* Sincronização posterior com a nuvem

---

## 💰 Sistemas Financeiros

Experiência com modelagem de operações financeiras e controle de movimentações.

Exemplos:

* Abertura de caixa
* Fechamento
* Suprimentos
* Sangrias
* Recebimentos
* Pagamentos
* Ajustes
* Transferências
* Conferência de valores

Sempre buscando manter a integridade das movimentações e rastreabilidade das operações.

---

## 🧾 Integrações Fiscais

Trabalho com arquitetura voltada para centralização de configurações fiscais.

Alguns desafios envolvidos:

* Configuração de documentos fiscais
* Certificados digitais
* NF-e
* NFC-e
* NFSe
* Validações fiscais
* Pendências de emissão
* Configurações por empresa

---

# 🤖 Inteligência Artificial

Tenho grande interesse em **IA aplicada a produtos reais**.

Atualmente exploro arquiteturas utilizando:

* OpenAI
* Embeddings
* PostgreSQL
* pgvector
* RAG
* Decision Engines
* Agentes de IA

Um dos focos é utilizar IA para melhorar processos de atendimento e suporte.

### Exemplos de aplicações:

```text
🎧 Análise de atendimentos

🧠 Classificação automática de problemas

📚 Busca semântica utilizando RAG

⚠️ Identificação de risco de churn

📊 Análise da saúde de clientes

🤖 Triagem inteligente de suporte
```

Meu interesse está principalmente em utilizar IA como parte da arquitetura do produto — e não apenas como um chatbot.

---

# 🎯 Minha Forma de Desenvolver

Quando penso em uma solução, normalmente tento olhar além da implementação imediata.

Algumas perguntas que costumo considerar:

```text
Isso escala?

Como essa funcionalidade vai evoluir?

Essa regra está no lugar certo?

Como evitar acoplamento?

O que acontece se o sistema ficar offline?

Como garantir integridade dos dados?

Como isso impacta outros módulos?

Como facilitar manutenção futura?
```

Acredito que desenvolvimento de software não é apenas escrever código.

É entender o problema, modelar corretamente o domínio e construir uma solução que continue fazendo sentido quando o sistema crescer.

---

# 📚 Atualmente Explorando

* Arquiteturas Multi-Tenant
* Sistemas Offline-First
* Inteligência Artificial aplicada a SaaS
* RAG
* Agentes inteligentes
* Decision Engines
* Arquiteturas escaláveis com NestJS
* PostgreSQL avançado
* Sistemas distribuídos

---

# 💻 Tecnologias que mais utilizo

```typescript
const stack = {
  backend: [
    "Node.js",
    "NestJS",
    "TypeScript",
    "PHP",
    "Laravel"
  ],

  database: [
    "PostgreSQL",
    "MySQL",
    "SQLite",
    "TypeORM",
  ],

  architecture: [
    "SOLID",
    "DDD",
    "Clean Architecture",
    "Rich Domain Model",
  ],

  infrastructure: [
    "Docker",
    "AWS",
    "Linux",
  ],

  ai: [
    "OpenAI",
    "Embeddings",
    "RAG",
    "pgvector",
    "Decision Engines",
  ],
};
```

---

# 📫 Vamos conversar?

Estou sempre interessado em discutir:

* Arquitetura de Software
* NestJS
* SaaS
* ERP
* PostgreSQL
* Sistemas Multi-Tenant
* IA aplicada a produtos
* Sistemas Offline-First

---

> **"Código resolve problemas de hoje. Arquitetura resolve os problemas que ainda não chegaram."**
