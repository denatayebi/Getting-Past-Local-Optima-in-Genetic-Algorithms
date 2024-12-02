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
     
    Parameters:

         <directory of instance>: Path to the directory containing the input instance file.
         <number of population>: Number of individuals in the population for the genetic algorithm.
         <number of iterations>: Number of iterations (generations) the algorithm will run.

     Example:
 
      ```bash
     ./GA-WSCP ../Benchmarks/OR-Small/scp41.txt  100 500
      ```
