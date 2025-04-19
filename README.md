# SVM Optimization Assignment - Multi-Class Classification


##  Dataset Info

- *Source*: [UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/letter+recognition)
- *Rows*: 20,000
- *Classes*: 26 (A-Z letters)

---

##  Task Performed

- Chose 10 different 70-30 train-test splits.
- Optimized SVM for each using Grid Search on:
  - kernel (linear, rbf, poly)
  - C (0.1, 1, 10)
  - epsilon (0.01, 0.1, 0.5)
- Recorded best parameters and accuracy for each.
- Plotted convergence graph of accuracy over 100 iterations for the best-performing sample.

---

##  Results

| Sample | Accuracy (%) | Kernel | C   | Epsilon |
|--------|--------------|--------|-----|---------|
| S1     | ...          | ...    | ... | ...     |
| ...    | ...          | ...    | ... | ...     |
| S10    | ...          | ...    | ... | ...     |

➡ Detailed results saved in svm_results.csv.

---

##  Convergence Graph

Convergence graph shows accuracy improvement over 100 iterations for the *best performing sample*:

![Convergence Graph](convergence_graph.png)

---

##  Requirements

```bash
pip install scikit-learn pandas matplotlib
