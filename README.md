# BadCalcuator
A calculator that predicts the answer of an equation using a neural network. Works about as well as you'd expect.

All data used to train & test the neural net is generated programmically to match a given answer. Generated equations are sorted into the proper file structure for tensor flow's standard text input pipeline. From there, it's just a matter of training the neural net to catagorize each piece of data. 

The nice part about generating data that can be easily verified is that we can generate a potentally infinite number of novel equations to train the network on. This removes the single most annoying part of building a neural net - collecting and labeling data. All said, this style of creating data has questionable utility in practice, however it is a useful thought experiment for learning neural nets.

With 25,000 examples generated per digit, and only allowing for answers 1-10, this model reaches ~37% accuracy. Making this calculator work at slightly below first grade level. If you ever needed to simulate a first grader doing homework, this repo has you covered.
