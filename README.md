# Spring

## Аннотации Spring:
- Configuration
- Bean
- Component - использование класса как бина
- ComponentScan("путь_к_папке") - указывает, где искать классы-бины, отмеченные аннотацией Component
- Aspect - определяемый класс является аспектом
- аннотация для совета
  - After
  - Before
  - AfterReturning
  - AfterThrowing
  - Around
- EnableAspectJAutoProxy - при работе с аспектами

## Аннотации Spring MVC
- Controller - разновидность Component (ничего не знает о бизнес-логике)
- Service - разновидность Component (осуществляет процессы бизнес-логики)
- RequestMapping - задаёт URL (при отстутсвии дополнительных аннотация метод **должен** возвращать строку - имя вызываемого html-файла)
  - PostMapping - задаёт URL при выполнение запроса типа POST
  - GetMapping - задаёт URL при выполнение запроса типа GET
  - addMapping
- PathVariable
- RequestParam
- ModelAttribute - получение данных из html-файла при выполнении запроса POST
- Repository - лучше не использовать
