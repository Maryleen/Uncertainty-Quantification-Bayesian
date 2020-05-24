# Uncertainty-Quantification-Bayesian

The task concerns generation of prediction intervals (PIs) along with point predictions by applying neural networks for quantifying uncertainty in regression tasks with 10 regression datasets provided.

We choose and implement two recent deep generative modeling techniques which are [Dropout as a Bayesian Approximation](http://proceedings.mlr.press/v48/gal16.pdf) and [Bayes by Backprop](https://arxiv.org/pdf/1505.05424.pdf).

For evaluation of your models, the tail 10% of a dataset is used as a test set. We measure at least root mean squared error (RMSE) for point predictions, and prediction interval coverage probability (PICP) and mean prediction interval width (MPIW) for 95% prediction intervals.

A [report](Report.docx) on the experiments including evaluation and discussion about shortcomings and limitations of implemented technique is provided.
