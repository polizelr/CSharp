# Construtor #

* Utilizado para inicializar objetos e variáveis de tipos de valor
* Faz com que o objeto seja inicializado no momento de sua instanciação
* Possui o mesmo nome da classe a que pertence

``` 
public Produto(string nome, double preco){
  Nome = nome;
  Preco = preco;
}

var p = new Produto("Caneta", 2.90);
```


# Construtor Padrão #

Além das características mencionadas anteriormente, o construtor padrão:

* Não recebe parâmetros
* Não precisa ser definido explicitamente, a menos que a classe possua outro construtor e seja necessária sua utilização

``` 
public Produto(){

}

var p = new Produto();
```

