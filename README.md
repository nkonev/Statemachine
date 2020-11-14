# Statemachine
Spring State Machine Wellcome!

This webapp is a purchase abstraction. App used Spring StateMachine Framework for implementation 
finite state machine theory 

# Playground
```bash
curl -v 'http://localhost:8080/reserve?userId=1&productId=2'
curl -v 'http://localhost:8080/cancel?userId=1'
```

Will log
```
Товар с номером 2 зарезервирован.
Переход из статуса NEW в статус RESERVED
Machine started
...
Резервирование товара 2 отменено
```