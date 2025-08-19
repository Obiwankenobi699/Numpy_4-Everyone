# 📘 NumPy 4 Everyone  

> A structured, hands-on journey to master **NumPy** — from basics to advanced linear algebra 🚀  

![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python)  
![NumPy](https://img.shields.io/badge/NumPy-1.24+-orange?logo=numpy)  
![License](https://img.shields.io/badge/License-MIT-green)  

---

## 📂 Learning Phases  

<details>
<summary>🔹 Phase 1 – Basics</summary>

### ✅ Concepts  
- Arrays from lists  
- NumPy vs Python lists (performance, memory, math ops)  
- Array dimensions & tensors  
- Array properties:  
  - `.ndim`, `.shape`, `.dtype`, `.nbytes`, `.itemsize`, `.size`  
- Flatten vs Ravel  
- Coordinates view of arrays  

### 🧮 Math Connection  
- Tensor = generalization of vectors/matrices  
- Dimension (`ndim`) ↔ Order of tensor  
- Shape ↔ Axes size  

</details>  

---

<details>
<summary>🔹 Phase 2 – Array Operations</summary>

### ✅ Concepts  
- Indexing & Slicing (1D, 2D, 3D)  
- Boolean masks & `np.where`  
- Array operations: `append`, `insert`, `concatenate`, `stack`  
- Broadcasting rules  
- Element-wise multiplication vs Matrix multiplication  
- Hands-on walkthrough of dot product & matrix multiplication  

### 🧮 Math Connection  
- Broadcasting = aligning smaller shapes to larger shapes for ops  
- Dot product formula:  

\[
\vec{a} \cdot \vec{b} = \sum_{i=1}^n a_i b_i
\]  

</details>  

---

<details>
<summary>🔹 Phase 3 – Applied Math & ML</summary>

### ✅ Concepts  
- Business problem case study (arrays in decision making)  
- Aggregations: `min`, `max`, `mean`, `cumsum`  
- Vectors & Dot product  
- Scalars vs Vectors rules (addition, multiplication)  
- Euclidean Distance vs Cosine Similarity  
- Applications in ML/NLP  
  - Cosine similarity in embeddings  
  - Vector projections  

### 🧮 Math Connection  
- **Euclidean distance**:  

\[
d(\vec{a}, \vec{b}) = \sqrt{\sum (a_i - b_i)^2}
\]  

- **Cosine similarity**:  

\[
\cos(\theta) = \frac{\vec{a} \cdot \vec{b}}{||a|| \, ||b||}
\]  

</details>  

---

## 📅 Study Planner  

| Week | Focus | Concepts | Mini Project |
|------|-------|----------|--------------|
| 1 | NumPy Basics | Arrays, Shapes, Indexing | Build embeddings |
| 2 | Array Ops | Broadcasting, Dot Product | Linear Algebra Demo |
| 3 | Slicing & Masks | Boolean filtering | Data Cleaning |
| 4 | Advanced Math | Stats, Similarity | Case Study Analysis |

---

## 🚀 How to Use  

```bash
# clone repo
git clone https://github.com/yourusername/numpy-4-everyone

# open notebooks
jupyter notebook Phase_1.ipynb
