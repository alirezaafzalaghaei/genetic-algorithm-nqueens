

A simple python script to solve N-Queens problem
--------------------------------------------------------------


**Genetic algorithm operators**

- Randomized initilization
- Tournoment parent selection
- PMX crossover
- Single swap mutation
- Remove worst surviver selection

**Requirements**

- python (2 to 3)
- cython (optional)
- turtle (to draw chess board when `board size <= 16`)
- matplotlib (to draw cost plot)

**How to use**

- python 3
```
python3 nqueen.py
```

- python 2
```
python nqueen.py
```

- cython 3
```
python3 setup.py build_ext --inplace
python3 result.py
```

- cython 2
```
python setup.py build_ext --inplace
python result.py
```



**Some benchmarks**

- ~4.5 sec for 64 queen in python 3.6
- ~1.7 sec for 64 queen in python 2.7
- ~0.7 sec for 64 queen in cython 3.6
- ~0.7 sec for 64 queen in cython 2.7

