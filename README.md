# OPFM-CC: Operator for Feature Models - Cardinality Contrained 

## Cardinality-Constrained Feature Modeling

This repository contains the prototype implementation of the `#choose` operator, introduced in the paper *"#choose: A Cardinality-Constrained Operator for
Feature Models"*.

The `#choose` construct enables bounded selection of features (e.g., in the case of our running example with CPUs) within a feature model, supporting more expressive and flexible configuration in embedded systems.

## 📘 Contents

- `notebook.ipynb` – Demonstrates how to use the `#choose` operator to generate valid configurations based on user-defined cardinality bounds.
- `tree_example.png` – Example image showing the generated configuration decision tree.

## 🚀 How to Use

Open the Jupyter Notebook and run the cells to explore how different values of \(\alpha\) and \(\beta\) affect the generated configurations.

```bash
jupyter notebook opfm-cc.ipynb
