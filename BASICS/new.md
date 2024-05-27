
| Machine Type                         | Transition Function Notation          | Description                                                                                       |
|--------------------------------------|---------------------------------------|---------------------------------------------------------------------------------------------------|
| Deterministic Finite Automaton (DFA) | δ: Q × Σ → Q                          | Given a current state and an input symbol, the next state is uniquely determined.                  |
| Non-deterministic Finite Automaton (NFA) | δ: Q × Σ → 2^Q                        | Given a current state and an input symbol, the next state can be one of many possible states.      |
| Epsilon-NFA (ε-NFA)                  | δ: Q × (Σ ∪ {ε}) → 2^Q                | Like an NFA, but transitions can also occur without consuming any input symbol (ε-transitions).    |
| Non-deterministic Pushdown Automaton (NPDA) | δ: Q × (Σ ∪ {ε}) × Γ → 2^(Q × Γ*)    | Given a current state, input symbol (or ε), and stack symbol, the next state and stack are non-deterministic. |
| Turing Machine (TM)                  | δ: Q × Γ → Q × Γ × {L, R}             | Given a current state and tape symbol, the next state, symbol to write, and direction to move are determined.  |
