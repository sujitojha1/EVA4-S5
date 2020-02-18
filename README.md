# S5
EVA4 Session 5 assginment

## Step 1

### Target . 

1.   Set up and defining skeleton with Convolution block, GAP and Convolution block.

### Results .  

1.   Parameters: 13,584
2.   Best Train Accuracy 98.53%
3.   Best Test Accuracy 98.34%

### Analysis   

1.   Basic skeleton model doesn't meet target accuracy of 99.4% and model is slightly over-fitting.
2.   Parameters count is >10k


## Step 2

### Target . 

1.   Adding batch-norm and drop-out to reduce over-fitting and improve the model efficiency.
2.   Iterate to find the best drop-out value (0.05 to 0.2)

### Results .  

1.   Parameters: 13,584
2.   Best results with 0.05 as Dropout value where difference b/w test and train accuracy is small.
3.   Best Train Accuracy 99.12%
4.   Best Test Accuracy 99.45%

### Analysis   

1.  Model is under-fitting and total parameters also > 10k.

## Step 3

## Step 4


## Step 5
