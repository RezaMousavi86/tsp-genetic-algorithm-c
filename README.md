# TSP Genetic Algorithm Solver in C

This project provides an efficient solution to the **Traveling Salesman Problem (TSP)** using a **Genetic Algorithm** implemented in C. It includes a real-time graphical visualization of the path optimization process using the **Raylib** library.

## Features
- **Genetic Algorithm:** Implements tournament selection, ordered crossover, and mutation to find the shortest path.
- **Real-time Visualization:** Watch the algorithm evolve and optimize the route dynamically using Raylib.
- **Dynamic Input:** Users can input the number of cities and their specific coordinates.
- **Optimized Calculation:** Efficient Euclidean distance calculation and path evaluation.

## Requirements
- **Compiler:** Any C compiler (e.g., GCC).
- **Library:** [Raylib](https://www.raylib.com/) must be installed to compile and run the project.

## How to Run
1. Ensure you have the Raylib library installed on your system.
2. Compile the code (linking with raylib):
```bash
   gcc main.c -lraylib -o tsp_solver
```   


---

## References & Resources

### Academic & Theoretical Foundations
*   **[ScienceDirect: Genetic Algorithm](https://www.sciencedirect.com/topics/engineering/genetic-algorithm)**: Used for understanding the theoretical foundations and engineering applications of Genetic Algorithms.
*   **[Traveling Salesman Problem (Wikipedia)](https://en.wikipedia.org/wiki/Travelling_salesman_problem)**: Classic reference for defining the constraints and objectives of the TSP.

### Tutorials & Inspiration
*   **[YouTube: Genetic Algorithm for TSP](https://youtu.be/kHyNqSnzP8Y)**: Provided essential guidance on implementing the core logic of the Genetic Algorithm for solving path optimization problems.

### Libraries & Tools
*   **[Raylib](https://www.raylib.com/)**: Used for real-time graphics rendering and visualization.
    *   [Raylib Cheatsheet](https://www.raylib.com/cheatsheet/cheatsheet.html)

---

## Acknowledgments
This project was developed as the final assignment for the Computer Programming course, under the supervision of **Professor [Mahdi Saadatmand]** at [Ferdowsi University of Mashhad]. 

I would like to express my gratitude for their guidance and the insights gained throughout the semester.

---

