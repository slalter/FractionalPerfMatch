# FractionalPerfMatch
Code from fractional perfect matching research.
Uses Sage math, which unfortunately is not directly pip installable or importable.
Combine cycles, translate them to line permutations, and get the terms of the pfaffian and use them to demonstrate existence of fractional perfect matchings by 
bijecting from the set of FPM's with weights {0,1/2,1} to the set of line permutations. All graphs with FPM's are guaranteed to have one such graph.
Furthermore, all FPM's of a graph are convex combinations of the FPM's with {0,1/2,1} on the complete graph, which lays the framework for an algorithm to find all FPM's 
of any given graph (code not shown).
