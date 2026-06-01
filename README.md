# 📊 NumPy — Basics to Advanced

> A structured, topic-by-topic NumPy learning repository covering everything from array fundamentals to advanced data cleaning techniques — with 11 well-organized Jupyter Notebooks and real dataset practice.

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Latest-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Notebooks](https://img.shields.io/badge/Notebooks-11-red?style=for-the-badge)
![DataScience](https://img.shields.io/badge/Data_Science-Journey-purple?style=for-the-badge)

---

## 📖 About This Repository

This repository is a complete NumPy learning resource, organized into 11 focused Jupyter Notebooks that progressively build your skills from absolute basics to advanced concepts like linear algebra, broadcasting, reshaping, and data cleaning. Each notebook covers a single topic with clean code and clear markdown explanations to reinforce your understanding.

---

## 🗂️ Repository Structure

```
NumPy-Basics-To-Advanced/
│
├── 📓 01_intro_and_performance.ipynb
├── 📓 02_array_attributes_and_dtypes.ipynb
├── 📓 03_indexing_slicing_filtering.ipynb
├── 📓 04_array_initialization.ipynb
├── 📓 05_broadcasting_and_vectorization.ipynb
├── 📓 06_array_manipulation.ipynb
├── 📓 07_repeating_and_copying.ipynb
├── 📓 08_math_linalg_statistics.ipynb
├── 📓 09_reshaping_and_flattening.ipynb
├── 📓 10_stacking_and_splitting.ipynb
├── 📓 11_missing_and_infinite_values.ipynb
│
└── 📄 data.txt
```

---

## 🧩 Topics Covered

### 🟢 Beginner

#### Notebook 01 — Intro & Performance
- What is NumPy and why use it
- Python Lists vs NumPy Arrays
- Execution time comparison
- Memory usage comparison
- Why NumPy is faster and more efficient

#### Notebook 02 — Array Attributes & Data Types
- Creating 1D and 2D arrays
- `ndim`, `shape`, `dtype`, `itemsize`, `size`, `nbytes`
- Manual vs built-in memory calculation
- Converting data types with `astype()`

#### Notebook 03 — Indexing, Slicing & Filtering
- Accessing elements in 1D, 2D, and 3D arrays
- Slicing with start, stop, and step
- Fancy indexing
- Boolean masking
- Loading data from external file with `genfromtxt()`
- Filtering with `any()` and `all()`
- Combining multiple conditions

---

### 🟡 Intermediate

#### Notebook 04 — Array Initialization
- `zeros()`, `ones()`, `identity()`
- `full()`, `full_like()`
- `arange()`, `linspace()`
- Random arrays with `rand()`, `randint()`, `random_sample()`

#### Notebook 05 — Broadcasting & Vectorization
- Scalar broadcasting
- Vector broadcasting
- Vectorized operations without loops
- Practical discount calculation example

#### Notebook 06 — Array Manipulation
- `insert()` — adding elements, rows, columns
- `append()` — appending to 1D and 2D arrays
- `concatenate()` — merging arrays horizontally and vertically
- `delete()` — removing elements, rows, columns

#### Notebook 07 — Repeating & Copying
- `repeat()` with axis control
- Horizontal and vertical repetition
- `copy()` — independent copy vs view
- Difference between modifying original vs copy

---

### 🔴 Advanced

#### Notebook 08 — Mathematics, Linear Algebra & Statistics
- Arithmetic operations on arrays
- Array-to-array operations
- Trigonometric functions
- `matmul()` — matrix multiplication
- `det()` — determinant of a matrix
- `inv()` — inverse of a matrix
- `trace()` — trace of a matrix
- `min()`, `max()`, `mean()`, `sum()`, `std()`, `var()`
- Row-wise and column-wise operations with `axis`

#### Notebook 09 — Reshaping & Flattening
- `reshape()` — changing array dimensions
- `ravel()` — flatten returning a view
- `flatten()` — flatten returning a copy
- View vs copy difference

#### Notebook 10 — Stacking & Splitting
- `vstack()` — vertical stacking
- `hstack()` — horizontal stacking
- `split()` — splitting 1D arrays
- `hsplit()` — column-wise splitting
- `vsplit()` — row-wise splitting

#### Notebook 11 — Missing & Infinite Values
- `isnan()` — detecting NaN values
- `isinf()` — detecting infinite values
- `nan_to_num()` — replacing NaN with custom values
- Replacing positive and negative infinity
- Preparing data for analysis and machine learning

---

## 🗃️ Data File

**`data.txt`** — A numerical dataset (3 rows × 18 columns, comma-separated) used in Notebook 03 to demonstrate:
- Loading external data with `np.genfromtxt()`
- Applying boolean filtering on real data
- Using `any()` and `all()` with the axis parameter

---

## 🚀 Getting Started

### Prerequisites
- Python 3.x installed on your machine
- Jupyter Notebook or JupyterLab
- NumPy library

### Install Dependencies
```bash
pip install numpy jupyter
```

### Clone the Repository
```bash
git clone https://github.com/daniyalarain12/NumPy-Basics-To-Advanced.git
cd NumPy-Basics-To-Advanced
```

### Launch Jupyter Notebook
```bash
jupyter notebook
```

Then open any notebook from the file browser and run cells from top to bottom.

---

## 📊 Repository Stats

| Detail | Count |
|--------|-------|
| Total Notebooks | 11 |
| Topics Covered | 40+ |
| Data Files | 1 |
| Language | Python 100% |

---

## 🎯 What You Will Learn

By going through all 11 notebooks in order, you will be able to:

- ✅ Understand why NumPy is faster and more memory-efficient than Python lists
- ✅ Create and inspect arrays of any shape and data type
- ✅ Index, slice, and filter arrays confidently
- ✅ Initialize arrays using built-in NumPy functions
- ✅ Leverage broadcasting and vectorization for clean, loop-free code
- ✅ Manipulate arrays by inserting, deleting, and concatenating
- ✅ Perform linear algebra and statistical operations
- ✅ Reshape and flatten arrays for machine learning pipelines
- ✅ Stack and split arrays efficiently
- ✅ Handle missing and infinite values for real-world data cleaning

---

## 🗺️ Learning Path

```
01 Intro → 02 Attributes → 03 Indexing → 04 Initialization → 05 Broadcasting
     ↓
06 Manipulation → 07 Repeating → 08 Math & Stats → 09 Reshaping → 10 Stacking → 11 Missing Values
```

> 💡 Follow the notebooks in order for the best learning experience.

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome!
- Open an **Issue** for bug reports or suggestions
- Submit a **Pull Request** with improvements or new examples

---

## 👨‍💻 Author

**Daniyal Arain**
- GitHub: [@daniyalarain12](https://github.com/daniyalarain12)

---

## ⭐ Show Your Support

If this repository helped you learn NumPy, please consider giving it a **⭐ star** — it helps others discover it too!

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
