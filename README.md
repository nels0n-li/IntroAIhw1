# IntroAIhw1
I'll use this to put psuedocode and other requirements. 

Part 1 - Understanding the methods [10 points]: Read the chapter in your textbook on uninformed and informed
(heuristic) search and then read the project description again. Make sure that you understand A* and the concepts of
admissible and consistent h-values.
a. Explain in your report why the first move of the agent for the example search problem from Figure 8 is to the east rather than the north given that the agent does not know initially which cells are blocked.
b. This project argues that the agent is guaranteed to reach the target if it is not separated from it by blocked cells. Give a convincing argument that the agent in finite gridworlds indeed either reaches the target or discovers that this is impossible in finite time. Prove that the number of moves of the agent until it reaches the target or discovers that this is impossible is bounded from above by the number of unblocked cells squared

Part 2 - The Effects of Ties [15 points]: Repeated Forward A* needs to break ties to decide which cell to expand next if several cells have the same smallest f-value. It can either break ties in favor of cells with smaller g-values or in favor of cells with larger g-values. Implement and compare both versions of Repeated Forward A* with respect to their runtime or, equivalently, number of expanded cells. Explain your observations in detail, that is, explain what you observed and give a reason for the observation.

Part 3 - Forward vs. Backward [20 points]: Implement and compare Repeated Forward A* and Repeated Backward A*
with respect to their runtime or, equivalently, number of expanded cells. Explain your observations in detail, that is, explain
what you observed and give a reason for the observation. Both versions of Repeated A* should break ties among cells with
the same f-value in favor of cells with larger g-values and remaining ties in an identical way, for example randomly.

Part 4 - Heuristics in the Adaptive A* [20 points]: The project argues that “the Manhattan distances are consistent in
gridworlds in which the agent can move only in the four main compass directions.” Prove that this is indeed the case.
Furthermore, it is argued that “The h-values hnew (s) ... are not only admissible but also consistent.” Prove that Adaptive A*
leaves initially consistent h-values consistent even if action costs can increase.

Part 5 - Heuristics in the Adaptive A* [15 points]: Implement and compare Repeated Forward A* and Adaptive A*
with respect to their runtime. Explain your observations in detail, that is, explain what you observed and give a reason for
the observation. Both search algorithms should break ties among cells with the same f-value in favor of cells with larger
g-values and remaining ties in an identical way, for example randomly.

Part 6 - Statistical Significance [10 points]: Performance differences between two search algorithms can be systematic
in nature or only due to sampling noise (= bias exhibited by the selected test cases since the number of test cases is always
limited). One can use statistical hypothesis tests to determine whether they are systematic in nature. Read up on statistical
hypothesis tests (for example, in Cohen, Empirical Methods for Artificial Intelligence, MIT Press, 1995) and then describe for one of the experimental questions above exactly how a statistical hypothesis test could be performed. You do not need to implement anything for this question, you should only precisely describe how such a test could be performed.
