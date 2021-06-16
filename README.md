{
 "metadata": {
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.9.5"
  },
  "orig_nbformat": 4,
  "kernelspec": {
   "name": "python3",
   "display_name": "Python 3.9.5 64-bit"
  },
  "interpreter": {
   "hash": "0a48755110956b4e642d187f0ea4379f17d0ea5d04f44da7b7029377a566289d"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 2,
 "cells": [
  {
   "source": [
    "## Simulated Annealing Algorithm\n",
    "------------------------\n",
    "\n",
    "Simmulated annealing is used to find the global minimum of a function. In practive this could mean optimizing a energy function for some optimizing problem. It was inspired from annealing in metallurgy, where a heated metal is cooled down in a controlled fashion. It is described in more detailed here:\n",
    "<a href=https://en.wikipedia.org/wiki/Simulated_annealing target=_blank>Wikipedia link</a><br><br>\n",
    "\n",
    "## Exemples\n",
    "--------------\n",
    "\n",
    "#### Exemple 1:\n",
    "\n",
    "We will be finding the global min of the objective function f(x) = ${x^2 - cos(4 \\pi x)}$ on the interval ${x \\in [-2.5,2.5]}$.\n",
    "Plot of the function:\n",
    "<img src='energy_function_1.svg'>\n",
    "\n",
    "Just looking at the plot of the function, we can see that function is minimized at x=0 on this interval. Now we can check that the Simmulated annealing algorithm gives the same result.\n",
    "<img src='SM_energy_function1.svg'>\n",
    "\n",
    "This graph shows the steps taking by the algorithm. We see that the last x-value is around 0, which is what we expected for this energy function. \n",
    "\n",
    "\n",
    "### exemple 2:\n",
    "--------------\n",
    "We will be optimizing the function f(t) = ${t^2/2^t}$.\n",
    "<img src='energy_function2.svg'>\n",
    "\n",
    "By inspection we can see that the minimum on this interval occurs at x=0. Verifying that our Simmulated annealing gives the correct result: \n",
    "<img src='SM_energy_function2.svg'>\n",
    "From the plot above, we see that the algorithm found the minimim to be x=0, as expected."
   ],
   "cell_type": "markdown",
   "metadata": {}
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ]
}