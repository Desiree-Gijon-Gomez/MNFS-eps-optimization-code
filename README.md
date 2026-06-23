# MNFS-eps-optimization-code
This is the GitHub repository containing the Sage code for the complexity analysis of section 4 of the preprint "On the Impact of Faster Sparse Linear Algebra on the Number Field Sieve" by Desirée Gijón Gómez.

There are 3 folders, one for each subcase considered in the paper. In each one of them we solve the corresponding optimization problem. As we said in the paper, that entails considering three polynomial subproblems. We solve them via Groebner basis and optimize in terms of the discrete parameters, and them plot the three functions in terms of epsilon, and the true complexity will be the minimum of them. We then plot the complexity as a graph. For the boundary case, it is plotted as functions of c_p, for several fixed values of epsilon. In addition, we included the checks refered in the Appendix that any other polynomial system to be considered in the optimization problem does not return valid solutions.

The files are text files, with each block of code intended to be run separately (until a long dashed line) in a unique cell, for example using [SageMathCell](https://sagecell.sagemath.org/). The online free version is enough to run all the calculations except for the code in `./Boundary medium-large/three complexities and plot` for which we use [SageBinder](https://github.com/sagemath/sage-binder-env/blob/master/README.rst). 

