In the provided repository there are 13 .ipynb files that have been used in our report concerning Gröbner bases and colouring problems together with corresponding .png files of the outputs. In this README.txt file we will briefly explain each function and how we have used it in our report.

4CollourablePlot.ipynb:
This .ipynb file was used to plot an example of a 4 colourable graph found in the literature. This was used just for illustrating.

AppollonianNetwork.ipynb
This .ipynb file was used to plot the Appollonian network found in the literature. We used this example to showcase that for large examples with many vertices the Gröbner basis could still apply to compute a solution to a colouring problem of such magnitude.

Chao12VertexExample.ipynb
This .ipynb file was used to plot an example from the literature. We extended this graph with additional vertices to showcase that for a three colourable graph the number of vertices can as well be large.

CompareQvsCyclictomic.ipynb
This .ipynb file was used to calculate the same graph problem but calculating it either through an cyclictomic extension or constructing different constraints that enforce the solutions to lie in Q. 

GraphCertificateExample.ipynb
This .ipynb file was used to showcase what happens if there is no solution to the polynomial system and how can one check for this. 

PlotRuntimeDataBetweenOrderings.ipynb
This .ipynb file was used to investigate and illustrate the difference in runtime between the choice of monomial ordering. The data used was constructed using createConnectedPseudorandomGraph.ipynb and is shown at the end of the file.

PlotRuntimeDataBetweenSolutionsInQandInExtention.ipynb
This .ipynb file was used to investigate and illustrate the difference in runtime between the choice of using an extension or constructing the roots of unity such that the solution lies in the rational numbers Q. The data used was constructed using CompareQvsCyclictomic.ipynb and is shown at the end of the file.

SudokuGraphPlot.ipynb
This .ipynb file was used to showcase what the sudoku example we used in the project would translate to a coloured graph. This graph is plotted by this file.

SudokuSquarePlot.ipynb
This .ipynb file was used to showcase the sudoku example. This time we plot it in the sudoku fashion with a 9x9 grid. It plots the unfilled sudoku where we would begin with and it plots the final result calculations. 

SudokuWithMistake.ipynb
This .ipynb file was used to showcase what would be the result if one would make a mistake and fill in a value that is not allowed, which would result in there being no solutions.

ThreeColourablePlots.ipynb
This .ipynb file was used to plot an example of a three colourable graph found in the literature. It was mainly used to showcase the permutations of the colourings, demonstrating that one solution could be permuted into many different colourings.

CountNumberOfSolutions.ipynb
This .ipynb file was used to count the number of solutions for a given colouring problem. It wil output the resulting number.
