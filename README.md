# qiskit-quantum-exercises
Qiskit Quantum Computing exercises and examples provided by IBM

[Learn more about the exercises here](https://qiskit.org/textbook/preface.html)

## Setup
1. The Qiskit textbook uses [Jupyter Notebook](https://jupyter.org/install). I suggest [downloading Anaconda](https://www.anaconda.com/products/individual), you can then create a contained environment with Jupyter notebook and qiskit installed. 

2. Open a terminal and run the command `conda create -n name_of_my_env python=3` followed by `conda activate name_of_my_env`. You've now activated your virtual environment. 

3. You can now install qiskit. If you use pip, just type `pip install qiskit`. You'll likely want to use visualization features so now type `pip install qiskit[visualization]`

4. Install the `qiskit_textbook` package with the command: `pip install git+https://github.com/qiskit-community/qiskit-textbook.git#subdirectory=qiskit-textbook-src`. You can also build it yourself using the repo [here](https://github.com/qiskit-community/qiskit-textbook), navigating to the root, and running the command `pip install ./qiskit-textbook-src`

5. Optionally, you can set some defaults to reproduce the exact output as seen in the textbook. You can follow along [here](https://qiskit.org/textbook/ch-prerequisites/setting-the-environment.html#Steps-to-reproduce-exact-prerendered-output-as-given-in-qiskit-textbook-(Optional)) if you'd like to do this.

6. To begin working, run anaconda-navigator and select to launch Jupyter Notebook.
