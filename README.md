To run the **Sudoku Solver with wxWidgets** project on GitHub, follow these steps:

### 1. Set Up Your Local Environment:
- **Install wxWidgets**:
  - First, install **wxWidgets** on your machine. You can download the appropriate version for your operating system from the [official wxWidgets website](https://www.wxwidgets.org/downloads/).
  - Follow the instructions to compile and set up wxWidgets on your machine.

### 2. Upload Your Project to GitHub:
- **Create a GitHub Repository**:
  - Go to GitHub and create a new repository for your project.
  - Clone the repository locally using the command:
    ```bash
    git clone https://github.com/Olendalepinto/Suduko-Solver.git
    ```
  - Copy all your project files (C++ source files and the `CMakeLists.txt` or `Makefile` if using one) into the cloned repository directory.

- **Push Your Project to GitHub**:
  - Stage, commit, and push your files to GitHub:
    ```bash
    git add .
    git commit -m "Initial commit for Sudoku Solver with wxWidgets"
    git push origin main
    ```

### 3. Set Up Build Instructions (Optional):
- If you are using **CMake** or a **Makefile** to build your project, make sure to include these files in your repository.
- In the README file of your GitHub project, provide instructions for users to clone, build, and run the project.

### 4. Clone and Build the Project Locally:
- After cloning your GitHub repository locally, you can build the project using `g++` or any IDE that supports wxWidgets (e.g., Code::Blocks, Visual Studio, etc.).
  
  - For example, if using `g++`:
    ```bash
    g++ your_sudoku_solver.cpp `wx-config --cxxflags --libs` -o SudokuSolver
    ./SudokuSolver
    ```

### 5. Run the Application:
Once the build is successful, you can run the compiled executable, and the Sudoku Solver application with the wxWidgets GUI will launch.
