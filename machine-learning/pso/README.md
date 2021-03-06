Nature-inspired algorithms
==========================

This folder implements a number of nature-inspired optimization
algorithms, starting from the classic Particle-Swarm Optimization and
through some more modern ones.

The code is for [my JavaZone talk on nature-inspired algorithms](https://2017.javazone.no/program/44daf1c2053049bc9934f4fff1d19c7b).

To try it out, check out the code, then run:

```
python driver.py
```

This will run the particle-swarm optimization on the Michaelwicz
function and try to find the best possible solution, which will be
printed at the end.

By tweaking the code you can plug in a genetic algorithm, Firefly, or
Cuckoo search, or even just random trial and failure.

There is also code for evaluating and tuning the algorithms.

Papers for the various algorithms:

  * [Standard Particle Swarm Optimisation](https://hal.archives-ouvertes.fr/hal-00764996),
    Maurice Clerc, 15 pages. 2012. <hal-00764996>.
  * [Firefly Algorithms for Multimodal Optimization](https://blog.acolyer.org/2015/09/23/firefly-algorithms-for-multi-model-optimization/), Adrian Colyer, the morning paper.
  * [Firefly Algorithms for Multimodal Optimization](http://arxiv.org/pdf/1003.1466v1.pdf), Xin-She Yang, 2010.
  * [Cuckoo search via Lévy flights](https://blog.acolyer.org/2015/09/25/cuckoo-search-via-levy-flights/), Adrian Colyer, the morning paper.
  * [Cuckoo search via Lévy flights](http://www.cs.tufts.edu/comp/150GA/homeworks/hw3/_reading7%20Cuckoo%20search.pdf), Yang et al, 2009 World Congress on Nature & Biologically Inspired Computing (NaBIC 2009)
  * [Fish-school search](https://en.wikipedia.org/wiki/Fish_School_Search)
