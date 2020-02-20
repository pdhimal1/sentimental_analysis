```
Prakash Dhimal
George Mason University
CS 584 Theory and Applications of Data Mining
Homework 1
```

Accuracy:
```
Miner username: mistor
Accuracy as of this report: 0.64
```

Please refer to:
    * `report/report.pdf` for the project report
    * `src/knn_classifier` for the source code
    * `src/jupyter-notebooks/validation.ipynb` for the validation work

`src/knn_classifier.py` takes a long time for a full run. Please see `../src/jupyter-notebook/knn_classifier_workbook.ipynb`
to see a full run.

#### Project organization:
  * `src` directory
    * `knn_classifier.py`
    * `jupyter-notebooks` directory
      * `validation.py` -> validation work
      * `workbook.py` -> this is the same source code as `knn_classifier.py`
  * `report` directory
    * `report.pdf`
  * `output` directory
    * Few output files produced by this program
  * `ReadME.md`

#### Dependency:
This python program depends on the following modules:
  * os
  * multiprocessing
  * string
  * collections
  * nltk
  * numpy
  * scipy

#### How to run this program:
  * `python knn_classifier.py`

The source code was developed and tested using PyCharms and jupyter-notebook on a CentOS 8 machine.
