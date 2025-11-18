# Enumerações
- - -
- São um tipo de dado usado para definir um conjunto de constantes predefinidas. -> **enum**
- Faz com que o compilador permita apenas valores que estão listados na enumeração.
###### Declaração:
``` java
public enum OrderStatus {
	PENDING_PAYMENT,
	PROCESSING,
	SHIPPED,
	DELIVERED;
}
```

##### Conversão de String para enum:
```java
OrderStatus os1 = OrderStatus.DELIVERED;
OrderStatus os2 = OrderStatus.valueOf("DELIVERED");
```

[[Design]]