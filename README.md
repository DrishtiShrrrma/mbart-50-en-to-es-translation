# Weight Decay Analysis

1. 0.0: No weight decay, meaning no regularization other than what comes from other sources (like dropout). This is a good baseline.
2. 1e-4: A small weight decay value that provides a small amount of regularization.
3. 1e-3: A moderate value that could yield a balance between fitting the data and regularizing the weights.
4. 1e-2: A higher value that should impose a noticeable amount of regularization, possibly at the expense of fitting the data well.
5. 1e-1: A very high value. Likely to significantly impact the ability of the model to fit the data but should serve as a good test of how much model is capable of being regularized
