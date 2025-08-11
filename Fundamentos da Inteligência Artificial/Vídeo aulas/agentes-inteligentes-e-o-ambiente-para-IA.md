# Agentes Inteligentes e Ambiente para IA

## 1. Conceito de Agente
- **Agente**: Vem do verbo *agir*, representando uma entidade capaz de realizar ações em um ambiente.
- **Agente Inteligente**: Deve ser capaz de agir de forma **autônoma**, tomando decisões sem intervenção externa.
- **Agente Racional**: Não apenas toma decisões, mas **toma a melhor decisão possível** para alcançar seus objetivos.

---

## 2. Teste de Turing
- Criado em **1950** por **Alan Turing**.
- Consiste em uma sequência de perguntas feitas tanto para uma máquina quanto para um humano.
- O avaliador deve determinar qual resposta foi dada por um humano e qual foi dada por uma máquina.
- Se a máquina enganar o avaliador com sucesso, é considerada "inteligente".

---

## 3. Tipos de Agentes

### 3.1 Agente Reativo Simples
- Baseia-se em **regras fixas**.
- Reage apenas aos estímulos atuais do ambiente.
- Não possui memória de eventos passados.

### 3.2 Agente Reativo Baseado em Modelo
- Similar ao reativo simples, mas **mantém informações** sobre estados passados.
- Usa um **modelo interno** do mundo para tomar decisões mais informadas.

---

## 4. O Papel do Ambiente
- O **ambiente** fornece **estímulos** (percepções) para o agente tomar decisões.
- As características do ambiente influenciam diretamente no comportamento do agente.

---

## 5. Tipos de Ambientes

### 5.1 Determinístico
- O próximo estado do ambiente é **totalmente previsível** a partir do estado atual e da ação do agente.
- **Estático**: Só muda quando o agente atua sobre ele.

### 5.2 Estocástico
- Não é possível prever exatamente o que vai acontecer.
- Depende de **fatores aleatórios**.

### 5.3 Episódico
- Cada ação é **independente** e não afeta ações futuras.
- O agente não precisa considerar o histórico de ações.

### 5.4 Estático, Dinâmico e Semi-Estático
- **Estático**: O ambiente só muda quando o agente age.
- **Semi-Estático**: O ambiente muda com o tempo, mesmo sem ação do agente.
- **Dinâmico**: O ambiente muda continuamente e rapidamente.

### 5.5 Discreto vs. Contínuo
- **Discreto**: O tempo e as percepções são divididos em etapas (turnos).
- **Contínuo**: O agente toma decisões de forma **ininterrupta**.

---

## 6. Grau de Observabilidade do Ambiente
- **Não Observável**: O agente não tem acesso a nenhuma informação direta do ambiente. Baseia-se apenas em pressupostos.
- **Parcialmente Observável**: O agente possui informações limitadas sobre o ambiente.
- **Totalmente Observável**: O agente tem acesso a **todas as informações relevantes** do ambiente.

---

## 7. Multiagentes
- **Sistemas Multiagentes**: Vários agentes atuando simultaneamente, de forma **autônoma** e **individual**, mas interagindo entre si.
- Podem cooperar, competir ou coexistir no mesmo ambiente.

---

## 📌 Resumo Visual

| Tipo de Agente                   | Característica Principal |
|----------------------------------|--------------------------|
| Reativo Simples                  | Reage com base em regras fixas. |
| Reativo Baseado em Modelo        | Usa histórico e modelo interno para decisões. |

| Tipo de Ambiente      | Característica |
|-----------------------|----------------|
| Determinístico        | Previsível. |
| Estocástico           | Aleatório. |
| Episódico             | Ações independentes. |
| Estático              | Só muda com ação do agente. |
| Semi-Estático         | Muda com o tempo. |
| Dinâmico              | Muda constantemente. |
| Discreto              | Dividido em etapas. |
| Contínuo              | Fluxo constante. |

| Grau de Observabilidade | Característica |
|-------------------------|----------------|
| Não Observável          | Sem informações diretas. |
| Parcialmente Observável | Visão parcial do ambiente. |
| Totalmente Observável   | Todas as informações disponíveis. |