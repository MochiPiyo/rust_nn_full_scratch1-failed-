# Neural Network pretend to learn !

the challenge to build full scratch neural network
end up with something look like 2 layer mnist learner but 
actually do not learn.




What I know about this silly code is

・it seems ok in first or maybe first and second epoch, but after that...
・only weights of eatch Affine layer are not learnable, biases of eatch affine layer
are updated correctly in all epoches.

・in second affine layer of 3th epoch, that always have all zero input. (though input is random)
 but output of the first affine layer are not all zero.
 So relu layer that is between first and second, seems suspicious.
 however relu looks ok in other iteration 
 WHY?

・Tensor module is not used.