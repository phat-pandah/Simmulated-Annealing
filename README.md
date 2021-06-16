Simulated Annealing Algorithm
------------------------

Simmulated annealing is used to find the global minimum of a function. In practive this could mean optimizing a energy function for some optimizing problem. It was inspired from annealing in metallurgy, where a heated metal is cooled down in a controlled fashion. It is described in more detailed here:
<a href=https://en.wikipedia.org/wiki/Simulated_annealing target=_blank>Wikipedia link</a><br><br>

## Exemples
--------------

#### Exemple 1:

We will be finding the global min of the objective function f(x) = ${x^2 - cos(4 \pi x)}$ on the interval ${x \in [-2.5,2.5]}$.
Plot of the function:
<img src='energy_function_1.svg'>

Just looking at the plot of the function, we can see that function is minimized at x=0 on this interval. Now we can check that the Simmulated annealing algorithm gives the same result.
<img src='SM_energy_function1.svg'>

This graph shows the steps taking by the algorithm. We see that the last x-value is around 0, which is what we expected for this energy function. 


### exemple 2:
--------------
We will be optimizing the function f(t) = ${t^2/2^t}$.
<img src='energy_function2.svg'>

By inspection we can see that the minimum on this interval occurs at x=0. Verifying that our Simmulated annealing gives the correct result: 
<img src='SM_energy_function2.svg'>
From the plot above, we see that the algorithm found the minimim to be x=0, as expected.