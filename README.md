# My personal repo for Stock Analysis Zoomcamp 2025 

The main repo of the project: [SAZC2025](https://github.com/DataTalksClub/stock-markets-analytics-zoomcamp/tree/main)

This second cohort starts in 19th of May, 2025. It will take roughly 6-7 weeks with, 5 weeks of lectures, 5 homeworks and 2 projects. I will share adjusted notebooks here, my own notebooks/scripts for homeworks and projects (there mmay be additional repos for projects which I will point out if so).

I will also be sharing this learning process with small stories on my [medium blog](https://medium.com/@neskafebardagi). Feel free to comment, share, and ask questions if you would have any.


## Setup & environment to reproduce 

Follow these steps to get started:

### 1. Install [`uv`](https://github.com/astral-sh/uv/)

Use `uv` to manage your virtual environments:

```bash
pip install uv
```

### 2. Create a virtual environment

Create an environment using python 3.10 (or your preferred version):

```bash
uv venv --python 3.10
```

### 3. Activate the environment

Activate the virtual environment:

```bash
source .venv/bin/activate
```

### 4. Install dependencies

Install all the required dependencies from the `requirements.txt` file:

```bash
uv pip install -e .
```

### 5. Install pre-commits

```bash
pre-commit install
```

### 6. Make the git commits and pushed automated

```bash
chmod +x git-auto.sh
```

Now you can just do ./git-auto.sh to push commits.

## Ready to code  
You're now all set to try out whatever you like in this repo.
