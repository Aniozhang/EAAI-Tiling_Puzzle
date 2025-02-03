# EAAI 2025 AI Assignments - Shapeshifting Coloring Problems
## Summary
This assignment presents students with a variant of an interactive tiling problem involving multiple constraints. Specifically, we randomly initialize a grid-environment with some cells colored in and ask students to color the remainder of the grid such that no two cells sharing an edge share the same color. We provide a set of colors and list of brushes to choose from – each of which takes on one of nine shapes and spans up to four cells on the grid. The objective is to also minimize the number of brush strokes and colors used.

Students are tasked with programmatically exploring the implicit search space graph and to find solutions using an AI search algorithm of their choice. By randomly iniitializing the grid environment with pre-filled cells, we incentivize students to build custom heuristics that are more generalizable.

We model the environment as a black box, providing an interface that mirrors real-world applications, such as the popular Gymnasium environ-ments for reinforcement learning. Thus, the assignment naturally lends itself to a range of algorithms from basic searches to reinforcement learning, allowing instructors to control difficulty.

