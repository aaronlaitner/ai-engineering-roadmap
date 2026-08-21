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

### Current Phase

Phase 1 — Data & Probability Foundations

### Next Tasks

* [ ] Begin Pandas fundamentals
* [ ] Practice DataFrame creation, indexing, and filtering
* [ ] Practice missing-value handling
* [ ] Practice grouping and aggregation
* [ ] Build a small Pandas analysis exercise
* [ ] Begin probability fundamentals
* [ ] Review probability rules and conditional probability
* [ ] Study common probability distributions
* [ ] Connect probability concepts to ML evaluation and uncertainty

### Notes

Completed both the OOP and NumPy checkpoints without relying heavily on internet or AI assistance.

The NumPy fundamentals project served as a practical test of retention after completing the notes.

Next focus: Pandas and probability.
