<a name="br1"></a> 

Qiskit Fall Fest 2023

Welcome again to the Qiskit Fall Fest! To properly run these challenge notebooks,

please make sure you’re following the instructions below:

IF USING IBM QUANTUM LAB

You’re ready to begin! Watch the video included in this .zip ﬁle for instructions on how to

upload the notebooks and also get your images working properly.

IF USING A HOSTED JUPYTER ENVIRONMENT

OTHER THAN IBM QUANTUM (e.g., Google Colab)

Upload the notebooks and images into the hosted Jupyter environment

In the top code cell of one of the notebook, please run the following code to install the

grader and Qiskit:

!pip install 'qc-grader[qiskit] @ git+https://github.com/

qiskit-community/Quantum-Challenge-Grader.git'

Follow your hosted Jupyter environment's instructions for uploading notebooks to

upload all the Qiskit Fall Fest Challenges notebooks.

IF RUNNING LOCALLY

Prerequisites:

Yo u should have a Python 3.10 or greater virtual environment

Install:

Yo u need to install our grader client, Qiskit, and Jupyter Lab to successfully run the

notebooks.



<a name="br2"></a> 

From a terminal window in your Python virtual environment, run one of these

commands:

If you need to install the grader client, Qiskit, and Jupyter Lab run:

pip install 'qc-grader[qiskit,jupyter] @ git+https://

github.com/qiskit-community/Quantum-Challenge-Grader.git'

If you already have Jupyter Lab in your Python virtual environment and only need to

install the grader client and Qiskit then run:

pip install 'qc-grader[qiskit] @ git+https://github.com/qiskit-

community/Quantum-Challenge-Grader.git'

If you already have Jupyter Lab and Qiskit (version 0.44.0 or greater) installed in your

Python virtual environment and only need to install the grader client then run:

pip install 'git+https://github.com/qiskit-community/Quantum-

Challenge-Grader.git'

Run:

From a terminal window in your Python virtual environment

Change to the directory where all the Qiskit Fall Fest Challenges notebooks reside. For

example:

cd ~/Qiskit-Fall-Fest-Challenges-Notebooks

Launch Jupyter Lab:

jupyter lab .

This should launch your Jupyter Lab instance in a new browser window showing the

Qiskit Fall Fest Challenges notebooks.

