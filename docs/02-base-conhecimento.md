# 📊 Base de Conhecimento do Agente

## 📌 Visão Geral

A base de conhecimento do agente financeiro foi construída com dados simulados, permitindo respostas mais consistentes, seguras e contextualizadas.

Esses dados ajudam o agente a entender o comportamento financeiro do usuário e oferecer orientações mais personalizadas, aproximando a experiência de um atendimento real.

---

## 📁 Fontes de Dados

### 1. Transações Financeiras (`transacoes.csv`)

Contém o histórico financeiro do usuário.

**Principais informações:**
- Data
- Tipo (entrada/saída)
- Categoria (alimentação, transporte, etc.)
- Valor

👉 Como o agente usa:
- Identifica padrões de gastos
- Calcula totais mensais
- Responde perguntas como:
  - "Com o que eu mais gasto?"
  - "Quanto gastei esse mês?"

---

### 2. Histórico de Atendimento (`historico_atendimento.csv`)

Registra interações anteriores do usuário com o sistema.

👉 Como o agente usa:
- Mantém consistência nas respostas
- Evita repetir informações
- Melhora a experiência do usuário

---

### 3. Perfil do Investidor (`perfil_investidor.json`)

Define características do usuário:

- Nível de risco
- Objetivos financeiros
- Preferências

👉 Como o agente usa:
- Personaliza recomendações
- Adapta linguagem
- Evita sugestões incompatíveis

---

### 4. Produtos Financeiros (`produtos_financeiros.json`)

Lista produtos disponíveis:

- Empréstimos
- Cartões de crédito
- Investimentos

👉 Como o agente usa:
- Explica produtos
- Sugere opções adequadas ao perfil
- Apoia decisões financeiras

---

## 🧠 Estratégia de Uso dos Dados

O agente combina diferentes fontes para gerar respostas mais completas:

- Analisa transações para entender comportamento financeiro
- Utiliza o perfil para personalizar respostas
- Consulta produtos para sugerir soluções
- Considera histórico para manter contexto

Essa integração permite respostas mais inteligentes e próximas de um atendimento consultivo.

---

## 🔒 Segurança dos Dados

- Todos os dados utilizados são simulados
- Nenhuma informação sensível é coletada ou armazenada
- O agente não realiza operações financeiras reais
- Uso exclusivo para fins educativos e demonstrativos

---

## ⚠️ Limitações

- Dados não refletem cenários reais completos
- Não há atualização em tempo real
- Análises são simplificadas
- Não substitui sistemas financeiros reais
