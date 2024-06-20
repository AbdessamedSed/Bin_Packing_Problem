# Bin Packing Problem Solutions

This GitHub repository contains several solutions to the bin packing problem, implemented as Jupyter notebooks (`.ipynb`), along with benchmarks to evaluate their performance.

## Bin Packing Problem

The bin packing problem involves packing a set of items of varying sizes into the minimum number of bins (or containers) of fixed capacity. The objective is to minimize the total number of bins used while adhering to capacity constraints.

### Implemented Solutions

1. **Solution 1 - Performance Graph**

   - Uses matplotlib to plot execution time versus the number of data points.
   - [View Notebook](solutions/1-Branch_and_Bound.ipynb)

2. **Solution 2 - Greedy Heuristics**

   - Implements the following greedy heuristics:
     - Next Fit
     - Best Fit
     - Worst Fit
     - First Fit
     - Next Fit Decreasing
     - Best Fit Decreasing
     - First Fit Decreasing
     - Best Fit with rearrangement
   - [View Notebook](solutions/2-Heuristics.ipynb)

3. **Solution 3 - Metaheuristics**

   - **Simulated Annealing:** Uses a probabilistic method to explore solution space and avoid local optima.
   - **Tabu Search:** Uses a strategy to remember forbidden moves to avoid revisiting the same solutions.
   - **Hill Climbing:** Simple heuristic search that explores direct neighbors of a solution to seek improvement.
   - [View Notebook](solutions/3-Metaheuristics.ipynb)

4. **Solution 4 - Evolutionary Methods**

   - **Genetic Algorithms:** Uses an approach inspired by natural evolution to optimize solutions.
   - **Ant Colony Optimization:** Inspired by ant behavior to search for efficient solutions to the problem.
   - [View Notebook](solutions/4-Metaheuristics_Population.ipynb)

5. **Solution 5 - Hyper-Heuristic**

   - Utilizes a hybrid approach where a high-level metaheuristic (Genetic Algorithms) orchestrates the use of multiple low-level greedy heuristics to improve overall performance.
   - [View Notebook](solutions/5-Hyper-Heuristics.ipynb)

## Running the Notebooks

Each solution is implemented in a separate Jupyter notebook located in the `solutions/` directory. You can run them by following these steps:

1. Clone this GitHub repository to your local machine.
2. Install Jupyter Notebook if not already installed: `pip install jupyterlab`
3. Launch Jupyter Notebook: `jupyter notebook`
4. Navigate to the desired notebook in the Jupyter interface and open it.
5. Execute the code cells in the notebook to see the results.

## Benchmarks

Benchmark files for testing the solutions are available in the `benchmarks/` directory. These files contain data used to evaluate the performance of different approaches.

---

**Note:** Make sure to adjust paths and specific details in the notebooks and benchmarks according to your actual implementations and requirements.
