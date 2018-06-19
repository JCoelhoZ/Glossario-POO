# Glossario-POO
Glossário criado para trabalho da disciplina de Programação Orientada a Objetos.

Sumário
=====
- [Construtor](#construtor)
- [Instanciação](#instanciação)
- [Palavras Reservadas](#palavras-reservadas)
  - [new](#new)
  - [instanceof](#instanceof)
  - [public](#public)
  - [private](#private)
  - [final](#final)
  - [this](#this)
- [Encapsulamento](#encapsulamento)
- [Getters e Setters](#getters-e-setters)
- [Assinatura de método](#assinatura-de-método)
- [Sobrecarga de método](#sobrecarga-de-método)
- [Escopos](#escopos)
  - [Escopo de classe](#escopo-de-classe)
  - [Escopo de objeto](#escopo-de-objeto)
- [Relacionamentos](#relacionamentos)
  - [Relacionamento de dependência](#relacionamento-de-dependência)
  - [Relacinamento de Agregação](#relacionamento-de-agregação)
  - [Relacionamento de Composição](#relacionamento-de-composição)

Construtor
=====
Construtores são métodos que não possuem indicação de retorno, e têm o mesmo nome da classe, sendo chamados apenas na hora da instanciação do objeto. No exemplo a seguir, é criado um método construtor dentro da classe Cachorro:
```java
public class Cachorro{
  public Cachorro(){
    public String cor;
    public String raca;
    }
  }
```
Instanciação
=====
É a criação de um objeto, utilizando sua classe, através do operador [new](#new)
```java
Cachorro Scooby = new Cachorro()
Scooby.cor = "Marrom";
Scooby.raca = "Dogue Alemão";
```

Palavras Reservadas
=====
new
-----
É um operador que aloca memória para um objeto, incializa variáveis, e chama um método construtor, como no [exemplo dado na instanciação do objeto](#instanciação)

instanceof
-----
Determina se um objeto é uma instância de uma classe, realizando uma comparação. No exemplo a seguir, é comparado se o objeto Scooby é uma instância de Cachorro. Caso seja, é impresso à tela que Scooby é um cão, caso não seja, é impresso que não é.
```java
if (Scooby instanceof Cachorro){
  System.out.println("É um cão.")
  }else{
  System.out.println("Não é um cão")
  }
```

public
-----
É um modificador de acesso, que faz com que a classe/método/variável possa ser acessado através de qualquer classe.

private
-----
Assim como o anterior, também é um modificador de acesso, mas que faz com que o método/variável só possa ser acessado pela sua própria classe.

this
-----
É uma variável de referência, utilizada para fazer definições em variáveis de uma instância específica de um objeto.

final
-----
Impossibilita de uma classe ser estendida, um método ser sobrescrito, ou uma variável ser alterada, tornando-a constante.

Encapsulamento
=====
Forma de esconder e proteger dados dentro de um método específico, de maneira que para acessá-los, deve ser apenas através de seu método.

Getters e Setters
=====
São métodos de acesso, 

Assinatura de Método
=====


Sobrecarga de método
=====


Escopos
=====
Escopo de classe
-----


Escopo de objeto
-----


Relacionamentos
=====
Relacionamento de dependência
-----

Relacinamento de Agregação
-----


Relacionamento de Composição
-----
