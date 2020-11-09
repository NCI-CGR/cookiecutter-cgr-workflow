# cookiecutter-cgr-workflow

Cookiecutter template for CGR workflows.  This is based off of conventions defined for Snakemake workflows, but may be adapted for any other workflow management system.

## Authors
B. Ballew

## Usage

### Step 1: Set up a development environment

- If needed, install miniconda by following the steps [here](https://docs.conda.io/en/latest/miniconda.html).
- Create a conda environment with, minimally, the dependencies defined in `dev_environment.yaml`.
```
# create the env
conda env create -f dev_environment.yaml

# activate the env
conda activate dev_environment.yaml
```

### Step 2: Start your project using cookiecutter
- Use cookiecutter and follow the prompts to populate a new directory with all the boilerplate and directory structure you'll need.
```
cookiecutter http://10.133.130.114/bballew/cookiecutter-cgr-workflow
```

### Step 3: Initialize your repo
- Navigate into your new project directory
- Initialized a new git repository
```
git init
```
- Set up pre-commit hook scripts.  This will apply linting and check for some common code formatting errors every time you commit.  See https://pre-commit.com/ for more details.  
```
pre-commit install
```

### Step 4: Create your workflow
- Have fun and commit often!



Originally forked from https://github.com/snakemake-workflows/cookiecutter-snakemake-workflow.git


