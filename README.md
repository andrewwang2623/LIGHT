# LIGHT
Light-curve Inference for Gravitational-lensing Hypothesis Testing

LIGHT is a ULAB (Undergraduate Lab at Berkeley) research project on gravitational microlensing: given only the first part of an event's light curve, how well can a model predict the rest? The notebooks fit a differentiable Paczyński single-lens model to each event with gradient descent in PyTorch, then compare the recovered parameters (t0, u0, tE) and the predicted future brightness against the true values across the full test set.
