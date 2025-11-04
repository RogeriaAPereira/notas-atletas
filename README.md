# notas-atletas
Projeto de certificação 1 - Pontuação dos atletas
// 🏅 Projeto: Cálculo de Média de Notas de Atletas
// Autor: Rogéria Pereira
# 🏅 Projeto: Cálculo de Média de Notas de Atletas

## 🧾 Resumo do Projeto
Este mini-projeto foi criado como **revisão prática da Trilha 1**, preparando os alunos para os **projetos de certificação**.  
O objetivo é criar uma aplicação capaz de receber o **nome e as notas de um atleta**, calcular a **média das notas válidas** (desconsiderando a maior e a menor nota) e apresentar o resultado ao usuário.

---

## 🎯 Introdução
Em uma competição de **ginástica artística**, vários atletas realizam apresentações para uma banca composta por **cinco jurados**.  
Cada jurado avalia um critério específico:
- Tempo de duração da apresentação  
- Originalidade da coreografia  
- Postura do atleta  
- Dificuldade das acrobacias  
- Sincronismo  

### 🧮 Regras de Avaliação:
- Cada jurado fornece uma nota de **1 a 10**.  
- A **média final** é calculada com base nas **três notas do meio**, **eliminando a maior e a menor nota**.

O organizador da competição contratou a sua equipe para criar uma aplicação que automatize esse cálculo.  
Você foi o encarregado de desenvolver a solução utilizando **JavaScript**.

---

## ⚙️ Especificações Técnicas
A aplicação deve:

1. Receber uma **matriz de objetos**, onde cada objeto contém:
   - O nome do atleta;
   - As cinco notas atribuídas pelos jurados.

2. Calcular a **média das notas válidas** (excluindo a maior e a menor nota).

3. Exibir no console:
   - O nome do atleta;
   - As notas obtidas;
   - A média calculada.

---

## 🧩 Estrutura de Entrada

```javascript
let atletas = [
 {
   nome: "Cesar Abascal",
   notas: [10, 9.34, 8.42, 10, 7.88]
 },
 {
   nome: "Fernando Puntel",
   notas: [8, 10, 10, 7, 9.33]
 },
 {
   nome: "Daiane Jelinsky",
   notas: [7, 10, 9.5, 9.5, 8]
 },
 {
   nome: "Bruno Castro",
   notas: [10, 10, 10, 9, 9.5]
 }
];
