# OSeMOSYS Pyomo

## Installation

To run OSeMOSYS Pyomo you need to install a few Python dependencies in a Python environment.

One of the easiest ways to install a Python environment is with
[miniconda](https://docs.conda.io/en/latest/miniconda.html).

After installing miniconda, run the following commands in your terminal window:

```bash
conda config --add channels conda-forge
conda config --set channel_priority strict
conda create -n pyomo python=3.8 pyomo glpk  # we install pyomo and the free GLPK solver
conda activate pyomo  # activate our Python environment called 'pyomo'
```

You're now ready to processed to the next step.

## Running you first model run

To run OSeMOSYS Python, enter the following line into your command prompt:

    pyomo solve --solver=glpk osemosys.py OSeMOSYS_Python/UTOPIA_2015_08_27.dat

## Where to get help

If you need general help with OSeMOSYS, please submit posts on our friendly global
[forum](https://groups.google.com/forum/#!forum/osemosys) where there are many topics
and existing answers to other questions.

If you have identified a problem specific to OSeMOSYS Pyomo, please submit a new issue in the [issue tracker](https://github.com/OSeMOSYS/OSeMOSYS_Pyomo/issues/new).

If you have an idea or have identified a bug or problem which you think is relevant for the wider OSeMOSYS
community, please submit a [new issue](https://github.com/OSeMOSYS/OSeMOSYS/issues/new/choose) at the main OSeMOSYS repository.
