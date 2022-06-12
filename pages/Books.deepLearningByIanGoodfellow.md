- Cita:
  ```latex
  @book{deepLearningByIanGoofellow,
      title={Deep Learning},
      author={Ian Goodfellow and Yoshua Bengio and Aaron Courville},
      publisher={MIT Press},
      note={\url{http://www.deeplearningbook.org}},
      year={2016}
  }
  ```
-
- # Notas
	- (PG. 163) It is best to think of feedforward networks as function approximation machines that are designed to achieve statistical generalization, occasionally drawing some insights from what we know about the brain, rather than as models of brain functions.
	- (PG. 138) One innovation associated with support vector machines ( #SVM ) is the ^^kernel trick^^. The kernel trick consists of observing that many machine learning algorithms can be written exclusively in terms of dot products between examples. For example, it can be shown that the linear used by the support vector machine can be re-written as 
	  id:: 62a562d9-700e-48e9-893b-437a053a9392
	  $$w^{T}x + b = b + \sum_{i=1}^{m} \alpha_i x^{T}x^{(i)} $$
	- (PG. 166) Learning in deep neural networks requires computing the gradients of complicated functions.
	- (PG. 168) The activation function $g$ is typically chosen to be a function that is applied element-wise, with $h_i = g(x^{T} W_{:,i} = c_{i} )$. In modern neural networks, the default reommendation is to use the
	-
	-