---
layout: single
title: "Quantum Game Theory for Digital Platform Competition"
author_profile: false
permalink: /
---

*Exploring how quantum strategies may affect competition between digital platforms.*

---

## Project Idea

This project proposes using quantum game theory to model a simplified competition between two digital platforms. I will compare the classical and quantum versions of the same economic game to investigate whether expanding the strategy space through quantum operations, interference, and entanglement can change expected payoffs or equilibrium behavior.

---

## Background

Game theory is the mathematical study of strategic decision-making between players whose outcomes depend on one another. In economics, game theory is commonly used to study competition, pricing, cooperation, bargaining, and market behavior.

A major concept in game theory is the **Nash equilibrium**, which occurs when no player can improve their payoff by changing their strategy alone.

Quantum game theory extends classical game theory by allowing players to use quantum strategies. Instead of choosing only fixed classical actions, players may apply quantum operations to qubits. Concepts such as **superposition, entanglement, phase, interference, and measurement** can influence the probabilities of the final outcomes.

For this project, I will study a simplified competition game between two digital platforms. Each platform will make a strategic choice, such as whether to maintain or lower its fees. I will first analyze the classical version of the game and then explore how the results may change when the strategy space is expanded using quantum game theory.

### Simplified Platform Competition Model

To begin, I will model two digital platforms that must each choose between two strategies:

- **Maintain fees**
- **Lower fees**

The outcome for each platform depends on both its own decision and the decision of its competitor. For example, lowering fees may attract more users when the competing platform maintains its fees, but if both platforms lower their fees, both may earn less revenue.

A simplified payoff matrix could look like this:

|  | Platform B: Maintain Fees | Platform B: Lower Fees |
|---|---:|---:|
| **Platform A: Maintain Fees** | (3, 3) | (0, 5) |
| **Platform A: Lower Fees** | (5, 0) | (1, 1) |

The first number in each pair represents Platform A's payoff, while the second represents Platform B's payoff. This example creates a strategic conflict: both platforms may benefit individually from lowering their fees, even though both maintaining their fees could produce a better combined outcome.

I will use game-theoretic concepts such as best responses and Nash equilibrium to analyze this classical version before constructing the quantum model.

### Motivation

I chose this project because it combines interests that I have such as mathematics, economics, computer science, and quantum computing. I have always been especially interested in problems where mathematical models can help explain real decisions and behavior.

In my previous research on digital housing platforms, I studied how competition between online rental marketplaces could influence pricing and market outcomes. That work made me more curious about the strategies platforms use, how they react to competitors, and how economists model those interactions.

During MathQuantum, I began learning how ideas such as qubits, quantum gates, Hilbert spaces, entanglement, measurement, and quantum algorithms can create new ways of representing information and decision-making. This project feels like a natural next step because it allows me to connect something I have already researched with a completely new mathematical framework.

## Complementary Video

Before diving into the mathematics of quantum game theory, the following video provides an intuitive introduction to the Prisoner's Dilemma, Nash equilibrium, and how quantum concepts such as superposition and entanglement can change strategic interactions.

[![Quantum Game Theory Explained](https://img.youtube.com/vi/_kLb1glm6EM/maxresdefault.jpg)](https://youtu.be/_kLb1glm6EM)

*Up and Atom – Quantum Game Theory Explained*

---

## Research Question

> How does expanding the strategy space from classical strategies to quantum strategies affect equilibrium behavior in a simplified model of digital platform competition?

---
## Quantum Game Framework

In the quantum version of the game, the two classical strategies will be represented using qubit basis states:

- \( |0\rangle \) = maintain fees
- \( |1\rangle \) = lower fees

Each platform will control one qubit and apply a quantum operation representing its strategy. The two qubits may also be entangled, allowing the final outcome probabilities to depend on quantum effects such as phase and interference.

The general process is:

\[
|00\rangle
\rightarrow
\text{entanglement}
\rightarrow
\text{player strategies}
\rightarrow
\text{measurement}
\rightarrow
\text{economic payoffs}
\]

After measurement, the possible outcomes \( |00\rangle \), \( |01\rangle \), \( |10\rangle \), and \( |11\rangle \) correspond to the four outcomes in the classical payoff matrix.

The quantum circuit determines the probability of each outcome, while the economic payoff matrix determines how valuable each outcome is to the two platforms.

## Proposed Approach

1. Create a simplified competition game between two digital platforms.
2. Give each platform two possible strategies.
3. Represent the game using a classical payoff matrix.
4. Identify the classical Nash equilibrium.
5. Encode the classical strategies using qubit basis states.
6. Use a quantum game theory framework to represent player strategies as quantum operations.
7. Simulate the possible outcomes.
8. Compare the classical and quantum expected payoffs and equilibrium behavior.

## Expected Project Outputs

The completed version of this project could include:

- a classical payoff matrix for platform competition,
- an analysis of the classical Nash equilibrium,
- a two-qubit quantum game circuit,
- simulated measurement probabilities,
- expected payoff calculations,
- and a comparison between classical and quantum strategic outcomes.

Possible visualizations could include quantum circuit diagrams, payoff tables, measurement histograms, and graphs comparing classical and quantum expected payoffs.

For the MathQuantum mini-project, I am presenting the research idea, mathematical background, proposed methodology, and future development plan. The full simulation and economic extensions will be completed after further literature review.
---

## Tools and Techniques

### Mathematics

- **Linear algebra** will be used to represent quantum states, matrices, and quantum gates.
- **Complex numbers** will be used to describe probability amplitudes and phase.
- **Tensor products** will be used to represent a two-player quantum system.
- **Probability** will be used to calculate measurement outcomes and expected payoffs.
- **Game theory** will be used to define strategies, payoffs, best responses, and Nash equilibria.
- **Optimization** may be used in future work to search for equilibrium strategies.

### Quantum Information Concepts

- Qubits
- Superposition
- Entanglement
- Quantum gates
- Unitary operations
- Measurement
- Quantum circuits
- Interference

### Computational Tools

- Python
- NumPy
- Qiskit
- Matplotlib
- Quantum circuit simulators

---

## Goals

My goal during MathQuantum is to develop a stronger conceptual understanding of quantum game theory and explain how quantum information concepts can be connected to strategic decision-making.

Through this project, I hope to strengthen my understanding of:

- how classical and quantum strategy spaces differ,
- how entanglement and interference affect outcome probabilities,
- how expected payoffs are calculated from quantum measurements,
- and how Nash equilibrium can be studied in a quantum setting.

After MathQuantum, I plan to continue developing this project by:

- completing a literature review on quantum game theory and quantum economic models,
- implementing the classical and quantum games in Python and Qiskit,
- comparing classical and quantum outcomes,
- testing different quantum strategies,
- varying the amount of entanglement,
- and incorporating more realistic features from platform economics.

In the future I wish to major in Computer Science and minor in Economics, continuing to take Quantum Computing courses.

## References

1. Sethi, R., & Weibull, J. W. (2016). *What Is... Nash Equilibrium?* Notices of the American Mathematical Society, **63**(5), 526–529. https://www.ams.org/publications/journals/notices/201605/rnoti-p526.pdf

2. Eisert, J., Wilkens, M., & Lewenstein, M. (1999). *Quantum Games and Quantum Strategies*. Physical Review Letters, **83**(15), 3077–3080. https://doi.org/10.1103/PhysRevLett.83.3077

