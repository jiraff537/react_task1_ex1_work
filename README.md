# react_tsak1_ex1_work

> quote


Field1 | Field2
-------|---
row1   | row2

```plantuml
@startuml
Bob -> Alice : hello
Alice -> Bob : you too
@enduml
```

```plantumlcode
@startuml
Bob -> Alice : hello
Alice -> Bob : you too
@enduml
```

```plantuml
@startuml component
actor client
node app
database db

db -> app
app -> client
@enduml
```