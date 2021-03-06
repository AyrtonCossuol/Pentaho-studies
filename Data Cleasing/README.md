# Pentaho-studies - Data Cleasing

Aqui nesta etapa, vamos trabalhar toda a parte de tratamento dos dados, buscando deixar a base mais limpa possível para que o time de negócio possa utilizá-la sem ter que demandar tempo para devidos tratamentos.

---
### Passo 1 - Mapeando os valores
Nessa primeira etapa, vamos começar a organizar alguns dados para que não aconteça ambiguidade, onde, na coluna 'Country' temos o caso de várias repetições de um nome que tem o mesmo significado, podendo ser transformado em um único valor.
<div style="display: flex; flex-direction: 'row'; align-items: 'center';" align="center">
   <img src="./assets/mapper_value_0.PNG" width="49%">
   <img src="./assets/mapper_value_1.PNG" width="49%">
   <img src="./assets/mapper_value_2.PNG" width="49%">
</div>

---
### Passo 2 - Replace de valores
Agora, vamos verificar alguns valores que estão com algum carácter indesejado, no caso da coluna 'City' existem valores com '#'. Assim, vamos aplicar o replace a eles substituindo por uma string vazia.
<div style="display: flex; flex-direction: 'row'; align-items: 'center';" align="center">
   <img src="./assets/replace_string_0.PNG" width="49%">
   <img src="./assets/replace_string_1.PNG" width="49%">
   <img src="./assets/replace_string_2.PNG" width="49%">
</div>

---
### Passo 3 - Fuzzy Match
Nesse passo 3, vamos utilizar o método de Fuzzy match com um auxílio de outra tabela, para alterar os nomes dos 'State' que vieram escrito de forma errada.
<div style="display: flex; flex-direction: 'row'; align-items: 'center';" align="center">
   <img src="./assets/fuzzy_match_1.PNG" width="49%">
   <img src="./assets/fuzzy_match_2.PNG" width="49%">
   <img src="./assets/fuzzy_match_3.PNG" width="49%">
   <img src="./assets/fuzzy_match_4.PNG" width="49%">
   <img src="./assets/fuzzy_match_5.PNG" width="49%">
</div>

---
<h4 align="center">
    Feito com :blue_heart: por Ayrton Cossuol
</h4>
