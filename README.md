# Getting-Past-Local-Optima-in-Genetic-Algorithms
# $${\color{blue}IGA-WSCP:\space Improved \space Genetic\space Algorithm\space for\space solving\space Set\space Cover\space Problem}$$
The algorithm improves a genetic algorithm for the Weighted Set Cover Problem by using the **Rosenthal potential function**, which smooths the optimization landscape by penalizing uneven element coverage across sets. This enables escaping local optima and finding higher-quality solutions, especially in challenging instances.


## Run GA-WSCP code
- Clone the repository

  ```bash
   git clone https://github.com/chuanluocs/NuSC-Algorithm.git
   ```

- Build GA-WSCP

  Navigate to the GA-WSCP directory and run the make command

  ```bash
  cd GA-WSCP_Algorithm/GA-WSCP
  make
  ```
- Run GA-WSCP
  
     To run the GA-WSCP, use the following command with the required arguments:

  ```bash
   ./GA-WSCP  <directory of instance> <number of population> <number of iteration>
   ```     
  
  Example:
   ```bash
    ./GA-WSCP ../Benchmarks/OR-Small/scp41.txt  100 500
     ```     

  This will execute the GA-WSCP on the input file scp41.txt, with a population size of 100 and 500 iterations.


**Output Format**

**Related Paper**

Tayebi, D., Ray, S., & Ajwani, D. (2024, September). An Improved Genetic Algorithm for Set Cover using Rosenthal Potential. In 2024 19th Conference on Computer Science and Intelligence Systems (FedCSIS) (pp. 689-694). IEEE.
