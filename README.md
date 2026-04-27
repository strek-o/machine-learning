# Machine Learning

[WFAIS.IF-XO307.0]

## Exercise 1 `Clustering`

[[commit]](https://github.com/strek-o/machine-learning/tree/64e1ef379501e89601004b1e781fb71925ee22c5)

- [x] Modify the HCM code to work for three groups.
- [x] For density clustering, plot the feature space with all element marked with different color, depending on the cluster that it's assigned to.
- [x] Build a method that plot based on dendrograms_history and pydot, a dendrogram for the divisive clustering method. You should base on agglomerative method, but keep in mind that it works top-down instead of bottom-up.
- [x] Implement the $s_{2}$ metric.
- [x] Draw the borders between clusters in the output image.

## Exercise 2 `Linear methods`

[[commit]](https://github.com/strek-o/machine-learning/tree/d6000597b8c675f149ec4aef4a329b00d3811075)

- [x] Use the cross-validation method to test the linear regression with different $\alpha$ values, at least three.
- [x] Implement a SGD method that will train the Lasso regression for 10 epochs.
- [x] Extend the Fisher's classifier to work with two features. Use the class as the $y$.

## Exercise 3 `Decision trees`

[[commit]](https://github.com/strek-o/machine-learning/tree/efd02949ffbdd9ca2a2a1725691fde666efddb8e)

- [x] Rewrite the CART method to the Gini index.
- [x] Use pydot do draw the tree for C4.5 example.
- [x] Implement the minimum number of objects pruning method.
- [x] Plot OC1 tree, but instead of elements id, print the feature id it was split by.

## Exercise 4 `SVM`

[commit](https://github.com/strek-o/machine-learning/tree/c119c06c7dc07e818f007eb10fe32f44f0ba308a)

- [x] Implement the polynomial kernel.
- [x] Implement the multiclass C-SVM.

## Exercise 5 `NLP`

[commit](https://github.com/strek-o/machine-learning/tree/ab3beca60bd2a41f17b7a07e789626b7093efa3e)

- [x] Build your own tokenizer, where you need to implement two functions to implement a tokenizer based on regular expression.
- [x] Get tags from Trump speech.
- [x] Get the nouns in the last 10 sentences from Trump's speech and find the nouns divided by sentences. Use SpaCy.
- [x] Build your own Bag Of Words implementation using tokenizer created before.
- [x] Build a 5-gram model and clean up the results.
