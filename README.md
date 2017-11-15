# MP-CNN-tensorflow

How to run:
-----------
``1.`` Please install the tensorflow library 

``2.`` Clone this repository.

``3.`` Create folder named glove.6B.

``4.`` Download data and put them in the folder above: http://nlp.stanford.edu/data/glove.6B.zip.

``5.`` Run python2 train1.py.

Features:
-----------
``1.`` Change l1-distance to elementwise-l1 distance in utils.py as discribed in paper.

``2.`` Allow various value of num_filter_A.

``3.`` Add small lambda before feeding into tf.sqrt to avoid nans in loss.