# Interpolação de Strings #

  A interpolação é uma alternativa mais legível e elegante à concatenação de strings.
  
  ```
  //concatenação
  Console.WriteLine("O " + produto.nome + " custa " + produto.preco); 
  ```


1.
```
  Console.WriteLine($"O {produto.nome} custa {produto.preco}");
```

2.
```
  Console.WriteLine("O {0} custa {1}", produto.nome, produto.preço);
```
