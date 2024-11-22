# Aula 23 - Tabelas
Fator que me enche o saco sempre que retorno a estudar sobre ou até mesmo fazer mini-projetos e coisas do tipo

## Como funciona?
Para iniciar uma tabela organizada, você deve utilizar a tag table, sendo a tag pai que terá todo o seu conteúdo 
organizado por dentro. Após isso, segue para:

### Elementos thead e tbody
Parecidos com as tags head e body no html, sendo a thead a tag que irá conter os títulos/rótulos de cada célula da 
tabela. Já o tbody irá compar em seu interior as células propriamente ditas, como valor da idade ou nome de um 
usuário, entre outras coisas. No entando, estas tags apenas comportarão os valores, sendo também tags "pai".

### Tags th e td
Agora sim, as tags que conterão os valores, sendo th uma célula dentro da tag thead e td outra célula que 
ficará por dentro do tbody

### Tag tr
Chamada de table row, é uma tag onde comportará as linhas das células na table.

## Em resumo
Processo de criação:
<table>
 <thead>
  <tr>
   <th>Nome</th>
   <th>Idade</th>
  </tr>
 </thead>
 <tbody>
  <tr>
   <td>Pedro</th>
   <td>22</th>
  </tr>
  <tr>
   <td>Beatriz</td>
   <td>20</th>
  </tr>
 </tbody>
</table>