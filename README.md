# math_lab
# Math Lab

Maths, statistics and probability concepts from my Economics degree and ML roadmap, solved on paper, then implemented and visualised in Python (NumPy, matplotlib).

## Why this exists

I learn a concept properly when I have to make it work, not when I read about it. Each time I cover a new idea in my studies, I solve problems on paper, then implement it from scratch in Python and visualise it. The aim is to learn maths, statistics, probability and programming together rather than separately, and to build a reference I can come back to.

## Method

For every concept:

1. **Learn** the concept from lectures or textbooks.
2. **Solve** problems by hand on paper.
3. **Implement** it in Python, checking the code against the paper answer.
4. **Visualise** it with matplotlib to build intuition.
5. **Write up** the intuition, the worked problem and what I found hard in the topic's README.

## Structure

Concepts are grouped by topic. Each topic folder holds one script per concept, a README with a section for each concept, and a `figures/` folder for the plots the scripts produce.

```
math_lab/
├── multivariable_calculus/
│   ├── README.md                   # one section per concept: intuition, paper problem, figure
│   ├── lagrange_multipliers.py     # one script per concept
│   └── figures/
│       └── lagrange_multipliers.png   # named after the script that saves it
├── probability/
├── linear_algebra/
└── requirements.txt
```

Topic folders are added as concepts are covered.

## Running it

Requires Python 3.13.

```
git clone https://github.com/dbharrison03/math_lab.git
cd math_lab
python -m venv .venv
.venv\Scripts\Activate.ps1          # Windows (PowerShell)
# source .venv/bin/activate         # macOS / Linux
python -m pip install -r requirements.txt
```

Run any concept from the repository root, for example:

```
python multivariable_calculus/lagrange_multipliers.py
```

Each script saves its figure into its topic's `figures/` folder.

## Index

| Concept | Topic | Date | Link |
|---|---|---|---|