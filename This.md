# This #

É uma referência para o próprio objeto.
Usos:

* Utilizado para diferenciar atributos de variáveis locais

```
public Produto (string Nome, double Preco){
  this.Nome = Nome;
  this.Preco = Preco;
}
```

* Utilizado para referenciar outro construtor em um construtor
```
public Produto (){

}

public Produto (string nome, double preco) : this(){
  Nome = nome;
  Preco = preco;
}

public Produto (string nome, double preco, int quantidade) : this(nome, preco){
  Quantidade = quantidade;
}

```

* Utilizado para passar o próprio objeto como argumento na chamada de um método ou construtor



