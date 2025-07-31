# test diagram
```mermaid
flowchart LR
  Metamodel["Metamodel"]
  Framework["EA Framework"]
  Model["Model"]
  EAModel["EA model"]
  Architecture["Architecture"]
  EA["EA"]
  System["System"]
  Ecosystem["Enterprise‑wide digital ecosystem"]

  Framework --> Metamodel : "Is a"
  Metamodel --> Model : "Is a manual for"
  Framework --> EAModel : "Is a manual for"
  EAModel --> Model : "Is a"
  
  Model --> Architecture : "Represents"
  EAModel --> EA : "Represents"
  
  Architecture --> System : "Has an"
  EA --> Ecosystem : "Has an"
  
  System --> Ecosystem : "Is a"

```
