# Decision-Tree

# Decision Tree in Machine Learning
A decision tree is a type of supervised learning algorithm that is commonly used in machine learning to model and predict outcomes based on input data. It is a tree-like structure where each internal node tests on attribute, each branch corresponds to attribute value and each leaf node represents the final decision or prediction. The decision tree algorithm falls under the category of supervised learning. They can be used to solve both regression and classification problems.

# Decision Tree Terminologies
There are specialized terms associated with decision trees that denote various components and facets of the tree structure and decision-making procedure. :

- Root Node: A decision tree’s root node, which represents the original choice or feature from which the tree branches, is the highest node.
- Internal Nodes (Decision Nodes): Nodes in the tree whose choices are determined by the values of particular attributes. There are branches on these nodes that go to other nodes.
- Leaf Nodes (Terminal Nodes): The branches’ termini, when choices or forecasts are decided upon. There are no more branches on leaf nodes.
- Branches (Edges): Links between nodes that show how decisions are made in response to particular circumstances.
- Splitting: The process of dividing a node into two or more sub-nodes based on a decision criterion. It involves selecting a feature and a threshold to create subsets of data.
- Parent Node: A node that is split into child nodes. The original node from which a split originates.
- Child Node: Nodes created as a result of a split from a parent node.
- Decision Criterion: The rule or condition used to determine how the data should be split at a decision node. It involves comparing feature values against a threshold.
- Pruning: The process of removing branches or nodes from a decision tree to improve its generalisation and prevent overfitting.

# How Decision Tree is formed?
The process of forming a decision tree involves recursively partitioning the data based on the values of different attributes. The algorithm selects the best attribute to split the data at each internal node, based on certain criteria such as information gain or Gini impurity. This splitting process continues until a stopping criterion is met, such as reaching a maximum depth or having a minimum number of instances in a leaf node.

# Why Decision Tree?
Decision trees are widely used in machine learning for a number of reasons:

- Decision trees are so versatile in simulating intricate decision-making processes, because of their interpretability and versatility.
- Their portrayal of complex choice scenarios that take into account a variety of causes and outcomes is made possible by their hierarchical structure.
- They provide comprehensible insights into the decision logic, decision trees are especially helpful for tasks involving categorisation and regression.
- They are proficient with both numerical and categorical data, and they can easily adapt to a variety of datasets thanks to their autonomous feature selection capability.
- Decision trees also provide simple visualization, which helps to comprehend and elucidate the underlying decision processes in a model.

# Decision Tree Approach

1) Information Gain: Measures the reduction in entropy (uncertainty) after splitting a dataset based on a particular attribute. The attribute with the highest information gain is chosen for splitting.

2) Gini Index: Measures the impurity or the probability of misclassifying a randomly chosen element if it were randomly labeled according to the distribution of labels in the subset. The attribute with the lowest Gini Index is chosen for splitting.

# Advantages of Decision Trees:

- Easy to understand and interpret
- Handle both numerical and categorical data
- No requirement for feature scaling
- Can capture non-linear relationships
- Robust to outliers

# Disadvantages of Decision Trees:

- Prone to overfitting
- Instability
- Biased towards features with more levels
- can create complex trees

# Applications of Decision Trees:

- Customer segmentation
- Credit risk assessment
- medical diagnosis
- Fraud detection
- Predictive maintenance
