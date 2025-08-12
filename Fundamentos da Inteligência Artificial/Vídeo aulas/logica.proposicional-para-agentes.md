# Lógica Proposicional para Agentes

A **lógica proposicional** é um ramo da lógica que trabalha com proposições — sentenças que podem ser **verdadeiras** ou **falsas**. Ela é muito usada em **inteligência artificial** para que agentes possam **tomar decisões baseadas em conhecimento lógico**.

---

## Diferença entre Sintaxe e Semântica

- **Sintaxe**  
  É a **forma** como escrevemos expressões lógicas, seguindo regras formais.  
  Exemplo: `(P ∧ Q) → ¬R`

- **Semântica**  
  É o **significado** ou interpretação da expressão.  
  Exemplo: `P` = "Está chovendo", `Q` = "Tenho guarda-chuva".  
  `(P ∧ Q) → ¬R` significa "Se está chovendo e tenho guarda-chuva, então não vou me molhar".

---

## Tabela Verdade

A **tabela verdade** é usada para verificar o valor lógico (**Verdadeiro** ou **Falso**) de uma proposição composta, dependendo dos valores de suas partes.

| P   | Q   | Operação       | Resultado |
|-----|-----|---------------|-----------|
| V   | V   | P ∧ Q          | V         |
| V   | F   | P ∧ Q          | F         |
| F   | V   | P ∧ Q          | F         |
| F   | F   | P ∧ Q          | F         |

Cada **operador lógico** age de forma diferente sobre as proposições.

---

## Operadores Lógicos

### 1. Operador **NÃO** (Negação) `¬`
- **Função:** Inverte o valor lógico da proposição.  
- **Exemplo:**  
  `P = Verdadeiro`  
  `¬P = Falso`  
- **Tabela verdade:**

| P   | ¬P  |
|-----|-----|
| V   | F   |
| F   | V   |

---

### 2. Operador **E** (Conjunção) `∧`
- **Função:** Só é verdadeiro se **ambas** as proposições forem verdadeiras.  
- **Exemplo:**  
  `P = "Tenho dinheiro"`  
  `Q = "A loja está aberta"`  
  `P ∧ Q` = "Posso comprar algo".
- **Tabela verdade:**

| P   | Q   | P ∧ Q |
|-----|-----|-------|
| V   | V   | V     |
| V   | F   | F     |
| F   | V   | F     |
| F   | F   | F     |

---

### 3. Operador **OU** (Disjunção) `∨`
- **Função:** É verdadeiro se **pelo menos uma** proposição for verdadeira.  
- **Exemplo:**  
  `P = "Tenho café"`  
  `Q = "Tenho chá"`  
  `P ∨ Q` = "Tenho algo para beber".
- **Tabela verdade:**

| P   | Q   | P ∨ Q |
|-----|-----|-------|
| V   | V   | V     |
| V   | F   | V     |
| F   | V   | V     |
| F   | F   | F     |

---

## Como isso se aplica para agentes inteligentes

- Os **agentes inteligentes** podem usar lógica proposicional para **decidir ações** baseadas em fatos do ambiente.
- Exemplo prático:  
  Se `EstáChovendo ∧ TenhoGuardaChuva` → `PossoSair`
- Isso ajuda a criar **regras de decisão** formais e previsíveis.

---

💡 **Resumo rápido:**
- Sintaxe = forma.
- Semântica = sentido.
- `¬` = negação (inverte).
- `∧` = E (só V se ambos forem V).
- `∨` = OU (V se pelo menos um for V).
- Tabela verdade ajuda a entender todas as combinações possíveis.