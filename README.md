# Getting Started: Running the Jupyter Notebooks

Welcome! This guide will walk you through the steps to run the Jupyter Notebook (`.ipynb`) files included in this repository on your local machine.

### Prerequisites
Before you begin, ensure you have the following installed:
* **Git:** To clone the repository.
* **A Code Editor:** We recommend [Visual Studio Code (VS Code)](https://code.visualstudio.com/) with the Python and Jupyter extensions installed.

---

### Step 1: Clone the Repository
First, download the repository to your local machine. Open your terminal (or command prompt) and run:

```bash
git clone https://github.com/coderx86/oop-python.git
cd oop-python
```
*(Note: Replace the URL above with the actual link to your GitHub repository.)*

### Step 2: Install Python
If you don't have Python installed, download and install it from the [official Python website](https://www.python.org/downloads/). 
* **Important for Windows users:** Make sure to check the box that says **"Add Python to PATH"** during the installation process.

### Step 3: Install Jupyter and IPykernel
To run the notebooks, you need the Jupyter environment and `ipykernel` (which allows Jupyter to communicate with your Python installation). 

In your terminal, run the following command:

```bash
pip install jupyter ipykernel
```
*(Pro-tip: It is highly recommended to do this inside a [virtual environment](https://docs.python.org/3/library/venv.html) to keep your project dependencies organized!)*

### Step 4: Open the Project in VS Code (or your preferred IDE)
Open the cloned repository folder in your code editor. If you are using VS Code, you can do this from the terminal by typing:

```bash
code .
```
Once opened, locate and click on any file ending in `.ipynb` in the file explorer to open it.

### Step 5: Select the Kernel and Run
When you open a notebook file in VS Code:
1. Look at the top right corner of the notebook window for a button that says **Select Kernel** (or the name of your current Python version).
2. Click it, choose **Jupyter Kernel**, and select the Python environment where you installed Jupyter in Step 3.
3. You can now run the code! Click the **"Run All"** button at the top to execute the entire notebook, or click the **Play** icon next to individual cells to run them one by one.

---

**Troubleshooting:** If the code doesn't run, ensure that your editor has successfully connected to the Python kernel and that any required libraries specific to the notebook's code (like `pandas` or `numpy`) are installed via `pip`.