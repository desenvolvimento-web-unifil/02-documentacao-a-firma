```mermaid
flowchart LR

    User --- Login
    User --- Registrar
    User --- Movimentar_Dinheiro
        Movimentar_Dinheiro -.extends.- Depositar
        Movimentar_Dinheiro -.extends.- Sacar
    User --- EscolherJogo
    User --- EntrarJogo
    User --- ApostarNoJogo
    
```

```Mermaid
flowchart LR
  Gerente --- ApostarNoJogo
  Gerente --- Login
  Gerente --- Registrar
      
``` 