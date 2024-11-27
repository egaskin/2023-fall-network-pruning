This project was part of Carnegie Mellon University's course "Machine Learning for Large Datasets" (10606). 

The goal of the project was to perform model compression on a simple neural network with >500,000 parameters while maintaining (or improving) accuracy of the model. This work was performed by three people, with efforts split as follows:

- [Ethan Gaskin](https://github.com/egaskin): Network slimming
- [Thomas Zhang](https://www.linkedin.com/in/thomas-zhang-347229169/): Magnitude based filter
- [Jen Yi Wong](https://www.linkedin.com/in/jen-yi-wong-907a816b/): Multi-armed bandit pruning, pareto plot generation

Of the three model compression methods we performed, we found that magnitude based filtering (the simplest) performed the best: introducing >72% sparsity (reducing the model's parameters by 72%) while maintaining greater than >85% training accuracy. For more details, check out our [report](https://github.com/egaskin/2023-fall-network-pruning/blob/main/project-report.pdf)! 
