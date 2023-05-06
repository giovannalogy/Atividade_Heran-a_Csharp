# Atividade_Heranca_Csharp

   
   Herança em C# com encapsulamento e polimorfismo
  
  Suponha que você esteja criando um sistema para uma loja que vende produtos
eletrônicos. Nesse sistema, existem diferentes tipos de produtos eletrônicos, como
celulares, notebooks e televisores. Todos esses produtos têm algumas informações em
comum, como marca, modelo e preço, mas também têm características específicas, como
tamanho de tela, capacidade de armazenamento e quantidade de entradas USB.
Para implementar essa funcionalidade, comece definindo uma classe abstrata chamada
"ProdutoEletronico", que contém as informações em comum entre todos os produtos
eletrônicos.
Crie nesta classe um método virtual chamado "MostrarInformacoes", que será usado
posteriormente para exibir as informações de cada produto eletrônico. Na classe
ProdutoEletronico este método deve imprimir a Marca, Modelo e Preço.
Em seguida, crie outras classes que herdam da classe ProdutoEletronico e adicionam
informações específicas. Por exemplo, podemos criar uma classe "Celular" que adiciona
informações como tamanho de tela e capacidade de armazenamento. Implemente o método
“MostrarInformacoes” com as especificações do celular.
Crie outra classe semelhante, agora para "Notebook" e "Televisor" com suas propriedades
específicas: TamanhoTela e QuantidadeEntradasUSB. Estas também herdando de
ProdutoEletronico. Implemente o método “MostrarInformacoes” com as especificações do
Notebook e Televisor.

  
  Chame o método MostrarInformacoes para cada classe no método Main.
