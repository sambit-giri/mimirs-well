# 🧠 Computational Intuition

**Building a "gut feeling" for abstract math and physics concepts through code.**

> "What I cannot create, I do not understand." — Richard Feynman

## 🔭 The Philosophy
The core mission of this repository is to bridge the gap between abstract formalism and concrete understanding.

While textbooks often focus on the mechanics of solving a problem, this project focuses on the **intuition** behind the solution. We use whatever computational tool is best for the job:
* **Simulations:** To see probability and chaos in action.
* **Visualizations:** To map complex functions and vector fields.
* **Symbolic Solving:** To derive equations and understand their structure.

The goal is to move from "following the rules" to "internalizing the behavior" of the system.

## 🧪 Experiments

| ID | Experiment | Key Concepts | Status |
| :--- | :--- | :--- | :--- |
| **01** | [**The Monty Hall Paradox**](./notebooks/01-monty-hall/) | `Probability` `Monte Carlo` `Game Theory` | ✅ Complete |
| **02** | [**Random Walks 1D/2D**](./notebooks/02-random-walks/) | `Stochastic Processes` `Diffusion` | 🚧 In Progress |
| **03** | ... | ... | ... |

## 🛠️ Usage

### 1. Clone the repository
   ```bash
   # Clone the repository
   git clone https://github.com/sambit-giri/computational-intuition.git

   # Enter the project directory
   cd computational-intuition
   ```

### 2. Set up the environment (Recommended)
It is best practice to use a virtual environment to avoid conflicting package versions. Several software options exist for this step, such as [venv](https://docs.python.org/3/library/venv.html), [conda](https://anaconda.org/) (Anaconda), and [mamba](https://mamba.readthedocs.io/).<br>
The example below assumes a Linux or Unix-based system and uses [venv](https://docs.python.org/3/library/venv.html).
   ```bash
   # Create a virtual environment
   python -m venv .venv

   # Activate the virtual environment
   source .venv/bin/activate
   ```

### 3. Install dependencies
Install the required libraries (numpy, matplotlib, jupyter, etc.) listed in the requirements file.
   ```bash
   # Install Python dependencies
   pip install -r requirements.txt
   ```

### 4. Run an experiment
Navigate to the experiment you want to explore and launch Jupyter.<br>
Example: running the Monty Hall simulation
   ```bash
   # Go to the experiment directory
   cd notebooks/01-monty-hall

   # Launch Jupyter Notebook
   jupyter notebook
   ```

## 📜 Structure
Each experiment is self-contained in the [notebooks](./notebooks/01-monty-hall/) directory.
   