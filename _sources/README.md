<img src="thumbnail.png" alt="thumbnail" width="300"/>

# SUNY Oswego Workshop Cookbook

[![nightly-build](https://github.com/jrobrien91/suny-oswego-workshop-2024/actions/workflows/nightly-build.yaml/badge.svg)](https://github.com/jrobrien91/suny-oswego-workshop-2024/actions/workflows/nightly-build.yaml)
[![Binder](https://binder.projectpythia.org/badge_logo.svg)](https://binder.projectpythia.org/v2/gh/ProjectPythia/cookbook-template/main?labpath=notebooks)
[![DOI](https://zenodo.org/badge/475509405.svg)](https://zenodo.org/badge/latestdoi/475509405)

This Project Pythia Cookbook covers working with radar data in Python, including examples from NEXRAD and the Doppler of Wheels from the [Lake Effect Electrication (LEE)](https://data.eol.ucar.edu/project/LEE) project. 

## Motivation

This cookbook will serve as a basis for an introduction to the open-radar science software stack, mainly [Py-ART](https://arm-doe.github.io/pyart/) and [xradar](https://docs.openradarscience.org/projects/xradar/en/stable/#). Users are encouraged to join the [Open Radar Discourse group](https://openradar.discourse.group/) for further interaction with the open-radar community. The majority of the material is repurposed from the [Project Pythia Radar Cookbook](https://projectpythia.org/radar-cookbook/README.html) and includes further details. 

## Authors

[Joe O'Brien](https://github.com/jrobrien91) [Max Grover](https://github.com/mgrover1), [Kai Mühlbauer](https://github.com/kmuehlbauer), [Alfonso Ladino](https://github.com/aladino), [Scott Collis](https://github.com/scollis), [Zach Sherman](https://github.com/zssherman), [Bobby Jackson](https://github.com/rcjackson), [Joe O'Brien](https://github.com/jrobrien91)

### Contributors

<a href="https://github.com/jrobrien91/suny-oswego-workshop-2024/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=jrobrien91/suny-oswego-workshop-2024" />
</a>

## Structure

This cookbook will be broken into three sections which include radar basics, radar software foundations, and an example from LEE for group exercise. 

### Section 1 ( Radar Basics )

Radar basics will include a presentation on radar data formats and background information on the open radar software stack.

### Section 2 (Py-ART Basics)

Example notebooks on the basics of Py-ART

### Section 3 ( SOURCE Example )

Students will work through an example notebook utilizing data obtained from SOURCE. 

## Running the Notebooks

You can either run the notebook using [Binder](https://binder.projectpythia.org/) or on your local machine.

### Running on Binder

The simplest way to interact with a Jupyter Notebook is through
[Binder](https://binder.projectpythia.org/), which enables the execution of a
[Jupyter Book](https://jupyterbook.org) in the cloud. The details of how this works are not
important for now. All you need to know is how to launch a Pythia
Cookbooks chapter via Binder. Simply navigate your mouse to
the top right corner of the book chapter you are viewing and click
on the rocket ship icon, (see figure below), and be sure to select
“launch Binder”. After a moment you should be presented with a
notebook that you can interact with. I.e. you’ll be able to execute
and even change the example programs. You’ll see that the code cells
have no output at first, until you execute them by pressing
{kbd}`Shift`\+{kbd}`Enter`. Complete details on how to interact with
a live Jupyter notebook are described in [Getting Started with
Jupyter](https://foundations.projectpythia.org/foundations/getting-started-jupyter.html).

### Running on Your Own Machine

If you are interested in running this material locally on your computer, you will need to follow this workflow:

1. Clone the `https://github.com/jrobrien91/suny-oswego-workshop-2024/` repository:

   ```bash
    git clone https://github.com/jrobrien91/suny-oswego-workshop-2024.git
   ```

1. Move into the `suny-oswego-workshop-2024` directory
   ```bash
   cd suny-oswego-workshop-2024
   ```
1. Create and activate your conda environment from the `environment.yml` file
   ```bash
   conda env create -f environment.yml
   conda activate oswego-radar
   ```
1. Move into the `notebooks` directory and start up Jupyterlab
   ```bash
   cd notebooks/
   jupyter lab
   ```
