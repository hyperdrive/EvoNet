# EvoNet
Evolve random projection based neural networks. 
The output of a linear random projection (RP) usually has a Gaussian distribution.  The product of 2 (or more) such RP's has a spiky non-Gaussian distribution.  A vector of such products is point-wise sparse, taking a further RP creates a pattern-wise sparse vector. This is probably a better form to multiply by weights for a neural network. 
Alternatively you can take the element wise square of one vector of random projections as a point-wise sparse vector, and then convert that to the (higher entropy) pattern wise sparse vector.

More information:
https://randomprojectionai.blogspot.com/
