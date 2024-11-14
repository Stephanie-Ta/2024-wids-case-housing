# WIDS Winter 2024 Housing Case Competition

To replicate our analysis:

1. Clone this GitHub repository to your local machine:
    - Click the green `<> Code` button and copy the url.
    - Navigate to where you'd like the cloned repository to reside in your local machine via the terminal.
    - Run the command `git clone <url>` in the terminal.
2. Create a conda environment from the environment file:
    - Navigate into the cloned (local) repository by running the command `cd 2024-wids-case-housing`.
    - Run the command `conda env create --file environment.yml` in the terminal.
    - Activate the environment by running the command `conda activate wids-housing` in the terminal.
3. Open JupterLab by running the command `jupyter lab` in the terminal.
4. In the JupyterLab web application, navigate to the `src` folder, open the file `edaok.ipynb`.
5. Change the kernel in the JupyerLab web application:
    - Under the `Kernel` tab, click on `Change Kernel...`.
    - Select the `Python [conda env:wids-housing]` option in the dropdown that pops up.
6. Run the report from top to bottom in the JupyterLab web application.