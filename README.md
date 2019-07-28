# Building a chatbot for practice
 Having troubles with the model. The is the error:
```
---------------------------------------------------------------------------
IndexError                                Traceback (most recent call last)
<ipython-input-41-b26a8b27a091> in <module>
      5 net = tflearn.fully_connected(net, 8) # hidden layer
      6 net = tflearn.fully_connected(net, 8) # hidden layer
----> 7 net = tflearn.fully_connected(net, len(output[0]), activation='softmax')
      8 net = tflearn.regression(net)
      9 

IndexError: index 0 is out of bounds for axis 0 with size 0
```

Guess is the `output` is length of `0`. 
