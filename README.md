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

    <p>Ao meu ver, podemos aplicar uns três padõres diferentes, são: Strategy, Template Method e Simple Factory. Entretando, esse último faz mais sentido ser
    aplicado do que os outros. Por que segundo a aplicabilidade do padrão:</p>

    * Sempre que tiver uma lógica definida para a criação de objetos, encapsule eles;
    * Para evitar a duplicação desta lógica em vários locais do projeto;
    * Essa lógica é normalmente representada por um bloco de if() que define as condições para a criação dos objetos.

    <p>Poderiamos resolver esse problema dos descontos com um bloco de ifs verificando cada situação.</p>


2. Como poderíamos implementar estes tipos de desconto sem utilizar Padrões de Projetos? 

3. Quais os problemas que tal implementação traria?

  
</div>
