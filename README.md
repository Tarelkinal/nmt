# nmt

* use tensorbord to see graphs and metrics obtained: all logs are stored in ./runs folder
  ```bash
  %load_ext tensorboard
  %tensorboard --logdir runs
  ```
  * bleu metrics comparison is on HPARAMS tab 
* models artifacts are in ./models folder
* networks implementations are in ./networks folder

## experiments
1. encoder - bidirectional GRU \
   decoder - GRU \
attention - energy between hiddens of encoder and previous hidden of decoder


2. encoder - bidirectional LSTM \   
   decoder - LSTM \
attention - cosine between hiddens of encoder and previous hidden decoder