# FDDB-Evaluation
Python Evaluation Code for [FDDB Face Dataset](http://vis-www.cs.umass.edu/fddb/index.html)


## Usage


##### before evaluating 

````
python3 setup.py build_ext --inplace
````

##### evaluating

**GroungTruth:** under the `ground_truth`

**Notice:** 
The prediction directory should be like widerface dataset.
 I generate the fake prediction result under `pred_sample` for you reference.


````
python3 evaluate.py -p <your prediction dir> -g <groud truth dir>
````

## Acknowledgements

some code borrowed from [Widerface-Evaluation](https://github.com/wondervictor/WiderFace-Evaluation)
