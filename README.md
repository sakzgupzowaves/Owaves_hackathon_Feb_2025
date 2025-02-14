# Owaves_hackathon_Feb_2025
README:

# Setting Up the Conda Environment

To ensure a consistent development environment, we use **Conda** to manage dependencies. Follow these steps to set up your environment:

To install Conda, you can install either **Miniconda** (lightweight) or **Anaconda** (full distribution). Miniconda is recommended for most users. You can download them from the following links:

- **Miniconda**: [Download Miniconda](https://docs.conda.io/en/latest/miniconda.html)
- **Anaconda**: [Download Anaconda](https://www.anaconda.com/download/)

After installing, restart your terminal and verify the installation by running:


conda --version


If Conda is installed correctly, it will output the Conda version.

Once Conda is installed, clone the repository and navigate into the project directory:

git clone https://github.com/yourusername/your-repo.git cd your-repo


Now, create the Conda environment using the `environment.yml` file:

conda env create -f environment.yml


After the environment is created, activate it with:

conda activate environment 


To verify the installation and ensure all dependencies are installed correctly, run:

conda list 


If the `environment.yml` file is updated in the future, you can update your existing Conda environment using:

conda env update --file environment.yml --prune


This will install any new dependencies and remove unused ones.

If you need to exit the Conda environment at any time, you can deactivate it using:

conda deactivate


By following these steps, you will have a fully configured Conda environment for the project. 
