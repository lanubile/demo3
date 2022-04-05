# demo3
Repository per l'esercitazione su GitHub Flow del corso di IngSoft 2020/2021 

## Modello di dominio per il gioco degli scacchi

Questo è un esempio di uso di **Mermaid**

```mermaid
classDiagram
class Scacchiera
class Cella {
    colore
    posizione
}
Scacchiera *-- Cella
Cella "0..1" -- "0..1" Pezzo : è occupata da
Pezzo <|-- Pedone
Pezzo <|-- Torre
Pezzo <|-- Cavallo
Pezzo <|-- Alfiere
Pezzo <|-- Regina
Pezzo <|-- Re
```
