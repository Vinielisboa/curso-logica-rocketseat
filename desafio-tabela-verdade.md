# Desafio Prático: Conectivos e Tabela Verdade

1. **Eu estudei para a prova e fiz todos os exercícios.**
- **Proposições:**
    - **p:** Eu estudei para a prova.
    - **q:** Eu fiz todos os exercícios.
- **Conectivo:** E
- **Representação Lógica:** p ∧ q

| **p** | **q** | **p ∧ q** |
| --- | --- | --- |
| V | V | 🟢 **V** |
| V | F | **F** |
| F | V | **F** |
| F | F | **F** |
1. **Eu vou ao cinema ou fico em casa assistindo séries.**
- **Proposições:**
    - **p:** Eu vou ao cinema.
    - **q:** Fico em casa assistindo séries.
- **Conectivo:** OU
- **Representação Lógica:** p ∨ q

| **p** | **q** | **p ∨ q** |
| --- | --- | --- |
| V | V | 🟢 **V** |
| V | F | 🟢 **V** |
| F | V | 🟢 **V** |
| F | F | **F** |
1. **Se eu acordar cedo, então conseguirei pegar o ônibus.**
- **Proposições:**
    - **p:** Eu acordar cedo.
    - **q:** Conseguirei pegar o ônibus.
- **Conectivo:** SE... ENTÃO
- **Representação Lógica:** p → q

| **p** | **q** | **p → q** |
| --- | --- | --- |
| V | V | 🟢 **V** |
| V | F | **F** |
| F | V | 🟢 **V** |
| F | F | 🟢 **V** |
1. **Se eu estudar muito, então passarei na prova e ganharei um presente.**
- **Proposições:**
    - **p:** Eu estudar muito.
    - **q:** Passarei na prova.
    - **r:** Ganharei um presente.
- **Conectivos:** SE... ENTÃO e E
- **Representação Lógica:** p → (q ∧ r)

| **p** | **q** | **r** | **q ∧ r** |  |
| --- | --- | --- | --- | --- |
| V | V | V |  🟢 V |  |
| V | V | F | F |  |
| V | F | V | F |  |
| V | F | F | F |  |
| F | V | V | 🟢 V |  |
| F | V | F | F |  |
| F | F | V | F |  |
| F | F | F | F |  |
1. **Eu vou jogar videogame ou vou estudar lógica de programação.**
- **Proposições:**
    - **p:** Eu vou jogar videogame.
    - **q:** Vou estudar lógica de programação.
- **Conectivo:** OU
- **Representação Lógica:** p ∨ q

| **p** | **q** | **p ∨ q** |
| --- | --- | --- |
| V | V | 🟢 **V** |
| V | F | 🟢 **V** |
| F | V | 🟢 **V** |
| F | F | **F** |
1. **Eu comi pizza e tomei refrigerante.**
- **Proposições:**
    - **p:** Eu comi pizza.
    - **q:** Tomei refrigerante.
- **Conectivo:** E
- **Representação Lógica:** p ∧ q

| **p** | **q** | **p ∧ q** |
| --- | --- | --- |
| V | V | 🟢 **V** |
| V | F | **F** |
| F | V | **F** |
| F | F | **F** |
1. **Se eu tiver dinheiro, então viajarei nas férias.**
- **Proposições:**
    - **p:** Eu tiver dinheiro.
    - **q:** Viajarei nas férias.
- **Conectivo:** SE... ENTÃO
- **Representação Lógica:** p → q

| **p** | **q** | **p → q** |
| --- | --- | --- |
| V | V | 🟢 **V** |
| V | F | **F** |
| F | V | 🟢 **V** |
| F | F | 🟢 **V** |
1. **Eu lerei um livro se e somente se terminar meu trabalho.**
- **Proposições:**
    - **p:** Eu lerei um livro.
    - **q:** Terminar meu trabalho.
- **Conectivo:** SE E SOMENTE SE
- **Representação Lógica:** p ↔ q

| **p** | **q** | **p ↔ q** |
| --- | --- | --- |
| V | V | 🟢 **V** |
| V | F | **F** |
| F | V | **F** |
| F | F | 🟢 **V** |
1. **Se estiver sol, então irei à praia ou ao parque.**
- **Proposições:**
    - **p:** Estiver sol.
    - **q:** Irei à praia.
    - **r:** Irei ao parque.
- **Conectivos:** SE... ENTÃO e OU
- **Representação Lógica:** p → (q ∨ r)

| **p** | **q** | **r** | **q ∨ r** | **p → (q ∨ r)** |
| --- | --- | --- | --- | --- |
| V | V | V | 🟢 V | 🟢 **V** |
| V | V | F | 🟢 V | 🟢 **V** |
| V | F | V | 🟢 V | 🟢 **V** |
| V | F | F | F | **F** |
| F | V | V | 🟢 V | 🟢 **V** |
| F | V | F | 🟢 V | 🟢 **V** |
| F | F | V | 🟢 V | 🟢 **V** |
| F | F | F | F | 🟢 **V** |
1. **Eu farei um bolo se e somente se comprar os ingredientes.**
- **Proposições:**
    - **p:** Eu farei um bolo.
    - **q:** Comprar os ingredientes.
- **Conectivo:** SE E SOMENTE SE
- **Representação Lógica:** p ↔ q

| **p** | **q** | **p ↔ q** |
| --- | --- | --- |
| V | V | 🟢 **V** |
| V | F | **F** |
| F | V | **F** |
| F | F | 🟢 **V** |