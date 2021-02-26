# LSTM-MATLAB

LSTM-MATLAB is Long Short-term Memory (LSTM) in MATLAB, which is meant to be succinct, illustrative and for research purpose only. It is accompanied with a paper for reference: [Revisit Long Short-Term Memory: An Optimization Perspective], NIPS deep learning workshop, 2014. 

Creater & Maintainer
Qi Lyu

FEATURES
  - original Long short-term Memory
  - all connect peephole
  - support optimization methods like LBFGS and CG
  - CPU or GPU acceleration
  - Mapreduce parallelization
  - gradient checking
  - easy configuration 
  - baseline experiment
 


#ACKNOWLEDGEMENTS
The minFunc code folder included is provided by Mark Schmidt (http://www.cs.ubc.ca/~schmidtm).
MATLAB Mapreduce is provided by Quoc V. Le(http://cs.stanford.edu/~quocle/optimizationWeb/index.html). 
  
#USAGE
To run the code, start from aStart.m. Data is generated by scripts in data directory on-the-fly. For faster LSTM implementation with complete features, see 'LSTMLayer' defined in [C++ version].
The dataset and labels etc follows the original LSTM paper in 1997.

License
----
MIT


[Revisit Long Short-Term Memory: An Optimization Perspective]:http://ml.cs.tsinghua.edu.cn/~jun/pub/lstm-parallel.pdf
[C++ version]:https://github.com/huashiyiqike/NETLAB/blob/master/layernet/core/layer-inl.hpp
