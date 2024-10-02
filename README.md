**1. Sobrescrita de métodos em uma hierarquia de veículo**
__Enunciado:__
Implemente uma classe base chamada Veiculo que possua um método mover(). Crie duas subclasses: Carro e Bicicleta, que sobrescrevam o método mover() com comportamentos específicos.

A classe Carro deve imprimir "O carro está dirigindo" e a classe Bicicleta deve imprimir "A bicicleta está pedalando".




**2. Sobrecarga de métodos**
__Enunciado:__
Crie uma classe Calculadora que contenha três versões do método somar(). A primeira versão deve receber dois parâmetros inteiros, a segunda deve receber três parâmetros inteiros, 
e a terceira deve receber dois parâmetros do tipo double.

Implemente as três versões do método somar() e teste chamando cada uma com diferentes combinações de argumentos.

Discuta como a sobrecarga de métodos permite a criação de várias versões do mesmo método com assinaturas diferentes.




**3. Sobrecarga de construtores**
__Enunciado:__
Crie uma classe chamada Produto com três construtores sobrecarregados:

O primeiro deve receber um nome do produto (String).

O segundo deve receber um nome e um preço (double).

O terceiro deve receber um nome, um preço e uma quantidade em estoque (int).

Instancie objetos da classe Produto utilizando cada um dos construtores e imprima as informações dos produtos.




**4. Sobrescrita de métodos em uma classe de pagamento**
__Enunciado:__
Crie uma classe base chamada Pagamento com um método processarPagamento(), que apenas imprime "Processando pagamento genérico". Em seguida, crie duas subclasses: PagamentoCartao e PagamentoBoleto.

A classe PagamentoCartao deve sobrescrever o método processarPagamento() para imprimir "Processando pagamento via cartão de crédito".

A classe PagamentoBoleto deve sobrescrever o método processarPagamento() para imprimir "Processando pagamento via boleto bancário".

Instancie objetos de ambas as classes e demonstre o polimorfismo chamando o método processarPagamento() em cada um deles.




**5. Sobrecarga de métodos em uma classe de conversão**
__Enunciado:__
Implemente uma classe chamada Conversor que contenha três versões sobrecarregadas do método converter():

A primeira versão deve converter uma temperatura de Celsius para Fahrenheit.

A segunda versão deve converter um valor de quilômetros para milhas.

A terceira versão deve converter uma string para letras maiúsculas.

Teste todas as versões do método converter() chamando cada uma com os parâmetros adequados.
