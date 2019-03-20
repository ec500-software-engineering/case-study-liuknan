# case-study-liuknan
## Chosen Project: Keras
Also see case study.key
### Technology and Platform used for development
* Keras is a fully Python program. Since Kears is a user friendly program and provide lots of APIs for users, I do not think it would use another language if it was started today. Python is the best choice.

* It has no build systems and you could just run it with any Python IDE.

* For libraries, it uses numpy and pyyaml. Users also need to install one program like TensorFlow, Theano or CNTK.
<img src="https://github.com/ec500-software-engineering/case-study-liuknan/raw/master/requirements.png" width="600" height="600">

### Testing
* Keras has code coverage test. They have .coveragerc file.

* It also has pytest file. In 'keras/tests/', we could find api test, loss tests, model tests and so on.

### Software architecture
* Keras is a kind of frontend and users could use Keras to build their own project. Keras is like an API. With different kinds of backend, users could easily build their own project with Keras.

* The core data structure of Keras is a model, a way to organize layers. The simplest type of model is the Sequential model, a linear stack of layers. 

*Work flow shows below
![](https://github.com/ec500-software-engineering/case-study-liuknan/raw/master/keras-workflow.jpg)

### Defects
* For issue #2436, we know that Keras supports multiple GPUs only with a TensorFlow backend. Since Keras is like an API for these Machine Learning programs and the feature of programs like Theano is rather new, so it will not support some features of Theano.

* For issue #3921, some words are pretty confusing in Keras. For instance, “Merge” and “merge” are two total different things. “Merge” is a layer and takes layers as input, and “merge” is a function and it takes tensors as input. 

### Demonstration
see main.py
