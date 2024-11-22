# Aula 23 - Tabelas
Fator que me enche o saco sempre que retorno a estudar sobre ou até mesmo fazer mini-projetos e coisas do tipo

## Como funciona?
Geralmente uma tabela é seguida de rótulos e células, sendo os rótulos os cabeçalhos ou nomes que representam 
cada valor de uma célula. Na prática, as células são construiídas como:

### table
Tag pai, que comportará todo o conteúdo da tabela, como uma grande "div" ou "container" por assim dizer

### thead e tbody
Elementos filhos de table, que serão a cabeça da tabela (conterá os cabeçalhos da tabela) e o corpo (as células 
propriamente ditas). Tags que vieram a partir do HTML5, melhorando a semântica para identificação do navegador e 
desenvolvedor

### tr
Seria a linha da tabela, onde comportarão os cabeçalhos e as células com seus respectivos valores

### th e td
th - Cabeçalho
td - Célula

## Extra
No html, é possível também criar tabelas personalizáveis, contendo células que ocupam mais de uma linha, ou até mesmo 
cabeçalhos que ocupam mais de uma coluna. No primeiro caso, utiliza-se o atributo "rowspan" nas tags "td´s" e 
"colspan" nas tags th´s

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