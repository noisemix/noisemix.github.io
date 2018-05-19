# Data Augmentation for Natural Language Text Datasets

Authors, date

## Introduction

TOC

## Existing Work

### Images

### Audio

### Text

How does this compare to pre-trained vectors?

## Implementation
Char-level vs word-level
Link to Appendix / Noise Types

## Results
vs baseline
vs more real data
% improvement, % errors cut

## Conclusion

1 - Noisification is very effective.
2 - Most of the information about features that are meaningful for a given task is in any small random subset of the rows, after that mostly only non-task-specific noise is being learnt.

One drawback is longer training time.

### Future work
Benchmarks on more diverse tasks, eg seq2seq
More languages, keyboard layouts etc  
Learn noisification models from raw data or pre-trained vectors  
Noisification as a hyperparameter - grid search  

### References

## Appendix

TOC

### Noise Types

### Output

#### Downloads
Links to actual datasets

#### Samples
Sample rows
Sample predictions by noisified model vs baseline model

### Reproducing
Explanation of how to reproduce the results
```
pip install noisemix
...
```


