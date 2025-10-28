- - -
**Boxing**:  processo de conversão de um objeto do tipo valor para um objeto do tipo referência. 

```java
int x = 20;
Object obj = x;
```

**Unboxing**: processo de conversão de um objeto do tipo referência para um objeto do tipo valor.

```java
int x = 20;
Object obj = x;
int y = (int) obj;
```

**Wrapper**:
- equivalentes aos tipos primitivos.
- Boxing e Unboxing é natural da linguagem.
- Uso comum: campos de entidade
- s em sistema da informação.
- Tipos referência (classes) aceitam valor null e usufruem de recursos orientados a objetos.

```java
Integer x = 10;
int y = x * 2;

public class Product{
	public String name;
	public Double price;
	public Integer quantity;
	(...)
```

[[Laço for each]]