# Metodo Construtor

Para que possamos usar essa classe ainda é necessario que o campo lado seja inicializado.<br>
É inacessivel do exterio pois é privado. Para isso é utilizado o Metodo Construtor!
<br>

Um construtor é um método cujo nome é igual ao nome de seu tipo. Sua assinatura do método inclui apenas um modificador de acesso opcional, o nome do método e sua lista de parâmetros; ela não inclui tipo de retorno. 

## Sintaxe do Construtor

Um construtor é um método cujo nome é igual ao nome de seu tipo. Sua assinatura do método inclui apenas um modificador de acesso opcional, o nome do método e sua lista de parâmetros; ela não inclui tipo de retorno.
Posso ter mais de um construtor, desde que eles tenham alguma diferença.

![code](https://user-images.githubusercontent.com/91918988/236368956-08b45fdb-1ca6-4cc6-80bb-eb9382ac71ec.png)

## Parametros do Construtor  

Os construtores também podem receber parâmetros, que são usados ​​para inicializar os campos.<br>
Dentro do construtor, definimos modelcomo modelName( model=modelName). Quando chamamos o construtor, passamos um parâmetro para o construtor ( "Mustang"), que definirá o valor de modelcomo "Mustang":
