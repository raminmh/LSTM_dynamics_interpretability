# Response charactrization for interpretation of the dynamics of long short term memory (LSTM) networks

We explore the dynamics of long short-term memory (LSTM) cells with a novel moethodology called response charactrization.

![alt text](https://www.safaribooksonline.com/library/view/deep-learning/9781491924570/assets/dpln_0424.png)

# Running Code

Creating data
```
python lstm_size_analysis.py
```

Plotting data
```
python ablation_plots.py
python bar_trends.py
python capacity_plots.py
```

The following initial files are included
- **lstm_module.py** Contains a numpy implementation of the vanilla LSTM cell introduced in Fig 1 of Greff et al. Currently it does not incorporate the pip-hole connections and other variations to the cell.
- **others/test_module.py** Compares our numpy implementation with a Tensorflow implementation
- **others/signal_test.py** Computes the response of an LSTM block and plots the traces for the internal state and the gate variables
- **others/io_test.py** Tests the load and stores methods of the LSTM module

# Picture Reference

LSTM: A Search Space Odyssey

Klaus Greff, Rupesh K. Srivastava, Jan Koutnik, Bas R. Steunebrink, Jurgen Schmidhuber
https://arxiv.org/pdf/1503.04069.pdf

