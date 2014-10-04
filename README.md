# SYSC 3110 Project – Board game framework with pluggable AI 

The goal of this team project is to come up with a small framework for computer-based board games, where the player confronts an “artificially intelligent” (more on that later!) computer opponent.  What we mean by “framework” is that there should be general facilities in place for developing concrete board games, and for developing various “artificial intelligence” (AI) strategies independently of the game in question. You don’t need to worry about what goes into that framework: the common facilities will be discovered as you refactor the design and implementation of your games to reduce duplication. In effect, to demonstrate that you have successfully complied with the requirements of the project, you are asked to develop 3 different (but simple!) games, for which you should use the same three different computer AI strategies. In other words, the various AI strategies should be independent of the specific nature of each game.

There are two mandatory board games: Tic Tac Toe and Othello, and one that is free for you to decide on. It can be a known game or one you invented!
Similarly, there are two mandatory AI strategies, and one that is up to you. The first mandatory AI strategy is simply to choose a legal move at random. The second mandatory AI strategy is known in the AI community as “minimax”.  You are asked to find out about minimax on your own, but your instructor and the TAs are happy to help you, should you have any questions!

Because minimax can be a resource-intensive strategy, you can either offer a smaller version of your game (e.g., a 4 x 4 Othello instead of the usual 8 x 8), you can limit the depth of the search algorithm (e.g., go only 3 moves deep), or you can use other “pruning” strategies (such as “alpha-beta”) that are easily found in books or online.

You only need to provide a graphical user interface for the game of Othello. The other games should be at least playable via the console, with simple text-based commands. 

The project is divided into 4 iterations, each ending with a milestone corresponding to deliverables that will be graded. You will be able to use the TA feedback from iteration i for iteration i+1. 

Milestone 1: Two console-based games: Tic Tac Toe and Othello; one strategy: random. 
- Deliverables: code (source + executable in a jar file), documentation complete with UML diagrams (including with complete variable and method signatures), and a readme file (see explanation below), all in one zip file. The code and the design are allowed to “smell” at this point.
- Deadline: Monday Oct 20th. Weight: 15% of the overall project grade.

Milestone 2: GUI for Othello, minimax strategy, unit tests. 
- Deliverables: source (including tests) + updated documentation and diagrams + readme file, all in one zip file. In particular, document the changes you made to your design and explain why. 
- Deadline: Friday Nov 7th. Weight: 15% of the overall project grade.

Milestone 3: 3rd game, 3rd strategy
- Deliverables: code + tests + documentation + readme file. Make sure that you document the changes since the last iteration and the reasons for those changes. Your code and design should be “smell-free” at this point.
- Deadline: Friday Nov 21st. Weight: 20% of the overall project grade.

Milestone 4: Two more features! Unlimited undo/redo moves and ability to save/load a game. 5% overall project bonus: port to Android platform. 
- Deliverables: code + design + documentation + readme file. 
- Deadline: Friday Dec 5th. Weight: 25% of the overall project grade.

Milestones must contain all necessary files and documentation, even those items that are unchanged from previous milestones. Missing files cannot be submitted after the deadline, no exceptions. Verify your submission contains all necessary files (in particular, don’t forget to include your source code!) before submitting on cuLearn.
The “readme” file, listed as a deliverable for each iteration, is typically a short text file that lists and describes: the rest of the deliverables, the authors, the changes that were made since the previous deliverable, the known issues (known issues are graded less severely than undocumented ones!) and the roadmap ahead.
“Documentation” includes up-to-date UML diagrams, detailed descriptions of design decisions made, complete user manuals, and javadoc documentation.

Note that nobody is stopping you from working ahead of schedule! In fact, iteration i+1 will very often give you good insight into iteration i. 

This is a team project. Each team should have 4 members (or exceptionally 3). A project’s success obviously depends on contributions from each member! So divide the work and cooperate. Each contribution (source code, documentation, etc.) must contain the name of its author: we will use this to determine whether there is any significant difference in the quality and quantity of the contributions of the team members. If any such difference is detected, the individual grades will be adjusted accordingly. 
You are expected to use Github to manage your project (version control, issue-tracking, wiki, etc...), but the deliverables for each milestone should also be submitted for marking on cuLearn. Each team will be given a private Github team repository. The TA and/or the instructor will also be members of each of the Github teams, so that they can track your use of the tool, verify that all group members are contributing, and their feedback will be given by opening new issues.

The marking scheme for each iteration will be comprised of: completeness of the deliverables, the quality of the deliverables, and, for iterations 2 to 4, we also look at whether you took into account the feedback you received from the TA in the previous iteration.

