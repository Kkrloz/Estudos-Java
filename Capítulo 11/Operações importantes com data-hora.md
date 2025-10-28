- - -
### Instanciação
- (agora) -> Data-hora
- Texto ISO 8601 -> Data-hora
- Texto formato customizado -> Data-hora
- dia, mês, ano, [horário] -> Data-hora local

### Formatação
- Data-hora -> Texto ISO 8601
- Data-hora -> Texto formato customizado

### Obter dados de uma data-hora local
- Data-hora local -> dia, mês, ano, horário

### Converter data-hora global para local
- Data-hora global, timezone (sistema local) -> Data-hora local

### Cálculos com data-hora
- Data-hora +/- tempo -> Data-hora
- Data-hora 1, Data-hora 2 -> Duração


**Instanciação das classes e uso** :
```java
import java.time.LocalDate;
import java.time.LocalDateTime;
import java.time.LocalTime;
import java.time.ZonedDateTime;

LocalDate hoje = LocalDate.now();
LocalTime agora = LocalTime.now();
LocalDateTime dataHoraAtual = LocalDateTime.now();
ZonedDateTime zdt = ZonedDateTime.now(); // Com o fuso horário padrão do sistema
```

[[Instanciando data-hora em java]]