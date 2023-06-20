# Code for "Neural networks can detect model-free static arbitrage strategies"

## Ariel Neufeld, Julian Sester

# Abstract

In this paper we demonstrate both theoretically as well as numerically that neural
networks can detect model-free static arbitrage opportunities whenever the market admits some.
Due to the use of neural networks, our method can be applied to nancial markets with a high
number of traded securities and ensures almost immediate execution of the corresponding trading
strategies. To demonstrate its tractability, e
ectiveness, and robustness we provide examples using
real nancial data. From a technical point of view, we prove that a single neural network can
approximately solve a class of convex semi-innite programs, which is the key result in order to
derive our theoretical results that neural networks can detect model-free static arbitrage strategies
whenever the nancial market admits such opportunities.

# Preprint

# Content

- The [Notebook](https://github.com/juliansester/Deep-Arbitrage/Download_Real_Data.ipynb) to download the real option data of SP 500 Constituents.
- The [Notebook](https://github.com/juliansester/Deep-Arbitrage/Real_Data.ipynb) containing Algorithm 1 (training of the neural network) applied to real data.
- The [Notebook](https://github.com/juliansester/Deep-Arbitrage/Testing_Historical_Data.ipynb) covering the backtesting procedure on historical data. (HISTORICAL OPTION DATA CAN UNFORTUNATELY NOT BE PROVIDED)
- The [Notebook](https://github.com/juliansester/Deep-Arbitrage/Testing_Real_Data.ipynb) covering the backtesting of the trained neural network on the test data.


- The  [trained neural network](https://github.com/juliansester/Wasserstein-Q-learning/blob/main/model_strat_real.h5) .

# MIT License

Copyright (c) 2023 Julian Sester

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
