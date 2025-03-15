# Spring Boot Circuit Breaker

## Start application
````
    curl http://localhost:8000/actuator/health/circuitBreakers
    curl http://localhost:8000/api/loans-retry?type=personal
```` 
## Turn of rate
- mostrar logs no actuator
    http://localhost:8000/actuator/health

    ````
    curl http://localhost:8000/actuator/health/circuitBreakers
    curl http://localhost:8000/api/loans-circuit?type=personal
    ````
    Turn of rate

- http://localhost:8000/h2-console


- http://localhost:9000/h2-console
