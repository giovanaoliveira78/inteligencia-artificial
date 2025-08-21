# Teoria da Decisão e Tratamento de Incertezas em IA

## 1. Teoria da Decisão
A **teoria da decisão** trata da escolha de ações em cenários com múltiplas alternativas, levando em conta probabilidades, consequências e preferências.  

- **Objetivo:** maximizar a utilidade esperada (ou algum critério de desempenho).  
- **Componentes principais:**
  - **Estados do mundo:** situações possíveis em que a IA pode se encontrar.  
  - **Ações:** opções que o agente pode executar.  
  - **Função de utilidade:** mede a “qualidade” de resultados possíveis.  
  - **Modelo probabilístico:** avalia incertezas nos efeitos das ações.  

---

## 2. Tratamento das Incertezas
A incerteza surge porque o agente **não tem controle completo sobre o mundo** ou não sabe todas as informações.  

### Estratégias para lidar com incerteza:
1. **Probabilística:** atribuir probabilidades aos eventos e calcular utilidade esperada.  
2. **Não determinística:** considerar múltiplos futuros possíveis e planejar contingências.  
3. **Heurística:** usar regras aproximadas quando cálculos precisos são inviáveis.  

**Exemplo prático:** Um carro autônomo decide se deve frear com base na probabilidade de outro carro cruzar seu caminho.

---

## 3. Tempo como variável em IA
O tempo é **crítico** para decisões:

- Algumas ações têm **efeito imediato**, outras impactam o futuro.  
- Planejamento deve considerar **sequência temporal de ações** (como em planejamento de tarefas ou jogos).  

### Tratamento do tempo:
- **Escalonamento antes da estratégia:** organizar ações e prioridades antes de decidir a estratégia global.  
- **Ações interdependentes em cada camada:** decisões em nível alto afetam ações primitivas, e vice-versa.  

---

## 4. Ações em IA (Russell & Norvig)
- **Ações primitivas:** indivisíveis, executáveis diretamente pelo agente.  
- **Ações de alto nível:** compostas de várias ações primitivas (ex.: “fazer café” → ligar cafeteira, adicionar água, colocar pó).  

---

## 5. Crenças e conhecimento no sistema
- **Crenças programadas:** informações que o sistema assume como verdade para decidir.  
- Permitem **inferir consequências** e **planejar sob incerteza**.  
- **Exemplo:** se o agente acredita que “a porta está fechada”, ele planeja abrir a porta antes de entrar.

---

## 6. Estratégias-chave
- Identificação de **itens-chave** ou **raiz:** decisões que impactam múltiplos níveis de ação.  
- Separação de **níveis de abstração:**
  - **Alto nível:** planejamento estratégico.  
  - **Baixo nível:** execução de ações concretas.  
- **Planejamento hierárquico** facilita lidar com incertezas e interdependências.

---

## 7. Como lidar com incertezas
1. Modelar probabilidades de eventos e resultados.  
2. Avaliar a utilidade esperada de cada ação.  
3. Planejar contingências e alternativas.  
4. Atualizar crenças conforme novas informações chegam (aprendizado online).