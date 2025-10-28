- - -
## Principais tipos Java (versão 8+)

**Data-hora local**
- LocalDate
- LocalDateTime

**Data-hora global**
- Instant

**Duração**
- Duration

**Outros**
- Zoneld
- ChronoUnit

```java
import java.time.LocalDate;
import java.time.LocalDateTime; 
import java.time.LocalTime;
import java.time.ZonedDateTime;
import java.time.Instant;

Instante instanteAgora = Instant.now();
LocalDate hoje = LocalDate.now();
LocalTime agora = LocalTime.now();
LocalDateTime dataHoraAtual = LocalDateTime.now();
ZonedDateTime zdt = ZonedDateTime.now(); // Com o fuso horário padrão do sistema
```