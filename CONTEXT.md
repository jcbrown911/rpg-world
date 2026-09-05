# Oakvale

Oakvale is a persistent simulated world whose residents act under limited knowledge and whose consequential changes remain inspectable over time.

## Language

**Resident**:
A fictional person in Oakvale with limited knowledge, goals, relationships, and resources.
_Avoid_: Agent, NPC

**Agent**:
A software process that controls or assists a resident without sharing knowledge the resident could not possess.
_Avoid_: Resident, character

**Operator**:
The human acting outside Oakvale with authority to run the simulation, inspect system state, and review exceptional or high-impact cases.
_Avoid_: Player, resident

**World turn**:
A deliberate, discrete advancement of Oakvale's clock during which intentions are chosen, rules resolve consequences, and accepted changes become history.
_Avoid_: Real-time tick, session
