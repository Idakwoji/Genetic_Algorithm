# Genetic_Algorithm
### Solving a job shop scheduling problem using a genetic algorithm
This project involved building a genetic algorithm to solve a job shop scheduling problem for an organization in Saudi Arabia.
It involves defining relevant algorithmic functions such as job order crossover, mutation, binary selection, etc.
Some other important functions include the addition of an adaptive mutation function that improves mutation rate based on performance, as well as various local search methods such as swapping local search, and generation of neighbors for a hill climbing local search.
The main codebase involves the implementation of all the functions, putting them together to solve the problem. After those functions are applied, a final makespan is gotten, and the minimum makespan is plotted along with the average makespan.
I observed that different random seed values gave very different accuracies. So I wrote a code to run the main code base by iterationg through different seed values. This helped me recognize the random seed values that produce the most optimal outomes. 
At the request of the organization, I also implemented a Gantt chart that helped in visualizing the optimal job schedules on each machine.
