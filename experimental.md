
### Gráfico de Barras con Mermaid


graph LR
    A[Inicio] --> B{Decisión}
    B -->|Sí| C[Acción 1]
    B -->|No| D[Acción 2]
    C --> E[Fin]
    D --> E[Fin]

pie title Gráfico de Pie
    "Series A" : 60
    "Series B" : 30
    "Series C" : 10

### Diagrama de Secuencia con PlantUML


@startuml
Alice -> Bob: Hola Bob, ¿cómo estás?
Bob --> Alice: Bien, gracias.
@enduml


flowchart LR

A[Hard] -->|Text| B(Round)
B --> C{Decision}
C -->|One| D[Result 1]
C -->|Two| E[Result 2]


pie
"Dogs" : 386
"Cats" : 85.9
"Rats" : 15