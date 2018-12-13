# Finite State Machines

> Be able to draw and interperet simple state transition diagrams for FSMs with no output

## What is a finite state machine?

A finite state machine is any device that stores **its current status** and whose **status can change** as the result of an input. 
It is mainly used as a **conceptual model for designing and describing systems**. A finite state machine can be represented in two ways: **State Transition Diagram** or **State Transition Table**. A FSM with no outputs is called a **Finite State Automata**.

## State Transition Diagram

A state transition diagram is a visual representation of a FSM using circles to represent states, and arrows to represent transition.

| Name | Symbol |
|------|--------|
| State | |
| Start State | |
| Accept / End State | |
| Transition ("i" is input, "j" is output) | |

## State Transition Tables

A state transition table is a tabular representation of a FSM showing **inputs**, **current state** and **next state**.

**Example:**

| Input | Current State | Next State |
|-------|---------------|------------|
| Button Pressed | S0 | S1 |
| Button Released | S1 | S2 |

## Mealy Machines

> Finite State Machines with outputs

A Mealy Machine produces output values based on the input values.

**Example:**

| Input | Current State | Output | Next State |
|-------|---------------|--------|------------|
| 0 | S0 | 0 | S2 |
| 1 | S0 | 0 | S1 |
| 0 | S1 | 1 | S2 |
| 1 | S1 | 1 | S1 |
| 0 | S2 | 0 | S2 |
| 1 | S2 | 0 | S1 |
