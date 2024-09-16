```mermaid
 classDiagram
    class Calculadora {
      +a:float
      +b:float
      +executar(a,b)
    }
    class Adicao {
        +adicionar(a, b):operacao
    }
    class Subtracao {
        +subtrair(a, b):operacao
    }
    class Multiplicacao {
        +multiplicar(a, b):operacao
    }
    class Divisao {
        +dividir(a, b):operacao
    }

    Calculadora <|-- Adicao
    Calculadora <|-- Subtracao
    Calculadora <|-- Multiplicacao
    Calculadora <|-- Divisao
```
