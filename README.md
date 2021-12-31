# Statistical Rethinking: A Bayesian Course Using CmdStanPy and Plotnine

## Intro

This repo contains the `python`/`stan` version of the Statistical Rethinking course that Professor Richard McElreath taught on the Max Planck Institute for Evolutionary Anthropology in Leipzig during the Winter of 2019/2020. The original repo for the course, from which this repo is forked, can be found [here](https://github.com/rmcelreath/statrethinking_winter2019). The course contains 20 lectures structured in 10 weeks with a series of assignments for each week.  The course is an excellent introduction to bayesian modelling in general and to the Rethinking Statistics wonderful [book](https://xcelab.net/rm/statistical-rethinking/) written by Professor McElreath.

## How to use this repo

There are ten `jupyter` notebooks, one for each week of the course. At the beginning of each notebook there are links to the youtube videos of the lectures, the slides used and the original homework questions and answers in `R`.

How I would use this repo is like this:

1. Go to the notebook of the week.
2. Watch the two videos for the lectures of that week. Their URL are at the very top of each notebook.
3. Read the original problems presented to the students and try to solve them on your own.
4. Follow the exercises solutions of the notebook with my code and explanations by Professor McElreath.

## Installing `CmdStanPy`

The `stan` code is executed thanks to `CmdStanPy`. [CmdStanPy](https://github.com/stan-dev/cmdstanpy) is a lightweight pure-Python interface to CmdStan which provides access to the Stan compiler and all inference algorithms. It provides the function `install_cmdstan()` which downloads CmdStan from GitHub and builds the CmdStan utilities. It can be can be called from within Python or from the command line. 

```python
import cmdstanpy
cmdstanpy.install_cmdstan()
```

You can found more information about the installation process [here](https://mc-stan.org/cmdstanpy/installation.html#installing-cmdstan).

## Other useful resources

There are a lot of very useful resources for bayesian statistical modelling out there. Specifically centered on Professor McElreath work I would mention:

1. Original [repo](https://github.com/rmcelreath/statrethinking_winter2019) for the course.
2. Original `rethinking` package [repo](https://github.com/rmcelreath/rethinking)

## Copyright

The present work is a derivative work of [Statistical Rethinking: A Bayesian Course Using python and pymc3](https://github.com/gbosquechacon/statrethink_course_in_pymc3) by Gabriel Bosque Chacon and [Statistical Rethinking: A Bayesian Course Using Python and NumPyro](https://github.com/asuagar/statrethink-course-in-numpyro) by Andrés Suárez. I made the stan code, the plotnine figures and slightly modifications to his comments.
