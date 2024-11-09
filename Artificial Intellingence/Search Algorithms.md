- **An open-loop system** is where an agent ignores its percepts after it has found a solution while it executes the actions that lead to the goal.
- The opposite to that is a **closed-loop** system which monitors the percepts
- **A problem** can be defined as a set of possible states that the environment can be in.
- The **Initial state** is the state in which the environment starts from.
- **A transition model** describes what each action does. RESULT(s,a) returns the state that results from doing action a in state s.	
- **An action cost function**, denoted by ACTION-COST(s, a, s ) when we are programming or c(s, a, s ) when we are doing math, that gives the numeric cost of applying action a in state s to reach state s'.
- A **path** refers to a sequence of actions .
- **A solution** is a path from the initial state to the goal state.
- **An option** has the lowest path cost from the initial state to the goal state.
- **A graph** represents a state space in which the vertices are states and the directed edges are the actions.
- **Abstraction** is the process of removing detail from a representation.
- **A standardized problem** refers to one which is intended to illustrate or exercise various problem-solving methods.
- **A real world problem** is one whose whose solutions people actually use and whose formulation is idiosyncratic. 

#### Example problems
1) GRID PROBLEM
- **STATES**: For this problem, a state of the world shows which objects are in which cells.
- **ACTIONS**: Any state can be the initial state representing where we are starting from to find a solution. Can  up, down, left or right.
- **TRANSITION MODEL**: This describes what each action does. ie. up makes the agent goes up, down makes the agent go down, left makes the agent go left, right makes the agent go left.
- **GOAL STATES**: The states in which all the tiles are arranged as we want them to be.
- **ACTION COST**: Each action costs 1.