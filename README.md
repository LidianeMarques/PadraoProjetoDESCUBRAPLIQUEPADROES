# <h1 align="center"> Padrões de Projeto </h1>
<hr/>

## <h2 align="center">DESCUBRA E APLIQUE PADRÕES </h2>

<div align="justify">
  
 ## <h2 align="center">Cálculo de Descontos </h2>
 
 <p>Considere que temos um sistema de vendas onde diferentes formas de desconto podem ser implementadas de acordo as promoções vigentes, como em datas comemorativas. O sistema deve permitir o cálculo do desconto sobre a venda das seguintes maneiras: </p>

  * Percentual de desconto definido (que pode vir de um banco de dados);

  * Percentual de desconto progressivo: valor da compra/25, não podendo ultrapassar 20% (este são apenas valores arbitrários de exemplo);

  * Desconto de 15% na data de aniversário do cliente;

Responda:

1. Qual padrão de projeto pode ser utilizado no desenvolvimento de uma solução? 

    <p>Ao meu ver, podemos aplicar uns três padõres diferentes, são: Strategy, Template Method e Simple Factory. Entretando, o primeiro faz mais sentido ser
    aplicado do que os outros. Por que segundo a aplicabilidade do padrão:</p>
      
    * Um comportamento de método(implementação de um algoritmo) precisa ser diferente em classes distintas e/ou <b> mudar em tempo de execução </b>;
    * Uma determinada classe deve ter comportamento específico (método) e outras não;
    * Não deseja-se que uma alteração em uma superclasse afete subclasses;
  
   
2. Como poderíamos implementar estes tipos de desconto sem utilizar Padrões de Projetos? 

    <p>Poderiamos resolver esse problema com um método responsável por aplicar os descontos aos produtos e apenas chamar o método na main fazendo a verificação se o cliente terá desconto ou não</p>
    
3. Quais os problemas que tal implementação traria?
    
    <p>Primeiro que sempre que fosse necessário acrescentar mais um desconto, por exemplo, teriámos que acrescentar outro if, correndo o risco de modificar a lógica e ocasionar bugs, temos duplicação de código, além de deixar todo a lógica de negócio na main. </p>

  
</div>
