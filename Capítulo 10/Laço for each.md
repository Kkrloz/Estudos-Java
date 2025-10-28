- - -
# Laço for each
- Usado como sintaxe opcional e simplificada para percorrer arrays.

**Sintaxe**:

```java
for (Tipo apelido : coleção){
	<comando 1>
	<comando 2>
}
```

Exemplo:

```java
String[] vect = new String[] {”Maria”, “Bob”, “Alex”};
for ( int i = 0; i < vect.length; i++){
	System.out.println(vect[i]);
}

for (String obj : vect){
	System.out.println(obj);
}
```

[[Listas]]