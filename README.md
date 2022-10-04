Data Science from Scratch
=========================

Here's all the code and examples from the second edition of my book _Data Science from Scratch_. They require at least Python 3.6.

(If you're looking for the code and examples from the first edition, that's in the `first-edition` folder.)

If you want to use the code, you should be able to clone the repo and just do things like

```
In [1]: from scratch.linear_algebra import dot

In [2]: dot([1, 2, 3], [4, 5, 6])
Out[2]: 32
```

and so on and so forth.

Two notes:

1. In order to use the library like this, you need to be in the root directory (that is, the directory that contains the `scratch` folder). If you are in the `scratch` directory itself, the imports won't work.

2. It's possible that it will just work. It's also possible that you may need to add the root directory to your `PYTHONPATH`, if you are on Linux or OSX this is as simple as 

```
export PYTHONPATH=/path/to/where/you/cloned/this/repo
```

(substituting in the real path, of course).

If you are on Windows, it's [potentially more complicated](https://stackoverflow.com/questions/3701646/how-to-add-to-the-pythonpath-in-windows-so-it-finds-my-modules-packages).

## Table of Contents

1. [Introduction](/blob/master/scratch/introduction.py)
2. [A Crash Course in Python](/blob/master/scratch/crash_course_in_python.py)
3. [Visualizing Data](/blob/master/scratch/visualization.py)
4. [Linear Algebra](/blob/master/scratch/linear_algebra.py)
5. [Statistics](/blob/master/scratch/statistics.py)
6. [Probability](/blob/master/scratch/probability.py)
7. [Hypothesis and Inference](/blob/master/scratch/inference.py)
8. [Gradient Descent](/blob/master/scratch/gradient_descent.py)
9. [Getting Data](/blob/master/scratch/getting_data.py)
10. [Working With Data](/blob/master/scratch/working_with_data.py)
11. [Machine Learning](/blob/master/scratch/machine_learning.py)
12. [k-Nearest Neighbors](/blob/master/scratch/k_nearest_neighbors.py)
13. [Naive Bayes](/blob/master/scratch/naive_bayes.py)
14. [Simple Linear Regression](/blob/master/scratch/simple_linear_regression.py)
15. [Multiple Regression](/blob/master/scratch/multiple_regression.py)
16. [Logistic Regression](/blob/master/scratch/logistic_regression.py)
17. [Decision Trees](/blob/master/scratch/decision_trees.py)
18. [Neural Networks](/blob/master/scratch/neural_networks.py)
19. [Deep Learning](/blob/master/scratch/deep_learning.py)
20. [Clustering](/blob/master/scratch/clustering.py)
21. [Natural Language Processing](/blob/master/scratch/nlp.py)  
[Natural Language Processing Advanced](/blob/master/scratch/nlp_advanced.py)  
22. [Network Analysis](/blob/master/scratch/network_analysis.py)
23. [Recommender Systems](/blob/master/scratch/recommender_systems.py)
24. [Databases and SQL](/blob/master/scratch/databases.py)
25. [MapReduce](/blob/master/scratch/mapreduce.py)
26. Data Ethics
27. Go Forth And Do Data Science
