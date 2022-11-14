



- $X$ = 
	- space (all possible values) of input values
- $y$ = 
	- space of output values
- $X = y = \mathbb{R}$, a set of real numbers
- $x^{(i)}$ = 
	- Input variables = features
- $y^{(i)}$ =
	- Output variables = target variables
- $m$ =
	- Number of training examples
- $(X, y)$ = 
	- single training example
	- $(x^{(i)}, y^{(i)})$ = i-th training example (1st, 2nd, 3rd, ...)
	- (i) is an index in the training set
-  $\{(x^{(i)}, y^{(i)}); i = 1, ..., m\}$ = 
	- Training set, a list of _m_ training examplesused to train the model
- $h$ = 
	- Hypothesis / function that predict output values y



#Supervised 
##### Learn from being given "right answers"

The goal of supervised learning is, given a training set, to learn a function $h:X -> y$ so that h(x) is a good predictor for the corresponding value of y.

By seeing correct pairs of input x and desired output label y, learns to take just the input alone without the output label and gives a resonably accurate prediction of the output.

#### Use cases
span filtering, speech recognition, machine translation, online advertising, self-driving car, visual inspection




#Regression 
- predict a number, infinitely many possible outputs
- target variable is continuous $(3399, 3943.23, 39432)$

#Classification 
- predict categories, small number of possible output
-  target variable is a discret value $(1, 0)$ or even no-numeric ($cat, dog$)

