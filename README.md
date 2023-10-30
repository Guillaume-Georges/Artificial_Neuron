Artificial neuron (perceptron) to categorize good and bad motivation letters.

INTRODUCTION

This project's goal was to better understand how deep learning works and I can apply them to concrete implementations.

I follow Machine Learnia's youtube channel and one of the first exercises was to create a perceptron to classify plants whether they are toxic or not (Neuron_predicts_plant_toxicity.ipynb).
I adapted this algorithm for a project to classify motivation letters submitted for a scholarship candidature (Neuron_predicts_candidature_quality.ipynb).

You will find more information on the project's objectives, solution, implementation and reflexion in Neuron_predicts_candidature_quality.ipynb file.

SET UP

This project uses a Jupyter notebook that was run with a custom kernel tied to a specific virtual environment with VS Code. To replicate the exact environment and ensure the notebook runs smoothly, follow these steps:

1. Creating the Virtual Environment:

Create a new virtual environment. Navigate to your project directory in the terminal and run:

python -m venv myenv

2. Activating the Virtual Environment:

Once the virtual environment is created, you need to activate it:

myenv\Scripts\activate

If you're on macOS and Linux:
source myenv/bin/activate

3. Installing Dependencies:

With the virtual environment activated, install the project's dependencies using the provided requirements.txt file:

pip install -r requirements.txt

4. Setting Up the Custom Kernel for Jupyter:

After setting up the virtual environment and installing the necessary libraries, you'll need to install the IPython kernel and set it up as a custom kernel for Jupyter:

pip install ipykernel
python -m ipykernel install --user --name=my_custom_kernel

5. Running the Notebook:

On VS Code, you can select the new kernel at the top right corner. 

 
