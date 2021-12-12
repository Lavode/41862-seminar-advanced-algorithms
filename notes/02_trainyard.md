# Trainyard is NP complete (2021-11-30)

## Game mechanics

- Goal: Get incoming coloured trains into properly coloured stations
- Place rails to guide them to targets
- Splitters, painters to change colours, trains merge and assume common colour,
  ...

## Solvability problem TRAINYARD

- Can rails be placed in such a way that the result is a solution to the level

## Reduction to MIN-MON-SAT problem

- Introduction of 'gadgets' which behave based on boolean assignment (see slides)
  - Each gadget implements one functionality of MIN-MON-SAT circuits (I think?)
- "Implemenation" of these gadgets in trainyard game
