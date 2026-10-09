# royal-lineage-traversal
# 👑 Royal Lineage Traversal Matrix

An ancient kingdom preserved its royal family records inside a giant hierarchical binary tree. This repository contains the algorithms built to traverse the lineage in the exact chronological sequence required to unlock the kingdom's hidden archives.

## 🌟 Mission Overview
Tree traversals are fundamental computer science operations. They provide the core structural logic used daily across industry systems, including:
* **File Systems:** Navigating nested folders and directory paths.
* **Document Object Models (DOM):** Rendering and querying HTML elements in web browsers.
* **Compilers:** Parsing source code into Abstract Syntax Trees (AST).
* **Databases:** Indexing records efficiently for high-speed queries.

---

## 🌲 The Royal Tree Architecture

The family tree maps out six historical figures using a chronological layout ruleset:

```text
         King
        /    \
    Prince   Princess
    /    \       \
 Duke   Duchess  Count
```

Performing an **Inorder Traversal** (Left ➔ Root ➔ Right) yields the secret lineage tracking path:
📌 `Duke ➔ Prince ➔ Duchess ➔ King ➔ Princess ➔ Count`

---

## 🎨 Traversal Architecture Visualization

Below is the geometric layout map displaying both the tree pointer connections and the resolved inorder chronology path:

![Royal Lineage Tree Visualization](assets/tree_diagram.png)

---

## 🔄 Algorithmic Complexity Comparison

| Performance Metric | Recursive Traversal Approach | Iterative Traversal Approach |
| :--- | :--- | :--- |
| **Time Complexity** | \(\mathcal{O}(N)\) — Visits every node once | \(\mathcal{O}(N)\) — Visits every node once |
| **Space Complexity** | \(\mathcal{O}(H)\) — System call stack frame overhead | \(\mathcal{O}(H)\) — Explicit tracking memory stack |
| **Implementation** | Minimal, highly readable code | Verbose runtime loops, structure heavy |
| **Risk Matrix** | Potential `StackOverflowError` on deep lines | Safe; bound strictly by standard heap memory limits |

---

## ⚙️ Environment Setup & Execution

### Prerequisites
Ensure your local environment includes Python 3.8+ along with the required visualization plotting dependencies:
```bash
pip install matplotlib networkx jupyter
```

### Running the Project
1. Clone this repository to your machine:
   ```bash
   git clone https://github.com
   cd royal-lineage-traversal
   ```
2. Fire up the interactive environment to check your cells:
   ```bash
   jupyter notebook
   ```
3. Open `Untitled87.ipynb` (or your renamed file) and execute all code blocks sequentially.
