## Environment setup

```
$ conda create --name commtoolbox python=2.7
$ source activate commtoolbox
$ conda install jupyter pandas numpy bokeh seaborn
$ pip install ipyparallel
$ pip install --pre dill
# from another folder
# don't install from release; buggy
$ git clone https://github.com/veeresht/CommPy.git
$ cd CommPy
$ python setup.py install
# in workspace folder
$ jupyter notebook
# on another prompt
$ ipcluster start
```

## Useful links for working with ipyparallel

* [dill and @interactive](http://nbviewer.ipython.org/github/ipython/ipython/blob/rel-2.2.0/examples/Parallel%20Computing/Using%20Dill.ipynb)

## Articles, papers

* A Study on DSSS Transceivers Using OQPSK Modulation by IEEE 802.15.4 in AWGN and Flat Rayleigh Fading Channels
* [Performance Study of IEEE 802.15.4 Using Measurements and Simulations](https://www.inets.rwth-aachen.de/pub/ZigBee.pdf)
* [Evaluation of SDR-implementation of IEEE 802.15.4 Physical Layer](http://www.diva-portal.org/smash/get/diva2:349061/FULLTEXT01.pdf)