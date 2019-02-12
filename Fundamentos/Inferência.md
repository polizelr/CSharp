# Inferência #

A palavra reservada *var* é utilizada para que não seja necessário especificar um tipo durante a declaração da variável, 
uma vez que o compilador o infere por meio do valor atribuído à variável na inicialização.

```
//o compilador infere que a variável é do tipo string
 var nome = "Maria";
```

Limitações:

* Variáveis de tipo implícito devem ser inicializadas
* Variáveis de tipo implícito não podem receber valores de tipos diferentes do tipo inferido na inicialização

