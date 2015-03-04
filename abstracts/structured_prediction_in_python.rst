Structured Prediction is a generalization of classification and regression to structured output spaces like sequences or trees.
Unlike standard classification algorithms, structured prediction methods can exploit correlation in output variables.
The general form of a structured predictor f is f(x) = argmax_y g(x, y) where g is a compatibility function between an output
structure y and the input x. Most methods for learning structured prediction are closely related to graphical models, which also
have the constraint of  g(x, y) being a probability distribution over y (in the conditional case).
The talk will give an introduction into structured prediction methods and the library PyStruct that implements many
common learning algorithms in python. 
