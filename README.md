**FINDING STEADY STATE OF NETWORK FLOW USED FOR OPTIMIZING SEARCH ENGINE RESULTS**

**GROUP-10 The OGs**

VATSAL SHAH    AU2040019         

USHMAY PATEL  AU2040253

DEEP PATEL      AU2040250          

NIHAAR PATEL  AU2040182

ABSTRACT

Each and Every system in the modern world holds a saturation point above which there is no possible way to optimize the system**. **So using concepts of Markov chain and network flow the aim is to optimize browsing results. A Markov chain or Markov process is a stochastic model describing a sequence of possible events in which the probability of each event depends only on the state attained in the previous event. A network flow is a directed graph where each edge has a capacity and each edge receives a flow, in graph theory. The aim is to improve the efficiency of search engine results by using the previous state achieved.

RESULTS


```
Instruction: 
1) The Input matrix of the network should be 'Symmetric Matrix'.
2) The sum of Column elments of the Matrix should be 'Unity'.
3) Input Non-Negative values.
Enter the number of rows:3
Enter the number of columns:3
Enter the entries rowise(one element at a time): 
0.4
0.3
0.3
0.3
0.4
0.3
0.3
0.3
0.4
Input Matrix: 
[0.4, 0.3, 0.3]
[0.3, 0.4, 0.3]
[0.3, 0.3, 0.4]

Eigen Values of the Matrix: 
[0.10000000000000003, 0.10000000000000003, 1.0]

Eigen Vectors of the Matrix(Column wise): 
[0.816496580927726, 0.0, 0.5773502691896258]
[-0.408248290463863, 0.7071067811865476, 0.5773502691896257]
[-0.4082482904638631, -0.7071067811865475, 0.5773502691896257]

Inverse of Eigen Vector Matrix(Column wise):
[0.8164965809277259, -0.408248290463863, -0.4082482904638631]
[-1.1102230246251565e-16, 0.7071067811865475, -0.7071067811865476]
[0.5773502691896257, 0.5773502691896257, 0.5773502691896258]

Steady State of Network Flow (after 100 iterations): 
[0.33333333333333337]
[0.3333333333333333]
[0.3333333333333333]

Steady State of Network Flow (after 200 iterations): 
[0.33333333333333337]
[0.3333333333333333]
[0.3333333333333333]
```


Result of Pagerank:


```
Enter the number of rows:3
Enter the number of columns:3
Enter the entries rowise (separated by space): 
0.4
0.3
0.3
0.3
0.4
0.3
0.3
0.3
0.4
Pagerank of given Network: 
[[0.33333333]
 [0.33333333]
 [0.33333333]]
```


References:


    _Online help_. Steady State Vector of a Markov Chain - Maple Help. (n.d.). Retrieved November 24, 2021, from [https://www.maplesoft.com/support/help/maple/view.aspx?path=examples%2FSteadyStateMarkovChain#:~:text=A%20common%20question%20arising%20in,vector%20of%20the%20Markov%20chain.](https://www.maplesoft.com/support/help/maple/view.aspx?path=examples%2FSteadyStateMarkovChain#:~:text=A%20common%20question%20arising%20in,vector%20of%20the%20Markov%20chain.) 


    _Math 312 - markov chains, Google's PageRank algorithm_. (n.d.). Retrieved November 24, 2021, from [https://www2.math.upenn.edu/~kazdan/312F12/JJ/MarkovChains/markov_google.pdf. ](https://www2.math.upenn.edu/~kazdan/312F12/JJ/MarkovChains/markov_google.pdf.)


    _Using row reduction to calculate the inverse and the ..._ (n.d.). Retrieved November 24, 2021, from [http://www.math.pitt.edu/~annav/0290H/row_reduction.pdf. ](http://www.math.pitt.edu/~annav/0290H/row_reduction.pdf.)


    Andrew Chamberlain, P. D. (2017, October 4). _Using eigenvectors to find steady state population flows_. Medium. Retrieved November 24, 2021, from [https://medium.com/@andrew.chamberlain/using-eigenvectors-to-find-steady-state-population-flows-cd938f124764. ](https://medium.com/@andrew.chamberlain/using-eigenvectors-to-find-steady-state-population-flows-cd938f124764.)


    _Machado Google PageRank Linear Algebra Project - UNCG_. (n.d.). Retrieved November 24, 2021, from [https://mathstats.uncg.edu/sites/yasaki/publications/machado-google-pagerank-linear-algebra-project.pdf. ](https://mathstats.uncg.edu/sites/yasaki/publications/machado-google-pagerank-linear-algebra-project.pdf.)


     D. S. (2019, July 16). _Introduction to markov chains_. Medium. Retrieved November 25, 2021, from [https://towardsdatascience.com/introduction-to-markov-chains-50da3645a50d. ](https://towardsdatascience.com/introduction-to-markov-chains-50da3645a50d.)


    _Page rank algorithm and Implementation_. GeeksforGeeks. (2021, November 6). Retrieved November 25, 2021, from [https://www.geeksforgeeks.org/page-rank-algorithm-implementation/. ](https://www.geeksforgeeks.org/page-rank-algorithm-implementation/.)

 

<p id="gdcalert1" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: equation: use MathJax/LaTeX if your publishing platform supports it. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert2">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>

