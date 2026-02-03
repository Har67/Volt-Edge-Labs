# Objective
To implement the same circuit (a 1011 sequence detector) using both Mealy and Moore Finite State Machines and compare their architectures and output behavior.

## What is a Sequence Detector (1011)?
A sequence detector is a sequential circuit that examines a serial input stream and produces an output when a specific pattern appears.

## Mealy Machine –  Output = f(Current State, Input)
A Mealy machine is a finite state machine in which the output depends on both the current state and the current input.

## Moore Machine – Output = f(Current State)
A Moore machine is a finite state machine in which the output depends only on the current state, not on the input directly.

## Architectural Difference: Mealy vs Moore
Feature	- Mealy Machine	Moore Machine
Output depends on	State + Input	State only
Output timing	Same clock cycle	Next clock cycle
Number of states	Fewer	More
Output stability	Can glitch	Glitch-free
Hardware complexity	Lower	Slightly higherOutput Logic Difference 

🔹 Mealy FSM
Output logic is inside the transition logic
Output can change immediately with input

🔹 Moore FSM
Output logic is separate from transition logic
Output changes only when state changes

