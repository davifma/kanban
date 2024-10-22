```mermaid
stateDiagram-v2
    [*] --> Disponível
    Disponível --> Emprestado: Data de Emprestimo maior que Data de Devolução
    Emprestado --> Disponível: Data de Devolução maior ou igual que a Data de Emprestimo

```
