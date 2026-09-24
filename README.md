# NumPy for AI/ML – Assignment

## About

This repository contains my **NumPy for AI/ML** assignment completed as part of **Module 3**.

The assignment focuses on understanding NumPy concepts, implementing vectorized solutions, predicting outputs, debugging code, and applying NumPy to AI/ML-related scenarios.

## Assignment Structure

The assignment is organized into **Sections A–D**, with **Section E as a Bonus / Challenge**.

Each section follows a different answer pattern based on the type of question.

---

## Section A – Conceptual Understanding

This section focuses on the basic and important concepts of NumPy used in AI/ML.

### Topics Covered

- NumPy arrays vs Python lists
- Vectorization
- Element-wise multiplication and matrix multiplication
- Broadcasting
- `flatten()` vs `ravel()`
- Array axes and aggregation
- Normalization and standardization
- Handling `NaN` values
- Array shapes for ML and RGB images
- Reproducibility and random seeds

### Answer Pattern

For each question:

- The concept is explained in simple words.
- A small example program is included wherever applicable.
- The program output is shown.
- A short explanation is provided to connect the example with the concept.

This section shows both the **conceptual understanding and practical implementation** of NumPy operations.

---

## Section B – Predict the Output

This section focuses on understanding NumPy code and predicting the output without executing it first.

### Topics Covered

- Broadcasting and array shapes
- Indexing and slicing
- Boolean filtering
- Matrix multiplication
- Handling `NaN`
- `np.where()`
- Array dimensions and size
- Reverse indexing

### Answer Pattern

For each question:

- The expected output or resulting shape is given.
- A short justification explains how the output was obtained.
- The explanation focuses on the NumPy operation used in the given code.

This section demonstrates **logical understanding of NumPy operations and output prediction**.

---

## Section C – Coding / Implementation

This section focuses on writing and executing vectorized NumPy programs.

### Topics Covered

- Classification using `np.where()`
- Z-score standardization
- Combining arrays using stacking
- Column-wise mean and standard deviation
- Matrix-based prediction using `X @ w + b`
- Mean Squared Error (MSE)
- Random data generation and reproducibility
- Min-max normalization
- Image batch processing

### Answer Pattern

For each coding question:

- NumPy code is provided.
- The code is executed.
- The actual output is included.
- A short one-line explanation describes what the code does.

The solutions use **NumPy/vectorized operations** instead of unnecessary explicit loops.

---

## Section D – Applied / Scenario-Based Problems

This section applies NumPy concepts to practical AI/ML situations.

### D1 – Data Preprocessing Pipeline

The answer demonstrates:

- Detecting missing values using `np.isnan()`
- Handling `NaN` values
- Using `np.nanmean()`
- Cleaning the data
- Standardizing the cleaned data

The answer includes the **step-by-step explanation, working code, output, and justification** for the chosen missing-value handling strategy.

### D2 – Image Batch Understanding

The answer explains the difference between:

- A single RGB image: `(height, width, channels)`
- A batch of RGB images: `(batch, height, width, channels)`

It also includes:

- Creating a random batch of images
- Computing the average image
- Resulting shape
- Explanation of why `axis=0` is used

### D3 – Debug the Model Code

The answer identifies the errors in the given model code and explains:

- The weight-vector shape mismatch
- Matrix multiplication compatibility
- Operator precedence in the MSE calculation
- The corrected implementation

The corrected code and output are also included.

---

## Section E – Bonus / Challenge

This section contains optional extra-credit problems using fully vectorized NumPy operations.

### E1 – Per-Column Min-Max Normalization

The answer demonstrates how to:

- Find the minimum of each feature column
- Find the maximum of each feature column
- Apply min-max normalization separately to each column
- Perform the operation without explicit loops

### E2 – Three-Level Score Classification

The answer demonstrates classification of scores into:

- `Fail`
- `Average`
- `Excellent`

using nested `np.where()` without explicit `if/else` statements or loops.

---

## Overall Answer Pattern

The notebook follows a consistent structure throughout the assignment:

**Concept → Code/Reasoning → Output → Short Explanation/Justification**

| Section | Main Focus | Answer Pattern |
|---|---|---|
| A | Concepts | Concept + Example Program + Output + Explanation |
| B | Output Prediction | Expected Output/Shape + Justification |
| C | Implementation | Code + Output + One-line Explanation |
| D | Applications & Debugging | Explanation + Working Code + Output + Justification |
| E | Bonus | Vectorized Code + Output + Explanation |

## File

The main assignment is provided as a Jupyter Notebook:

`firstname_numpy.ipynb`

## Tools Used

- Python
- NumPy
- Jupyter Notebook

## Purpose

The purpose of this assignment is to develop a practical understanding of NumPy and its applications in numerical computation, data preprocessing, image processing, and basic AI/ML operations.
