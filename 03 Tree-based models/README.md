<h2 align="center">03 Tree-based Models</h2>

## Material:
Ch 6 + 7

Session material: In this folder.

You will need to install the graphviz and pydotplus modules in python. You can do this by following these steps:

1) Open the anaconda prompt  
2) Install graphviz by typing ```conda install python-graphviz```
3) Install pydotplus by typing ```conda install pydotplus```

Alternatively, if the above doesn't work:

1) Go to [https://graphviz.gitlab.io/_pages/Download/Download_windows.html](https://graphviz.gitlab.io/_pages/Download/Download_windows.html)  
   and download graphviz  

2) Add the following to your code:

```python
import os  
os.environ["PATH"] += os.pathsep + 'C:/Program Files (x86)/Graphviz2.38/bin/'
```

## Topics
This lecture covers **decision trees** and related methods. We will talk about:

- Decision trees
- Random forests
- Gradient-boosted decision trees

---

After attending this lecture, reading the corresponding part of the book and doing exercises, I expect you to be able to:

- Use and implement decision trees, random forests and gradient boosted decision trees in python.  
- Describe the advantages and disadvantages of using decision trees, random forests and gradient boosted decision trees, respectively.
- Visualize decision trees in different ways.
- Extract and interpret feature importance.
- Describe how the Gini impurity index can be used to determine which feature to branch off on.
- Explain what is meant by pre-pruning.
- Explain how random forests are random, including what is meant by bootstrapping and feature selection in this context.
- Explain what is meant by soft voting.
- Discuss different hyperparameters of tree-based methods, and how tuning these parameters influence the results.

