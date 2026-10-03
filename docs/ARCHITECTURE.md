# Architecture

## 5-Layer Design

    +---------------------------------------+
    |  Layer 4: APPLICATION                 |
    |  Timeline - Ultra Prompt - Palettes   |
    +---------------------------------------+
    |  Layer 3: LOGIC                       |
    |  Color Algebra - Predicates           |
    +---------------------------------------+
    |  Layer 2: PROBABILITY                 |
    |  Bayesian - Markov - Statistical      |
    +---------------------------------------+
    |  Layer 1: PHILOSOPHY                  |
    |  Newton - Goethe - Munsell - Itten    |
    +---------------------------------------+
    |  Layer 0: CORE                        |
    |  Color Math - PRNG - Conversion       |
    +---------------------------------------+

## Dependencies

Layer 4 -> Layer 3 -> Layer 2 -> Layer 1 -> Layer 0

A layer can only depend on lower-numbered layers.

## Layer Responsibilities

- Layer 0: Pure math, color spaces, PRNG
- Layer 1: Color theory, rules, psychology
- Layer 2: Probability, statistics, prediction
- Layer 3: Logic, algebra, predicates
- Layer 4: User-facing features
