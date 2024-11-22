# Aula 27 - Inputs no html
Nesta aula, vamos dar uma passada por cima dos principais tipos de input no html

**Extra:** Para deixar o campo do input obrigatório, utilizar o atributo *required*

## Campo de texto
Visto na aula anterior e o mais comum, permite que você insira texto pelo input
- input type="text"

## Campo de email
Campo de input específico para o email, contendo sempre um @ em sua identificação
- input type="email"

## Campo de senha
Campo específico para senha, sendo identificado por ficar ter seus caracteres "escondidos"
- input type="password"

## Campo radio
Campo específico para seleção, na maioria das vezes sendo *uma única opção*. Necessário também ser sempre o 
*mesmo "name"!* e *"value" único*
- input type="radio"

## Campo checkbox
Campo específico para seleção, similar ao radio, porém recebendo mais de uma opção. Ou seja, *mesmo "name"* e 
*value único*
- input type="checkbox"

## Campo de Data
Como o nome já diz, você poderá selecionar a data com o documento html.
- input type="data"

## Campo de arquivo
O documento html permite que seja feito um upload de arquivo pelos inputs dos formulários.
- input type="file"

## Campo de seleção
Diferente dos inputs, porém funciona também como um campo de seleção. Composto pela tag principal "section", seguido pelas tags "option" com seu value para ser usado no back-end

## Area de Texto
Simular ao input, em seu campo de texto comum. Geralmente utilizado para informar suas observações em um determinado 
formulário. Além disso, seu tamanho é flexível, podendo ser alterado pelos atributos *rols* e *cols*