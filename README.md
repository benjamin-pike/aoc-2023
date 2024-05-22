# Advent of Code 2023 Solutions
This repository contains my solutions to the daily coding challenges from the [Advent of Code 2023](https://adventofcode.com/2023) event, written in Python using Jupyter notebooks.

## Repository Structure
The repository is organised as follows:

- `/inputs` - Directory for input files. **NB:** Inputs are copyrighted and thus not included in the repository. You will need to add your own input files to this directory.
- `/notebooks` - Directory containing the Jupyter notebooks with the solutions for each day's challenge.

## Getting Started
To run the notebooks and test my solutions with your inputs, follow these steps:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/benjamin-pike/advent-of-code-2023.git
    cd advent-of-code-2023
    ```

2. **Install Python**

    If you do not have Python installed on your system, you can download it from the [official website](https://www.python.org/downloads/).

3. **Install Jupyter**
    
    Install Jupyter using `pip`:

    ```bash
    pip install jupyter
    ```

3. **Install required packages**
    
    Other than Jupyter only package used that is not included in the Python standard library is `numpy` If required, you can install it using `pip`:

    ```bash
    pip install numpy
    ```


4. **Add your input files**

    Create an `/inputs` directory in the root of the repository and add your input files. Each input file should be named `<day-number>.txt` (e.g., `1.txt` for Day 1, `2.txt` for Day 2).

    ```bash
    mkdir inputs
    # Add your input files to the `inputs` directory
    ```

5. **Run the Jupyter notebooks**

    Launch Jupyter Notebook:

    ```bash
    jupyter notebook
    ```

    Open the notebook for the corresponding day (e.g., `1.ipynb` for Day 1) from the `/notebooks` directory and run the cells to test the solutions.

## Credits
Thank you to [Eric Wastl](https://twitter.com/ericwastl), the creator of Advent of Code, for organising this event 🎄✨