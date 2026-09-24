# Weekly Progress Log

## Week 0 — August 13, 2026

### Completed

* [x] Python diagnostic
* [x] Probability/statistics diagnostic
* [x] Created AI engineering roadmap repository

### What I Learned

* Core Python is fairly strong but needs some refreshing.
* Classes/OOP need additional practice.
* NumPy and Pandas are major learning priorities.
* Probability/statistics intuition is stronger than formal knowledge.
* Probability distributions and ML evaluation metrics need dedicated study.

---

## Week 1 — August 14–20, 2026

### Completed

* [x] Python OOP refresher
* [x] Reviewed classes, objects, `__init__`, and `self`
* [x] Reviewed inheritance, encapsulation, polymorphism, and `__str__`
* [x] Rebuilt `Experiment` class from scratch
* [x] Added `num_trials()` and `worst_result()` independently
* [x] Completed NumPy fundamentals notes
* [x] Practiced NumPy indexing and slicing
* [x] Practiced `axis`, shape, dimensions, and `dtype`
* [x] Practiced boolean masks and `np.where`
* [x] Practiced broadcasting and vectorized operations
* [x] Practiced standardization
* [x] Practiced matrix multiplication
* [x] Practiced reshaping and use of `-1`
* [x] Completed NumPy Fundamentals Project
* [x] Verified the NumPy project runs successfully from a fresh kernel
* [x] Prepared NumPy notes and project for GitHub

### OOP Checkpoint

Initial diagnostic score: 1 / 3

Current practical level: ~2.5 / 3

Successfully implemented an `Experiment` class with:

* Instance attributes
* Methods that modify object state
* Methods that calculate and return values
* `__str__`
* `mean_result()`
* `best_result()`
* `worst_result()`
* `num_trials()`

Main concept reinforced:

`print()` displays a value, while `return` sends a value back to the caller.

### NumPy Checkpoint

Completed structured NumPy fundamentals notes covering:

* Array creation and inspection
* Shapes, dimensions, axes, and data types
* Indexing and slicing
* Aggregations
* Boolean masking
* `np.where`
* Broadcasting
* Standardization
* Vectorization
* Matrix multiplication
* Reshaping
* Random data generation

Completed a NumPy student-performance analysis project using a simulated `(100, 5)` dataset.

The project included:

* Descriptive statistics
* Per-student and per-assessment aggregation
* Boolean filtering
* Conditional replacement
* Weighted grade calculation using matrix multiplication
* Feature standardization
* Vectorized transformations
* Array reshaping
* Final summary statistics

Most of the project was completed from memory. Notes were mainly needed for selected syntax such as random generation and reshaping.

### What I Learned

* I retained more NumPy syntax and concepts than expected after completing the notes.
* I am comfortable reasoning about array shapes and performing operations across different axes.
* Boolean masks and vectorized NumPy operations can replace many explicit Python loops.
* Broadcasting allows operations between arrays of compatible shapes without manually duplicating data.
* Matrix multiplication can be used naturally for weighted calculations.
* Standardization transforms data to approximately zero mean and unit variance.
* Jupyter notebooks can retain hidden state, so restarting the kernel and running all cells is important before publishing a project.
* Reproducible random generation is useful when sharing data-analysis notebooks.

## Progress Update — September 6, 2026

### Completed

* [x] Completed the Kaggle pandas course and its exercises
* [x] Created a combined notebook with concept notes and exercise solutions
* [x] Organized that notebook into `learning_pandas.ipynb` and `pandas_exercises.ipynb`
* [x] Updated the roadmap to include practical GPU training and PEFT/LoRA

### Pandas Topics Practiced

* DataFrames, Series, CSV reading, and CSV export
* Label-based and positional selection, Boolean filtering, and assignment
* Summary functions, mapping, and row-wise transformations
* Grouping, aggregation, multi-indexes, and sorting
* Data types, missing values, renaming, concatenation, and joins

### Next Tasks
* [ ] Review probability rules, independence, and conditional probability
* [ ] Study random variables and common probability distributions
* [ ] Practice expectation and variance with NumPy simulations
* [ ] Study ML evaluation metrics and basic statistical inference
* [ ] Complete the independent Phase 1 pandas analysis project

## Progress Update — September 24, 2026

### Completed

* [x] Reviewed core probability rules
* [x] Practiced complements, unions, intersections, conditional probability, and independence
* [x] Reviewed random variables
* [x] Learned Bernoulli and Binomial distributions
* [x] Practiced expected value, variance, and standard deviation
* [x] Practiced manual variance and standard deviation calculations
* [x] Studied Normal distributions and the 68–95–99.7 rule
* [x] Practiced z-scores
* [x] Studied sampling distributions
* [x] Learned standard error and its relationship to sample size
* [x] Reviewed the Law of Large Numbers and Central Limit Theorem
* [x] Learned confidence intervals and critical values
* [x] Studied null and alternative hypotheses
* [x] Learned p-values and one-sided vs. two-sided hypothesis tests
* [x] Studied Type I and Type II errors
* [x] Learned statistical power
* [x] Reviewed covariance and correlation
* [x] Completed a closed-notes statistics self-test
* [x] Completed the Phase 1 probability/statistics mini-lab
* [x] Created a consolidated probability/statistics Colab notebook

### Probability & Statistics Checkpoint

Completed the Phase 1 probability/statistics review covering:

* Probability rules
* Conditional probability
* Independence
* Random variables
* Bernoulli and Binomial distributions
* Expected value
* Variance and standard deviation
* Normal distributions
* z-scores
* Sampling distributions
* Standard error
* Law of Large Numbers
* Central Limit Theorem
* Confidence intervals
* Hypothesis testing
* p-values
* Type I and Type II errors
* Statistical power
* Covariance and correlation
### Current Phase

### Next Tasks

* [ ] Study ML evaluation metrics
* [ ] Practice confusion matrices, precision, recall, F1, specificity, ROC-AUC, and PR-AUC
* [ ] Connect statistical concepts to train/validation/test evaluation
* [ ] Complete the independent Phase 1 pandas analysis project
* [ ] Clean up and publish Phase 1 notebooks to GitHub
* [ ] Complete Phase 1 and begin Phase 2: ML fundamentals and PyTorch

### Current Phase

Phase 1 — Data & Probability Foundations

Next focus: ML evaluation metrics and the Phase 1 analysis project.
