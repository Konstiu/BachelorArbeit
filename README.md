# Repository Dependency Metrics Analysis

A Jupyter notebook to clone a GitHub repo, extract dependency metrics for Java (Maven & Gradle), Python, and JavaScript files across commits, and save the results as JSON.

---

## Table of Contents

## Table of Contents

- [1. Setup](./Dependency_analysis_notebook.ipynb#1-setup)
  - [1.1 Imports](./Dependency_analysis_notebook.ipynb#11-imports)
  - [1.2 Global Variables](./Dependency_analysis_notebook.ipynb#12-global-variables)
- [2. Function Definitions](./Dependency_analysis_notebook.ipynb#2-function-definitions)
  - [2.1 Compute Metrics per Commit](./Dependency_analysis_notebook.ipynb#21-compute-metrics-per-commit)
  - [2.2 Process Commits (POM, Gradle, Py/JS)](./Dependency_analysis_notebook.ipynb#22-process-commits-pom-gradle-pyjs)
  - [2.3 Save Merged Data](./Dependency_analysis_notebook.ipynb#23-save-merged-data)
  - [2.4 Find Files](./Dependency_analysis_notebook.ipynb#24-find-files)
  - [2.5 Commit History Helpers](./Dependency_analysis_notebook.ipynb#25-commit-history-helpers)
  - [2.6 Parse POM XML](./Dependency_analysis_notebook.ipynb#26-parse-pom-xml)
  - [2.7 Load File at Commit](./Dependency_analysis_notebook.ipynb#27-load-file-at-commit)
  - [2.8 Python/JS Parsing Helpers](./Dependency_analysis_notebook.ipynb#28-pythonjs-parsing-helpers)
  - [2.9 Gradle Parsing Helpers](./Dependency_analysis_notebook.ipynb#29-gradle-parsing-helpers)
  - [2.10 Merge & Clean Results](./Dependency_analysis_notebook.ipynb#210-merge-clean-results)
- [3. Execution Workflow](./Dependency_analysis_notebook.ipynb#3-execution-workflow)
  - [3.1 Initialize & Clone](./Dependency_analysis_notebook.ipynb#31-initialize-clone)
  - [3.2 Discover Files](./Dependency_analysis_notebook.ipynb#32-discover-files)
  - [3.3 List Commits](./Dependency_analysis_notebook.ipynb#33-list-commits)
  - [3.4 Parse Java-POM](./Dependency_analysis_notebook.ipynb#34-parse-java-pom)
  - [3.5 Parse Python & JS](./Dependency_analysis_notebook.ipynb#35-parse-python-js)
  - [3.6 Parse Java-Gradle](./Dependency_analysis_notebook.ipynb#36-parse-java-gradle)
  - [3.7 Merge & Save](./Dependency_analysis_notebook.ipynb#37-merge-save)
- [4. Results & Calculated Metrics](./Dependency_analysis_notebook.ipynb#4-results-calculated-metrics)

---
