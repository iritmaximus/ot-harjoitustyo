# Machine sequence diagram thing

```mermaid

Some function->>Machine: Machine()
Machine->>FuelTank: FuelTank()
Machine->>Engine: Engine(tank)
FuelTank->>Machine: tank(0)
Engine->>Machine: engine()

```
