- - -
- ### Conceitos:
Data local:
- Hora opcional e sem fuso horário. *Data-[hora] local*
Data global:
- Possui hora e fuso-horário.  *Data-hora global*  
Duração
- É o tempo decorrido entre duas *data-horas*.

### Quando usar?

**Data-[hora] local:**
- Quando o momento exato não interessa para pessoas de outro fuso horário. Ex.: planilhas do excel, etc.
**Data-hora global:**
- Quando o momento exato interessa para pessoas de outro fuso horário. Ex.: sistemas multi-região, web, etc.
### Timezone

São relativos ao GMT ( Greenwich Mean time). 
-  Zulu time, Z time. 
- Horário do padrão UTC (Coordinated Universal Time).

Outros fuso horários são relativos ao GMT/UTC.
- São Paulo: GMT-3
- Manaus: GMT-4
- Portugal: GMT+1

Podem utilizar nomes para as timezones
- "US/Pacific"
- "America/Sao_Paulo"
- etc.
Boa prática
- Armazene global e mostre local
[[Padrão ISO 8601]]