# 🧭 Guia Modelo para Construção de um Projeto de Software
**Baseado nos pilares do "Guia Dev"**  
📄 *Formato bilíngue: Português / English*  
🔁 *Iterativo e adaptável conforme o projeto*

---

## 🏢 Pilar 1: Negócio / Business
**Objetivo:** Entender o problema, definir escopo e alinhar valor entregue.

### 🔍 Perguntas e Respostas Exemplares

- **Qual é a necessidade de negócio que o software deve resolver?**  
  *What is the core business need the software must address?*  
  ✅ Exemplo: “Reduzir o tempo de atendimento ao cliente em 30%.”  
  ✅ Example: “Reduce customer service response time by 30%.”


- **Quem são os usuários-alvo e quais suas dores?**  
  *Who are the target users and what are their pain points?*  
  ✅ Exemplo: “Gerentes de loja que precisam acompanhar vendas em tempo real.”  
  ✅ Example: “Store managers who need real-time sales tracking.”


- **Quais funcionalidades são essenciais nesta versão?**  
  *Which features are essential in this release?*  
  ✅ Exemplo: “Dashboard de vendas, alertas de estoque, login seguro.”  
  ✅ Example: “Sales dashboard, stock alerts, secure login.”


### 💡 Recomendações
- Use técnicas como *Lean Inception*, *Design Thinking* ou *Event Storming*.
- Documente as *personas* e *user journeys*.

---

## 🏗️ Pilar 2: Arquitetura de Software / Software Architecture
**Objetivo:** Definir a estrutura técnica que sustenta o produto.

### 🔍 Perguntas e Respostas Exemplares

- **Qual padrão arquitetural será adotado?**  
  *Which architectural pattern will be adopted?*  
  ✅ Exemplo: “Arquitetura Hexagonal com DDD.”  
  ✅ Example: “Hexagonal Architecture with DDD.”


- **Como será feita a persistência de dados?**  
  *How will data persistence be handled?*  
  ✅ Exemplo: “PostgreSQL com repositórios desacoplados.”  
  ✅ Example: “PostgreSQL with decoupled repositories.”


- **Como será tratada a escalabilidade?**  
  *How will scalability be addressed?*  
  ✅ Exemplo: “Uso de microsserviços com balanceamento de carga.”  
  ✅ Example: “Use of microservices with load balancing.”

### 💡 Recomendações
- Documente decisões com *ADR (Architecture Decision Records)*.
- Use ferramentas como *C4 Model* para visualização.

---

## 🧰 Pilar 3: Linguagens e Ferramentas / Languages and Tools
**Objetivo:** Escolher tecnologias que suportem a arquitetura.

### 🔍 Perguntas e Respostas Exemplares

- **Qual linguagem será usada no backend?**  
  *Which language will be used for the backend?*  
  ✅ Exemplo: “Kotlin por sua compatibilidade com arquitetura reativa.”  
  ✅ Example: “Kotlin for its compatibility with reactive architecture.”


- **Quais ferramentas de testes serão utilizadas?**  
  *Which testing tools will be used?*  
  ✅ Exemplo: “JUnit, Mockito e Cypress.”  
  ✅ Example: “JUnit, Mockito, and Cypress.”

### 💡 Recomendações
- Priorize ferramentas que tenham boa comunidade e suporte.
- Evite decisões baseadas apenas em familiaridade da equipe.

---

## 💻 Pilar 4: Código Fonte / Source Code
**Objetivo:** Garantir qualidade, legibilidade e testabilidade do código.

### 🔍 Perguntas e Respostas Exemplares

- **Quais práticas de código limpo serão adotadas?**  
  *Which clean code practices will be adopted?*  
  ✅ Exemplo: “Métodos curtos, nomes significativos, SRP.”  
  ✅ Example: “Short methods, meaningful names, SRP.”


- **Como será feita a revisão de código?**  
  *How will code review be conducted?*  
  ✅ Exemplo: “Via Pull Requests com checklist de qualidade.”  
  ✅ Example: “Via Pull Requests with quality checklist.”

### 💡 Recomendações
- Use *linters* e *análise estática* (ex: SonarQube).
- Adote *TDD* sempre que possível.

---

## 🔄 Pilar 5: Integração Contínua / Continuous Integration
**Objetivo:** Automatizar testes e validações a cada mudança de código.

### 🔍 Perguntas e Respostas Exemplares

- **Qual ferramenta de CI será usada?**  
  *Which CI tool will be used?*  
  ✅ Exemplo: “GitHub Actions com pipeline YAML.”  
  ✅ Example: “GitHub Actions with YAML pipeline.”


- **Quais testes serão executados na pipeline?**  
  *Which tests will run in the pipeline?*  
  ✅ Exemplo: “Testes unitários, de integração e cobertura.”  
  ✅ Example: “Unit, integration, and coverage tests.”

### 💡 Recomendações
- Configure *builds rápidos* e *feedback contínuo*.
- Use *badges* de qualidade no repositório.

---

## 🚀 Pilar 6: Entrega Contínua / Continuous Delivery
**Objetivo:** Automatizar deploys e garantir entregas frequentes e seguras.

### 🔍 Perguntas e Respostas Exemplares

- **Qual será a estratégia de deploy?**  
  *What will be the deployment strategy?*  
  ✅ Exemplo: “Blue/Green para minimizar downtime.”  
  ✅ Example: “Blue/Green to minimize downtime.”


- **Como será feito o versionamento?**  
  *How will versioning be handled?*  
  ✅ Exemplo: “SemVer com changelog automatizado.”  
  ✅ Example: “SemVer with automated changelog.”

### 💡 Recomendações
- Use *feature flags* para controle de funcionalidades.
- Automatize rollback em caso de falha.

---

## 👥 Pilar 7: Pessoas / People
**Objetivo:** Engajar e desenvolver o time para garantir sucesso contínuo.

### 🔍 Perguntas e Respostas Exemplares

- **Como será promovido o desenvolvimento do time?**  
  *How will team development be promoted?*  
  ✅ Exemplo: “Mentorias semanais e plano de carreira.”  
  ✅ Example: “Weekly mentoring and career plan.”


- **Como será garantido o alinhamento entre áreas?**  
  *How will alignment between areas be ensured?*  
  ✅ Exemplo: “Rituais de sincronização e reuniões de descoberta.”  
  ✅ Example: “Sync rituals and discovery meetings.”

### 💡 Recomendações
- Invista em *soft skills* e *feedback contínuo*.
- Promova *diversidade* e *segurança psicológica*.

---

