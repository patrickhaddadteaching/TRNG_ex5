In this exercise, you can analyze the impact of design parameters of the MO-TRNG on the generator output. 

You can launch the application and observe how the number of xored oscillators, the jitter variance, and the accumulation time affect the randomness of the generated numbers. 
By checking the box, you can save the generated bits in a local file.

Randomness is analyzed thank to 5 black box tests included in the AIS31 test suite (four of which are also included in the FIPS 140-1).

Your goal is to find the the the highest throuput (i.e. lowest $D$) for which the MO-TRNG would successfully pass all black box tests.

## How to launch the exercise ?
* We can execute this exercise on [Colab](https://colab.research.google.com/github/patrickhaddadteaching/TRNG_ex5/blob/main/TRNG_ex5_nb.ipynb)
    * [Click here](https://colab.research.google.com/github/patrickhaddadteaching/TRNG_ex5/blob/main/TRNG_ex5_nb.ipynb)
    * Then press Ctrl+F9 or click on Runtime/Run All
* We can also execute this exercise on Binder
    * Click or scan the QR-code <a href="[https://mybinder.org/v2/gh/patrickhaddadteaching/paramt1/main?urlpath=voila%2Frender%2Fparamt1
_binder.ipynb](https://mybinder.org/v2/gh/patrickhaddadteaching/TRNG_ex5/main?urlpath=voila%2Frender%2FTRNG_ex5_nb.ipynb)"><img src="qr-code-TRNG_ex5.png" style="width:100px;height:100px;"></a>
* The exercise is a jupyter notebook compatible with voila.
The following libraries are required:
    * numpy
    * matplotlib
## Examples of procedures to execute the exercise with different systems.
1. Windows
    * First of all, Let clone this repositorie
    ```
     git clone https://github.com/patrickhaddadteaching/TRNG_ex5
    ```
    * [Download and install the latest Miniconda](https://docs.conda.io/en/latest/miniconda.html#latest-miniconda-installer-links).
    * Open the Anaconda Powershell Prompt associated to Miniconda3 and type the following commands to install  to install all the dependencies required by this exercise.
     ```
        conda install jupyter
        conda install numpy
        conda install matplotlib
        conda install -c conda-forge voila    
    ```
    * Now, you can either launch the notebook by executing the folowing command in the directory where you cloned this repositorie.
    ```
    jupyter-notebook.exe .\TRNG_ex5_nb.ipynb
    ```
    
    * Or, you can directly launch it with voila  by executing the folowing command in the directory where you cloned this repositorie.
    ```
    voila.exe .\TRNG_ex5_nb.ipynb
    ```
2. Linux
3. Mac OS X
## Solutions
* [Click here](https://github.com/patrickhaddadteaching/TRNG_ex5/blob/main/solution.md) to see the solutions
